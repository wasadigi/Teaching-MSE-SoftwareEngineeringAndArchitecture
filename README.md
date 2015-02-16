# Welcome to the Software Engineering & Architecture (SEA) Git Repository

## Introduction

In the second part of the course, we will focus on agile development methodologies, practices and tools. Our goal is to have a **balance between theory and practice**. For this reason, the program will combine the following elements:

1. **Lectures**, where we will **introduce concepts and present theoretical background**. For instance, we will talk about [software evolution](http://en.wikipedia.org/wiki/Software_evolution) and explain how the philosophy of agile development is not something new (the limits of the waterfall model have been identified decades ago). We will also talk about [software reengineering](http://scg.unibe.ch/download/oorp/) and explain how these types of projects are different from *green field* software development projects. In terms of practices, we will talk about [continuous delivery](http://continuousdelivery.com/) and [behavior driven development](http://dannorth.net/introducing-bdd/).

2. **Labs & Experiments with Tools**, where will introduce several software engineering tools. Firstly, in the area of **continuous delivery**, we will present tools such as [jenkins](http://jenkins-ci.org/) and its relationship with other tools like [maven](http://maven.apache.org/) and [git](http://git-scm.com/). We will also show that it is now possible to [build continuous delivery pipelines in the cloud](http://www.cloudbees.com/). Secondly, in the areas of **behavior driven development**, we will introduce tools like [jbehave](http://jbehave.org/), [cucumber](http://cukes.info/) and [selenium](http://docs.seleniumhq.org/).

3. **Case Studies**, where we will **learn about the concrete experience of practitioners** who have applied agile methodologies and practices on real projects. Do the methodologies really work? What is the difference between what you read in books and what you experience in real life? What are the quick wins? What is hard? How do you concretely put continuous delivery and behavior driven development in practice? We will hear from **guest speakers** who have gained experience both in different types of organizations, **from start-ups to large corporations**.

## Schedule

 *Agile Topics, taught by Olivier Liechti* 

Date    | Topic  | Lab
--------|--------|------
16.02.2015  | Intro to agile development | [Intro to vagrant & docker](https://github.com/wasadigi/Teaching-MSE-SEA-Lab-VagrantDocker)
23.02.2015  | From continuous integration to continuous delivery | Building a CI/CD pipeline
02.03.2015  | Behavior Driven Development (BDD) | BDD in practice  
09.03.2015  | Agile testing | Building an integrated testing infrastructure
16.03.2015  | Agile development in practice (Guest) | Designing an agile room

 *Architecture Topics, taught by Olivier Biberstein* 
 
Date    | Topic  | Lab
--------|--------|------
23.03.2015  | | 
30.03.2015  | | 
13.04.2015  | |  
20.04.2015  | |
27.04.2015  | |

  *Evolution Topics, taught by Olivier Liechti* 

Date    | Topic  | Lab
--------|--------|------
04.05.2015  | Software evolution | Software quality with SonarQube 
11.05.2015  | Software re-engineering | Group activity 
18.05.2015  | Group presentations | Group presentations 
01.06.2015  | Guest speaker (TBD) | Recap/Q&A session before the exam 


## Evaluation

All activities organized in the context of the course, including the **lectures**, the **presentations of guest speakers** and the **practical work with tools**, will be evaluated in the exam. Since it is an *open books* exam, you should be ready to express your opinion and to express your own thinking about the course material (rather than simply reproducing the content of slides).

A list of readings will also be provided for every lecture. You will have to read and be familiar with the content of these readings before the exam, as there will be questions on this material as well.

## Readings

1. The Scrum Methodology
    * [Overview](http://www.mountaingoatsoftware.com/agile/scrum/overview)
    * Roles: the [Scrum Master](http://www.mountaingoatsoftware.com/agile/scrum/scrummaster/), [Product Owner](http://www.mountaingoatsoftware.com/agile/scrum/product-owner/) and the [Team](http://www.mountaingoatsoftware.com/agile/scrum/team/)
    * Artifcats: the [Product Backlog](http://www.mountaingoatsoftware.com/agile/scrum/product-backlog/), the [Release Burndown Chart](http://www.mountaingoatsoftware.com/agile/scrum/release-burndown/), the [Sprint Backlog](http://www.mountaingoatsoftware.com/agile/scrum/sprint-backlog/) and the [Task Board](http://www.mountaingoatsoftware.com/agile/scrum/task-boards/)
    * Ceremonies: the [Daily Scrum](http://www.mountaingoatsoftware.com/agile/scrum/daily-scrum/), the [Planning Meeting](http://www.mountaingoatsoftware.com/agile/scrum/sprint-planning-meeting/), the [Spring Review Meeting](http://www.mountaingoatsoftware.com/agile/scrum/sprint-review-meeting/) and the [Sprint Retrospective](http://www.mountaingoatsoftware.com/agile/scrum/sprint-retrospective/)
    
2. Software Evolution
    * A [seminal article](papers/softwareEvolution/Lehman-LawsOfSoftwareEvolution.pdf) by Lehman on the laws of software evolution (1980) and a [more recent article](papers/softwareEvolution/Lehman-SoftwareEvolutionOverview.pdf) by Lehman which gives an overview of 35 years of research in this field.
    * An [article](papers/softwareEvolution/Parnas-SoftwareAging.pdf) by Parnas that discusses software evolution issues with an interesting analogy.

3. Object Oriented Reengineering
    * The [book](http://scg.unibe.ch/download/oorp/) on the subject, on which the lecture was based (free pdf available for download).
    
4. Continuous Delivery
    * [Free chapter](./papers/continuousDelivery/ContinousDeliveryPipeline.pdf) of the Continuous Delivery [book](http://www.amazon.com/dp/0321601912?tag=contindelive-20) and [companion web site](http://continuousdelivery.com/).
    
