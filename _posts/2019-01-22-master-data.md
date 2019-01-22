---
title: "Master Data Overview"
excerpt: "Software Integrations"
tags: 
  - PIM / MDM
  - Software Integration
  - software
author: ernesto
published: true
---

{% include toc %}

# On time information

On time information is on demand. On time information has become a key component on our every day decisions. We are not willing to wait 2 days for the answer, if someone can give me the information now, the one I want to know, that is relevant to me, then that is who I'm going to buy from.

I want to know what I'm buying, and I want that information now. In fact, I'd rather have enough data now, then deep data 2 days from now.

And I'm not the only one. B2B executives want it know, shareholders want it know, clients want it now, millennials want it now, and kids want it now.

- By 2015, 64% percent of adults in the USA **buy online because the products presented there have more precise information than in stores.*** *- Source: Forrester 2016: Product Information Management Solutions, Q4 2016*. This strategy seems to work, according to [statista.com](https://www.statista.com/topics/2477/online-shopping-behavior/), retail e-commerce sales worldwide are forecast to nearly double between 2016 and 2020.

We want to have access to it, to understand enough of what we are buying, so we can make the decision now.

# The Challange: Scattered information

However, providing the updated data is a big challenge for business. Typically a company grows to a point where this is needed, but there was not forethought for this while the company is growing. As a result the data is scattered around a bunch of excel sheets, ERP and accounting systems

If you own the company, or you fullfil a top role, you might feel trapped and guilty about this situation. First of all, don't feel bad, this is the norm, not the exception. You had no idea your company was going to grow so much. But it is time to do something about it, and you need a plan.

Each company has it's own environment of variables to deal with that makes them unique, it's own context. So a "one size fits all" solution does not exists.

I want to contribute a little to anyone out there that has this challenge now days, by providing some concepts and steps that hopefully helps points to the right direction.

# Why is MDM so important?

I want to start by explaining what Master Data is as a concept, I believe that if you understand this concept, then yo will know what is the core ingridient required for accesing on time information.

![master_data_overview]({{ "/assets/images/integrations_1/MasterDataOverview.png"}})

 [Source Dataversity](https://es.slideshare.net/Dataversity/lessons-in-data-modeling-data-modeling-mdm)

Ok, so first I'll give you the formal, very technical concept, and  I'll break it down later:
> Master Data is the consistent and uniform set of identifiers and extended attributes that describes the core entities (product, customer, etc...) of the enterprise - *[Source gartner.com](https://www.gartner.com/technology/it-glossary/mdm.jsp)*

So if our entity is product, then this means, that he goal is to create unique reference that holds all the other references of the other products.

You might have stock information, price information, marketing information such as pictures, and so on different sources, each of them is represented in the above image as database source.

Well with the MDM you can access all of that updated information at an instant to create view for different users.

Here is an example for the **Customers Entity**:

![master_data_overview]({{ "/assets/images/integrations_1/customer_mdm.png"}})

*Source [Microsoft Wiki](https://social.technet.microsoft.com/wiki/contents/articles/2021.mapping-multiple-systems-with-master-data-services.aspx)*

In the above example, Code represents the Master Data Identifier.

# Attaining Master Data in 3 steps

Here is a simplified example to acquire MDM.
You need to:

1. **Store the Information in systems**: For the information to be on time, it most flow, for it to flow it most be on some type of system. Each time the information is updated, it most be updated directly on the system

2. **Allow the flow of information flow**: Once the information is constantly being updated on a system, each product will have an unique identifier in that system. Now you can set the system to connect to the central system.

3. **Match the identifiers to create MD (Master Data)**:  Using a combination of fuzzy matching techiniques and with the cooperation of knwoladgeble personal, you assign all of the products it's Master Number, lets say Black Logitech Mouse, SKU: 3243 in the store X, with Black M. Logitech, SKU: AC23 stored in your warehouse. **Once assigned one time, you won't ever need to do it again.**

Now you can create views and applications that show the customer information they need to make their desicion, such as the picture, origin information or availability, and to the salesman you can show the cost, sugested price, and any information useful at the sales pitch moment.

# A Summarized Checklist for Software integration

Now, before feeling overwhelmed about the challenge at hand, know this.

*You can reap the benefits of integrations, of becoming "digital" one small step at the time. You do not need to invest in a 3-year project now, just commit to 3 months, do a small integration, enjoy the returns of your investment, and afterward put the next brick.*

Slowly but uninterrupted. This is a much faster way to become digital, it creates a habit around development, and habits my friend bring on tangible results.

**Tip**: **Aim for effectiveness**. What is the one question that if answered faster would solve many problems at once, for the most people in the company? Identify and focus on that one, do not try to take on 10 unarticulated data problems. You won't solve them, you will create a 7 head beast that will breathe down your neck every night at bedtime, it will waste money, team effort, and most important, waste tons of time.

The following is a quick more detailed list to give you an idea of the process as a whole on integrating systems, if it's of your interests you can find detailed information and references in [this fantastic post by Donna Burbank](https://es.slideshare.net/Dataversity/lessons-in-data-modeling-data-modeling-mdm)

Here are the most basic steps:

1. **Modeling Data**: Identify Data Entities
2. **Choosing the Architecture**: Centralized Vs Virtualized
3. **Identify Source Systems**: Where is my data?
4. **Choose The Matching Strategy**: How to tie it all together.

Whatever we choose to develop a tailored system, or customized an off-the-shelf-solution, these steps are common to both approaches.

# Finding the middle ground: Custom vs Off The Shelf Software

> “The vision always precedes and itself determines the realization.”
> 
> -- Lillian Whiting

As you can see in the previous steps, you need to understand why are you doing the integration, identify what data to use, from which systems, and figure out how to merge them together.

I recommend to Re-use what is working, use third-party for specific and tested solutions like CRM or E-commerce, and customize the part of your eco-system that ties everything together, that makes you unique... The integration core, the business core.

You don't want to invest in a year project, with a complete re-write or replace of a system, experience major downtime and potential errors, just to have the same system you had before.

**Word of caution:** Vendors are usually interested in selling their software (I guess this is not new to you). Most commercial offers from the companies that I talked to for [P.I.M](https://en.wikipedia.org/wiki/Product_information_management) software do not include the integration itself to the systems in the company, they redirect you to integrators that they know, who at the end of the day, are going to be the more important role than the systems you are buying.

And they will not tell you this clearly but at the very end of the selling process. At first is all "yes, yes, do not worry, this is what the package is worth, these are the yearly fees, and with that, your problems will be solved, etc...".

There are several vendors out there, but last time I checked, very few offered key on hand solutions and the ones that do serve the Enterprise segment.

# Market Facts: Systems Integrations, an increasing focal point for businesses

Here are some facts I pulled out from a research I did in 2017 that might hopefully prompt you to take some kind of action:

- **Experiences in the B2C world increase B2B purchases**, almost 75% say that buying from a web page is more convenient than buying to sales representatives when they buy products or services for work. *-Source: PIM Is A Cornerstone Of Your Digital Business Why Customer-Obsessed Firms Need Product Information Management January 18, 2017*

- [InRiver](https://www.inriver.com/), one of the leading PIM vendors, claims that they have an **annual growth rate (CAGR) of %70**. I did check other vendors data, and all of them have grown big time.

- **87% of data leaders and analysts implemented or are planning to implement or expand on PIM** (Software Integration for Products). Why? Managing spreadsheet and separated systems is not sustainable. To save time, minimize errors, increase the time to market, and manage constantly changing requirements content for allies, digital business need automated checks *- Source: Vendor Landscape: Product Information Management (PIM), Q3 2017*

- In 2015, %67 of decision makers related to infrastructure said that develop a complete strategy in the cloud was a high or critical priority. **Additionally %56 projected an increase on investment in cloud services by the end of 2015.** *- Source: The Forrester WaveTM: Master Data Management, Q1 2016*

> **Scotty:** She's all yours, sir. All systems automated and ready. A chimpanzee and two trainees could run her!
>
> **Captain Kirk:** Thank you, Mr. Scott. I'll try not to take that personally.
>
> — [STAR TREK]

The benefits riped out of these integrations are beyond measure. They will save you money, give you status, and more important, tons of Time, the non renouvable resource

Man is ill-equipped to manage time, however, time is the most important resource in your life, and in your business. Traditionally, business theory teaches us that there are 3 types of resources: Capital, People and Time.

For time, no matter how high the demand, the supply will not go up. There is no price for it, and it can't be stored in any way. Yesterday time is gone and it will never come back.

On top of that, everything requires time, it is the true and only universal condition. All work takes time, uses time, requires time.

System integration are one of the few ways I know to create time where there was none. So take a moment to plan your strategy, and be part of a healthy future.

## References

- [Lessons in data modeling](https://es.slideshare.net/Dataversity/lessons-in-data-modeling-data-modeling-mdm)
- [The Effective Executive by Peter F. Drucker](https://www.amazon.com/Effective-Executive-Definitive-Harperbusiness-Essentials/dp/0060833459)
- [Forrester Wave](https://go.forrester.com/)

## Thank You, support if you can

We hope this article was fun and helpful for you. If you want me to keep generating content for you, you can tell me what would you like to help you with and you can help us by donating a small contribution in our [patreon page](https://www.patreon.com/ernesto_and_cindy).

[![Become a Patreon for Ernesto and Cindy]({{"/assets/images/become_a_patron_button.png"}})](https://www.patreon.com/ernesto_and_cindy)