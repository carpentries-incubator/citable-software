---
title: "Introduction"
teaching: 0
exercises: 0
questions:
- "Why do we need to learn how to make code citable?"
- "Why kind of code is shared in research?"
objectives:
- "Understand to make code citable requires extra work."
- "Distinguish two forms of shared code for research purpose: research compendium and software package."
keypoints:
- "Research compendium is the bundle of code, data, and necessary documentation that you shared for accompanying your published research, so that others can reproduce it and extend it."
- "Software package is a formal format of shared code that can be distributed to others for reuse."
---

If you frequently work with code in your research, at some point you may reach a point when it becomes appropriate to share your code: Be it a script for data analysis, code you have written for collecting and processing data, or some convience functions that you have invented for smoothing your own computing workflow. If you are writing a research paper, then there may be an imperative (e.g., from a journal) for you to share your replication package. Or, others could benefit from your own code as they may want to do similar things, such as retrieving data from a web API and transforming it into rectangular data tables. It is also possible that you are working on some advanced methods or techniques, for data analysis or modelling, and you want to share it with your research community.

One thing to keep in mind is, to give your code away somewhere online does not mean it could reach your audience. Neither can it ensure that you (and perhaps your colleagues as well) receive the due credit when it is reused by others. We would want our code product to be like journal publications, in the sense that it can be disseminated to its intended audience through well recognized channels; and it can be easily shared and referenced when others build on it for their own work. (Of course, you can imagine if the publication is open access, all this become far easier.) That means eventually the impact of your research work gets properly acknowledged. What is even trickier is that academic search engines and indexing databases (e.g., Google Scholar, CrossRef, Web of Science) capture publication records and even a tally of citations as a proxy of research impact. Can they capture the impact of your code?

Thus, this lesson intends to better prepare code authors to share their code in a manner that makes the code best available and enable crediting. Surprisingly, there exists a lot of frictions for someone to properly find and cite your code. It becomes part of the code authors' job to make this process easier. Fortunately, there are many efforts to improve the discoverability and citability of research code. All we need to catch up here is to master the means to maximize the chance for others to idenfity and reference our code.


> ## Think for a moment
> - Where do you share your code?
> - How do you want your users cite your code?
> - What do your users need to know in order to properly cite your code?
{: .callout}

We will talk about means you can use to make your code citable in this lesson. But how to use them really depends on how you share your code. For different forms of code to reach their users, there are also various avenues of sharing. So, let's think about what kind of code you are working with.

## Understand your code
Consider the following scenarios. Which one matches your condition better?

**A**. Amy is working on some data analysis in Jupyter Notebooks. She plans to write the results into her working paper, and submit the paper to a journal, along with her notebooks and data as a replication package.

**B**. Tori is a postdoc in computational chemistry and she works in a lab. She is currently writing some modeling code with the advising of the principal investigator of the lab, Dr. Chang. Their plan is to publish a paper detailing the methods implemented in the modeling code once it is completed, so other computational chemistry researchers can learn about their method.

**C**. Nick recently wrote some R scripts to calculate some measures of economic complexity. He has found that it is actually a good chance to distribute his scripts as an R package so that others can simply load it and calculate the same measures in their research.

In Scenario A, a replication package, required by some academic journals nowadays as part of the submission requirements, resembles the idea of [**Research Compedium**](https://research-compendium.science/), essentially is to provide all the necessary data, code, and documentation to make the research reproducible. Code is part of a **research compendium**, and the compendium comes along with your publication, usually. So you would want it to be identifiable along with your paper. i.e., when people find your paper, ideally they know where the replication package is, and *vice versa*.

In Scenario B and C, Tori and Nick both have the intention to share some code that can be reused by others. If they publish the code with documentation, that probably would benefit their audience the best. But they do not really need to offer their users data to accompany the code to be released. Tori would want to link the code release to her upcoming paper as her audience perhaps need both at the same time to be able to run the code. In contrast, Nick does not feel a necessity to write a paper for his code, though it could be a nice thing to do so. But in order to make their code publicly available and reliable for reuse, both Tori and Nick would want to do a formal release, where they package their code and publish it with necessary metadata and documentation, what we call a **software package**.

{% include links.md %}

