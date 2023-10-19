---
title: "Open Data: planning for Open Data"
author:
  - Lottie Provost
tags:
  - Open
  - Data
  - FAIR
  - Repository
  - Training
---

```{contents}

```

Adapted from [OpenSciency OpenData] (https://github.com/opensciency/OpenData/blob/main/lessons/lesson5.md)
# Data Management Plan : Planning for Open Data

	In the previous lessons it has been shown that effective open data needs to be managed. As we have seen this is not trivial and requires work and preparation. Correspondingly, there can be cost implications for your institutions to do this. Rather than facing these issues on an ad hoc basis, one should plan and prepare what you will need to do before you generate the data. With this in mind, we will

* discuss the data life cycle which places a focus on the reuse of data as it is generated.
* Introduce the concept of a data management plan, where one documents the steps that will be carried out to ensure that your data can be shared in an appropriate fashion.
* Introduce the concept of metadata, namely documenting your data which is essential if another researcher is to make use of your data.
* Finally, who to contact in terms of advice and support.

### Learning Objectives
- insert here

### Target Group 
- PhD 
- Early career researchers

This can be summarized in the following image.

![Linear workflow focussed on publications](https://github.com/learnopenscience/TOPS-OC2-data/blob/adb7137694dde403ca54c7b8f755e79dd60fe8d8/assets/Figure5.1.png "Figure 5.1 Linear workflow model")

### Duration
1 hour

### Prerequisites
[Lesson 4](https://www.go-fair.org/wp-content/uploads/2022/01/FAIRPrinciples_overview.pdf)

## Learning tools
- access to training platform 
- access to word processor
## 1. Planning
#### The data life cycle
With a focus on generating papers, a researcher implicitly ended up with the following research workflow model in mind of how they worked with their data.
It’s important to note here that because the focus is on the paper, there’s no thought to how the data changes at different stages of the process, or thought to how the data should be managed after a paper is published. Usually the data were included as part of the paper as a supplementary file.

This can be summarized in the following image. (ADD image)

On the other hand, if one thinks of open data that can be FAIR (and thus reused) then tanother model emerges. In particular, we note that
	- Data needs to be available beyond the publication of a paper.
	 - Data no longer has to be associated with one paper.
	 - Data can be reanalysed.
	 - More data, from different sources or the same lab, can be added in at any time, including later.
Instead of the process being a linear progression, with a start and a finish, the process for data becomes more complex and there is cycle.
These ideas were put together in the ![DCC Curation Lifecycle model](http://www.ijdc.net/article/view/69) 

The original life cycle is complicated but a summary of the life-cycle is listed below

![The DataOne Data life cycle](https://old.dataone.org/sites/all/images/DLC2015_sm.png "Figure 5.2 A summary of the data life cycle")

Figure 5.2: A summary of the data life cycle (reproduced from https://old.dataone.org/data-life-cycle)

Here the focus is very much moved away from the idea of research -> publication and instead is on the data itself as a first class research output.
Let’s look at these individual steps

* **Plan**: a description of the data that will be compiled, how the data will be managed and made accessible throughout its lifetime.
* **Collect**: this corresponds to the data gathering step (illustrated in Figure 5.1).  It can include both primary (raw) and processed data.
* **Assure**: the quality of the data is assured through checks and inspections.
* **Describe**: data is accurately and thoroughly described through documentation (e.g. metadata).
* **Preserve**: these are the steps necessary to make sure that the data will be accessible going forward so in particular ensuring that the data is stored in a fashion that others can use it (in particular storing at a data repository). Ideally this should be done in a fashion that matches the CARE and FAIR principles (lesson 4). This may also include the step of removing data that may not be of use to future researchers. For example, high resolution images may no longer be themselves useful if in the analysis step one has extracted the features of interest from them. Not storing the high resolution image and simply storing the feature data would provide a considerable saving of storage.
* **Discover**: here other researchers can extract either the entirety or some subset of the data for their own purposes.
* **Integrate**: data from disparate sources are combined to form one homogeneous set of data that can be readily analyzed (this could include this one data set being analyzed).
* **Analyze**: corresponds to the data analysis step as illustrated in Figure 5.1.
There are a variety of different interpretations of the data life-cycle (see the reading list for this lesson) with varying degrees of complexity. It’s also important to note that this is an idealization of what goes in general. Nonetheless, it is important to think of all these steps as an ongoing, interactive process that requires thorough planning and continued consideration and to recognize that they are non-trivial to do.

## 2. Data Management Plans (DMP)
Seeing as the above steps are not trivial before one begins to gather, collate or generate a data set it is useful to plan out what you will do with the data. This is referred to as a Data Management Plan or DMP for short.

A DMP means that you can think ahead of any particular issues that might crop up in terms of handling the data, such as the potential cost of storage, whether data needs to be anonymised and so on.

A detailed description of what one should put into a DMP is described [here](https://the-turing-way.netlify.app/reproducible-research/rdm/rdm-dmp.html) [3]. As outlined in this [document from the UKRI](https://www.ukri.org/councils/stfc/guidance-for-applicants/what-to-include-in-your-proposal/data-management-plan/) [4], the central funder for the UK, these can include answering questions such as

* What type of data will be generated or preserved? This could include data formats, rough estimates of the amount of data to be stored during a research project and similarly what will be preserved beyond the lifetime of the project?

* What type of metadata will be used and preserved. It is worth noting that one of the more detailed aspects of the FAIR principles is to keep the metadata of the data set available even if the original data set no longer exists.

* Where should the data be preserved? i.e. what repository will be used (repositories are discussed in the next lesson). How long should it be stored? (five years? ten years?) More concretely, data regulations can require that certain data be kept in certain ways for at least a certain amount of time. This will vary depending on the type of data (e.g. medical records, population statistics). It is advised that these expiration dates are explored in the literature, and/or policy guidelines.  
* How will any private data be stored so that it is kept securely?

DMPs are not meant to be exhaustive documents! Typically they are 1-2 pages of A4 and often are less than a few thousand words. The important point is that they sketch out what a researcher or research team plans to do with their data well before they are gathered and can identify any steps that need to be taken rather than facing a major challenge now.

DMPs are [increasingly used by funders](https://dmptool.org/public_templates) and their institutions as a means to have researchers map out what they will do with their data in a research proposal. Research proposals often require DMPs, and hence DMPs are often the ‘sharp end of the stick’ for researchers with respect to Open Science [5].  A good DMP is a criterion for assessment in grant applications and hence doing a good DMP will help your grant be funded.

### 3 Documenting your Data (Metadata)

As discussed in the previous lessons, the FAIR principles emphasize the importance of metadata, namely documenting your data. Metadata is described in more detail [here](https://the-turing-way.netlify.app/reproducible-research/rdm/rdm-metadata.html) [6].

A perennial question is what type of metadata and description of the data should be provided for a data set. If you are dealing with electronic data should one provide metadata for a whole set of files, an individual file … each individual bit?

The simplest rule of thumb is if there aren’t any guidelines for your type of data or domain repositories, then try and provide enough documentation about your data that you would ask for if you were downloading this data yourself.

For example if this was data taken from a field trip where location is important then you might want to include longitudinal and latitudinal coordinates. If it’s data from a wet lab then it might include parameters you normally include in the materials and methods section of a paper. If it’s data from purely computational work you may want to list the software run and the parameters used.

Data repositories will be discussed in the next lesson. Domain specific repositories will often give more precise requirements on metadata (another reason to use them).

If there are no guidelines then a simple README file attached with the data is a start (for an example see [here](https://cornell.app.box.com/v/ReadmeTemplate)) - though it’s important to note that ideally one should use metadata schema which is described in much more detail [here](https://www.dcc.ac.uk/guidance/standards) as FAIR data should be machine-actionable [7] [8].

## 4. Help
Much of the ins and outs of dealing with Open Data, or more particularly Open Data that follows good practice such as the FAIR principles, can be technical and lies beyond the domain of knowledge of researchers. How does one navigate this landscape?

This can be summarized in the following diagram -

![Figure 5.3 Diagram pointing to four possible sources of informaiton a researcher can approach.](https://github.com/learnopenscience/TOPS-OC2-data/blob/8509153045f69f2c52c6a6192c52476c54560071/lessons/Figure5.3.png "Figure 5.3 Sources of information and support on Open Data that a researcher could access.")

Figure 5.3 Sources of information and support on Open Data that a researcher could access.

#### **Research communities (international and national)**

Individual research disciplines may already have put together materials and have advice on how to implement Open Science in their discipline. For example [FAIRsharing](https://fairsharing.org/) is a educational and information resource on data and metadata standards [9].  The [Research Data Alliance](https://rd-alliance.org/) have a variety of different [interest and working groups](https://www.rd-alliance.org/groups) in data sharing in specific disciplines. Scientific Societies and Publishers can also provide advice [10] [11].

#### **Open Science related communities**

There are a number of communities that are focussed on Open Science activities. [ReproducibiliTea](https://reproducibilitea.org/) is a grass-roots journal club initiative that is based in over 100 institutions and is a forum to discuss reproducibility, closely allied to Open Science [12]. The [FAIRdata forum](https://fairdataforum.org/) allows you to browse materials and raise questions that are related to FAIR [13]. Correspondingly the [PID forum](https://pidforum.org/) allows you to ask questions on PIDs in general [14]. A list of Open Science communities is provided in the next module (Open Tools).

## Conclusion
Rendere i dati aperti non è unèattività banale. Non si tratta semplicemente di collocare un set di dati su un cloud drive. Tuttavia, se viene fatto correttamente, i dati aperti sono disponibili per il riutilizzo. Il riutilizzo può coinvolgere completamente un team di ricerca diverso o potrebbe riguardare lo stesso team di ricerca che deve continuare il lavoro dopo che un membro del team responsabile dei dati si è spostato. Ciò significa che bisogna considerare i dati come parte del ciclo di vita ed è importante pianificare (un Piano di Gestione dei Dati) prima di creare i dati per assicurarsi che siano conservati in modo appropriato. Parte dell'operazione di rendere i tuoi dati FAIR consiste nel fornire metadati che descrivono i dati che stai depositando. Infine, non sentirti obbligato a fare tutto da zero,  ci sono vari luoghi dove puoi trovare supporto per rendere i tuoi dati aperti e FAIR.

## Assessment
Practice what you just learnt

**Example**
* Can you identify what were the above steps with that data?

Think now about a data set in your own discipline.

* What would be the steps that you would need to take with that data to match up with the data life cycle?
