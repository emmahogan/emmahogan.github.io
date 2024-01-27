---
layout: post
title: UCSD CSE Research Open House
date: 2024-01-26 12:00:00
description: Presenting at and attending the CSE Research Open House at UCSD
categories: work
---

I had a fantastic time at the CSE Research Open House today, where I presented a poster on some of my recent work. 

This was my first time formally presenting research related to my main thesis topic, improving computing education in prisons. It was great preparation for my upcoming presentation at SIGCSE in March on our experience report on teaching CS1 in prison, even though this poster was not on the same paper. I got meet and talk to a lot of undergraduate students, some fellow CSE Ph.D. students in other research areas, along with some of the UCSD CSE professors I've had for my graduate coursework here. 

The elevator pitch I gave went something like this: There are some significant barriers for incarcerated students learning computer science, such as not having access to an interpreter and/or lacking experience with modern technology. One of the most impactful innovations in CS education research has been computing in context, such as using media computation in introductory CS courses (i.e., grounding the concept of a 2-dimensional list in projects related to image modification using a 2-d array of pixels), which produced dramatic increases in retention and engagement in CS1 courses. However, media computation and other popularized contexts proposed in existing literature are logistically impossible or would be extremely challenging to implement in the majority of prisons in the US. Therefore, this work aimed to identify what potential contexts could be relevent specifically for incarcerated students. To answer this question, we did a qualitative analysis of 78 Python programs written by incarcerated CS1 students from the course I taught in prison this past fall. Each of the four programming assignments had an open-ended portion where students could write a program about any topic, incorporating whichever topics were covered during that period in the course. Through our qualitative analysis of all of these submissions, we identified 24 topics total, the three most popular being business management, sports statistics, and physical health. We plan to incorporate these topics into the curriculum next time we teach the course in Fall 2024 (i.e., in assignments, lecture examples, etc.), which we have reason to believe will increase student motivation and engagement in the course.


One of the more difficult questions I received was what makes this specific to Computer Science -- isn't this applicable to other disciplines as well? This is something I had discussed with my advisors in research meetings, so it wasn't the first time I had thought about it. I do believe that certain topics may be particularly suitable to topics we teach in CS1 and the computational nature of the material, but I also think it will be interesting to explore in the future how this may be true of other disciplines outside of CS. 



Before the poster presentations, I also was able to attend some of the research talks by UCSD faculty in the Machine Learning area. Dr. Taylor Berg-Kirkpatrick put on a fantastic presentation on the interdisciplanary work his lab is doing on using image recognition to identify who printed historical works. 

After taking two graduate-level Machine Learning classes with Dr. Berg-Kirkpatrick during my time here, I always enjoy how great he is at explaining complex Machine Learning models and algorithms. Today was no exception. Essentially, unidentified works are matched to identified works by the imperfections in certain characters, which indicate that the same imperfect letter stamp was used from the same printing press. The first step is to use binary classification to isolate only the imperfect characters from the two works. Then, the model distills an occurence of the same imperfect letter from the two sources into feature vectors, and subtracts the feature vector generated from a "normal" printing of the same letter (isolating just the "abnormalities" from the occurences). Then, the model uses attention to see how well the abnormalities in the two letters match up (for example, factoring in where the abnormality is). Ultimately, the team was able to identify the origination of a Shakespeare work that had previously been thought to be an unsolvable problem -- even better, they published the work in Shakespeare Quarterly!



Overall, the CSE Research Open House was a great experience, and I'm so glad I was able to participate!

