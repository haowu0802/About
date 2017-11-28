For Ormuco
-

Here are some of my experience that show a high correlation to the job functions described in the Senior Python role with Ormuco

## 0.worked on a cloud based fault injection platform, in a large telecommunication/cloud service company(Huawei) 2017

### `decouple and containerize`
> __Before__ I worked on it: different modules of the system are squeezed into one large, unstable, hard to maintain application.

> __After__ I worked on it: split the system into independent applications including - 
* a fault injection controller with Restful+GraphQL APIs as the central
* a front-end portal for UI that consumes the APIs
* distributed lightweighted computational applications for data processing and CPU heavy calculations that comes from the controller
* all containerized, free of installation/dependency/virtualenv hassle
### `restful API optimized with GraphQL(Graphene)`
> replace some inefficient restful APIs that over/under fetch all the time with GraphQL endpoint to reduce wasteful data transfer

## 1.worked in the data science team, of a mid-large TV show analysis company(Corbis) 2016
### `replace crontab for ETL tasks with Apache-Airflow`
> __Before__, with crontab: no logic between tasks, need devOps to manually intervene errors all the time

> __After__, with Apache-Airflow: Data Scientist can login to Airflow to manipulate, monitor tasks. Large tasks, related tasks are turned into Directed Acyclic Graphs, states and logics can be used.
### `made custom operator for docker interface`
>ETL tasks are containerized, but Airflow doesn't natively support operating containers, so I made a plugin to make it able to.
## 2.worked on APIs of a mid-large e-commerce company (Dangdang) 2012-2014
### `turn soap to rest`
> __Before__: API backend uses raw SQL to CRUD in SOAP manner. Manual table alterations. Lengthy table design -> review -> approve process.

> __After__: Resources are identified, as objects. ORM applied, migration introduced. No more raw SQL, better performance, easier alterations with migration.
---
|other relevant facts|
|:---:|
|started using python on and off since 2009, started using python full-time since 2014|
|python based tools used: Django/Restful, Flask, Apache-Airflow, SQLAlchemy, Graphene(GraphQL), NumPy, Pandas, Matplotlib|
|started coding with OOP since 2006(in college), recently digging into Golang for its goroutine and composition based class design, with python3.6 async and goroutine, fast and powerful things can be done.|
|deploy code to Heroku, use Docker for containerization, use Alpine images(minimal linux base images) with Python for applications.|
|started using MySQL since 2006(in college), know how to write raw SQL statements without ORM. |
|started using KeyValue DB (Redis) since 2012, MongoDB since 2016
started using version control since 2012(Subversion), then Mercurial(HG), now Git(github.com/haowu0802).|
|use agile(scrum) since 2012|
|like to use TestDrivenDevelopment with high unittest coverage|
---
# A general introduction

What I do
-
I'm a senior software engineer focusing on __backend__ development and __data__ engineering. 

I use Python for building __data pipeline__, __RESTful APIs__ and backend of __MVC__ web applications.

I code with __Agile, TDD__ methodologies and work remotely in most of my previous roles. 

A list of my skill set can be found in [my resume](https://github.com/haowu0802/About/blob/master/Resume_Senior_Software_Engineer_Hao_Leon_Wu.pdf)

Who I am
-
 
I'm a life time learner, coder and a tech geek. I started coding since junior high (MS-DOS 6.22), with modding computer games. I play computer games.

I believe in moving forward in small steady steps, in life and in coding, I persistently learn everyday.

I became close friends with most of my previous team members, and we enjoy continue working on interesting projects even after we no longer are in the same team. The relationship doesn't stop at being just co-workers.

What I'm looking for
-
A small team that is family like. A long term relationship.

A place that I can contribute my effort and craft to help making a difference.

A chance to share and learn from others, and improve the craft together.

What others comment on my work
-
Nicholas Johnson - Data Science Lead Developer - Corbis (Branded Entertainment Network)

>"I worked directly with Hao at the BEN Group data development/science team. While on our team Hao headed up the development of a critical ETL management system and deployed it to production, worked on data exploration and regression analysis projects, and also pushed our team to have improved development practices. Hao is a sharp, self-directed engineer that produces high quality, easy to understand software. He is also very business-oriented; he focuses on understanding the customer and delivering features that benefit the customer and ultimately the business."

December 28, 2016, Nicholas managed Hao directly
 
Posted on https://www.linkedin.com/in/haowu0802/
