# princeton-scraping-task

##Background

Because some of the richest data on real-world social behavior and outcomes is now generated or stored online, our lab’s research frequently draws on data from various online sources (e.g., Twitter, university websites, Department of Education and other federal databases). Gathering this data often requires web scraping using either APIs or custom web crawlers, and then transforming the raw scraped data into a format that can be easily merged with other data (typically CSV files).
In a previous project, we scraped information about colleges and universities from US News and World Report’s [Best Colleges](https://www.usnews.com/best-colleges) lists. We subsequently linked this scraped data to other education datasets in order to look at the associations between college characteristics and psychological variables. We would like you to replicate the web scraping component of this project.

## Instructions

For each school listed in [US News 2021 Best National University Rankings](https://www.usnews.com/best-colleges/rankings/national-universities), we would like you to scrape the name of the school, the national university ranking, the overview text, and the 7 fields listed under “General Information” (school type, year founded, religious affiliation, academic calendar, setting, 2019 endowment, and school website). For example, for [Princeton's page](https://www.usnews.com/best-colleges/princeton-university-2627), this would include the 10 pieces of information identified in red on the next page of this document.

We would like you to return this scraped data in a CSV file that has one row per university with 10 columns, one for each piece of information. You do not need to worry about cleaning the text; for example, if the overview text includes embedded hyperlinks, ads, or weirdly spaced text, that is fine. We don’t want you to spend too long on perfecting this, as the goal is just to show that you can apply your web scraping skills to a typical use case in our lab.

Please let us know if you have any questions! Also, if you believe that this scraping task is not possible for any reason, please let us know (and let us know what you tried and what barrier(s) you encountered). It has been a couple years since we did this scraping task, so it is possible that something on the US News site has changed to prevent scraping.
