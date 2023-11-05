---
title: LU2-ResearchData-content
author:
  - Lottie Provost
tags:
  - Data
  - Repository
  - FAIR
  - RDM
---

# Why should we care about research data?

[ QUIZZ - ask now and re-ask again at the end
- are you a transparent researcher?
- what is research data according to you?
- do you care about your data ?]
- README ?

the content in this LU is from Essentials 4 Data support https://datasupport.researchdata.nl/en/start-the-course/i-a-birds-eye-view/data-jargon/rdm-open-and-fair

### Learning objectives
This lesson will answer the following questions/ After this lesson you will
- List Learning Objectives
### Target Group 
- Early career researchers
- SSH researchers

### Duration
1 hour

### Prerequisites
None

## Learning tools
- access to training platform 
- access to word processor


## 1. Research Data
### 1.1 Values behind Data Management

The point here is that for research to be credible it has to be of high quality. But who guarantees this quality ? We will take a look at the values underpinning high quality research, and flaws in the current academic/scientific landscape (reproducibility crisis/publishing crisis/)
they are philosophical but include practical/technical aspects which you will learn to include in your research practices. 

#### Research integrity 
	*integrate quizz on are you a transparent researcher?*

	"If scientific and scholarly research is to perform this role properly, research integrity is essential. Researchers who are not guided by the principles of honesty, scrupulousness, transparency, independence and responsibility risk harming both the quality and the trustworthiness of research" | [VSNU, 2018](https://www.vsnu.nl/files/documents/Netherlands%20Code%20of%20Conduct%20for%20Research%20Integrity%202018.pdf)

![Image from [Essentials 4 Data Support](https://datasupport.researchdata.nl/en/start-the-course/i-a-birds-eye-view/core-values/research-integrity)](attachments/Pasted%20image%2020231031180233.png)

Scientific integrity is essential for the proper functioning of science. Scientific integrity is an umbrella term for the behavioural norms to which a scientist should adhere to ensure that research is reliable and of good quality.

Standards of conduct for scientific integrity are laid down in codes of conduct such as The European Code of Conduct for Research Integrity ([ALLEA, 2017]).
In The Netherlands Code of Conduct for Scientific Integrity ([VSNU, 2018](https://www.vsnu.nl/files/documents/Netherlands%20Code%20of%20Conduct%20for%20Research%20Integrity%202018.pdf)), five principles form the basis of ethical research:
- Honesty
- Scrupulousness
- Transparency
- Independence
- Responsibility

In order to prevent research data from being invented, fabricated or falsified (intentionally manipulated or misinterpreted) and to stimulate reproducibility, a transparent researcher makes clear on which data he or she bases the conclusions and how these data were collected. If research data cannot be made openly accessible, the researcher must state the reasons why this is not possible. 

#### Reproducibility

	"Reproducibility means that research data and code are made available so that others are able to reach the same results as are claimed in scientific outputs" | [The Open Science Training Book, 2018](https://book.fosteropenscience.eu/en/02OpenScienceBasics/04ReproducibleResearchAndDataAnalysis.html)

<u>While different definitions of reproducibility exist in scientific literature, here we will call research reproducible when researchers provide all the necessary data, metadata, software and computer scripts that make it possible to either re-conduct the research or to make re-analysis of the research data possible.</u>

<u>Setting up reproducible research requires a thorough preparation in the planning phase. In Chapter II we will discuss a number of tips and tools that aim to increase the reproducibility of scientific research.</u>

### 1.2 Vocabulary/Data Jargon

#### <font color="#9bbb59">Research Data</font>
##### Definitions 
- 4 Definitions to show that what the understanding of 'research data'  varies from researcher to researcher, and this mostly depends on the significance of these data in the research process. 
	- Major differences across scientific disciplines. 
	- Many formats for research data, which can be read with many types of software. 
- Check below the 4 definitions of research data.
	- "Research data constitute primary research data (the raw, rough measurements or observation) and secondary research data (the results after the data have been processed by a researcher (recoded, combined, categorised, visualised, etc.))." [Utrecht University, 2016](https://www.uu.nl/sites/default/files/university_policy_framework_for_research_data_utrecht_university_-_january_2016.pdf)
	- "Research data may be facts, observations, interviews, recordings, measurements, experiments, simulations and software; numerical, descriptive and visual; raw, cleaned up and processed; they may or may not support an actual or intended publication; and may be stored and exchanged in various formats on various storage media." [Van Berchum & Grootveld, 2017](http://hdl.handle.net/20.500.11755/a9539a60-ecef-4e62-a998-0fda190b303b)
	- "Research data means data in the form of facts, observations, images, computer program results, recordings, measurements or experiences on which an argument, theory, test or hypothesis, or another research output is based. Data may be numerical, descriptive, visual or tactile. It may be raw, cleaned or processed, and may be held in any format or media." [Queensland University of Technology, 2013](http://www.mopp.qut.edu.au/D/D_02_08.jsp)
	- "are the factual records (numerical scores, textual records, images and sounds) used as primary sources for scientific research, and that are commonly accepted in the scientific community as necessary to validate research findings. A research data set constitutes a systematic, partial representation of the subject being investigated." [OECD, 2007](http://www.oecd.org/sti/inno/38500813.pdf)"

##### Ways of looking at data 
- **How is data collected or obtained?** 
There are various ways: through experiments, simulations, observations, derived data or source research.
- **Which are the forms that the data take?** 
Look the form in which that data are recorded, this is often what is used to define the data. It can be a text document, spreadsheets, electronic lab journals, field notebooks and diaries, questionnaires, transcriptions and code books, audio and video tapes, photographs and films, artefacts, slides, database schemes, models, algorithms and scripts, workflows, protocols, metadata and other data files such as reports from literature research and e-mail archives.
- **In which formats is the data stored?**
Look at the data format in which different data types (textual, numerical, multimedia, structured, software code, etc.) are stored. Statistical data can be stored, for example, as SPSS (* .sav) or STATA file formats, films such as * .mpg or * .avi, structured data such as * .xml or in a relational MySQL database and text files such as * .docx, * .pdf or * .rtf.
- **What is the size of the data files?**
The size of the data files is important, as is their complexity. Managing a relatively small and simple dataset poses different challenges than managing large, complex databases.
- **To which phase do they correspond to in the research lifecycle?**
The different life stages of research data each have their own challenges for (supporting) research data management.

#### <font color="#9bbb59"> Research lifecycle</font>
Research data have a longer lifespan than the moment they are generated. One way of looking at this is with a so-called research lifecycle. In this section, we will explain the concept in more detail.

##### There are different lifecycles
A life-cycle model provides insight into how the various phases in the life of research and research data fit together and how the choices you make in one phase influence data quality in the other. In this way you can shift the perspective from the short term to the long term: what do we want with these research data? 
There are many lifecycles in circulation, focused on a certain use or a certain user group. We look at some of them here.

Research lifecycle focusing on the research tools that can be sued in different phases of the workflow. Bosman & Kramer, 2015. 

![](attachments/Capture%20d’écran%202023-11-01%20à%2012.09.51.png)

![Research lifecycle [UCF libraries (2017)](https://library.ucf.edu/about/departments/scholarly-communication/overview-research-lifecycle/)](attachments/UCF-lifecycle.png)

Another type of view: Image below is adapted from the UK Data Service: 

![Adapted from ](attachments/Research%20Lifecycle.drawio.png)




(1) Planning research: 
- design research
- plan data management
- plan consent for sharing 
- plan data collecting, processing protocols and templates
- explore existing data sources

(2) Collecting data
 collect data 
 capture data with metadata 
 acquire existing third party data

(3) Processing and Analysing Data
- enter, digitise, transcribe and translate data
- check, validate, clean, anonymise
- derive data
- describe and document data
- manage and store data 
- analyse and interpret data
- produce research outputs 
- cite data sources

(4) Publishing and sharing data 
- establish copyright
- create user documentation
- create discovery metadata
- select appropriate access to data 
- publish / share data 
- promote data 

(5) Preserving Data 
- migrate data to best format / media
- store and back up data 
- create preservation documentation 
- preserve and curate data 

(6) Reusing Data 
- conduct secondary analysis
- undertake follow up research 
- conduct research reviews
- scrutinise findings
- use data for teaching & learning 

#### <font color="#9bbb59">RDM, open and </font><font color="#9bbb59">FAIR</font>

RDM Open and FAIR: FAIR and open both focus on data sharing, ensuring content is made available in ways that promote access and reuse. Data management by contrast is about the stewardship of data from the point of conception onwards. It makes no assumptions about access, but is essential if data are to be meaningful to others. | [Higman, 2019](http://doi.org/10.1629/uksg.468)

**RDM**: Research data management (RDM) refers to how you handle, organise, and structure your research data throughout the research process. Data management:

- Begins with your initial considerations regarding what will be necessary for using or collecting your particular type of data;
- Includes measures for maintaining the integrity of the data, making sure that they are not lost due to technical mishaps, and that the right people can access the data at the appropriate time; 
- Looks forward to the future, making it clear that you should provide detailed and structured documentation to be able to share your data with other colleagues and prepare them for long-term availability. |  [CESSDA, 2018](https://www.cessda.eu/Training/Training-Resources/Library/Data-Management-Expert-Guide/1.-Plan/Benefits-of-data-management)

**Data stewardship:** For research institutes, including universities, university medical centres, universities of applied sciences as well as other research organizations, it is becoming ever clearer that professionalisation of data stewardship, or research data management as it is also known, is important; that data stewards are indispensable and that the various data stewardship roles must be placed within an organisational framework. | [Verheul, e.a., 2019](http://doi.org/10.5281/zenodo.2642066)

**Open Data**: A piece of data or content is open if anyone is free to use, reuse, and redistribute it - subject only, at most, to the requirement to attribute and/or share-alike. | [Open Knowledge Foundation (n.d.)](http://opendefinition.org/)

**FAIR Data:** If data management is done according to the FAIR principles ([Wilkinson, 2016](https://www.nature.com/articles/sdata201618)) research data will be: Findable, Accessible, Interoperable, Reusable. 

**Open Science:** Open Science is about extending the principles of openness to the whole research cycle, fostering sharing and collaboration as early as possible thus entailing a systemic change to the way science and research is done. | [Foster Open Science, n.d.  
](https://www.fosteropenscience.eu/content/what-open-science-introduction) Open science is about increasing the reuse of research. Key to achieving this is adhering to FAIR principles: ensuring the findings and data behind research results are findable, accessible, interoperable, and reusable. | [Bruce & Cordewener, 2018](https://blogs.lse.ac.uk/impactofsocialsciences/2018/07/26/open-science-is-all-very-well-but-how-do-you-make-it-fair-in-practice/)**

**What does FAIR mean:** In order to make full use of the potential of research data, it is necessary to include them in the research eco-system as Findable, Accessible, Interoperable and Reusable as possible (Force 11, 2014; Wilkinson et al., 2016; GoFAIR, n.d.). The FAIR principles consist of 15 facets ([GoFAIR, n.d.](https://www.go-fair.org/fair-principles/)). The main thing is that research data should not only be FAIR for people, but also for computers/machines. The FAIR principles are now an integral part of the data management landscape and form the basis of the construction plan for the [European Open Science Cloud](https://datasupport.falco213.lcube-server.de/start-de-cursus/iv-oogstfase/european-open-science-cloud).

**Does FAIR=Open?** No. In an [article by Mons et al.](https://content.iospress.com/articles/information-services-and-use/isu824) (2017) you can read the following explanation:  
The 'A' in FAIR stands for 'Accessible', accessible under well-defined circumstances. There may be legitimate reasons not to make research data available in open access, such as protecting the privacy of research participants. FAIR is about making research data findable by man and machine by:
- enriching the data in such a way that value of the data for reuse is clear;
- explicitly - with a clear, preferably machine-readable licence - indicating the conditions under which data may be reused; 
- giving clear instructions on how to quote in case of reuse.
None of these principles requires research data to be 'open' or 'free'. FAIR is about clarity and transparency about the conditions for access and reuse. <u>Data can therefore be FAIR and not open. The other way around, data can also be open but not FAIR.</u>

**What is FAIR data management:** FAIR data management is the set of decisions and measures taken during the life cycle of research data to deliver research data as FAIR as possible. What is important here is the choice of a data license, the data format, the recording of metadata and data documentation, naming conventions, etc. These aspects are all discussed in the following chapters of Essentials 4 Data Support.

FAIR is a brilliant acronym and this is one of the reasons why FAIR is an integral part of the data management landscape. By the way, they are not the only data principles in circulation. In addition to the FAIR acronym, there is also the FACT acronym - Fair, Accurate, Confidential, Transparent - as described on the [Digital Society website](https://www.thedigitalsociety.info/about/data-principles/) (n.d.).

**What is the role of data archives in making data FAIR**? The role of data archives in making data FAIR is very large. In this course we focus on researchers and what they can do to prepare data for FAIRness. But without a data infrastructure built on FAIR principles, researchers can't do very much. The recommendations for creating FAIR data often focus on both target groups: researchers and data archives. This can be confusing. 

The Parthenos Guidelines to FAIRify data management and make data reusable ([Parthenos, 2018](http://10.0.20.161/zenodo.2668478)) make a distinction between the measures per target group. So that those who fit the shoe can also put it on. - see italian version: https://zenodo.org/records/3363243 

One of the [recommendations of the European Commission](https://research-and-innovation.ec.europa.eu/strategy/strategy-2020-2024/our-digital-future/open-science/european-open-science-cloud-eosc_en) (2017) to make data FAIR is to publish it in a reliable data archive that adheres to the FAIR principles. How such a data archive exactly manages this is not something that a researcher needs to know exactly. 

### 1.3 Data supporters

“The basic assumption is that the researcher [themselves are] primarily responsible for all data. However, the researcher does need professional support to achieve this. To that end, diverse supportive data stewardship roles and functions have evolved in recent years” |  [Verheul, et al., 2019](http://doi.org/10.5281/zenodo.2642066)

Data supporters or data stewards face the challenge of translating the available infrastructure, tools and data policy into meaningful, tailor-made, discipline-specific advice for storing, managing, archiving and sharing research data. The flavours of data support within an organisation vary considerably. A study by [Verheul, et al.](http://doi.org/10.5281/zenodo.2642066) (2019) into the tasks and roles of data stewards in Dutch research institutions shows that the variation mainly shows in:
- **Job title**: Data supporters are called data stewards, data experts, data scientists, data consultants, data librarians, data managers, data management specialist, data stewardship coordinator etc. In addition to their research tasks, researchers may also take on data steward tasks without this being expressed in their job title by itself. 
- **Place within the organisation:** A data steward can take a central place (for example at a library or IT department) or can be deployed at faculty level.
- **Roles and tasks:** There are general data stewards, data stewards that are assigned to a certain project (an embedded data steward) and/or that fulfil a discipline-specific role. The general data stewards often have an advisory role, while the embedded or discipline-specific data stewards are also working hands-on in supporting the researcher's workflow. A third category of data stewards has a more strategic or coordinating role. All roles are necessary and the boundaries between the roles are not as strict as the illustration below - based on [the classification by Verheul, et al.](http://doi.org/10.5281/zenodo.2642066) (2019) - suggests.


____________________














___________________________________

Adapted from [OpenSciency OpenData] (https://github.com/opensciency/OpenData/blob/main/lessons/lesson5.md)

Data lifecycle
* **Plan**: a description of the data that will be compiled, how the data will be managed and made accessible throughout its lifetime.
* **Collect**: this corresponds to the data gathering step (illustrated in Figure 5.1).  It can include both primary (raw) and processed data.
* **Assure**: the quality of the data is assured through checks and inspections.
* **Describe**: data is accurately and thoroughly described through documentation (e.g. metadata).
* **Preserve**: these are the steps necessary to make sure that the data will be accessible going forward so in particular ensuring that the data is stored in a fashion that others can use it (in particular storing at a data repository). Ideally this should be done in a fashion that matches the CARE and FAIR principles (lesson 4). This may also include the step of removing data that may not be of use to future researchers. For example, high resolution images may no longer be themselves useful if in the analysis step one has extracted the features of interest from them. Not storing the high resolution image and simply storing the feature data would provide a considerable saving of storage.
* **Discover**: here other researchers can extract either the entirety or some subset of the data for their own purposes.
* **Integrate**: data from disparate sources are combined to form one homogeneous set of data that can be readily analyzed (this could include this one data set being analyzed).
* **Analyze**: corresponds to the data analysis step as illustrated in Figure 5.1.

There are a variety of different interpretations of the data life-cycle (see the reading list for this lesson) with varying degrees of complexity. It’s also important to note that this is an idealization of what goes in general. Nonetheless, it is important to think of all these steps as an ongoing, interactive process that requires thorough planning and continued consideration and to recognize that they are non-trivial to do.

**About DMPs (intro level)**
Seeing as the above steps are not trivial before one begins to gather, collate or generate a data set it is useful to plan out what you will do with the data. This is referred to as a Data Management Plan or DMP for short.

A DMP means that you can think ahead of any particular issues that might crop up in terms of handling the data, such as the potential cost of storage, whether data needs to be anonymised and so on. A detailed description of what one should put into a DMP is described [here](https://the-turing-way.netlify.app/reproducible-research/rdm/rdm-dmp.html) [3]. As outlined in this [document from the UKRI](https://www.ukri.org/councils/stfc/guidance-for-applicants/what-to-include-in-your-proposal/data-management-plan/) [4], the central funder for the UK, these can include answering questions such as
* What type of data will be generated or preserved? This could include data formats, rough estimates of the amount of data to be stored during a research project and similarly what will be preserved beyond the lifetime of the project?
* What type of metadata will be used and preserved. It is worth noting that one of the more detailed aspects of the FAIR principles is to keep the metadata of the data set available even if the original data set no longer exists.
* Where should the data be preserved? i.e. what repository will be used (repositories are discussed in the next lesson). How long should it be stored? (five years? ten years?) More concretely, data regulations can require that certain data be kept in certain ways for at least a certain amount of time. This will vary depending on the type of data (e.g. medical records, population statistics). It is advised that these expiration dates are explored in the literature, and/or policy guidelines.  
* How will any private data be stored so that it is kept securely?

DMPs are not meant to be exhaustive documents!  The important point is that they sketch out what a researcher or research team plans to do with their data well before they are gathered and can identify any steps that need to be taken rather than facing a major challenge now.

DMPs are [increasingly used by funders](https://dmptool.org/public_templates) and their institutions as a means to have researchers map out what they will do with their data in a research proposal. Research proposals often require DMPs, and hence DMPs are often the ‘sharp end of the stick’ for researchers with respect to Open Science [5].  A good DMP is a criterion for assessment in grant applications and hence doing a good DMP will help your grant be funded.

-------
Data repositories will be discussed in the next lesson. Domain specific repositories will often give more precise requirements on metadata (another reason to use them).

If there are no guidelines then a simple README file attached with the data is a start (for an example see [here](https://cornell.app.box.com/v/ReadmeTemplate)) - though it’s important to note that ideally one should use metadata schema which is described in much more detail [here](https://www.dcc.ac.uk/guidance/standards) as FAIR data should be machine-actionable [7] [8].



## Conclusion
Rendere i dati aperti non è unèattività banale. Non si tratta semplicemente di collocare un set di dati su un cloud drive. Tuttavia, se viene fatto correttamente, i dati aperti sono disponibili per il riutilizzo. Il riutilizzo può coinvolgere completamente un team di ricerca diverso o potrebbe riguardare lo stesso team di ricerca che deve continuare il lavoro dopo che un membro del team responsabile dei dati si è spostato. Ciò significa che bisogna considerare i dati come parte del ciclo di vita ed è importante pianificare (un Piano di Gestione dei Dati) prima di creare i dati per assicurarsi che siano conservati in modo appropriato. Parte dell'operazione di rendere i tuoi dati FAIR consiste nel fornire metadati che descrivono i dati che stai depositando. Infine, non sentirti obbligato a fare tutto da zero,  ci sono vari luoghi dove puoi trovare supporto per rendere i tuoi dati aperti e FAIR.

## Assessment
Practice what you just learnt

**Example**
* Can you identify what were the above steps with that data?

Think now about a data set in your own discipline.

* What would be the steps that you would need to take with that data to match up with the data life cycle?
