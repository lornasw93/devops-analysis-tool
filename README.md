# DevOps Analysis Tool

*From fun side project to new company internal tool*

## 💡 What is it?
An unhealthy engineering team leads to infrequent product releases, mass defects and low customer satisfaction rates.
 
I've developed a web app tool to simplify common DevOp tasks in a single place using a combination of the Bitbucket, Team City and Octopus Deploy APIs in Node.js and Angular 11.

BETA target audience is for management with the plan after release to expand to (and not limited to) software devs, QA and product owners.

## ⚡ Motivation
I started this side project pretty much as soon as I started at IRIS back in September 2020 and have worked on the project 90% in my own time purely for fun and self-learning. I enjoy data analysis, spreadsheets, documentation. Previously in another role, I created a very similar side project to this but for Azure with the sole target audience being devs.

Main product I work on uses Bitbucket, Teamcity, Octopus Deploy and Jira - I wanted to consolidate key info within a single place.

## 💻 Tech Stack
* Frontend: Angular 11
* Backend: Node.js
* Hosting: Azure (not implemented yet, in process)
* Authentication: Azure Active Directory (not implemented yet, in process)
* Other: Docker, APIs

## ⭐ Features
* Improve existing processes
* Highlight (potential) issues    
* Highlight inconsistencies i.e. tags    
* Less clicks i.e. finding common info quick without the noise    
* Centralising useful info in 1 place    
* Measurable data e.g.:
    * DORA
	    * Deployment Frequency
	    * Lead Time for Change
	    * Time to Restore Services
	    * Change Failure Rate
    * Other
	    * Defect Density
	    * QA Pass Rate
	    * Sprint Completion Ratio
	    * Outstanding Defects
* Build dynamic shareable dashboards
* Chart trends
* Data dumps

## 👷‍♀️ Layout

## 🎨  Mockups

## Other
* [Blog post](https://dev.to/lornasw93/exploring-team-city-api-with-examples-55dm) I wrote about findings with Teamcity API 
