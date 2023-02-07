# .github

# Getting Started

API Logic Server is an open source Python project to make it faster and easier to create __database web applications.__  It provides a CLI to create customizable projects with a single command, that you can then run / customize / debug in your IDE.  

Created projects provide an API, an Admin Web App, and spreadsheet-like business rules to enforce database integrity. They can be containerized to simplify deployment. 

Additional background is provided in the next section, below.  Extensive [documentation is available here](https://apilogicserver.github.io/Docs/) - checkout the [FAQs]([https://valhuber.github.io/ApiLogicServer/FAQ-Frameworks/](https://apilogicserver.github.io/Docs/FAQ-Low-Code/)).

You can use this page in 2 ways:

* __Tutorial:__ [Click here](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=593459232) to open codespaces to see a created project.
    * Includes the **Learning Center:** a "quick access" table that illustrates key concepts for Flask and SQLAlchemy.
    * These concepts apply to both an API Logic Server Project, and a manually coded project -- you can explore both.

* __Create a Project:__ [Click here](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=526240678) to open codespaces with instructions for creating and exploring the sample project ([preview](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=580569201) here).

&nbsp;

# Why: Partial Automation, Proprietary IDEs

We saw __shortfalls in current approaches__ for building database systems:

* __Frameworks: too slow -__ _multi-endpoint APIs_ and _multi-page apps_ would require _weeks_ in frameworks such as Flask or Django, since it's all code -- no automation

* __Low Code Tools: no backend automation, proprietary IDEs__ - good UI automation, but none for backend business logic (nearly half the effort), and often do not leverage existing IDEs (VSCode, PyCharm, etc).

&nbsp;

# Instant, Full System Automation, Leverage Existing Tools
So, we created API Logic Server: with a single command, create __executable / customizable database projects__, providing an __Admin App__, an __API__, and __spreadsheet-like rules__ for business logic.

API Logic Server is an __open source__ Python project: a __CLI__ for project creation, and a set of __execution runtimes.__  Install with a standard Python (`pip`) install or Docker.<br/><br/>

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


