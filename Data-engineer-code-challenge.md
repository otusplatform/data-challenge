# OTUS Data Engineering Take Home 
## Coding
**Wikipedia Log scraping and analysis**

**Your assignment** 

Publish a repo on Github that i can clone and run on my local machine. Your repo should contain full code for a program that scrapes [https://dumps.wikimedia.org/](https://dumps.wikimedia.org/) across 7 days (pick your date range) and can answer the following questions
	
	1. Most requested article by day
	2. Least requested article by day
	3. Top 5 categories by day

 Use Python or a JVM language to complete this.
 
	1. If you use a JVM language, avoid the use of mega-frameworks like Spring Data.  
	2. Automated tests need to be in place
	3. Support for running on Kubernetes should be in place
	
**How we evaluate**
	1. Functionality — Does your program work according to the specifications of the problem?
	2. Modeling — Is the program's control flow clear?
	3. Documentation — Is your code appropriately documented in the form appropriate to your implementation language?
	4. Language Use — Do you make good use of the features available in the language you chose?
	5. Testing — Did you include tests that explain and reinforce the design of your code?


## Written
**New Systems** 
 We are building a brand new query engine with a brand new backend and reusing a frontend and have 6 months to deliver query with a team of 4 people plus you.  2 sr platform ´engineers (same as this role) and 2 jr full stack engineers.

The high level requirements are that:
	* the new system should pull data from the original monolith system (PHP/Node & Angular & RDS mysql)  at near real time (5 seconds delay is OK ) - this monolith is the source system and we want the new query system to treat its datastore as ephemeral    
	* the new UI will be built on top of the older angular pages and components and hence be coupled to other teams who use the same frontend
	* the data layer and APIs will be built brand new and need to be able to serve up the data for 300k students in 1-2 seconds across a time range of 3 years - data includes grades, attendance, standardized test reports, Otus Assessments, gender, ‘race’, subjects/class, school district, and teacher.  
	* the infra for the new system is in place - EKS/K8s, Codefresh, AWS, Terraform, Prometheus, Sumo, Grafana, PagerDuty.  
	* The old system and the new system are both on AWS.  They can be in the same or different AWS accounts.
	* the team is small 4 people and we optimize for speed and delivery - we use managed services wherever possible.
	* SLOs need to be defined and adhered to for the new service(s).

Whats the high level logical architecture look like for this? What services and tech would you select for this system?  How do you rationalize those decisions? Summarize your approach in a 1-2 page document.

**Ramping up**
Explain what an ideal 30/60/90 day plan looks like for you as you start a new role with Otus. This is important since we are small and you will need to self-direct most days.

## Timeframe for this assignment
 You set the date.  This gives you plenty of time to do this. 


#work/otus/coding_challenges/data
