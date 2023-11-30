---
layout: post
title: "Learning Azure: Playing w/Document Translator"
---
**Background**
I passed my Azure AI Fundamentals exam this past week and now that I'm done studying, I have actually have time to tinker around with  Azure AI. 

A favorite hobby of mine is to research my family genealogy. I have a family tree on Ancestry.com, and have spent a lot of time on that site gathering resources. A large part of my family is from Germany. T and I'm currently struggling with translating old records into English. 

**Defining the Problem**
I'd like to figure out if there is a way that I can use Azure AI + Machine Learning to translate old, handwritten German family records.

**Actions**

My first step was to look into what services I thought would help me. Since Azure AI offers Document Translation (currently in Preview mode), I opened up the Language Studio and started there. 

I had to create: 

* Translator Resource (with Storage Blob Data Contributor role on the storage account)
* Blob Storage Account

After creating these, the Language Studio steps were pretty straightforward.
![Language Translator Steps](/tanyaselvog.github.io/assets/job.png)

**Results**

I uploaded the PDF and honestly, I wasn't anticipating much in the way of results. Some dates were translated, but none of the names were correct. 

![Original record](/tanyaselvog.github.io/assets/familyTree.jpg)

![German family record translated](/tanyaselvog.github.io/assets/textTranslated.jpg)



**Next Steps**

I'm not entirely sure where to go home from here, but I plan on reading more about machine learning and modeling to see if that will be beneficial for anything. 

