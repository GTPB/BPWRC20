---
layout: page
schemadotorg:
  "@context": http://schema.org/
  "@type": CreativeWork
  "genre": TrainingMaterial

  # Course details
       # "name" -> The acronym and extended name of the course, separated by " - "
       # "description" -> Short description of the course
  name: "BPWRC20 - Best Practices for Writing Reproducible Code"
  description: ""

  # Keywords -> Consult EDAM:Topic
  keywords:  ""

  # Audience -> Following Elixir-Tess input
  audience: ["Academia/ Research Institution", "Industry", "Non-Profit Organisation", "Healthcare"]

  # Author info
  author:
    - "@type": Organization
      name: "The Gulbenkian Training Programme in Bioinformatics"
      alternateName: "GTPB"
      sameAs: "gtpb.igc.gulbenkian.pt/bicourses/index.html"

  # predominant type of learning resources
  "learningResourceType": ["presentation", "exercise", "scripts", "handout"]

  # Contributor info
  contributor:
    - "@type": Person
      name: "Barbara Vreede"
    - "@type": Person
      name: "CO-AUTHOR_2"
    - "@type": Person
      name: "CO-AUTHOR_3"

  # License & Language & url
  license: https://creativecommons.org/licenses/by/4.0/
  inLanguage: "en-us"
  url: "https://gtpb.github.io/BPWRC20/"
---

## Course Description
Ensuring your research is reproducible can be a difficult task. Scripting your analysis is a start, but this in and of itself is no guarantee that you, or someone else, can faithfully repeat your work at a later stage. In this workshop, we will help you not only to make your work reproducible, but also to increase the efficiency of your workflow. We do this by teaching you a few good programming habits: how to set up a good project structure, how to code and comment well, and how to document your code so that it can be used by others. We will furthermore introduce you to Git and GitHub, which are essential tools in managing and publishing code. Reproducibility requires extra effort, but we will focus on teaching you skills that will save you much more time in the long run than they cost to implement.

In this hands-on workshop, you will learn to become a better programmer. We will take you through a project from research question to published code. At the end of this day you will know:

- How to create a research compendium with an efficient project structure;
- How to use Git for version control, and GitHub to publish your code;
- How to write robust code that allows and invites re-use;
- How to document your code well;
- How to license and release your code to ensure maximum reusability.

We require participants to have at least a basic understanding of a programming language, and preferably already have some code to work with. The course content accommodates most languages, but insofar as we give examples of specific tools, we will cater to R and Python users. If you are unsure if the language you use will fit our course, please get in touch.

## Target Audience
Researchers who alread use a programming language for their work, but would like to make their workflow more efficient and robust, and their final product reproducible. Ideally, a participant joins with an ongoing project, which they can work on during the course.

## Detailed Program
#### Day 1: Morning
- Introduction to the command line
- Project setup & version control
  - starting a research compendium
  - choosing a license
  - using git for version control
  - publishing your project on github
#### Day 1: Afternoon
- Code quality
  - code readability
  - reusable code
  - defensive programming: error management
#### Day 2: Morning
- Code quality (cont.)
  - defensive programming: unit tests
- Documentation
  - writing good comments
  - creating an effective project README
#### Day 2: Afternooon
- Documentation (cont.)
  - using notebooks
- Publication
  - obtaining a doi and ensuring accessibility
  - dealing with requirements and dependencies
- Exchange & reproduction of projects

---

### Instructors

#### Barbara Vreede
After defending her PhD in Evolutionary Biology at the Gulbenkian Institute in 2012, Barbara learned Python and R for her postdoc positions, then left active research to join the University Library in Utrecht, the Netherlands. There, she has been focusing on supporting researchers writing and publishing software. This workshop was developed with researchers at Utrecht University, and has been a staple since its inception.

---

The source for this course webpage is [in github](https://github.com/GTPB/BPWRC20).

<br/>

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">BPWRC20</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">GTPB</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
