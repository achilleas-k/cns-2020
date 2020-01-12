#### Developing from the field.
##### Shifting design processes and roles between makers and practitioners around research tools development within an interdisciplinary research lab.

Note:

Abstract:
Software design and development within interdisciplinary research teams is a specific activity which closely associates makers and practitioners in the equipment of experimental research methods and practices. This closeness allows practitioners to tackle research endeavours’ specific requirements, such as understanding the methodological assumptions encoded within the tools. It also induces a specific relationship between “makers” and their publics of “users” : a non-commercial, situated and case-based crafting process, implying shifting roles and complex decision making. How does this peculiar context affect the design and valorization practices around open research tools and their evolution ? What are the benefits and difficulties of such settings, in terms of work organization, pedagogical approaches, and scientific methodology ? What can be shared for other contexts such as activism or journalism ? Grounding on the presentation of several case studies of research tools’ design and development elaborated at the médialab of Sciences Po, this talk will offer an account of how an interdisciplinary research environment affects and dialogs with established methods of design (“participative design”, “user experience research”), development (“agile methods”), and tool valorization and socialization.


Description:
Audrey Baneyx has a PhD in artificial intelligence from Paris 6 university. She is a research engineer at the médialab (Sciences Po, Paris) where she works at the intersection of digital methods, knowledge modelling and designing pedagogical storytellings. She is teaching digital culture and methods and, as a mediator, developing médialab tools communities of practitioners. She is co-leading a research group focusing on gender issues online.

Robin de Mourat is research designer at the médialab laboratory (Sciences Po, Paris). He works at the intersection between academic equipment and inquiry practices, combining a background in product design, design history & theory, and human-computer interactions, with diverse material and discursive experiments in the Humanities and Social Sciences. He has participated to the making of texts, things and conversations about the epistemology of design activities, interdisciplinary methodologies, and social & cultural studies of scholarly practices. He has been involved for several years in the development of advanced tools for academic writing and publishing in humanities and social sciences contexts.

---

#### Developing Open-Science Research Platforms
**Zotero, PressForward, Tropy, DHARPA**

Note:

Abstract:
From Zotero to PressForward to Tropy, my research team has developed a wide range of open-science research tools over the last 13 years. I'll talk about how the availability and selection of our technology stacks has influenced humanities (and non-humanities) research methodologies, and I'll provide an update on my team's newest and most comprehensive research platform, DHARPA.

Description:
I'm flexible on the length of the talk and the format. No expected prior knowledge.

---

#### DSpace 7: A major leap forward for the leading institutional repository platform
**Tale of a mature, international FOSS community embracing Angular**

Note:

