---
title: Open Research Tools and Technologies
theme: black
css: style.css
revealOptions:
  transition: 'none'

---

## Open Research Tools and Technologies

### FOSDEM track preview

##### Achilleas Koutsou

##### 2020-01-13

---

# Part 1
## FOSDEM and the devroom

---

#### Free and Open source Software Developers' European Meeting

> FOSDEM is a free and non-commercial event organised by the community for the community.

> Devrooms are a place for teams to discuss, hack and publicly present latest directions, lightning talks, news and discussions. We believe developers can benefit a lot from these meetings.

- [fosdem.org/2020/about](https://fosdem.org/2020/about)

---

## Open Research Tools and Technologies

> The Open Research Tools and Technologies devroom addresses FLOSS developers in a broad community concerned with research production and curation: scientists, engineers, journalists, archivists, curators, activists.

- [research-fosdem.github.io](https://research-fosdem.github.io/)
- [fosdem.org/2020/schedule/track/
open_research_tools_and_technologies](https://fosdem.org/2020/schedule/track/open_research_tools_and_technologies/)

Note:

Our proposal was merged with a similar one by Paul Girard of Sciences Po (Paris Institute of Political Studies) médialab and Mathieu Jacomy of Aalborg University TANT (Techno Anthropology) Lab.

Our goal was to bring together researchers and software developers to begin bridging the gap between tool makers and their users.

---

- Allow knowledge-based tool developers to publicise their efforts and become aware of other FLOSS projects.
- Facilitate the pooling of coding efforts on (often poorly funded) tools.
- Create a network where otherwise isolated developers and research engineers can share common concerns.
- Provide social recognition for people who work in fields where designing and developing tools does not produce the traditionally recognisable outcomes.

Note:

We want researchers to have open lines of communication with the developers of the open source tools their work depends on.  The benefits of this should be obvious:
- Developers who work on research tools should understand the needs of their users.
- Developers who work on general open source software that is used for research should be aware of the specific requirements and challenges that researchers face.
- Researchers should feel comfortable speaking with developers about the challenges of their field (wrt to the software).
- Open source software isn't only beneficial but essential for open and reproducible science.  We want researchers to care about the software they use and the people that make them.

In general, we want to make FOSDEM (and perhaps other software developer conferences) appealing to research software developers and researchers.

---

#### The good and the bad sides of developing open source tools for neuroscience

- The role of open source solutions in improving the reproducibility of published research.
- Problems with open source projects in neuroscience.
- Open source based workflow for creating and storing data and metadata.


**Jan Grewe**, Institute for Neurobiology, University of Tuebingen.

---

#### Challenges and opportunities in scientific software development
##### An example from the neurosciences

- Exemplary open source packages from the field of neuroscience.
- The special requirements for open source software development and services in the field.

**Julia Sprenger**, Doctoral Researcher, Research Centre Juelich


Note:

Problem:
- Scientific software developers lack the training, skill, and knowledge of tools and methods that one expects from professional software developers.
- Additionally, due to the exploratory nature of the scientific method at the frontier of knowledge, most projects require the implementation of custom code.
- Scientific code is often not suited for sharing and long term maintenance.

---

#### NeuroFedora: Enabling Free/Open Neuroscience

- Fedora-based operating system for Neuroscientists.
- Over 130 neuroscience packages ready to use + over 120 in the queue.
- [neuro.fedoraproject.org](https://neuro.fedoraproject.org)

**Aniket Pradhan**, Indraprastha Institute of Information Technology, Delhi

Note:

A NeuroFedora lab image is now available, with over 130 neuroscience packages ready to use. With an up to date documentation at (neuro.fedoraproject.org) and about 120+ packages in the queue, we encourage more FOSS enthusiasts to join the team to help NeuroFedora better aid the open (neuro)-science and research community.

---

#### Spotlight on Free Software Building Blocks for a Secure Health Data Infrastructure

- Tools and frameworks for open health data exchange infrastructure.
- Encourages participants to contribute to the use of open systems in Medical Informatics.

**Markus Suhr**, Department of Medical Informatics, Georg-August-University Goettingen.

Note:

- Exchanging data at the scales common in Medical Informatics requires open data formats and protocols, multi-stakeholder collaboration, and agile development.

---

#### DataLad
##### Perpetual decentralized management of digital objects for collaborative open science

A software tool developed to aid with everything related to the evolution of digital objects:
- Keeps track of data and code.
- Makes sharing, retrieving, and linking (meta)data easy.
- Full digital workflow of data and science.

**Michael Hanke**, Psychoinformatics, Reserch Centre Juelich

Note:

- Datasets as git repositories.
- Decentralised: Datalad can retrieve data from various sources.
- Does not transform files (avoids lock in).

---

#### Frictionless Data for Reproducible Research

- Frictionless Data initiative: [frictionlessdata.io](https://frictionlessdata.io)
- Specifications for data and metadata interoperability.
- Collection of open source software libraries that implement the specs.

**Lilly Winfree**, Product Owner, Frictionless Data for Reproducible Research Project, Open Knowledge Foundation

Note:

The Frictionless Data initiative (https://frictionlessdata.io/) at Open Knowledge Foundation (http://okfn.org) aims to reduce friction in working with data, with a goal to make it effortless to transport data among different tools and platforms for further analysis, and with an emphasis on reproducible research and open data.

---

#### On the road to sustainable research software.

- ELIXIR: intergovernmental organization that brings together life science resources across Europe.
- Recommendations for encouraging best practices in research software (4OSS).
- Create and publish training materials and comprehensive guidelines.

**Mateusz Kuzak**, Research Software Community Manager, Netherlands eScience Center

Note:

The 4OSS simple recommendations are as follows:
- Develop a publicly accessible open-source code from day one.
- Make software easy to discover by providing software metadata via a popular community registry.
- Adopt a license and comply with the licence of third-party dependencies.
- Have a clear and transparent contribution, governance and communication processes.

---

#### Stylo: A user friendly text editor for humanities scholars

- [stylo.ecrituresnumeriques.ca](https://stylo.ecrituresnumeriques.ca)
- WYSIWYM editor for writing scientific articles.
- Targeted at humanities and social sciences.

**Antoine Fauchié**, Ph.D candidate, University of Montréal

Note:

**Lightning talk**

- Stylo is designed to simplify the writing and editing of scientific articles in the humanities and social sciences.
- It is intended for authors and publishers engaged in high quality scientific publishing.

---

#### Using Advene to accompany research in AudioVisual Digital Humanities

- Video annotation platform for audiovisual analysis workflows.
- [advene.org](https://advene.org/)

**Olivier Aubert**, Research engineer and R&D consultant, University of Nantes

Note:

**Lightning talk**

---

#### Shrivelling world
##### A Three dimensional visualisation development for representing geographical time-space

- Tool for producing images of the global geographical time-space.
- Approaching initial release (_first functional version_).
- Code to be opened and released.

**Nicolas Roelandt**, Geospatial information system engineer, IFSTTAR research institute
Note:

**Lightning talk**

IFSTTAR: The French Institute of Science and Technology for Transport, Development and Networks

The FOSDEM presentation aims at opening the code to the scientific community, now that the application is close to a first functional version.

---

#### Empowering social scientists with web mining tools
##### Why and how to enable researchers to perform complex web mining tasks

- Web mining via scraping and crawling of web pages.
- médialab designs and develops tools to enable researches to perform web mining tasks.
- Examples & demos of tools:
  - minet: [github.com/medialab/minet](https://github.com/medialab/minet)
  - artoo.js bookmarklet: [medialab.github.io/artoo/](https://medialab.github.io/artoo/)

**Guillaume Plique**, Research engineer, médialab, Sciences Po, Paris.

Note:

- How a social sciences laboratory life can be a very fruitful context for tool R&D regarding webmining
- How to create performant & effective webmining tools that anyone can use (multithreading, parallelism, JS execution, complex spiders etc.)
- How to re-localize data collection: researchers should be able to conduct their own collections without being dependent on external servers or resources
- How to teach researchers the necessary skills: HTML, the DOM, CSS selection etc.

---

#### Revamping OpenRefine
##### A reproducible data wrangler

- OpenRefine: A free, open source, powerful tool for working with messy data ([openrefine.org](https://openrefine.org))
- Overview of efforts to revamp the 10-year-old project.
- Seeks feedback and discussion about reconstruction project.

**Antonin Delpeuch**, Doctoral student, New College, University of Oxford

Note:

- Data transformation tool popular in many communities: data journalism, semantic web, GLAMs, scientific research.

---

#### Pocket infrastructures to bridge reproducible research, live coding, civic hacktivism and data feminism for/from the Global South

- Grafoscopio: a flexible, extensible, self contained _pocket infrastructure_.
- Inclusive approaches and tools for/from the Global South (the _pocket infrastructures_).
- Bring reproducible research and publishing methodologies and tools outside of academic places:
  - investigative journalism, data deminism, and civic hacktivism.

**Offray Luna**, Hacktivist, Researcher and Data Visualiser.

Note:

In sharp contrast with exclusionary approaches like _Big Data_ or others that start with big and/or overcomplex infrastructures and are getting traction in the Global North (or are being imported from there to the Global South as the ""only way" forward regarding reproducibility).


Showcased reproducible research applied to other fields (outside of research and publishing) by building several prototypes, including:
- Making the _Panama Papers_ data leak story reproducible
- Creating domain specific visualizations for medicine information released by 16 governments
- Porting the Spanish Data Journalism Handbook and the Data Feminism book to their _pocket infrastructures_
- The creation of agile and resilient tools and practices to write and publish together.


Grafoscopio showcase: one of such pocket infrastructures for reproducible research and publishing, agile visualization and data storytelling.
Some prototypes developed with it, and the community practices that allow the development of such projects and prototypes deconstructing also binary relations of power (software developer/user, data producer / consumer, software binary / source code, male/female).

---

#### Journalists are researchers like any others

- Datashare: a tool to answer all the interesting questions about a corpus of documents (primarily from data leaks).
- Made by _developers working for journalists_.
- Extracts and indexes content and metadata from all types of documents.
- Exposes data and information through web interface.
- Built on open source tools and frameworks.

**Anne L'Hôte**, Front-end developer, ICIJ, in charge of implementing Datashare
**Bruno Thomas**, Senior developer, ICIJ

Note:

"We are not journalists. But we are developers working for journalists."

How Datashare happened:
- a command line tool to extract text from huge document corpus
- a proof of concept of NLP pipelines in java
- a shared index based on blacklight/ RoR and SolR
- opensource tools and frameworks  !!

Issues:
- UX hard to improve because it is a shared open source repository (layout, ...)
- scalability of SolR with millions of documents
- integration of all the tools in one
- maintainability and robustness while increasing code base

ICIJ: International Consortium of Investigative Journalists

---

#### Developing from the field.
##### Shifting design processes and roles between makers and practitioners around research tools development within an interdisciplinary research lab

- Software design and development in an interdisciplinary research team.
- The benefits and difficulties of collaboration between developers and users of open source research tools.
- Presentation of several case studies of research tools' design and development at the médialab of Sciences Po.

**Audrey Baneyx**, Research engineer, médialab, Sciences Po, Paris
**Robin de Mourat**, Research designer, médialab, Sciences Po, Paris

Note:

Abstract:
- Allows practitioners to tackle research endeavours' specific requirements, such as understanding the methodological assumptions encoded within the tools.
- It also induces a specific relationship between "makers" and their publics of "users": a non-commercial, situated and case-based crafting process, implying shifting roles and complex decision making.
- How does this peculiar context affect the design and valorization practices around open research tools and their evolution ?
- What are the benefits and difficulties of such settings, in terms of work organization, pedagogical approaches, and scientific methodology?
- What can be shared for other contexts such as activism or journalism ? , this talk will offer an account of how an interdisciplinary research environment affects and dialogs with established methods of design (“participative design”, “user experience research”), development (“agile methods”), and tool valorization and socialization.

---

#### A community-driven approach towards open innovation for research communication

eLife projects:
- Reproducible Document Stack (RDS), an open-tool stack capturing code, data and compute environment in a live paper to improve research reproducibility.
- eLife Innovation Sprint.

**Emmy Tsang**, Innovation Community Manager, eLife

Note:

> A reproducible document is one where any code used by the original researcher to compute an output (a graph, equation, table or statistical result) is embedded within the narrative describing the work.

https://elifesciences.org/labs/7dbeb390/reproducible-document-stack-supporting-the-next-generation-research-article

>  eLife Innovation Sprint, a global gathering of researchers, developers, designers, technologists, publishers and others to develop open-source prototypes to change the ways we discover, share, consume and evaluate research.

https://elifesciences.org/labs/d13e1547/innovation-sprint-2019-project-roundup
