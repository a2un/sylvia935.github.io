---
layout: archive
title: "Research Projects"
permalink: /research/
author_profile: true
redirect_from:
  - /research-project/
  - /research-prokects
---
<script src="https://www.w3counter.com/tracker.js?id=129746"></script>

## Active Projects
------

### *StudyBuddy*: A Chatbot Designing for College Freshman Study Habits
*Collaborators: Ishrat Ahmed, Arun Balajiee, Zak Risha, Jacob Biehl*<br/>
*University of Pittsburgh, School of Computing and Information*

<img align="right" width="450" height="650" src="/images/chatbot.png">

Check out our [prototype video](https://youtu.be/bLlDL5UCMeI) on YouTube! 

This is a course project for CS 3570 Advanced User Interface Seminar.
In the transition to a new stage of learning, college freshmen are in specific need of developing their study habits and skills to achieve independent work in higher education. We designed a chatbot *StudyBuddy* to support freshman’s behavoiral change. We administered interviews with peer tutors and surveys freshmen at Pitt’s CS department, which we found students have difficulties managing their project and time. We built prototypes in both high fedality over *Slack* and low fedality as storyboards. To evaluate a chatbot's role in support learning, we conducted cognitive walkthrough studies with both senior and first-year CS students. Finally, we offered design guidelines of the chatbot supporting learning behavioral change for college Computer Science freshman. 

### Rapport Management in Multi-session Interactions with a Social, Teachable Robot
*Collaborators: Nichola Lubold, Leah Friedman, Erin Walker*<br/>
*University of Pittsburgh, Facet lab*

<img align="right" width="450" height="650" src="/images/teachable-robot.jpg">

This is an independent research project. I studied middle school students’ rapport (interpersonal closeness) with a robot who speaks socially called *Emma* for multiple sessions. Prior research has investigated the effects of social robots on student rapport and learning in a single session, but little is known about how individuals build rapport with a robot over multiple sessions. We modeled learners’ rapport-building linguistic strategies to understand whether the ways middle school students build rapport with the robot over time follow the same trends as human conversation, and how individual differences might mediate the rapport between human and robot.

### *Allo Alphabet*: Mobile Literacy System Improving Children's French Literacy in West Africa
*Collaborators: Michael Madaio, Amy Ogan* <br/>
*Carnegie Mellon University, Human Computer Interaction Institute*

<img align="right" width="450" height="600" src="/images/AlloAlphabet.png">

This is my research intern work at Carnegie Mellon. *Allo Alphabet* is an IVR and SMS based literacy system that is currently deployed in rural Côte d’Ivoire. Literacy has been linked to pervasive poverty, unemployment and illness, educational technologies can help mitigate low levels of childhood literacy. But some children may get developmental delays in pre-literacy skills due to their family's literacy level, bilingual environment, etc. Given that computer-mediated literacy learning systems often have a fixed progression through the curriculum, it might not effectively support different learners. My research involves modeling students' phonological awareness skills using *Bayesian Knowledge Tracing* and investegating factors that associate with differing the learnabilities of children's pre-literacy skill. With our modeling, we can provide more adaptive support for different individuals in the literacy learning systems.

## Past Projects
------

### Social Media Attention Effectiveness for Fundraising among Nonprofit Organizations
*Collaborators: Rosta Farzan* <br/>
*University of Pittsburgh, Sustainable Social Computing lab*

<img align="right" width="450" height="650" src="/images/nonprofit.png">

This is an independent study supervised by Dr. [Rosta Farzan](rosta-farzan.net/) during Spring 2019. I explored how nonprofit organizations’ use of social media for publicity and for gaining donations. I analyzed 414,312 Twitter posts of local non-profit organizations in Chile and their donations records. I found that a nonprofit being “heard” does not solely depend on how “loud” it speaks (i.e. the number of tweets), instead, these accounts also rely on “whom” they speak to and “where” they speak (i.e. Mentions “@” and Hashtags “#”). Using the findings from this research, nonprofit organizations can allocate their restricted capacity more effectively.


### Online Educational Information Quality Modeling and Perceived Difference Comparison 
*Collaborators: Jing Li* <br/>
*Anhui University, Department of Management Science*

<img align="right" width="450" height="650" src="/images/mooc.png">

This is my *undergraduate research training* project advised by Dr. [Jing Li](https://www.researchgate.net/profile/Jing_Li216) at AHU. We investigated the relationship between online educational information resource quality and learning performance. We conducted 233 questionnaires, utilized structural equation model (SEM) to verify our proposed theoretical model. We found that the *content quality, form quality* and *utility quality* of the online educational information resources had positive impact on information usage, and then positively influenced the user's learning performance. We conducted qualitative analysis on differenct information seeking behaviors among online courses (such as MOOC), search engine and education Q&A platforms (like Zhihu), which offered design implications for improving learning experience of people using online educational resources. 

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
