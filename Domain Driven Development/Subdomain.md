#DDD #Design #StrategicDesign #SoftwareDevelopment
# Definition
The subdomain is a business activity to solve a problem; we can say that subdomains are problem space, and [[Bounded Context]]—solution space. This defition implies that subdomain is a set of coherent and interrelated use-cases. 

# Types of subdomains
There are three subdomains types:
- Core subdomain
- Generic subdomain
- Supporting subdomain
## Core subdomain
This is a company main activity, for example McDonalds offers fast-food services for its customers. Core subdomain is complex and other companies can't copy it. Also, core subdomain is volatile, because companies trying to improve and innovate it to do more money in future.
## Generic subdomain
This is a common thing used by all companies, like in-app authorization or e-mail newsletter. Often it is hard to implement, like authorization, where you would like to use cryptographic things to provide security.
## Supporting subdomain
This is an activity that unique for certain business but this is common to implement, likely most [[CRUD]] or [[ELT]] systems. The goal of supporting subdomain is simplify business tasks. Supporting subdomains are not important much like core subdomains, because they don't make money, but they help to make money.

![[Determining subdomain type (Figure 1.1).png]]
