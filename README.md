# Utility-Rate-Cases

We have experimented with data collection of closed proceeding documents for five rate cases in California (CA) and seven (major) electric utility rate cases in New York (NY). Data includes filed documents and public comments associated with the regulatory dockets. Of note, we have developed a tool based on Selenium Python to automate web browser interactions. We have used this tool in preliminary efforts to semi-automatically collect proceeding files and public comments. We have only uploaded the CA cases in this repository due to storage limit.

The specific steps for collecting the data for CA are as follows:
-	Go to [the proceeding information search website](https://apps.cpuc.ca.gov/apex/f?p=401:1::::::) 
-	In the search panel, enter a specific company name in the filer field and then click “Search”.
-	Examine closed proceedings related to rate increases.
-	Click the proceeding number to access the case details.
-	Download all documents under the “Documents” tab and the PDF document of public comments under the “Public Comments” tab.
-	Repeat these steps to collect all available cases for each of the three IOUs in California.

The specific steps for collecting the data for NY are as follows:
-	Go to [the Pending and Recent Electric Rate Cases website](https://dps.ny.gov/pending-and-recent-electric-rate-cases). 
-	On the left side, navigate to a company, such as Central Hudson Gas & Electric, under Pending Cases.
-	Find a past case and click on it.
-	Download all documents under the “Filed Documents” tab and download all public comments for that case. Note that, for NYS, it also has a party list  available in each of the rate cases, and we are also collecting that information.
-	Repeat these steps to collect all past cases for each of the seven IOUs in New York.
