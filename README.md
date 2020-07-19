# Job Searching Optimizer
As a new grad, I found some company when they post a job online, thy would put the job under entry lvl and associate lvl and ask for 5 - 10 years of experience. And some job that is recommend to me doesn't really fit my skill set. So I decided to make my own job searching database and use NLP and AI to optimize my job searching experience. 
### Project Plan
#### 1. Web Scraping
Since glassdoor has interactive web page that requires clicks to reveal the hidden element, I choose to use selenium to scrape the job information I need, which includes job title, company name, job description and apply link. And I would return a dataframe after and save it into postgresql database. I already finished this part with the help of this [repo](https://github.com/arapfaik/scraping-glassdoor-selenium).
#### 2. NLP
This is a relatively new area for me and I'm still learning. Now I'm thinking using RNN or LSTM to train my algorithm. 
