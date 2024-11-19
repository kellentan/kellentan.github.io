---
title: 'General Exam Reflection'
date: 2024-04-17
permalink: /posts/2024-04-17/general-exam-reflection/
tags:
  - General_Exam
  - PhD
  - NLP
mathjax: true
---

This post will be a reflection of my experience taking (and passing!) my PhD general exam in the ECE department at Princeton, as well as what I learned throughout this process.

Preparation
======

Every university has different procedures for their general exam/qualifying exam. In our department, the exam consists of two portions: a research presentation (and accompanying Q&A), and an oral exam. Each part is slated for 90 minutes, so a total of 3 hours for the entire process. For me though, my exam was capped at 2 hours, due to the constraints of one of my committee members (so roughly 60 minutes for both portions). I also had the option of scheduling each portion on separate days, or as one contiguous exam - I chose to take both portions together, since I wanted to complete it all in one sitting. I felt this option also made sense for the committee, since coordinating times for three different members is quite difficult. 

Leading up to the exam, I was fairly confident about the research portion, since I had published two papers (EMNLP'23, NAACL'24) at Princeton. As I was second and first author on those papers, I was pretty familiar with the content, and felt prepared for any questions that might be asked in the Q&A. I was actually more concerned with the oral exam, since there are no limits on the questions the committee could ask. While it's loosely based on the coursework you have taken up to that point, I had taken courses in many different areas, so naturally there was a wide breadth of topics that could be asked. 

There were a couple factors that helped my preparation. First, I started studying quite early, roughly 2.5 months before my exam. Having this time really allowed me to plan out my schedule, and figure out when to focus on each topic. Being able to create this structured studying plan ensured that I could visit all the topics I wanted to brush up on. Second, I was also a TA (Princeton calls it assistant instructor) for an intro ML course. Teaching and distilling these concepts for my students ended up being a great way to study these concepts for my general exam.  

General Exam
======

To say I was nervous on the exam date would be a massive understatement. In the moment, it felt like a pivotal checkpoint in my research career, since it would indicate whether I had the capabilities to pursue a PhD. Ultimately though, I knew I had put in the proper work and preparation, so now it was just a matter of showcasing my knowledge to the committee. 

The research presentation flew by really quickly. I was confident and familiar with the content I was presenting, and I think this confidence was definitely conveyed to my committee. They were quite receptive during my talk, and I could tell their questions came from a place of genuine curiosity rather than a place of judgment. I think it also helped to get a couple of laughs from some jokes I had put into my slides, just to break the ice a little.

Once we finished the presentation, I was given the option of a 5 minute break before the oral exam. I ended up skipping this, as I felt that I would just spend that time second-guessing myself and getting more nervous. During my oral exam, each member asked all their questions at once, so roughly 20 minutes for each. I was actually able to answer most of the questions posed by my committee, and it really helped buid my confidence when they started by asking simple questions, before transitioning to more complicated questions. Even for questions I was unable to answer, the committee was still interested in hearing my thought process, which definitely helped lessen the pressure. Some questions involved whiteboarding (basic proofs, or drawing diagrams/figures), while others felt more like a research discussion. 

After the last question, I was told the committee would take a few minutes to deliberate my decision, where I ended up passing my general exam!

Takeaways
======

In hindsight, I definitely over-prepared for the general exam, but given the stakes, it's better to be over-prepared rather than under-prepared. It also helped to think of it less as an exam per se, but more like a technical interview. At the end of the day, the committee is more interested in gauging how you think through problems, and evaluating the limits of your knowledge. Treat the exam as a litmus test - it lets the committee know what you know, and helps them understand areas of growth that your advisor can help you with.

The biggest advantage you can give yourself is time, by starting early. I started brushing up on topics 2.5 months out, and it was also around this time that I finalized my committee. Getting the administrative stuff finalized is quite important, as it allows you to settle on a committee and schedule your exam. It's quite difficult to find a time that works for everyone, and you don't want to be scrambling to find a committee member late in the game, or realizing that all the dates and rooms are completely booked.

For me personally, passing the general exam and hearing the praise of my advisor really gave me the self-belief and confidence to grow as an independent researcher. While I had published papers, it was extremely validating to see the stamp of approval from my committee members, and it made me less scared to propose my own ideas and methods moving forward. 

Oral Exam Questions
======
In case it's helpful, I also thought I'd include the questions that were asked of me (the ones I can remember at least!) during the oral exam. For reference, my research is in NLP, and my committee consisted of Dr. Suma Bhat, Prof. Niraj Jha, and Prof. Danqi Chen. Dr. Suma Bhat is my advisor and a research scholar in Princeton's CS department, as well as a professor in UIUC's ECE department. Prof. Niraj Jha is a professor in Princeton's ECE department. Prof. Danqi Chen is a professor in Princeton's CS department. 

Prof. Chen asked mostly NLP-specific questions. First, she asked me to explain word2vec in detail, and then asked a couple of followups. One of these included explaining why we needed two matrices for word2vec. Next, she asked me to explain the attention mechanism, and then asked a couple of followups about that. This included distinguishing between self and cross-attention, and differences between encoder and decoder attention, to name a few. Finally, she asked me to explain the training procedure behind ChatGPT. 

Prof. Jha started by asking me to describe GNNs, and specifically graph convolutions. He also asked me to relate both RNNs and GNNs, mainly that signals from far away vertices or tokens can be attenuated. In the same vein, he asked me to think about how transformer models could be applied onto graphs. Next, he asked me to explain LoRA fine-tuning and why it works. Finally, he asked me a challenge question from a recently published paper titled "DoRA: Weight-Decomposed Low-Rank Adaptation" (ICML'24), specifically how the authors implemented their method. Obviously, as the paper was recently published, I hadn't read it yet, but he was more interested in hearing my thought process for how I would approach this problem. 

Dr. Bhat asked me to explain linear regression and write out the relevant equations. From here, she asked me for the optimal weights, so I derived the closed-form solution. Next, she asked me to describe the classification loss function (i.e. cross-entropy), and how it's derived (i.e. from Bernoulli random variables). She used this to transition into logistic regression in NLP, asking me to explain logistic regression and how to apply it on text data. 
