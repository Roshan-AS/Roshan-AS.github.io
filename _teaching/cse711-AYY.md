---
layout: page
title: CSE 711 -- AYY
description: AI-Driven Wireless Sensing and Next-Generation Communication Systems (Spring 2026)
img: assets/img/cse4510.jpg
importance: 1
---

| [Course Policies](#course-policies) | [Academic Integrity](#academic-integrity) | [AI Tools](#ai-tools) | [Piazza](https://piazza.com/buffalo/spring2026/cse711ayy) | [Grading Policies](#grading-policies) | [Medical Emergencies](#medical-emergencies) | [Accessibility Resources](#accessibility-resources) |

## Class Updates
All updates, Q&A, class schedule, paper Reading Assignments, In-Class Participation, and Final Project are updated on <a href="https://piazza.com/buffalo/spring2026/cse711ayy">Piazza</a>. Please join at the following link: 
https://piazza.com/buffalo/spring2026/cse711ayy
Access Code: You should find it under the **Announcements** tab in UBLearns Brightspace.

## Teaching Staff

**Instructor:** Roshan Ayyalasomayajula, Assistant Professor\
Office: 113I Davis Hall\
Office Hours:TBD\
Phone: 716-6451590\
Email: roshana [at] buffalo.edu

## Time and Location
 - Lectures: Wed, 1:00-3:50 PM, Davis 338A

----------

## Course Description


This seminar explores the cutting edge of wireless systems at the intersection of signal processing, machine learning, and next-generation communication technologies. Students will learn how AI can both interpret and generate wireless signals — from device-free human activity recognition using WiFi and mmWave, to neural-radiance RF fields that model propagation as differentiable digital twins, to deep-learning-enabled integrated sensing and communication (ISAC) for adaptive 6G networks. The course blends theory, hands-on MATLAB/ML labs, and project-based learning, giving students experience reproducing state-of-the-art systems such as SLNet, SenseFi, NeRF², NeWRF, and RF-Genesis. Through weekly lectures, paper discussions, coding assignments, and a semester-long project, students will gain a holistic understanding of how AI and ML are reshaping wireless sensing and communication, equipping them to design, implement, and critically evaluate next-generation wireless algorithms.

## Tentative Course Outline

| Date  | Topics                                                       | Assigned Reading        | Student Presentation           |
|-------|--------------------------------------------------------------|-------------------------|--------------------------------|
| 01/21 | Overview + Fundamentals of Sensors + Fundamentals of DSP     |                         |                                |
| 01/28 | Overview of FFT + Tx/Rx Chains                               | (0) [How To read a paper](https://cse.buffalo.edu/~yaxiongx/teaching/CSE710/2022fall/paper/HowToRead.pdf) |                                |
| 02/04 | Channel State Information                                    | (1) [ArrayTrack](https://www.usenix.org/system/files/conference/nsdi13/nsdi13-final51.pdf)          |                                |
| 02/11 | WiFi and BLE protocols                                       | (2) [DLoc](https://dl.acm.org/doi/epdf/10.1145/3372224.3380894)                |                                |
| 02/18 | FMCW                                                         | (3) [P2SLAM](https://www.acsu.buffalo.edu/~roshana/assets/pdf/p2slam.pdf)              | (1) [RLoc](https://dl.acm.org/doi/epdf/10.1145/3631437)                       |
| 02/25 | RADAR                                                        | N/A                     | (2) [BatMobility](https://batmobility.github.io/)                |
| 03/04 | N/A                                                          | (4) [See-Through Wall](https://openaccess.thecvf.com/content_cvpr_2018/papers/Zhao_Through-Wall_Human_Pose_CVPR_2018_paper.pdf)    | Project Pitches                |
| 03/11 | 3D FFT                                                       | (5) [Complex Valued CNNs](https://arxiv.org/abs/1602.09046) | (3) [RF Human Pose](https://dl.acm.org/doi/epdf/10.1145/3230543.3230579)              |
| --    | Spring Break                                                 | --                      | --                             |
| 03/25 | Complex Valued CNNs                                          | N/A                     | (4) [SLNet](https://www.usenix.org/system/files/nsdi23-yang-zheng.pdf)                      |
| 04/01 | N/A                                                          | (6) [Moisture Estimation](https://dl.acm.org/doi/epdf/10.1145/3300061.3345440) | Mid Project Review             |
| 04/08 | Understanding EM-based Material Properties                   | (7) [NeRF2](https://dl.acm.org/doi/epdf/10.1145/3570361.3592527)               | (5) [RF-Material Classification](https://dl.acm.org/doi/epdf/10.1145/3742432) |
| 04/15 | Maxwell's Equations based Simulators and Boundary Conditions | (8) [FIRE](https://dl.acm.org/doi/epdf/10.1145/3447993.3483275)                | (6) [RF-Genesis](https://dl.acm.org/doi/epdf/10.1145/3625687.3625798)                 |
| 04/22 | Summary                                                      |                         | (7) [GSRF](https://arxiv.org/abs/2502.01826)                       |
| 04/29 |                                                              |                         | Final Presentation + Demos     |


------------------
 
## Pre-requisites
**Linear Algebra, Intro to ML, Computer Vision, Probability and Statistics**
**Other Pre-reqs**: 
 - Programming concepts: Python and PyTorch/Tensorflow 
 - Optional: Background in signal processing, optimization, and machine learning may allow you to better appreciate certain aspects of the course material.

 
---------------

### Reference Textbooks
 - Oppenheim, Alan V., and A. S. Willsky. “Signals and Systems”. Prentice Hall, 1982. ISBN: 9780138097318. <span style="color:red">**Recommended!**</span>
 - Proakis JG. “Digital signal processing: principles, algorithms, and applications”, 4/E. Pearson Education India; 2007. <span style="color:red">**Recommended!**</span>

--------------------
## Grading Policies

(Tentative and subject to change)
Each student must correctly answer all the questions in the AI Quiz within a month (Feb 24), in order to receive any final grade other than F. Each student will have an unlimited number of tries before the above stated deadline.

Assuming that the student answers all the questions in the AI Quiz correctly, then the overall score will be calculated based on the scores from the Paper Readings, paper Presentation and Final Projects is as follows:

 - Paper Readings + In-Class participation (8 Paper readings): 20%
 - Paper Presentation: 30%
 - 1 Final Project: 50% 
    - Project Pitch(5%): In Class Presentation (3%) - March 4th , 1 page overview (2%)
    - MidTerm Progress (15%): In Class Presentation (10%) – April 1st , 3 page report (5%)
    - Final Project (30%): In-Class Demo + Presentation (10%) – April 29th , 6 pages max report (10%), Code + Reproducability (10%)

**Tentative assignment of grades**: 
S/U is decided based on the number of credits the student has registered for:
 - 3 credit: Satisfactory for score >= 80% and unsatisfactory for score < 80%.
 - 2 credit: Satisfactory for score >= 60% and unsatisfactory for score < 60%.
 - 1 credit: Without Accounting for the project, within the rest 50%: Satisfactory for score >= 35% and unsatisfactory for score < 35%.
  
-------------
## Class Policies

### Paper Readings

This is how it Paper-readings and In-Class participation will work.

- Each of you will post 4 well thought out comments on the paper on Perusall by Tuesday 11:59PM (day before the class)
- On Wednesday in class we will discuss these comments and address them

**On-posting comments:**

- Please use the following link to sign-up to the class in Perusall: [https://app.perusall.com/join/A-MJGAD](https://app.perusall.com/join/A-MJGAD)
- Or use the following student enrollment code: **A-MJGAD**
- **Signing-up on Perusall:**
    - Simply go to the official website of [Perusall](https://cse.buffalo.edu/~yaxiongx/teaching/CSE710/2022fall/perusall.html) and register one account.
    - Please correctly config the user name inside Persuall so that I can recognize you.

### Paper Presentations

Sign-up by 02/09

As we have discussed in the last class here is a sign-up sheet for presenting a specific paper from the paper-presentation list, the presentation date is next to it in the Google Sheets link: [here](https://docs.google.com/spreadsheets/d/1omW2UZzPjBqJZBhLocLf9vp11NnPcjCmWGTM3QkW7CE/edit?usp=sharing)

*Note*: Please do not overwrite any of your classmates request, instead put your name in a column next to it. (It will mostly be on first-come first-serve basis)

### Project
 - In-Class Presentations: Project Pitch (March 4th), Mid-term Review (April 1st), Final Presentatation + Demo (April 29th)
 - project Reports: Templates availabe on Piazza. Deadlines: same as above.

-------------
## Academic Integrity

- **Complete the AI Quiz** available on the UBLearns Brightspace platform under Assessments>Quizzes>AI Quiz. More information can be found [**HERE**](ttps://www.buffalo.edu/academic-integrity/resources/Academic-Integrity-at-UB.html).
  - Successfull completion with 100\% grade is **MANDATORY** for both Undergraduate and the Graduate students.
- **No tolerance on cheating!**
  - All academic integrity violation cases will be reported to the department, school, and university, and recorded.
  - Fail the course on any homework assignment/lab, project, or exam even for first offense.
  - Team members are equally responsible.
  - Consult the Department and University Statements on <a href="http://engineering.buffalo.edu/computer-science-engineering/information-for-students/policies/academic-integrity.html" target="_blank">Academic Integrity</a>.
- Group study/discussion is encouraged, but the submission must be your own work.
- Homeworks: Homework reports must be written up **individually**. Use of reference materials in the library or online is allowed, providedthat the homework explicitly cites the references used. Note that copying the solutions from online sources or the previous semester is still considered cheating even if you cite the sources
- Programming assignments/Final Project: Programming assignments are to be done  *in teams of up to 2 students* for grads and *in teams of up to 4 students* for undergrads. One submission per team, one grade per team. Engaging in discussions concerning concepts is permitted; however, sharing of source code is strictly prohibited. In instances where external resources have been consulted, such as online materials, the provided demonstration code, or other guides, students must clearly annotate the relevant sections of their work with commentary, demarcating the beginning and termination of the referenced material. **Importantly, under NO circumstances may students rely on the work of their peers, including but not limited to GitHub repositories or code submissions from previous academic terms.** We reserve the right to make the ultimate determination regarding breaches of academic integrity policies.
- Students who do share their work with others are as responsible for academic dishonesty as the student receiving the material. Students are not to show work to other students, in class or outside the class. Students are responsible for the security of their work and should ensure that printed copies are not left in accessible places, and that file/directory permissions are set to be unreadable to others.
- Excuses such as  "I was not sure" or "I did not know" will not be accepted. If you are not sure, ask the instructor.
- Any student may withdraw their submission (homework, PAs, projects) any time, no questions asked, BEFORE any AI violation is discovered.

--------------------

## AI Tools
**No use of AI Tools for any submissions**
 - AI Tools like ChatGPT, Google Bard, etc. are not allowed.
 - They can be used to understand the concepts and for clarifications.
 - Use of AI Tools for the submissions in any class work (Homeworks/Programming Assignments/Final Project) **will not be acceptable**.

---------------------

## Medical Emergencies

Accommodation for medical emergencies will be made on a case-by-case basis. Requests for extensions based on medical emergencies must be
accompanied by documentation of the emergency from student health services:  [http://www.buffalo.edu/studentlife/who-we-are/departments/health.html](http://www.buffalo.edu/studentlife/who-we-are/departments/health.html).

----------------------

## Accessibility Resources

If you have a diagnosed disability (physical, learning, or psychological) that will make it difficult for you to carry out the course work as outlined, or that requires accommodations such as recruiting note-takers, readers, or extended time on exams or assignments, please advise the instructor during the first two weeks of the course so that we may review possible arrangements for reasonable accommodations. In addition, if you have not yet done so, contact: [https://www.buffalo.edu/studentlife/who-we-are/departments/accessibility.html](https://www.buffalo.edu/studentlife/who-we-are/departments/accessibility.html).









