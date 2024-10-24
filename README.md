# brandon-lord-portfolio

## Table of Contents

- [brandon-lord-portfolio](#brandon-lord-portfolio)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [FFIEC Data Transformation](#ffiec-data-transformation)
  - [Customer Relationship Management (Services POC)](#customer-relationship-management-services-poc)
  - [Competitive Intelligence Owner](#competitive-intelligence-owner)

## Introduction

**Linkedin**: [www.linkedin.com/in/brandon-lord-mba](https://www.linkedin.com/in/brandon-lord-mba)

This repo is a summary of projects published as part of my portfolio. Each project is housed in its own dedicated repo. In the sections below, projects are detailed at a high-level to provide context on the primary focus, business use case, and skills showcased. Follow the link in each section to find each dedicated repo.

## FFIEC Data Transformation

**Project Link**: [Click Here](https://github.com/i-am-bl/ffiec-data-transformation)

**Project Summary**:\
Financial Institutions (FI) are federally regulated by the FFIEC (Federal Financial Institutions Examination Council). All data points reported by mandate are publicly available at [FFEIC.gov](https://www.ffiec.gov/). Business use case is written from the perspective of a business targeting FIs and needs to ingest FFIEC data to streamline their market analysis.

**Measurements (KPIs)**:

- Time spent gathering data to analyze.
- Segmenation of the market.

**Objectives**:

- Decrease time spent gathering data to analyze.
- Increase marketing click through rates by 0.5% through market segmentation.
- Align marketing and sales for an increase in deal closure by 3%.

**Outcome**:\
FFIEC data was provided in the form of csv files. Python program was written to automate the importing of numerous csv files into a Postgres Database. SQL scripts were written to transform and clean data to meet business needs. Python program was written to automate the execution of scripts. Deliverable provided a value add that met the immediate business needs and it open for future iterations.

**Key Takeaways and Lessons Learned**:\
Environments with a rapid pace can drive great employees to work harder, looking for ways to contribute. Contributions can lead to unguided duplicity. "Do more with more people," can misinterpreted as "redoing the same work differently," effectively diminishing the success level. It is okay to stop and say, "this is not working." The expense in time to invest in a bigger idea can offer a much larger return in the long term compared to forgoing the cost. This case study is a first-hand experience where the problem transparent but required the mindset of a leader to change the plan of execution.

**Demonstrations:**\
Primarily focusing on SQL acumen in this project, demonstrations include the following:

- **DML (Data Manipulation Language)**\
  Operations include select, insert, update, delete, common table expressions, subqueries, window functions, etc.
- **DDL (Data Definition Language)**\
  Operations include table creation, table definitions, etc.
- **PL/pgSQL (Procedural Language/SQL)**\
  Procedures include variable declaration, loops, dynamic SQL, etc.

**Technologies**:\
The following highlights the technologies applied. Each was selected for an attribute to demonstrate the contextual knowledge of capabilities offered.

- **Python**\
  Chosen for the Pandas (data science) and SQLAlchemy (Object-Relational Mapping, or ORM) libraries. Pandas library was used to read the SQL files, minor data manipulation, and to write the files to the database via SQL Alchemy.
- **Docker**\
  Chosen to provide a consistent environment for running the code. Explicit instructions can be found in the project README.
- **PostgreSQL**\
  Chosen due to its feature rich dialect of SQL and its popularity as an open-source RDBMS (Relational Database Managment System).

## Customer Relationship Management (Services POC)

**Project Link**: [Click Here](https://github.com/i-am-bl/crm-services-poc)

**Project Summary**:\
Growing pains are inevitable in start-ups. Simplicity is key to early success; maturity requires process. Maturing process requires time and solutions. Business use case is written from the perspective of a business maturing customer relationships and pricing strategies. This will discuss problems faced that include but are not limited to price variations, unbilled revenue, incorrect billing, and difficulties managing contract agreements. To demonstrate strong technical acumen, a POC (proof of concept) for API design was included to articulate solutions. This originated from a first-hand experience as a product manager managing price strategies in this environment.

**Measurements (KPIs)**:

- Instances of incorrect billing.
- Instances of missed contract renewal dates.

**Objectives**:

- Retain historical pricing information to provide actionable insights into pricing strategy.
- Implement more control for allowed price adjustment per product (global scope) and price list (local scope).
- Store relevant contract information facilitate client relationship monitoring.

**Outcome**:\
This case study encompasses some of the solutions that were implemented to solve real problems. The original solution included flexible CRM with a low code solution for modifications. The low code tool simplified the code for the backend and front-end development; however, it still required the gathering of requirements, acceptance criteria, and solution design. The case study does not disclose any design of previous products used.

Solutions resulted in a decline in the billing problems and significantly decreased time spent managing price strategies.

Client succcess managers visited my office quite often, following the solutions, I rarely heard from them outside our scheduled time. Problems decreased by nearly 90%.

**Key Takeaways and Lessons Learned**:\
Strategic direction can be a slow ship to turn. The shift can uncover difficult problems to solve. When difficult, it can be easy to fight change, but a difficult problem can be an indicator that change is needed. Pricing strategies with 1–5-year agreements can have a lagging impact on the future pricing strategy. In this case, the focal point was shifting strategy. The strategy was strong, the plan of transition was weak.

This case is written from the first-hand experience as a price strategy owner. Communication was low in a resource limited environment. Shifts were made and notifications were distributed after. Requirement gathering is a well-established paradigm for product development due to the high cost. Requirement gathering is important for all business areas, not just development.

**Demonstration**:\
Primarily focusing on API design and problems faced managing extremely flexible pricing strategy, demonstrations include the following:

- **Problem Definition**\
  Problem and solution brief establish a strong story for a clear understanding of requirements.
- **Asynchronous API design**:\
  REST APIs include an asynchronous design pattern for scalability.
- **Data Design**
  Design normalizes production data, allowing for efficient queries for performance and the ability to monitor data attributes for account management and pricing strategy.

**Technologies**:\
The following highlights the technologies applied. Each was selected for an attribute to demonstrate the contextual knowledge of capabilities offered.

- **Python**:\
  This project is written in Python. Chosen for ease of use, readability, and access to the FastAPI framework.
- **FastAPI**:\
  An API python framework. Chosen for the asynchronous programming support, type safety, performance capabilities, and automatic documentation. Asynchronous non-blocking I/O is extremely efficient for interacting with the database layer, decreasing client wait times.
- **PostgreSQL**:\
  RDBMS (Relational Database Management System) technology, chosen for the feature rich dialect of SQL. It is an open-source solution that has well established branch and reputation in the market. Software defects are resolved quicker than other open-source solutions.
- **Docker**:\
  Chosen to provide a consistent environment for running the code.

## Competitive Intelligence Owner

**Project Link**: [Click Here](https://github.com/i-am-bl/competitive-intelligence-owner)

**Project Summary**:\
The complexities of intelligence gathering can greatly differ between industries. Products with self-sign-up that offer a free trial are much easier compared to larger commercial products that require two sales calls to receive a demo. There are numerous frameworks for analyzing data, but data collection comes first.

A strategy for producing competitive intelligence is essential to effective ownership. Executive buy-in on the strategy should be the first step. This first-hand experience describes how the strategy shifted when strong buy-in was not present. The strategy for market coverage quickly shifted from a few to many with little notice. The question of "what are they doing", quickly became "what is everybody doing?" Case study discusses how an effective outcome was produced to overcome resource limitations to meet expectation for market coverage.

**Measurements (KPIs)**:

- Engagement rate of CI owner.
- Growth rate of competitive intelligence knowledge base.
- The shared understanding the competitive landscape between business units.

**Objectives**:

- Decrease the engagement rate with CI owner by 20%.
- Centralize data, establishing an accessible knowledge base.
- Increase the growth rate of CI by 5% quarter over quarter.

**Key Takeaways and Lessons Learned**:\
Executive buy-in for a competitive intelligence strategy is essential for clearly defining the scope of coverage. Without early buy-in, it can quickly become a wish list for information that can be difficult to prioritize. I learned the cost in time to gain this buy-in is worth the cost to have clear communication.
