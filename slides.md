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

#### DataLad
##### Perpetual decentralized management of digital objects for collaborative open science

A software tool developed to aid with everything related to the evolution of digital objects.
- Keeps track of data and code.
- Makes sharing, retrieving, and linking (meta)data easy.
- Full digital workflow of data and science.

**Michael Hanke**, Psychoinformatics, Reserch Centre Juelich

Note:

- Datasets as git repositories.
- Decentralised: Datalad can retrieve data from various sources.
- Does not transform files (avoids lock in).

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
