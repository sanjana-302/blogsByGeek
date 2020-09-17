---
title: 'I analysed Google security!'
date: "2020-07-27T07:26:03.284Z"
description: "This blog depicts some analysis of Data Security. P.S. This was done out of curiosity."
categories: [paragraph]
comments: true
---

 I remember once scrolling through my instagram feed I found a post saying :
>Only 1% of Googlers get to visit Data centers of company.

I kept wondering for long about why is it so ?

So, recently I became interested in data security and cryptography. Here I came to know a lot about it. Instantly I had a thought, why not check how tech giants with massive data are doing it?

Obviously I cannot visit the data centers as of now, but documentation had some really cool stuff.

I did a small thesis and it's all written here.

I hope you find this interesting and understand the importance of data security.

Let's dive in!

This is how it goes in any tech giant that has data of millions of humans.

To make it even clearer I have reffered the Google Data Security Norms mentioned in the official documentation.

You can find it [here](https://privacy.google.com/businesses/security/#!?modal_active=defense-in-depth-overlay&article_id=physical-security-to-protect-data-integrity) for your reference.


    Any data center requires these two modes of security : 
    - Physical Security
    - Security Protection of Hardwares and Softwares 




## Distribution of Data across centers 
There are monitored data centers with locations at multiple places. So If there is any kind of disaster this data can be shifted to locations easily.
## Hardware protection
This is a must. For any upper layers to work hardware protection is a must. No clear techniques have been mentioned in documentations.Customized chips,vetting the vendors etc are some stated points.I think every company that has massive data centers needs most of it protection and expenditure at this step.This small story itself from tech giant in early days of it is a lesson.

>Sanjay looked at Jeff. For months, Google had been experiencing an increasing number of hardware failures. The problem was that, as Google grew, its computing infrastructure also expanded. Computer hardware rarely failed, until you had enough of it—then it failed all the time. Wires wore down, hard drives fell apart, motherboards overheated. Many machines never worked in the first place; some would unaccountably grow slower. Strange environmental factors came into play. When a supernova explodes, the blast wave creates high-energy particles that scatter in every direction; scientists believe there is a minute chance that one of the errant particles, known as a cosmic ray, can hit a computer chip on Earth, flipping a 0 to a 1. The world’s most robust computer systems, at nasa, financial firms, and the like, used special hardware that could tolerate single bit-flips. But Google, which was still operating like a startup, bought cheaper computers that lacked that feature. The company had reached an inflection point. Its computing cluster had grown so big that even unlikely hardware failures were inevitable.

This is an abstract from a report by The New Yorker. This happened in year 2000 and is a lesson why hardware requires special attention. You can read the complete report [The friendship that made Google huge](https://www.newyorker.com/magazine/2018/12/10/the-friendship-that-made-google-huge). This will give you deeper insights regarding handling of data and hardware problems.
Therefore, Data security is a major challenge for any company.
All this gives a glimpse about how data security practices are being carried out in these firms and data breaches are a major concern. 

This ends my small thesis regarding security of data at these giants. Another field known as cryptography now comes into play. The story of encryption and decryption is in itself very interesting. I did not wanted this blog to introduce technical terms. This was just for purpose of understanding massive data handling. Hope to see you soon in another piece of my work regarding cryptography!

You can read more about this here.
[Visiting Google Data Centers](https://blog.google/inside-google/infrastructure/how-data-center-security-works/#:~:text=To%20keep%20our%20customers'%20data,data%20center%20is%20absolutely%20secure.)

Thank you for reading!







