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

- Why is Research Data Management important?
- What is Research Data Management?
- What are your (personal) benefits in Research Data Management?
- What does a Data management plan (DMP) have to do with it?

-----

At the end of the workshop you…

- have a basic idea of the general concept of RDM and know some important related terms.
- can describe what research data and research data management is.
- can describe basics about the data management plan.

-----

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

{{1-2}}
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


- All information that adequately describes and documents the collection, processing, storage, archiving, and publication of research data in the context of a research project.

- "[...] analysis of the workflow from the generation of the data to their use.“^1^

^[1] J. Ludwig, H. Enke (Hrsg.) Leitfaden zum Forschungsdaten-Management. Handreichungen aus dem WissGrid-Projekt. Verlag Werner Hülsbusch: Glückstadt, 2013.^


## Components of a DMP

{{0}}
**********
>- Administrative data
**********

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

{{0}}
**********
>- Data Description

**********

{{2-3}}
**********

  - Type of research data

    - data types and formats that are reused or generated
    - tools or software to be used

  - volume
    - amount of data to be expected
    - size of the largest individual file

{{0}}
**********
>- Data documentation & quality control

**********


{{3-4}}
**********
  - folder and file naming conventions
  - versioning
  - metadata standards
  - controlled vocabularies / ontologies
  - supporting documentation
  - virtual research environments / databases / ELAB journals

*********

{{0}}
**********
>- Storage & Backup

**********

{{4-5}}
**********
  - storage and data sharing during the project
  - backup strategy
  - access control according to protection requirements (e.g. GDPR)
  - long-term storage according to GRP

*********

{{0}}
**********
>- Legal aspects

**********

{{5-6}}
**********
  - Data protection
  - Copyright and rights of use
  - Licensing law, patent law, etc.

*********

{{0}}
**********
>- Data publication

**********

{{6-7}}
**********
  - selection of datasets
  - name of the (domain-specific) repository
  - timeline of data transfer to the archive
  - time of publication (embargo, if applicable)
  - reason for restrictions
  - selection of usage licenses

*********

{{0}}
**********
>- Responsibilities & Ressources

**********

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

### DMP templates

> **So, how to start...? Use templates!**

***********

{{1-3}}
***********

**Templates**

* [DFG Checklist (for section 2.4 of the proposal)](https://www.dfg.de/download/pdf/foerderung/grundlagen_dfg_foerderung/forschungsdaten/forschungsdaten_checkliste_en.pdf)

* [EU Horizon Europe-Template](https://fdm.uni-koeln.de/sites/FDM-UzK/Templates/data-management-plan-template_he_en-2.docx)

* [Science Europe Template](https://www.scienceeurope.org/our-priorities/research-data/research-data-management/)

***********

### DMP tools

{{1}}
***********
**Generic DMP-Tools**

[Research Data Management Organizer (RDMO) - DFG-funded](https://rdmorganiser.github.io/)

[DMPonline - Digital Curation Centre (DDC), hosted by University of Edinburgh](https://dmponline.dcc.ac.uk/)

[DMP Tool - California Digital Library](https://dmptool.org/)

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