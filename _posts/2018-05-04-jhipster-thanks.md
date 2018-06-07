---
title: "A thank you letter to the Jhipster Team"
excerpt: "How this amazing opensource project impacted our lives"
tags: 
  - story
author: ernesto

---

*Thank you letter to [Julien Dubois](https://twitter.com/juliendubois) and the [Jhipster Team](https://twitter.com/java_hipster) originally sent by email* 

Hello !

My name is Ernesto Buttó, I'm Co-Funder with [Cindy Marin](https://twitter.com/laslorma ) of a small software company (currently 3 people) called [catwizard.io](http://www.catwizard.io). Cindy recently did a [workshop](http://catwizard.io/workshop.html) in Women Tech Makers Barcelona 2018 about jHipster. 

This platform has made a huge impact in our lives and the people around us. I wanted to thank you for making this platform and I thought that the best way we could do it was telling you the story, and to offer the little time we can find to help on some tickets as collaborators or maintainers.

We have been working together for 11 years now, we are both originally from Venezuela, we started a software company there, that now days is called [catwizard.io](http://www.catwizard.io) (originally Bambu Soluciones).
  After we graduated from Computer Engineering in the [University](https://www.ucab.edu.ve/), we started our path as software developers as well as entrepreneur. Those days we had a partner that recommended Spring as the backend of a platform we commercialized there, we developed our first product called Catwizard, a CMS + Product Catalog. We had a partner that helped us get started and with out first sales, and it was all growing slowly but surely until Venezuelan economy and personal security levels started a fast decline. There were some common products like toilet paper, eggs, legums, that frequently began to be scarce, many people are armed there, and as a result crime went up and we started to look for a place to go, but we did not want stop working together on our company. Because our product had turned into a set of modules and services that we sold to companies, and nobody knew us outside of Venezuela, we started working on custom developments and consulting primary to a costumers in the USA, and we started to strenght our relationships with a particular customer that we already had a good relationship with. However the principal demand was to create custom solutions, they began to raise the bar in terms of delivery time and the features difficulty levels. We had also new customers and refuse to give up on our Venezuelan customers. As a result we had to get better as developers among the other fronts that an enterprenour has to deal with.

So after traveling and living in different countries (Colombia, Peru, Chile, Sicily) we ended up in Spain, a town close to Barcelona called Lloret de Mar a little more then a year ago (We are in Girona now).

Anyways, when we settled in Spain, we were forced in a very stressfull situation, basically we had to accept a project that was going to affect a core process of our main customers in the USA, but we had very little time, a very limited budget to do it and it touch many areas. It required security and reliability to handle everyday operations, it integrated with SalesForce, to their products marketing information and to their accounting system for inventory information. In any other circunstantes we would not have agreed to it, but we had no other source of income and zero contacts in Spain. No body knows us, we don't know how to market ourselves here.

So, 2 days after agreeing to the project I was feeling like I was already behind and very anxious, and then we remembered that we had tried Jhipster some years back messing around in the Internet. I went and looked at it again and was amazed on everything you had built around the generator. The JDL language, the easy of use of the  development workflow, the security, the users administration, the monitors, the loging, the profiles, java testing, frontend testing, the sonar integration, performance tests, integration tests... I mean... and the Options! I felt like Mickey in the Fantasy scene where the Wizard is creating a world. Now we were able to learn and apply about a lot of technologies and concepts that we simply could not afford in the past. There was a way of updating the entities fields and relationships, exporting the model, the production profile was so well packaged, the ElasticSearch... we included ng-prime and solved specific user interface requirements, and the Angular2 was almost out of Beta. I mean I was so excited at the tech behind it and at all it could do for us and for our customers. Fast forward some months, and we were delivering the project built in jHipster and it was approved for production, replacing a very old legacy lotus notes workflow, allowing collaboration between the users, monitoring, delivering branded PDF's, creating tasks on the CRM etc... we delivered on time, and we even made a profit thanks to the hours we saved. Another module was approved afterwards and we already delivered it. 

Thanks to that we were able to pay for the migration costs, find a better place to live, get the papers in order (I have European pastport and Cindy the residency), and the USA customers say their solution is used in daily operations. Additionally we were able to help our partner in Venezuela (Fatima Pestana) to deal with a devastating economic crisis, and we were able to help family leave the country. 

Then Cindy submitted the jhipster workshop to Women Tech Makers Barcelona, it's the most viewed video of all the talks (I think that because is very practical and in Spanish) and we are connecting with the community. Currently I'm helping out in the next Software Craft Barcelona 2018 event. 

On top of that, the learning! The learning because of the quality of the generated code (AAA in sonarqube currently!) and because behind each option there are concepts and well thought out solutions to set of problems. There is a huge benefit of seeing how you apply the concepts in practical code because it's very easy to get confused in this craft about the best practices. For example, is hard to know if a particular approach is a must because of technical debt, or if it's something that makes sense in some cases.

This is a small example in the Spring part: the service layer... should I build a service layer for every endopoint or can I get away with calling the repository directly? How do we deal with that kind of thing... ok how does jhipster generates it and why ? so we go read your documentation, test it with some cases, and very quickly we understand come to our own conclusions. Because behind your tool there are philosophies and concepts that support the results, we also benefit greatly in understanding them faster and better.

I woul recomend 100% to anyone who is in the path of learning about Java + Angular/React/Ionic , or about architectures, or about microservices, or about spring security, or about devops (because the profile and docker stuff is awesome!), or about data modeling, or comparing paradigms like NoSql vs Sql, or about multilanguage architecture, etc... if you want to learn it faster and better, create a simple project with jhipster, see what it does, add a technology you would like to understand, see what it does, repeat.

Recently I was learning and implementing docker, and we have a real use case of a company that have two monolith applications that work together comunicating through their JSON API's. I was't sure if this was right, or common or if there are ways of packaging them. Then in your docker section I found: 

> If your architecture is composed of several JHipster applications, you can use the specific docker-compose sub-generator, which will generate a global Docker Compose configuration for all selected applications....

Ooohh!! That's how!

I mean, every technology in this solution has a reason to be, it's useful, and more if it's combined with another one. But to succesful implement these combinations (JWT Spring security + Angular for example, or ElasticSearch... or Social, etc..) are not trivial. If you want to learn it you need a lot of time, and budgets of SMBs project won't cover for these researches. You, and Depu and all the core team changed that.

- Depu marketplace ()
- Remove the part that we are strugling, tell jdubois that want to focus on thanks. It's not good for trust. Change it the we are moving forwards. 

Now we are building a product of our own for the education industry with an ionic framework mobile app frontend that uses jhipster in the backend. We are still very short in money and in a financially unstable situation basically because we are invisible in the market, I don't even know how to make ourselves visible, and that's why we had not connected with you sooner and why we haven't collaborated more actively (I have only helped once updating the documentation).

Cindy says that before the Barcelona talk you asked her to contact you so she could collaborate with tickets.

We are offering both of us with any tickets you think we could help with.

Again, thank you for making this amazing platform, it was a fundamental solution for a very stressful time of our lives and it's a fundamental part of our learning and as solutions providers.
