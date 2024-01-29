# SpecLLM: Exploring Generation and Review of VLSI Design Specification with Large Language Model
Mengming Li, Wenji Fang, Qijun Zhang and Zhiyao Xie, "SpecLLM: Exploring Generation and Review of VLSI Design Specification with Large Language Model," [[paper]](https://arxiv.org/pdf/2401.13266.pdf)

## Abstract
  The development of architecture specifications is an initial and fundamental stage of the integrated circuit (IC) design process. Traditionally, architecture specifications are crafted by experienced chip architects, a process that is not only time-consuming but also error-prone. Mistakes in these specifications may significantly affect subsequent stages of chip design. Despite the presence of advanced electronic design automation (EDA) tools, effective solutions to these specification-related challenges remain scarce. Since writing architecture specifications is naturally a natural language processing (NLP) task, this paper pioneers the automation of architecture specification development with the advanced capabilities of large language models (LLMs).

  The absence of a clear and precise definition of architecture specifications poses the first challenge in our research. To address this, we propose a structured definition of architecture specifications, categorizing them into three distinct abstraction levels.
Leveraging this definition, we create and release a specification dataset by methodically gathering 46 architecture specification documents from various public sources. Our clear definitions of architecture specifications, coupled with the dataset we have
formed, lay a solid foundation for prospective research in employing LLMs for architecture specifications. 

  Leveraging our definition and dataset, we explore the application of LLMs in two key aspects of architecture specification development: (1) Generating architecture specifications, which includes both writing specifications from scratch and converting RTL code into detailed specifications. (2) Reviewing existing architecture specifications. We got promising results indicating that LLMs may revolutionize how these critical specification documents are developed in IC design nowadays. By reducing the effort required, LLMs open up new possibilities for efficiency and accuracy in this crucial aspect of chip design.

## Sub-directories Overview

Directories are shown below.

```
.
├── DEMO                   # documents used to demonstrate the ability of LLMs to generate and write architecture specifications
│   └── amber-core         # complete/split Amber 2 Core Specification used to generate architecture specifications
├── HAS                    # Highest-level Architecture Specifications (HAS) listed in Table 1
├── MAS                    # Middle-level Architecture Specifications (MAS) listed in Table 1
└── LAS                    # Lowest-level Architecture Specifications (LAS) listed in Table 1
```

