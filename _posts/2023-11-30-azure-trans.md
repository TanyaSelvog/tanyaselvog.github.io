---
layout: post
title: "Learning Azure: Playing w/Document Translator"
---
**Background**

I passed my Azure AI Fundamentals exam this past week 😁 and now that I'm done studying, I actually have time to tinker around with Azure AI. 

A favorite hobby of mine is to research my family genealogy. I have a family tree on [Ancestry.com](https://www.ancestry.com/profile/0866cf60-0006-0000-0000-000000000000?preview=true), and have spent a lot of time on that site gathering resources. Many of my ancestors came from Germany and so a lot of old records are obviously in German. I saved several pages of family records from Württemberg and I've researched how to translate them, but I'm still struggling.

**Defining the Problem**

I'd like to figure out if there is a way that I can use Azure AI + Machine Learning to translate old, handwritten German family records. I realize it won't be a perfect translation, since it's old German script, but I'd like to see if there is at least some data I can get from translating them with AI.

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

The results were about what I expected. I can't really do much with what I have, but it's a good starting point and it was just good to feel comfortable tinkering around with Azure AI.


**Next Steps**

I'm not entirely sure where to go home from here 🤷‍♀️. One thing I'm going to do is read more documentation from [Microsoft](https://learn.microsoft.com/en-us/azure/ai-services/). 