Abstract:
The DSpace community is anticipating the largest release ever in 2020 with DSpace 7 ( https://wiki.duraspace.org/display/DSPACE/DSpace+Release+7.0+Status ). The platform is used in thousands of research institutions around the globe and powers systems including dspace.mit.edu, dash.harvard.edu and openknowledge.worldbank.org. If you download an academic paper through Google Scholar today, the chance is large that it is served to you thanks to a DSpace institutional repository.

The talk aims to briefly introduce the scope and usage of the DSpace software. Attendees will learn how the governance of the DSpace community is structured, and what lead to the decision to drop the two legacy UIs, JSPUI and XMLUI, in favour of an endeavour to introduce Angular as the new UI layer.

The most relevant piece of the presentation for the Fosdem audience, will be an outline of the tooling and best practices applied in the community, together with a pro and con evaluation.

We are very keen on learning from other participants in the audience what they could advise, both on a technical and organisational level, going forward.

## Previous presentations on DSpace 7

[Introducing DSpace 7](https://lecture2go.uni-hamburg.de/l2go/-/get/v/24819)
[DSpace 7 Configurable Entities](https://lecture2go.uni-hamburg.de/l2go/-/get/v/24831)
[The DSpace 7 Angular UI from a user perspective](https://lecture2go.uni-hamburg.de/l2go/-/get/v/24820)


---

#### Empowering social scientists with web mining tools
**Why and how to enable researchers to perform complex web mining tasks**

Note:

Abstract:
Web mining, as represented mostly by the scraping & crawling practices, is not a straightforward task and requires a variety of skills related to web technologies.
However, web mining can be incredibly useful to social sciences since it enables researchers to tap into a formidable source of information about society.

But researchers may not have the possibility to invest copious amount of times into learning web technologies in and out. They usually rely on engineers to collect data from the web.
The object of this talk is to explain how Sciences Po's [médialab](https://medialab.sciencespo.fr/en) designed & developed tools to empower researchers and enable them to perform web mining tasks to answer their research questions. Here is an example of issues we will tackle during this talk:

* How a social sciences laboratory life can be a very fruitful context for tool R&D regarding webmining
* How to create performant & effective webmining tools that anyone can use (multithreading, parallelism, JS execution, complex spiders etc.)
* How to re-localize data collection: researchers should be able to conduct their own collections without being dependent on external servers or resources
* How to teach researchers the necessary skills: HTML, the DOM, CSS selection etc.

Examples will be taken mainly from the [minet](https://github.com/medialab/minet) CLI tool and the [artoo.js](https://medialab.github.io/artoo/) bookmarklet.

## Speaker

[Guillaume Plique](https://github.com/Yomguithereal) is a research engineer working for SciencesPo's [médialab](https://medialab.sciencespo.fr/en). He assists social sciences researchers daily with their methods and maintain a variety of FOSS tools geared toward the social sciences community and also developers.


---

#### Journalists are researchers like any others

Note:

Abstract:
We are not journalists. But we are developers working for journalists. When we received leaks, we are flooded by the huge amount of documents and the huge amount of questions that journalists have, trying to dig into this leak. Among others :
    * Where to begin ?
    * How many documents mentioned ",tax avoidance", ?
    * How many languages are in this leaks ?
    * How many documents are in CSV ?
See, journalists have more or less the same questions than researchers ! So to help them answer all these questions we developed Datashare. In a nutshell, Datashare is a tool to answer all your questions about a corpus of documents : just like Google but without Google and without sending information to Google. That means that it extracts content and metadata from all types of documents and index it. Then, it detects any people, locations, organizations and email addresses. The web interface expose all of that to let you have a complete overview of your corpus and search through it. Plus Datashare lets you star and tag documents.

We didn't want to reinvent the wheel, and use our assets that has been proved to work well. How did we end up with Datashare from an heterogeneous environment :
    - a command line tool to extract text from huge document corpus
    - a proof of concept of NLP pipelines in java
    - a shared index based on blacklight/ RoR and SolR
    - opensource tools and frameworks  !!

Issues we had to fix :
    - UX hard to improve because it is a shared open source repository (layout, ...)
    - scalability of SolR with millions of documents
    - integration of all the tools in one
    - maintainability and robustness while increasing code base


---

#### Pocket infrastructures to bridge reproducible research, live coding, civic hacktivism and data feminism for/from the Global South

Note:

Abstract:
We will showcase Grafoscopio, a flexible, extensible, self contained ",pocket infrastructure",, which simplifies infrastructure to amplify participation, so reproducible research and publishing, agile data storytelling and custom data visualization can be used in fields like investigative journalism, data feminism and civic hacktivism. We will show prototypes developed with Grafoscopio in the previously mentioned domains, the motivations behind Grafoscopio and the local community practices around it that deconstruct binary relations of power (software developer/user, data producer / consumer, software binary / source code, male/female) and approach reproducible research practices and tools from a perspective located and embodied in a particular place of the Global South in Latin America and in contrast/dialogue with Global North perspectives.

Description:
Reproducible research (and publishing) has been confined mostly to academic places. But it has a lot of potential in several other places like investigative journalism, data feminism and civic hacktivism, as we have showcased by building several prototypes, including: making the so called ",Panama Papers", data leak story reproducible; creating domain specific visualizations for medicine information released by 16 governments; porting the Spanish Data Journalism Handbook and the Data Feminism book to our ",pocket infrastructures", and the creation of agile and resilient tools and practices to write and publish together (see proposal links for a detailed view of such prototypes).

To bridge reproducible research and publishing, agile data storytelling and custom data visualization, with the previously mentioned domains, we have co-designed, developed, used and extended a set of inclusive approaches and tools for/from the Global South, that we have called ",pocket infrastructures",. Our ",pocket infrastructures", simplify infrastructure to amplify participation, and they are mostly self contained, flexible, extensible, and work well with good, low or non connectivity and run from a variety of hardware, from a USB drive, to low end computers, to servers and the ",cloud", and anything in between and beyond.
This is in sharp contrast with exclusionary approaches like ",Big Data", or others that start with big and/or overcomplex infrastructures and are getting traction in the Global North (or are being imported from there to the Global South as the ",only way", forward regarding reproducibility).

Grafoscopio is one of such pocket infrastructures for reproducible research and publishing, agile visualization and data storytelling and this lecture will showcase Grafoscopio, the motivations behind it, and some prototypes developed with it, and the community practices that allow the development of such projects and prototypes deconstructing also binary relations of power (software developer/user, data producer / consumer, software binary / source code, male/female).


---

#### Revamping OpenRefine
**a reproducible data wrangler**

Note:

Abstract:
OpenRefine is a data transformation tool popular in many communities: data journalism, semantic web, GLAMs, scientific research… In this talk I give an overview of our recent efforts to revamp this project as it approaches its 10th anniversary. We are working on exciting improvements which should help alleviate some of the most salient issues faced by our users. My intention is not to lecture the attendance about how to deal with technical debt or to grow a contributor community - I instead seek feedback and spark discussions about our choices. Let us know what you think and help us take good care of this fantastic tool!


---

#### Shrivelling world
**A Three dimensional visualisation development for representing geographical time-space **

Note:

Abstract:
Representing geographical time-space is a fundamental issue in geography, addressing core questions of the discipline, i.e. where are places and what distance separate them. Yet, considering the properties of geographical time space shaped by transport means, no satisfying cartographic representation – including classical maps and plastic space approaches –  has been proposed so far.
The ",shriveling_world", project aims at producing images of the global geographical time-space, using the third dimension, as in time-space relief maps. The word ",shriveling", was introduced by Waldo Tobler in his comments of Mathis-L'Hostis time-space relief image, in order to describe the complex contraction process suggested by the model.
The FOSDEM presentation aims at opening the code to the scientific community, now that the application is close to a first functional version.


---


#### Stylo : a user friendly text editor for humanities scholars

Note:

Abstract:
As an editor for WYSIWYM text, Stylo is designed to change the entire digital editorial chain of scholarly journals the field of human sciences.

Stylo (https://stylo.ecrituresnumeriques.ca) is designed to simplify the writing and editing of scientific articles in the humanities and social sciences. It is intended for authors and publishers engaged in high quality scientific publishing. Although the structuring of documents is fundamental for digital distribution, this aspect is currently delayed until the end of the editorial process. This task should, however, be undertaken early on in the process; it must be considered by the author himself. The philosophy behind Stylo consists in returning the task of managing the publication markup to researchers. This repositioning of tasks relating to the editorial process relies on the author’s semantic rather than graphic skills.

This lightning talk will be the opportunity to present this tool and several publishing projects realized with Stylo.


---

#### The Journal of Open Source Software:  credit for invisible work

Note:

Abstract:
Researchers rarely cite software they use as part of their research. As a result, research software and the time spent developing it have become invisible scholarly contributions. This lack of visibility reduces the incentives that are necessary to produce and share high quality software that are essential for the progress of science.  The Journal of Open Source Software (JOSS) is an open source, open access journal primarily designed to make it easier for those individuals authoring research software to gain career credit for their work by publishing short software papers. Software papers are a recognized mechanism for authors of research software to create a citable ‘entity’ which can easily be cited in journals and as such directly impact a researcher’s career via established metrics such as the h-index. JOSS is unique in that it only accepts very short (~ 1-2 pages) papers, with short summaries and links to the software repository. In that sense, the software papers are not the focus of the review. Instead, we ask reviewers to conduct a thorough review of the associated software (which must be open source) ensuring that it is well documented, straightforward to install and functions as expected. In this talk I will describe the origin and impact that JOSS has had on research open source and also touch upon issues such as sustainability and credit.


---

#### Transforming scattered analyses into a documented, reproducible and shareable workflow

Note:

Abstract:
This presentation is a feedback from experience on helping a researcher transforming a series of scattered analyses into a documented, reproducible and shareable workflow.
Time allocated by researchers to program / code the analyses required to answer their scientific questions is usually low compared to other tasks. As a result, multiple small experiments are developed and outputs are gathered as best as possible to be presented in a scientific paper. However, science is not only about sharing results but also sharing methods. How can we make our results reproducible when we developed multiple, usually undocumented analyses? What do we do if the program is only applicable to our computer directory architecture? This is always possible to take time to rewrite, re-arrange and document analyses at the time we want/have to share them. Here, I will take the exemple of a ",collaboration fest", where we dissected R scripts of a researcher in ecology. We started a reproducible, documented and open-source R-package along with its website, automatically built using continuous integration: <https://cesco-lab.github.io/Vigie-Chiro_scripts/>.
However, can we think, earlier in the process, a better way to use our small programming time slots by adopting a method that will save time in our future? In this aim, I will present a documentation-first method using little time while writing analyses, but saving a lot when the time has come to share your work.


Description:
## Session type (Lecture or Lightning Talk)
Lecture

## Session length (20-40 min, 10 min for a lightning talk)
30 min

## Expected prior knowledge / intended audience
No prior knowledge expected. Example will be about building documentation for R software but any developper, using any programming language may be interested in the method adopted.

## Speaker bio
Sébastien Rochette has a PhD in marine ecology. After a few years has a researcher in ecology, he joined ThinkR (https://rtask.thinkr.fr), a company giving courses and consultancy around the R-software. Along with commercial activities, he is highly involved in the development of open-source R packages. He also shares his experience with the R-community through free tutorials, blog posts, online help and other conferences. https://statnmap.com/


## Links to code / slides / material for the talk (optional)
I wrote a blog post in French about what I am planning to present: https://thinkr.fr/transformer-plusieurs-scripts-eparpilles-en-beau-package-r/
This topic is also related to another blog post: https://rtask.thinkr.fr/when-development-starts-with-documentation/

## Links to previous talks by the speaker
Talks about R are in my Github repository: https://github.com/statnmap/prez/. The ",README", lists talks that have a live recorded video.
As a researcher, I also gave multiple talks about marine science, modelling and other topics related to my research.

---

#### Using Advene to accompany research in AudioVisual Digital Humanities

Note:

Abstract:
Advene is a video annotation platform (free software) that aims at accompanying scholars in their audiovisual analyses workflow. It promotes flexible and evolving annotation structures and interfaces in order to deal with the inherent dynamic nature of analysis. In this presentation, I will present the platform itself, and illustrate its usage through existing Digital Humanities projects that use it, from structuring videos for interview analyses to implementing a workflow for semantic annotation of movies.

