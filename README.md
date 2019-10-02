# Resources for Analytics Engineers (Work in Progress)
This repository is a curation of good blog posts and books for Analytics Engineers. It can also be very useful for Data Analysts and Data Scientists. 

## Contribute
I really appreciate any contribution. Just make sure to describe the theme and why you found the resource useful. 

# Table of Contents
- [SQL](#sql)
- [Python](#python)
- [Infrastructure](#infrastructure)
- [Analytics Skills](#analytics-skills)
- [Data Warehousing](#data-warehousing)
- [Data Pipelines](#data-pipelines)
- [Starting analytics in a company](#starting-analytics-in-a-company)
- [Testing data](#testing-data)
- [Success Stories](#success-stories)
- [Organisation](#organisation)
- [Data Visualisation](#data-visualisation)
- [Marketing and data](#marketing-and-data)
- [More rigor for the analyst](#more-rigor-for-the-analyst)
- [Other readings lists](#other-readings-lists)
- [Top bloggers/blog](#top-bloggersblog)

# Readings

Definition of the Analytics Engineer: [The Analytics Engineer](https://www.locallyoptimistic.com/post/analytics-engineer/). 


### SQL
  * [Learning SQL 201: Optimizing Queries, Regardless of Platform](https://towardsdatascience.com/learning-sql-201-optimizing-queries-regardless-of-platform-918a3af9c8b1) By Randy Au. I finally found a complete post on advanced SQL.

### Python 
  * [Python for Data Analysis](https://www.amazon.com/Python-Data-Analysis-Wrangling-IPython/dp/1491957662). Very comprehensive book about using python for data stuff. 
  * [Pandas Cheatsheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf) I use it everyday!
  * [TIL Python by Vicki Boykis](https://github.com/veekaybee/til/blob/master/python/pandas_cheat_sheet.md). Some tricks to deal with some frequent tasks when manipulating data.
  * [Modern pandas](https://tomaugspurger.github.io/modern-1-intro.html). A series of blog posts on intermediate/advanced pandas written by one of the maintainers. 

### Infrastructure

  * [The Startup Founder's Guide to Analytics](https://thinkgrowth.org/the-startup-founders-guide-to-analytics-1d2176f20ac1). An excellent introduction to the stack necessary for analytics and its evolution following the growth of the start-up.  
  * [The missing layer of Analytics Stack](https://blog.getdbt.com/the-missing-layers-of-the-analytics-stack). 
  * [Choosing a Data Warehouse](https://discourse.getdbt.com/t/choosing-a-data-warehouse/62/4). A lot of excellent answers on what to choose for your data warehouse. 
  * [Data science for start-ups](https://bgweber.github.io/intro.html). You can find some useful information in this free book.

  **Comparison of tools by Stephen Levin**
  * [Looker vs Tableau vs Mode. Data Visualisation tools compared](https://www.stephenlevin.co/advanced-analytics-part-3-data-visualization/). . 
  * [Segment vs Fivetran vs Stitch: Which Data Ingest Should You Use?](https://www.stephenlevin.co/segment-vs-fivetran-vs-stitch-which-data-ingest-should-you-use/)

### Analytics Skills
  * [One analyst's guide for going from good to great](https://blog.getdbt.com/one-analysts-guide-for-going-from-good-to-great/)
  * [Suceeding as the first data person in a small company/startup](https://towardsdatascience.com/succeeding-as-a-data-scientist-in-small-companies-startups-92f59e22bd8c). A must read for anyone working in data even in a big company. 
  * [Prioritizing data science work](https://towardsdatascience.com/prioritizing-data-science-work-936b3765fd45). Too many engineers like building ivory towers. Make sure you don't fall in the trap.

### Data Warehousing

  * [The beginner guide to data engineering series](https://medium.com/@rchang/a-beginners-guide-to-data-engineering-part-i-4227c5c457d7). Start here if you don't know what is a star schema, Airflow and some basic practices when writing data pipelines.    
  * [Best practices for data modeling](https://www.stitchdata.com/blog/best-practices-for-data-modeling/). A lot of practical tips on naming, grain, permissions and materialization. 
  * [The Data Warehouse Toolkit](https://www.amazon.com/Data-Warehouse-Toolkit-Definitive-Dimensional/dp/1118530802/ref=sr_1_1?crid=FV5A2S72XIZO&keywords=data+warehouse+toolkit&qid=1566644628&s=gateway&sprefix=data+ware%2Caps%2C213&sr=8-1) by Ralph Kimball. A classic in Business Intelligence. Some chapters can be gold on modeling your data warehouse.   
  * [Functional Data Engineering — a modern paradigm for batch data processing](https://medium.com/@maximebeauchemin/functional-data-engineering-a-modern-paradigm-for-batch-data-processing-2327ec32c42a). You will learn the spirit behind good data pipelines and a well-designed data warehouse.  
  * [The rise of the Data Engineer](https://medium.com/free-code-camp/the-rise-of-the-data-engineer-91be18f1e603). Explains recent evolutions of the job and data practices.   
  * [Five principles that will keep your data warehouse organized](https://blog.getdbt.com/five-principles-that-will-keep-your-data-warehouse-organized/)
  * [For Data Warehouse Performance, One Big Table or Star Schema?](https://fivetran.com/blog/obt-star-schema). Discussion on an alternative to star schema. 

### Data Pipelines

  * [Functional Data Engineering — a modern paradigm for batch data processing](https://medium.com/@maximebeauchemin/functional-data-engineering-a-modern-paradigm-for-batch-data-processing-2327ec32c42a). You will learn the spirit behind good data pipelines and a well-designed data warehouse.
  * [Maintenable ETL: Tips for Making Your Pipelines Easier to Support and Extend](https://multithreaded.stitchfix.com/blog/2019/05/21/maintainable-etls/). Best practices to write good ETL. 

### Starting analytics in a company
  * [Building a data practice from scratch](https://www.locallyoptimistic.com/post/building-a-data-practice/). Very useful for your first weeks as a data person. 
  * [The Startup Founder's Guide to Analytics](https://thinkgrowth.org/the-startup-founders-guide-to-analytics-1d2176f20ac1). An excellent introduction to the stack necessary for analytics and its evolution following the growth of the start-up.  


### Testing data
  * [Automated Testing In The Modern Data Warehouse](https://medium.com/@josh.temple/automated-testing-in-the-modern-data-warehouse-d5a251a866af). Practical advice to test data. Useful for everyone building data pipelines. Rare to found such a post dealing with non-sexy thing in data. 


### Success Stories
  * [Scaling analytics at Wish](https://medium.com/wish-engineering/scaling-analytics-at-wish-619eacb97d16)
  * [Building Analytics at 500px](https://medium.com/@samson_hu/building-analytics-at-500px-92e9a7005c83)

### Organisation
  * [Engineer shouldn't write ETL](https://multithreaded.stitchfix.com/blog/2016/03/16/engineers-shouldnt-write-etl/). It's more data science focused but it's a classic.
  * [Does my startup data team need a data engineer?](https://blog.getdbt.com/does-my-startup-data-team-need-a-data-engineer-/)

### Marketing and data
  * [Data Driven Marketing](https://www.amazon.com/Data-Driven-Marketing-Metrics-Everyone-Should/dp/0470504544/ref=sr_1_1?crid=38ZUOKHZZEY6D&keywords=data+driven+marketing&qid=1566644698&s=gateway&sprefix=data+driven%2Caps%2C209&sr=8-1). Reading some chapters can help you think like a marketer with data driven approach. It's a gem. Didn't find this kind of insights elsewhere.

### More rigor for the analyst
These books/articles helped me to think better when analysing data. 

  * [Common Data Mistakes to Avoid](https://www.geckoboard.com/learn/data-literacy/statistical-fallacies/). Excellent summary of the most common fallacies when analyzing data. Very clear and well-explained. 
  * [Thinking fast and slow](https://www.amazon.com/dp/0374533555/ref=cm_sw_em_r_mt_dp_U_wOryDb6WC3CVE). Learning about bias can be super useful. For instance, I didn't have the reflex to think of a base rate anytime I see a figure. 
  * [Fooled by randomness](https://www.amazon.com/Fooled-Randomness-Hidden-Markets-Incerto/dp/0812975219/ref=sr_1_1?crid=2QEXPWM35W0BR&keywords=fooled+by+randomness&qid=1566644880&s=books&sprefix=foole%2Cstripbooks-intl-ship%2C207&sr=1-1).
Nassim Taleb taught so much both professionally and personnaly. In Fooled By Randomness, you will learn about major pitfalls when dealing with data in **real life**. 
  * [Why you should care about the Nate Silver vs. Nassim Taleb Twitter war](https://towardsdatascience.com/why-you-should-care-about-the-nate-silver-vs-nassim-taleb-twitter-war-a581dce1f5fc). Great chess players learn from high elo games. Great data people learn from debate between data experts. 
  * [Five books every data scientist should read that are not about data science](https://towardsdatascience.com/five-books-every-data-scientist-should-read-that-are-not-about-data-science-f7335fb1f84f). I have not read them all yet. But these suggestions seems judicious. 


### Data Visualisation 
   * [Fundamentals of Data Visualisation](https://serialmentor.com/dataviz/). Complete guide to visualisation. Free version online.

### Other readings lists

I really love [Reading in Applied Data Science](https://github.com/hadley/stats337#readings). But it is more for data scientists.  
   The GitLab data team also made an [excellent list](https://about.gitlab.com/handbook/business-ops/data-team/#data-learning-and-resources). (close to mine)

# Top bloggers/blog
  * [Randy Au](https://towardsdatascience.com/@Randy_Au). You can read almost all his posts there are all very relevant for analytics engineers.
  * [Locally Optimistic](https://www.locallyoptimistic.com/). A blog dedicated to data in organizations. 
  * [Tristan Handy](https://medium.com/@jthandy). I also love his newsletter: [Data Science Roundup](http://roundup.fishtownanalytics.com/).


# Where is the community?
  * Dbt blog
  * Twitter
  * Locally Optimistic

