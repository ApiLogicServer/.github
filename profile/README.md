# .github

# Why: Partial Automation, Proprietary IDEs

We saw __shortfalls in current approaches__ for building database systems:

* __Frameworks: too slow -__ _multi-endpoint APIs_ and _multi-page apps_ would require _weeks_ in frameworks such as Flask or Django, since it's all code -- no automation

* __Low Code Tools: no backend automation, proprietary IDEs__ - good UI automation, but none for backend business logic (nearly half the effort), and often do not leverage existing IDEs (VSCode, PyCharm, etc).

&nbsp;

# Instant, Full System Automation, Leverage Existing Tools
So, we created API Logic Server as an __open source__ Python project: a __CLI__ for project creation, and a set of __execution runtimes.__  Install with a standard Python (`pip`) install or Docker.<br/><br/>

## Project Creation is Instant: Single Command
 
&nbsp;&nbsp;&nbsp;&nbsp;
`ApiLogicServer create --project_name=ApiLogicProject --db_url=`<br/><br/>


## Projects are Highly Functional: Admin UI and API
API Logic Server reads your schema, and creates an  __executable__ project:

* __API__ - an endpoint for each table, with filtering, sorting, pagination and related data access

* __Admin UI__ - multi-page / multi-table apps, with page navigations and automatic joins<br/><br/>

## Projects are Customizable: Using _Your_ IDE

Customize projects in __your IDE__ (VSCode, PyCharm, etc.) for edit, debug and code management.<br/> <br/>


## Business Logic is Automated: Unique Rules :trophy: 

Declare business logic with spreadsheet-like rules (40x more concise than code), extensible with Python.

&nbsp;

# Exploration Guide

Extensive [documentation is available here](https://valhuber.github.io/ApiLogicServer/) - checkout the [FAQs](https://valhuber.github.io/ApiLogicServer/FAQ-Frameworks/).
