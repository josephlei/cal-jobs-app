# California Jobs Application
### A more user friendly version of www.jobs.ca.gov

This application is intended to be a demonstration project showcasing the advantages of "freeing" the data contained in the state jobs database to application developers and job seekers.

**Advantages:**
* Puts the right information in front of the right job seekers, easing the learning curve of applying for a state position
* Simplified syndication to external jobs websites, multiplies the effective force of each job posting
* Extends functionality of existing information (for example, geocoding locations for a more granular "within x miles from me" search)
* Reduces state processing of applications that may not be logistically feasable (more on this to come)
* Technology stack utilizes high availability and open source software: Heroku hosted MongoDB, NodeJS, Python, Kimono, Django/Flask/Pyramid/Other (templating framework TBD)

**Disadvantages:**
* Without direct API or other access to the raw repositories, this service will be reliant on 3rd party aggregation tools.  Any downtime or failures will be propagated to production
