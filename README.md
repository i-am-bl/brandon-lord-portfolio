# brandon-lord-portfolio

## Table of Contents

- [brandon-lord-portfolio](#brandon-lord-portfolio)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [FFIEC Data Transformation](#ffiec-data-transformation)

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

- **Python**\
  Chosen for the Pandas (data science) and SQLAlchemy (Object-Relational Mapping, or ORM) libraries. Pandas was used to read the SQL files, minor data manipulation, and to write the files to the database via SQL Alchemy.
- **Docker**\
  Chosen to provide a consistent environment for running the code. Explicit instructions can be found in the project README.
- **PostgreSQL**\
  Chosen due to its feature rich dialect of SQL and its popularity as an open-source RDBMS (Relationship Database Managment System).
