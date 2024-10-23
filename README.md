# brandon-lord-portfolio

## Table of Contents

- [brandon-lord-portfolio](#brandon-lord-portfolio)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [FFIEC Data Transformation](#ffiec-data-transformation)
  - [Customer Relationship Management (Services POC)](#customer-relationship-management-services-poc)

## Introduction

**Linkedin**: [www.linkedin.com/in/brandon-lord-mba](https://www.linkedin.com/in/brandon-lord-mba)

This repo is a summary of projects published as part of my portfolio. Each project is housed in its own dedicated repo. In the sections below, projects are detailed at a high-level to provide context on the primary focus, business use case, and skills showcased. Follow the link in each section to find each dedicated repo.

## FFIEC Data Transformation

**Project Link**: [Click Here](https://github.com/i-am-bl/ffiec-data-transformation)

**Project Summary**:\
Financial Institutions (FI) are federally regulated by the FFIEC (Federal Financial Institutions Examination Council). All data points reported by mandate are publically available at [FFEIC.gov](https://www.ffiec.gov/). Business use case is written from the perspective of a business targeting FIs and need to ingest FFIEC data to stramline their market analysis.

**Outcome**:\
FFIEC data was provided in the form of csv files. Python program was written to automate the importing of numerous csv files into a Postgres Database. SQL scripts were written to transform and clean data to meet business needs. Python program was written to automate the execution of scripts. Deliverable provided a value add that met the immediate business needs and it open for future iterations.

**Demonstrations:**\
Primarily focusing on SQL acumen in this project, demonstrations include the following:

- **DML (Data Manipulation Language)**\
  Operations include select, insert, update, delete, common table expressions, subqueries, window functions, etc.
- **DDL (Data Definition Language)**\
  Operations include table creation, table definitions, etc.
- **PL/pgSQL (Procedural Language/SQL)**\
  Procedures include variable declaration, loops, dynamic SQL, etc.

**Technologies**:

The following highlights the technologies applied. Each was selected for an attribute to demonstrate the contextual knowledge of capabilities offered.

- **Python**\
  Chosen for the Pandas (data science) and SQLAlchemy (Object-Relational Mapping, or ORM) libraries. Pandas was used to read the SQL files, minor data manipulation, and to write the files to the database via SQL Alchemy.
- **Docker**\
  Chosen to provide a consistent environment for running the code. Explicit instructions can be found in the project README.
- **PostgreSQL**\
  Chosen due to its feature rich dialect of SQL and its popularity as an open-source RDBMS (Relationship Database Managment System).

## Customer Relationship Management (Services POC)

**Project Link**: [Click Here](https://github.com/i-am-bl/crm-services-poc)

**Project Summary**:\
Growing pains are inevitable in start-ups. Simplicity is key to early success; maturity requires process. Maturing process requires time and solutions. Business use case is written from the perspective of a business maturing customer relationships and pricing strategies. This will discuss problems faced that includes but are not limited to price variations, unbilled revenue, incorrect billing, and difficulties managing contract agreements. To demonstration strong technical acumen, a POC (proof of concept) for API design was included to articulate solutions. This originated from a first-hand experience as a product manager managing price strategies in this environment.

**Outcome**:\
This case study encompasses some of the solutions that was implemented to solve real problems. The original solution included a flexible CRM with a low code solution for modifications. The low code tool simplified the code for the backend and front-end development; however, it still required the gathering of requirements, acceptance criteria, and solution design. The case study does not disclose any design of previous products used.

Solutions resulted in a decline in the billing problems and significantly decrease time spent managing price strategies.

Client succcess managers visited my office quite often, following the solutions, I rarely heard from them outside our scheduled time. Problems decreased by nearly 90%.

**Demonstration**:\
Primarily focusing on API design and problems faced managing extremely flexibly pricing strategy, demonstrations include the following:

- **Problem Definition**\
  Problem and solution brief establish a strong story for a clear understanding requirements.
- **Asynchronous API design**:\
  REST APIs include an asynchronous design pattern for for scalability.
- **Data Design**
  Design normalizes production data, allowing for efficient queries for performance and the ability to monitor data attributes for account management and pricing strategy.

**Technologies**:

The following highlights the technologies applied. Each was selected for an attribute to demonstrate the contextual knowledge of capabilities offered.

- **Python**:\
  This project is written in Python. Chosen for ease of use, readability, and access to the FastAPI framework.
- **FastAPI**:\
  An API python framework. Chosen for the asynchronous programming support, type safety, performance capabilities, and automatic documentation. Asynchronous non-blocking I/O is extremely efficient for interacting with the database layer, decreasing client wait times.
- **PostgreSQL**:\
  RDBMS (Relational Database Management System) technology, chosen for the feature rich dialect of SQL. It is an open-source solution that has well established branch and reputation in the market. Software defects are resolved quicker than other open-source solutions.
- **Docker**:\
  Chosen to provide a consistent environment for running the code.
