---
---

[Cloud-SPAN](https://cloud-span.york.ac.uk) is a project run by the Biology Department of the University of York with the aim to develop advanced modules covering specialised knowledge and skills to generate and analyse 'omics data using cloud-based High Performance Computing (HPC) resources.

This course is based on the Data Carpentry's [Genomics Workshop](https://datacarpentry.org/genomics-workshop/), streamlined and extended to serve as the foundation course for the Cloud SPAN advanced modules.

The course teaches data management and analysis for genomics research including: (1) best practices for organization of bioinformatics projects and data, (2) use of command-line utilities to connect to and use cloud computing and storage resources, (3) use of command-line tools for data preparation, (4) use of command-line tools to analyze sequence quality and perform and automate variant calling.

The course is designed to be taught over four half days of instruction.

> ## Getting Started
>
> This course follows on from our [prenomics course] (https://cloud-span.github.io/prenomics00-intro/) please  > refer to this material to see whether you will be familiar with the concepts covered there first.
> If you are unsure whether you need to attend the genomics course or the prenomics course first, then try    > [our quiz](https://shiny.york.ac.uk/er13/prenomics-quiz/#section-some-general-questions) first which should  > be able to help you judge which is best for you. The prenomics course assumes no prior experience and is    > designed for absolute beginners. This course presumes some familiarity with the biological concepts,        > including genomic variation, and some experience with using command line previously.      

>
> To get started, follow the directions in the [Setup](setup) tab to get access to the required
> software and data for this workshop.
{: .prereq}

> ## Data
>
> This course uses data from a long term evolution experiment published in 2016: [Tempo and mode of genome evolution in a 50,000-generation experiment](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4988878/) by Tenaillon O, Barrick JE, Ribeck N, Deatherage DE, Blanchard JL, Dasgupta A, Wu GC, Wielgoss S, Cruveiller S, Médigue C, Schneider D, and Lenski RE. (doi: 10.1038/nature18959)
>
> All of the data used in this workshop can be [downloaded from Figshare](https://figshare.com/articles/Data_Carpentry_Genomics_beta_2_0/7726454).
> More information about this data is available on the [Data page](https://cloud-span.github.io/genomics02-proj-mngt-cloud-genomics/data/index.html).
{: .prereq}

# Course Overview

| Lesson                     | Overview |
| -------------------------- | ---------|
| [Project management for cloud genomics](https://cloud-span.github.io/01genomics/) | Learn how to structure your data and metadata, plan for an NGS project, log onto a cloud instance and start navigating using the command line.|
| [Data preparation and organisation](https://cloud-span.github.io/02genomics/) | Learn how to automate commonly used workflows, organise your file system for a new project, and use command-line tools to perform quality control.|
| [Assessing read quality then trimming and filtering reads] (https://cloud-span.github.io/03genomics/) | Learn how to identify the quality of data, then filter out poor quality data.|
| [Finding sequence variants](https://cloud-span.github.io/04genomics/) | Learn how to align reads to a reference genome, identify and visualize between-sample variation.|

# Teaching Platform

This workshop is designed to be run on pre-imaged Amazon Web Services (AWS) instances. All the software and data used in the workshop are hosted on an Amazon Machine Image (AMI). To access your AMI instance remotely, follow the directions in the [Setup](setup).
