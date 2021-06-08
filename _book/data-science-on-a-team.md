# Data Science on the CCPS Team {#team}

## What is data science? 

Translation of raw data into insight, actionable intelligence.

Can usefully divide the work into stages of *data*, *analytics*, and *communications*.

<img src="/Users/Arthur/GitRepos/Teaching/data_science/boot-camp/images/data-science-explore.png" width="80%" style="display: block; margin: auto;" />


*Data*: acquiring, organizing, managing, curating data (= symbols representing some measurements about the world); reformating and staging data to make it ready for analysis. 
      - In practice, these activities absorb ~ 80% of the time of a working data scientist. (Your best friend is a good data manager!) 
      - Hence the value of *data standards*: the more consistency in the way *meaning* is represented in data, the less time, tedium, and expense spent on data mapping and transformations. 
      
*Analytics*: statistics, machine learning, modeling, other techniques for extracting summary intelligence from data. 
      - In general, data science practitioners don't work on developing new techniques, nor on writing code to efficiently implement techniques. Those are specializations. Most of the work involves identifying the appropriate techniques, and the right software to implement those techniques, given the data and the goals. In some cases, work will be done in close collaboration with domain area specialists, e.g., climate scientists.
      
*Communications*: creating visualizations, narratives, etc., to reveal complexity, to convey insights. Also includes the creation of reports, dashboards, other *data products*.

Doing data science requires a mix of skills: computing; statistics and other analytics; visual design and communications.

## Data science projects and products 

The overall mission of the Cooper Center is to leverage the resources of UVA in public service to Virginia and beyond. We have a particular focus on providing assistance to state and local officials, and to other community stakeholders. A substantial share of this work involves generating and delivering insights based on analysis of data.

### Decision tools and dashboards

The DMME Dashboard

The SolTax tool; the SolDev tool

CTE Trailblazers dashboards: growth; gaps

### Publications

Virginia decarbonization studies

Virginia Local Tax Rates survey

Virginia Energy Almanac

CTE Trailblazers publications: cluster briefs, longer reports

Academic publications

Student-led projects and publications

### Research 

Energy systems modeling

Virginia Paid Family and Medical Leave analysis

Many others, including those in collaboration with colleagues across UVA and beyond:
* Hurricane evacuation (with Engineering)
* Negative emissions 
* Carbon sequestration risks
* ...


## Shared resources

Our organization site on Github

Code base:
* Code for data cleaning and preparation
* Code for data visualization

Databases: PostgreSQL database; MySQL database; collections of flat files

Share files and folders - generally, project-specific: Box; OneDrive

Remote file storage

Slack

*Cogito, ergo Zoom.*

(Email? Not so much.)


## Working collaboratively in a team

When working on a personal project, such as a student assignment, it is typically not so necessary to assure that others can access, learn from, critique, reproduce, and build on your work. 

In a team setting, it is mandatory. 

We have adopted tools, processes, workflows to try to assure that your own work can be used by others, and vice versa.


## Reproducible workflows

Essential for us that workflows be *reproducible*, auditable, transparent. 

### The concept of reproducibility

Idea: when you present your results, you present *all* of the data and the code that another practitioner (of reasonable skill) would need to reproduce your work.[^1] 

[^1]: We distinguish *reproducibility* versus *replicability*. Your work is *reproducible* if someone else can regenerate exactly your same results, using your data and your code. Your research results are *replicable* if another researcher can get essentially the same results when applying your techniques to different but comparable data. 

We are very much a "reproducible workflow" shop. In ideal practice this means:

* If you generate a report or other data product, you should be able to reproduce it entirely by re-running your code. If you were to delete your report, you should be able to regenerate it exactly, simply by re-running your code. This process should require no manual inputs from you, no cutting-and-pasting. 

* If you provide someone else with your code and your data, they should be able to reproduce your report by running your code on their machine. This should be true even if they are using a different type of machine, with a different operating system and directory structure. They should not need to edit your code, make manual inputs, or perform any cut-and-paste operations. 

### How we create reproducibility in practice

These conditions are ideals. In practice, we want to get as close as we can, within reason. Many of the tools that we use, and work processes we adopt, are designed to make our workflows hew closely to this ideal of full reproducibility. 

R Markdown is designed specifically to enable the generation of reports and other products reproducibly. 

Git and Github enable frequent backup of code and other files, and collaboration between colleagues without losing version control.

Cloud servers for maintaining files and databases help assure that our work is available to each other, properly backed up and curated, and organized in a structured way to facilitate reuse, without loss of version control.

We seek to avoid as much as possible exchanges of the form, "I don't know why my code won't work on your machine. It runs just fine on mine!"

In particular: except possibly in the course of single work session, you should never have work-related data or code that exists only on your own machine. Ever. Your work, including data and code, should always be backed up to resources that are accessible by other team members.


<!-- # Materials from [Basecamp](https://3.basecamp.com/4370323/buckets/15566178/documents/2688047578) -->

<!-- R and R Studio -->
<!-- Datacamp -->
<!-- Cheatsheet for ggplot2 -->
<!-- R for Data Science  -->
<!-- Coursera  -->
<!-- R Documentation -->
<!-- Stack Overflow   -->


<!-- R Shiny  -->
<!-- Tutorial -->

<!-- git and Github -->
<!-- Background Info -->
<!-- Version Control Info -->
<!-- Please edit your Github profile to show your name. A photo is nice, too. -->

<!-- SQL and PostgreSQL -->
<!-- Background Info -->
<!-- How to access database? -->
<!--  Doc&Files -> Instructions for DB access  -->

<!-- Zotero -->
<!-- Team Link  -->
<!-- Background Info  -->

<!-- Zoom/Collab -->
<!-- Team Link  -->

<!-- Markdown and R Markdown -->
<!-- Background -->
<!-- More Background Info  -->
<!-- R Markdown: The Definitive Guide -->

<!-- One Drive  -->
<!-- Syncing R and OneDrive: Download and install the OneDrive desktop app that syncs  cloud files with a folder on your local machine. Then point the R code to that folder.  -->
<!-- Note: One can use OneDrive as the home for several repos, especially if project data files are too large to post on Github. Add an appropriate line to the .gitignore file to tell git not to sync the large data files. Thus the data files can be kept locally together with the other files in the repo, and can be accessed by other team members, without syncing them to github. -->
<!-- Link to OneDrive  -->

