<!--

author:   Central Research Data Management of Kiel University, Linda Zollitsch
email:    zollitsch@ub.uni-kiel.de
version:  0.1.0
language: en
narrator: UK English Female

icon:     images\cau-norm-en-lilagrey-rgb.png

link: https://raw.githubusercontent.com/RDM4CAU/Intro-to-RDM/refs/heads/main/cau-style.css

comment:  Presentation for 1h workshop "Introduction to Research Data Management" for PhDs

-->

# Welcome

<script input="button">
alert("Disclaimer: Please note that you are leaving the CAU net once you open this presentation in your browser. This presentation includes links to other third party websites and services. These sites are not under our control. RDM@CAU is not responsible for the content of linked third party websites. Please be aware that the security and privacy policies on these sites may be different than CAU policies. Please read third party privacy and security policies closely.")

"Disclaimer"
</script>

> Central Research Data Management of Kiel University
>
> To see this document as an interactive LiaScript rendered version, click on the
> following link/badge:
>
> [![LiaScript](https://raw.githubusercontent.com/LiaScript/LiaScript/master/badges/course.svg)](https://liascript.github.io/course/?https://raw.githubusercontent.com/LindaZollitsch/presentation_1h_en.md#1)
>
> If you need help, feel free to ask us any questions:
>
> [info@fdm.uni-kiel.de](mailto:info@fdm.uni-kiel.de)
>
> ____________________________________________
>
> ![ccby](images/ccby.png) This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/) with exception of the used material from other copyright holders.

## Agenda

Let us have a look at our workload for the next hour:

<div style="float:left; width:60%;">
  <p>

- Why is Research Data Management important?
- What is Research Data Management?
- What are your (personal) benefits in Research Data Management?
- What does a Data management plan (DMP) have to do with it?

</p>
</div>

{{2}}
****************

At the end of the workshop you…

<div style="float:left; width:60%;">
  <p>

- have a basic idea of the general concept of RDM and know some important related terms.

- can describe what research data and research data management is.

- can describe basics about the data management plan.

</p>
</div>

****************

# Why is Research Data Management important?

-----

{{1-2}}
****************

Let us first watch a short video

<iframe width="560" height="315" src="https://www.youtube.com/embed/66oNv_DJuPc
" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

****************

{{2}}
****************

- What do you think about the video?

- Has someone experienced similar things already?

- Which parts of the video do you think refer to research data management?

****************

# What is Research Data Management?

## Research Data

{{1}}
********************************************************************************

Examples for research data:

- Audio and video recordings
- Diaries
- Geographic information system (GIS) data
- Laboratory and field notebooks
- Model, script and research software code
- Pictures and figures
- Questionnaires and codebooks
- Samples and artifacts
- Sensor data
- Sequence data
- Spectra
- Text and spreadsheet documents
- Text corpora and annotations
- Topography data
- Transcripts
- ...

********************************************************************************

{{2}}
**********
What is research data?
---

> _‘Any information you use in your research.‘_
>
>[University of Camebridge PrePARe Project](https://www.repository.cam.ac.uk/handle/1810/243750)

************

{{3}}
***************
> _‘The term “research data” generally refers to all kinds of (digital) data that represent the result of scientific work or that serve as a basis for such work. Research data is generated using a wide variety of methods, such as measurements, source research or surveys. Therefore, it is always subject- and project-specific.’_
>
>[Uni Giessen](https://www.uni-giessen.de/ub/en/resteach/researchdata#anchor_what-is-research-data)

**************

## Research Data Management

{{1-3}}
****************
> ‘Research data management is an explicit process covering the creation and stewardship of research materials to enable their use for as long as they retain value.’
>
>[DCC Glossary](https://www.dcc.ac.uk/about/digital-curation/glossary#R)

****************

{{2-3}}
****************
> ‘Research Data Management (RDM) is the methodical handling of the information produced or re-used during the course of academic research.’
>
>[University of Edinburgh Research Data Service](https://www.ed.ac.uk/information-services/research-support/research-data-service/research-data-management)

******************

{{3}}
****************

Research Data Management concerns all aspects of the research process. From simple aspects like naming conventions for data and folder up to complex aspects like specific digital tools that are needed for the research process.

****************

## Research data lifecycle

<center>
{{0-1}}
************

![RD-Lifecycle](images\FDM_Zyklus_klein_ohneText.jpg "Illustration: Cleo Michelsen, based on UK Data Service") <!-- width="500px" -->

************
</center>

{{1-2}}
************
**Planning**:

* How do you plan to create data?
* Will data be reused? How is the data available?
* Which data types, in terms of data formats (e.g. image data, text data or measurement data in tables) are created?
* What volume of data can be expected?
* What legal and ethical aspects need to be taken into account?
* Who is responsible (for what)?
* Which analyses are planned? What requirements must the data meet in order to be analysed as planned? What kind of software environment will you need?

************

{{2-3}}
************
**Collection and analysis**:

* Which (digital) methods and tools (e.g. software) are required collect and safe the (raw) data?
* What measures are taken to ensure high quality of the data?
* What approaches are taken to document all your work in a comprehensible manner?
* Which digital methods and tools (e.g. software) are required to read, use and analyse the data?
* How and where will the data be stored during the project?
* What is your back up strategy?
* How will the security of sensitive data be guaranteed during the project (access and usage management)?

************

{{3-4}}
************
**Archiving & publication**:

* What legal conditions need to be considered in regard of publishing your research data?
* What ethical conditions need to be considered in regard of publishing your research data?
* Are there any effects or restrictions to be expected with regard to publication or accessibility of the data?
* How are usage and copyright aspects as well as ownership issues taken into account?
* Are there any important scientific codes or professional standards that should be taken into account?

************

{{4}}
************
**Re-use**:

* Which data is particularly suitable for re-use?
* What criteria are used to select research data in order to make it available for re-use by others?
* Do you plan to archive your data in a suitable infrastructure?
* Are there embargo periods?
* When can the research data expected to be used by third parties?

************

## FAIR Data Principles

{{0-1}}
****************

<div style="width:50%;">
  <img src="images/fair2.jpg" alt="targets">
  <sub><span style="text-align: right;">Illustration: Patrick Hochstenbach in Engelhardt, Claudia et. al. (2021)</span></sub>
</div>

****************

{{1-2}}
****************

> An important goal of research data management is to keep data 
>
>🔍 **F**indable,
>
>🔐 **A**ccessible,
>
>🔗 **I**nteroperable and
>
>♻️ **R**eusable
>
>in the ~~long term~~ and ~~independent of individuals~~.

****************

{{2}}
****************

🔍 **F**indable (use persistent identifier (PIDs) like DOI, ORCiD, ROR...)

🔐 **A**ccessible (make Metadata available, describe how to get access)

🔗 **I**nteroperable (use Standards and open formats like csv, svg, jpg)

♻️ **R**eusable (use licences, have a data documentation)

****************

# RDM in a nutshell

- Systematic file and folder naming and hierarchy

- document changes

- think about metadata necessary to understand your data

- use Open Document Format (ODF)

- __Generic and open standard file formats__ last longer than proprietary file formats

- Desktop and laptop for work on current research data only

- [Creative Commons](https://creativecommons.org/): data with a necessary creation height; ideally CC0 or CC BY

*************

## What are your (personal) benefits in Research Data Management?

- a structured process

- easier access to your reseach process

- compliance with rules of funders

- less data loss


# What does a Data management plan (DMP) have to do with it?

## What is a data management plan?

{{1-2}}
**********
- All information that adequately describes and documents the collection, processing, storage, archiving, and publication of research data in the context of a research project.

- "[...] analysis of the workflow from the generation of the data to their use.“^1^

^[1] J. Ludwig, H. Enke (Hrsg.) Leitfaden zum Forschungsdaten-Management. Handreichungen aus dem WissGrid-Projekt. Verlag Werner Hülsbusch: Glückstadt, 2013.^

***********

## Components of a DMP

>- Administrative data

{{1-2}}
**********

  - Basic data
    - Project title
    - data originator
    - other contributors
    - contact
    - funding organisation
    - grant number
  
  - Relevant guidelines and policies 

**********

>- Data Description

{{2-3}}
**********

  - Type of research data

    - data types and formats that are reused or generated
    - tools or software to be used


  - volume
    - amount of data to be expected
    - size of the largest individual file



>- Data documentation & quality control

{{3-4}}
**********
  - folder and file naming conventions
  - versioning
  - metadata standards
  - controlled vocabularies / ontologies
  - supporting documentation
  - virtual research environments / databases / ELAB journals

*********



>- Storage & Backup

{{4-5}}
**********
  - storage and data sharing during the project
  - backup strategy
  - access control according to protection requirements (e.g. GDPR)
  - long-term storage according to GRP

*********



>- Legal aspects

{{5-6}}
**********
  - Data protection
  - Copyright and rights of use
  - Licensing law, patent law, etc.

*********

>- Data publication

{{6-7}}
**********
  - selection of datasets
  - name of the (domain-specific) repository
  - timeline of data transfer to the archive
  - time of publication (embargo, if applicable)
  - reason for restrictions
  - selection of usage licenses

*********

>- Responsibilities & Ressources

{{7-8}}
**********
  - Who is responsible for RDM?
    - regulation of responsibilities
    - access control
    - training of project participants
    - data curation
  - What does RDM cost?
    Budget at least 5% for RDM costs!

*********

{{8}}
**********

Length can vary from a few paragraphs to several pages!

*********


## How? Templates & Tools

![](../DMP/images/orientation.png)

### DMP templates
{{0-1}}
***********
<div style="width: 20%; float:right">
![working](../DMP/images/working.png)
</div>

> **So, how to start...? Use templates!**

***********

{{1-3}}
***********
<div style="width: 20%; float:right">
![working](../DMP/images/working.png)
</div>

**Templates**

* [DFG Checklist (for section 2.4 of the proposal)](https://www.dfg.de/download/pdf/foerderung/grundlagen_dfg_foerderung/forschungsdaten/forschungsdaten_checkliste_en.pdf)

* [EU Horizon Europe-Template](https://fdm.uni-koeln.de/sites/FDM-UzK/Templates/data-management-plan-template_he_en-2.docx)

* [Science Europe Template](https://www.scienceeurope.org/our-priorities/research-data/research-data-management/)

***********

### DMP tools

{{1}}
***********
**Generic DMP-Tools**

<div style="width: 20%; float:right">
![working](../DMP/images/working.png)
</div>

[Research Data Management Organizer (RDMO) - DFG-funded](https://rdmorganiser.github.io/)

[DMPonline - Digital Curation Centre (DDC), hosted by University of Edinburgh](https://dmponline.dcc.ac.uk/)

[DMP Tool - California Digital Library](https://dmptool.org/)

***********

{{2}}
***********
**Subject-specific DMP tools**

* biodiversity and environmental research: [GFBio DMP-Tool](https://www.gfbio.org/plan)

* humanities & social sciences / language data: [CLARIN-D Wizard](https://www.clarin-d.net/de/aufbereiten/datenmanagementplan-entwickeln)

* geosciences: [MOSES DMP tool](https://moses-dmp.gfz-potsdam.de/) - prototype under development

* psychology: [DataWiz](https://datawiz.leibniz-psychology.org/DataWiz/)

* educational research: standardized DMPs ([STAMP](https://www.forschungsdaten-bildung.de/stamps-nutzen) soon available with RDMO tool or pdf file)
***********


### Common mistakes in DMP writing

* lack of accuracy

* reuse of (generic) text blocks

* terminological inaccuracies

* lack of resource calculation

### DMP checklist

1. Determine the Research Funder Requirements

2. Identify the Data to Be Collected

3. Define How the Data Will Be Organized

4. Explain How the Data Will Be Documented

5. Describe How Data Quality Will Be Assured

6. Present a Sound Data Storage and Preservation Strategy

7. Define the Project’s Data Policies

8. Describe How the Data Will Be Disseminated

9. Assign Roles and Responsibilities

10. Prepare a Realistic Budget

Michener WK (2015) Ten Simple Rules for Creating a Good Data Management Plan. PLoS Comput Biol 11(10): e1004525. 
https://doi.org/10.1371/journal.pcbi.1004525 





## Questions

>**Nearly done!**
>![image](images/FragezeichenTyp.jpg) <!--
style="width: 10%; max-width: 800px; float:right"
title="puzzle"
onclick="alert('Questions?');"
-->
>
>Time for questions!



## Thank you! :-)

Please take care of your data! 🌼
---






### Data Organisation: General notes

{{0-3}}
*****************

- **Never touch raw data! Always keep your raw data unchanged in a separate folder**.

********************************************************************************

{{1-3}}
********************************************************************************

- Try to find ‘speaking’ names for folders and files ➞ no ‘fantasy names’ 🦄, no random character strings

- Develop a standardised scheme and a logical structure

  - for both folder and file names.

  - Folders in hierarchical order with the most important first.

  - Limit yourself to a maximum of three folder levels, ensure a maximum path length of 256 characters.

  - Keep your personal preferences in mind during development, e.g. for ___sorting!___

********************************************************************************

{{2-3}}
********************************************************************************
- Follow [***ISO 8601***](https://en.wikipedia.org/wiki/ISO_8601) for dates and times

  - Date and time, e.g. YYYY-MM-DD-hh-mm-ss or YYYYMMDDhhmmss

********************************************************************************

{{3-4}}
********************************************************************************

- Always avoid spaces and all special characters (including special letters, such as german umlauts).

  - The following characters in particular should **NOT** be used in folder or file names:

    - less than: <

    - greater than: >

    - colon: :
    
    - double quotation mark: “
    
    - slash: /
    
    - backslash: \
    
    - vertical bar or pipe: |
    
    - question mark: ?
    
    - asterisk: \*

  - The only unproblematic special characters in folder or file names are underscore (_) and hyphen/minus (-)

********************************************************************************

{{4-7}}
********************************************************************************

- Prefix consecutive numbers with a sufficient number of zeros (e.g. 001 for numbering from 1 to 100)

********************************************************************************

{{5-7}}
********************************************************************************

- Use only one dot per file name -> between the file name and format suffix (e.g. filename.txt)

********************************************************************************

{{6-7}}
********************************************************************************

- Upper and lower case is considered different by some file systems, but not by others.  

********************************************************************************

{{7}}
********************************************************************************

- ***Document*** your folder structures as well as the naming conventions and abbreviations used!

  - Readme.md

**********************************************************

<div style="page-break-after: always;"></div>

### Examples

{{0-1}}
********************************************************************************

**Example for a folder hierarchy**

<center>
  <img src="images/Abb_OrdnerstrukturArchproject_2022_bp.png" alt="example folder hirarchy">
    <sub style="text-align: right;">Provided by Oliver Nakoinz</sub>
</center>

********************************************************************************

{{1-2}}
****************************************

>**Example for a file name following a naming convention**
>
>[Project name]\_[Approach]\_[Location]\_[Person-ID]_[Date].[Format-Suffix]
>
>Rebel-Hunting\_Interview\_DS-1-Orbital-Battle-Station\_Organa\_1976-05-25.mp4

****************************************

{{2}}
****************************************

>**Why [***ISO 8601***](https://en.wikipedia.org/wiki/ISO_8601) for dates and times?**
>
>>- **Kristall\_765\_spektr\_2016-12-03.csv**
>>- **Kristall\_765\_spektr\_16-12-03.csv**

****************************************

<div style="page-break-after: always;"></div>


## Data documentation


  **A good data documentation should include**

  - Information on the collection of data

      - Methods, units, time periods, locations, technique used, etc.

  - Structure of the data and their mutual relationships

  - Explanation of variables, labels and codes

  - Differences between different data set versions

  - Measures for data cleaning

  - Information on access and terms of use

      - Licensing

  - Ideal world

      - Description of the research undertaking

        - Goals

      - Hypotheses


## Back up & long-term storage

{{0}}
Where do you store your data?
---

<div style="float:right; width:40%;">
  <img src="images/backup.png" alt="No back up? No mercy!">
</div>


{{1}}
****************
> **Recommendations for your back up**
>
>- At least 3 copies of a file
>- On at least 2 different media
>- At least one of which is remote
>- Test data recovery at the beginning and at regular intervals.

****************

{{2}}
How do your store your (sensitive) data?
---

{{3}}
****************
> **Protect your (sensitive) data**:
>
>- Hardware (e.g. separate lockable room).
>- File encryption
>- Password security
>- At least two people should have access to your data

*****************

<div style="page-break-after: always;"></div>

### Back up vs. long-term storage

| Back up                                                                          | Long-term storage             |
| -------------------------------------------------------------------------------- | ----------------------------- |
| Automatic backup of all data   | Storage of only selected data |
| All versions                                                                     | Final version only            |
|   to prevent data loss <br>(technical, e.g. defective, <br>or human, e.g. accidentally deleted) | Integrity backup <br> (e. g. regular check for modified or damaged data, <br>file system consitency)      |
|                                                                                  | Long-term storage             |
|                                                                                  | Searchability                 |

<div style="page-break-after: always;"></div>


## Openess of Data

* Open Access

* Open Data

* Open Educational Resources

* Open Source Research Software

* Open Methodology

* Citizen Science

* ...


<div style="page-break-after: always;"></div>

### Open Access

>"Open access is the term given to access granted to research publications and other materials online free of charge. A research document published under open access conditions may be read, downloaded, saved, linked to, printed and used by anybody at no cost."
>
>Source: [DFG](https://www.dfg.de/en/research_funding/programmes/infrastructure/lis/open_access/what_is_open_access/index.html)

<div style="float:left; width:80%;">
**Open access** contributions are often represented with the help of an open lock.

- Distribution of research output online, __freely available__ for everyone

  - __no restrictions__ for use und republication

  - In practice: __attribution__ to the original author or creator

- Formerly only open publication of journal articles, papers, etc.

</div>

<div style="float:right; width:10%;">
![Open Access](images\access.png)
</div>

### Open Data

>"Open data are data that have been made available for free use, re-use and dissemination. They can comprise any kind of data from learning materials to geographical data, statistics, traffic data, academic publications, medical data, radio and tv broadcasts.
>
>In oder to mark data as "open", different choices of license are available. Data with restrictive licences, which limit use by prohibiting derivatives or commercial use, do not strictly count as "open data" even though they can certainly improve the academic exchange of ideas." (https://forschungsdaten.info/praxis-kompakt/english-pages/open-data-open-access-and-re-using-data/)

-----

- Open Data

  - Publication of data without legal or technical restrictions
  - for use, re-use and dissemination
  - __Indispensable__ for data science
  - Generic __non-proprietary__ formats
  - different types of data as well as __Metadata__

-----

## Licenses
{{0-1}}
*******************
- Licenses regulate conditions of subsequent use of published data.
- Free licenses allow the use, redistribution and modification of copyrighted works

  - are usually available for free use and only need to be linked to
  - Prerequisite is that you are the copyright holder


Selection of the license depends on the type of data:

  - e.g. Creative Commons (CC) licenses for articles, monographs, images, etc.

  - Open-Database-License (ODbL) for DB or CC starting with version 4

  - General Public License (GNU) for software

- If no license is granted, the stricter copyright applies, as far as applicable to data

***********
