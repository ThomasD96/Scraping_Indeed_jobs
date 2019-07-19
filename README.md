# What are today's in-demand skills in the data science market?

So, you have read the [Harvard Business Review](https://hbr.org/2012/10/data-scientist-the-sexiest-job-of-the-21st-century) report proclaiming that data science is the *sexiest job* of the 21st century, and want to become a data scientist yourself. You have an advanced quantitative degree with some programming experience and believe that you are a good fit for such roles. You go to Indeed.com and start searching for relevant jobs. But...

Have you been applying to data scientist jobs recently and getting overwhelmed by the demands of the job listings? Don't know where to start and which technologies to learn? Do the fancy job titles like Data scientist, Data Analyst, Data Engineer, DevOps Engineer, Machine Learning Engineer, AI Engineer,... confuse you? 

You have come to the right place! This notebook will help you scrape job listings from [Indeed.com](Indeed.com) and analyse the key skills that employers are looking for in a data scientist/data engineer.
<img src="Frustration.jpg" alt="Drawing" style="width: 300px; height: 300px"/>

#### **The code works as follows:**

- The user enters his/her desired job title and the city of choice. This constitues a search query.
- The code takes this information and scrapes Indeed.com for all the job links that it throws up for the given search query.
- Then it analyzes the job descriptions and looks for relevant keywords. 
- Creates a nice visualization where you can see which technologies and skills are most searched for by employers in your region.
- Job listings in two cities -- **Pune** (India) and **Toronto** (Canada), are compared.


