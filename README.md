# CSCI - 2897

CU Boulder's CSCU 2897 - Calculating Biological Quantities\
Prof. [Daniel Larremore](http://larremorelab.github.io/)\
Spring 2021\
Meets online, Tu/Th 8:00-9:15, Zoom

## Schedule

| Week | Date      | Topic                                                         | Reading | Links | Assignments |
|------|-----------|---------------------------------------------------------------|---------|-------|-------------|
|    1 |     01/14 | Syllabus & a tour of math. models & linear algebra            |         |       |             |
|    2 |     01/19 | How to Construct a Model                                      |         |       |             |
|    2 |     01/21 | Solutions to Differential Equations — Numerical vs Analytical |         |       |             |
|    3 |     01/26 | Exponential & Logistic Growth                                 |         |       |             |
|    3 |     01/28 | Coding for Exponential & Logistic Growth                      |         |       |             |
|    4 |     02/02 | Separation of Variables                                       |         |       |             |
|    4 |     02/04 | Equilibrium states, phase portraits, and direction fields     |         |       |             |
|    5 |     02/09 | Haploid and Diploid models of natural selection               |         |       |             |
|    5 |     02/11 | Species Interactions: Lotka Volterra                          |         |       |             |
|    6 |     02/16 | Consumer-Resource Models                                      |         |       |             |
|    6 |     02/18 | Math: Integrating Factors & Linear Equations                  |         |       |             |
|    7 |     02/23 | SIR models (Measles)                                          |         |       |             |
|    7 |     02/25 | SI models (HSV)                                               |         |       |             |
|    8 |     03/02 | Exam 1 Review                                                 |         |       |             |
|    8 |     03/04 | Exam 1 (Open Notes, In Class)                                 |         |       |             |
|    9 |     03/09 | SEIR models (COVID)                                           |         |       |             |
|    9 |     03/11 | Linearization                                                 |         |       |             |
|   10 |     03/16 | Vaccination and SIRS models                                   |         |       |             |
|   10 |     03/18 | Transmission-blocking vaccines                                |         |       |             |
|   11 |     03/23 | Malaria                                                       |         |       |             |
|   11 |     03/25 | Spring "Break" :/                                             |         |       |             |
|   12 |     03/30 | Multiple variables, and systems of equations                  |         |       |             |
|   12 |     04/01 | Vectors                                                       |         |       |             |
|   13 |     04/06 | Matrices and inverse matrices                                 |         |       |             |
|   13 |     04/08 | Extras: trace, determinant                                    |         |       |             |
|   14 |     04/13 | Eigenvalues & Eigenvectors                                    |         |       |             |
|   14 |     04/15 | Class-structured population models                            |         |       |             |
|   15 |     04/20 | Age-structured SEIR models                                    |         |       |             |
|   15 |     04/22 | What else can you do with matrices? I                         |         |       |             |
|   16 |     04/27 | What else can you do with matrices? II                        |         |       |             |
|   16 |     04/29 | Final Exam Review                                             |         |       |             |
|      | Final Day | Final Exam (Open Notes)                                       |         |       |             |

## Syllabus
Course: CSCI 2830 / CSCI 2897\
Lectures: Tuesday & Thursday, 8:00am – 9:15am\
Zoom: Unpublished. Please email.\
Lecturer: Daniel Larremore.\
Office Hours: Online via Zoom, times TBD.\
Email: daniel.larremore@colorado.edu\
Webpage: https://github.com/dblarremore/CSCI2897

### Description
*Calculating Biological Quantities* is an interdisciplinary course that brings together mathematics, coding, modeling, and biology. It is part of CU Boulder's *Computational Biology* minor.  Our goals in this course include 
* mastering practical mathematical techniques for representing and analyzing biological quantities of different kinds
* developing mathematical intuition about common biological calculations and concepts
* learning to model biologically related feedback processes, and solve or analyze their corresponding differential or difference equations
* adapting and combining methods to solve biological problems
* gaining confidence in decoding mathematical models and language, including the ideas and vocabulary of differential equations and linear algebra

### Prerequisites
MATH 1300 or APPM 1350 (Calc I).  This course has its roots in biology, math, and computer science, and while knowledge of all three is great, the whole point of the class is to develop strengths in the interdisciplinary space *between* these three fields. If you are enrolled in the course and feel that one area or another is a problem, let's talk about it. 

### Texts 
* [Required] Otto & Day: *A Biologist's Guide to Mathematical Modeling in Ecology and Evolution*
* [Optional] Zill: *A First Course in Differential Equations*

### Overview
* Mostly lecture-style class, in which I write on blank-ish slides and we talk about problems. 
* Reading the textbook before class will prepare you well. 
* Problem sets (every other week) consist of two types of exercises: "free throws" / "pushups" in which you get repeated practice on an easy or old topic, and more challenging problems with multiple parts where we engage with new concepts. (70%) 
* Exams (one midterm, one final) will cover the course materials, and must be taken "live" but are open note. (15% per exam)
* Computational Biology is cool.

 ### Lecture Recordings
* All lectures will be *live* and will also be recorded for later watching or rewatching. 
* Attendance will not be taken. 
* Links to recorded lectures will be posted on Canvas.
* If you need help with getting Zoom up and running, please visit [CU's OIT site](http://www.colorado.edu/oit/services/conferencing-services/web-conferencing-zoom).

### Coursework & Grading
* **Grade Breakdown:** 30% exams, 70% homework. Letter grades will be assigned at the end of the course so that I can incorporate *your* feedback on the problem sets and discount the ones that I make too difficult accordingly. 
* **Schedule:** There will be 6-8 problem sets, due approximately every 2 weeks. The number and schedule may vary due to partial reordering of the course material based on student feedback, and because of potential disruptions due to  the unfolding COVID-19 pandemic.
* **Exams:** There will be 2 exams—a midterm and a final. There will be a special review session, in-class, for each, which will be driven by student questions. **Exams must be taken live, during class time.**
* **Problem Sets:** Problem sets will be a mixture of math (e.g. solve this problem), writing (e.g. explain how X works in a few sentences), and coding (e.g. implement code for this model and produce a plot). Format for solutions will depend on the type of problems, but could include scans (use an app!) for handwritten math, PDF for written explanations, and Jupyter Notebooks for coding problems. 
* Turn in all assignments via Canvas.
* **Late / Dropped Assignments:** Life happens! Privacy is important! You don't need to ask for a homework to be dropped or to turn something in. Instead: (1) your lowest homework grade will be automatically dropped at the end of the semester. (2) You get three "late days" to use as you wish. You could, for example, turn in one homework 3 days late, or you could turn in three homeworks 1 day late each. Use wisely! Any late turn-ins are rounded up to the nearest whole day, e.g. turning in 5 minutes late or 23 hours late would both count as one day. 
* **Collaboration Policy:** Don't Google, StackOverflow, buy the teacher's edition of the books, or buy Chegg. Instead, work together. *Collaboration is encouraged* on the problem sets. However, you may not copy (in any way) from your collaborators and you must respect University academic policies at all times. To be clear: you may discuss the problems verbally, but you must write up your solutions separately. If you do discuss the problems with someone (and you are encouraged to!), you must then list and describe the extent of your collaboration in your solutions (a footnote is fine). 
* If you're unsure about anything above, please ask ahead of time.

### Suggestions: 
Suggestions for improvement are welcome at any time. Any concern about the course should be brought first to my attention. Further recourse is available through the office of the Department Chair or the Graduate Program Advisor, both accessible on the 7th floor of the Engineering Center Office Tower.

## Campus-Level Syllabus Information

### Classroom Behavior

Both students and faculty are responsible for maintaining an appropriate learning environment in all instructional settings, whether in person, remote or online. Those who fail to adhere to such behavioral standards may be subject to discipline. Professional courtesy and sensitivity are especially important with respect to individuals and topics dealing with race, color, national origin, sex, pregnancy, age, disability, creed, religion, sexual orientation, gender identity, gender expression, veteran status, political affiliation or political philosophy. For more information, see the policies on  [classroom behavior](http://www.colorado.edu/policies/student-classroom-and-course-related-behavior)  and the  [Student Code of Conduct](https://www.colorado.edu/sccr/sites/default/files/attached-files/2020-2021_student_code_of_conduct_0.pdf).

### Requirements for COVID-19

As a matter of public health and safety due to the pandemic, all members of the CU Boulder community and all visitors to campus must follow university, department and building requirements, and public health orders in place to reduce the risk of spreading infectious disease. Required safety measures at CU Boulder relevant to the classroom setting include:
-   maintain 6-foot distancing when possible,
-   wear a face covering in public indoor spaces and outdoors while on campus consistent with state and county health orders,
-   clean local work area,
-   practice hand hygiene,
-   follow public health orders, and
-   if sick and you live off campus, do not come onto campus (unless instructed by a CU Healthcare professional), or if you live on-campus, please alert  [CU Boulder Medical Services](https://www.colorado.edu/healthcenter/coronavirus-updates/symptoms-and-what-do-if-you-feel-sick).

Students who fail to adhere to these requirements will be asked to leave class, and students who do not leave class when asked or who refuse to comply with these requirements will be referred to  [Student Conduct and Conflict Resolution](https://www.colorado.edu/sccr/). For more information, see the policies on  [COVID-19 Health and Safety](https://www.colorado.edu/policies/covid-19-health-and-safety-policy)  and  [classroom behavior](http://www.colorado.edu/policies/student-classroom-and-course-related-behavior)  and the  [Student Code of Conduct](http://www.colorado.edu/osccr/). If you require accommodation because a disability prevents you from fulfilling these safety measures, please see the “Accommodation for Disabilities” statement on this syllabus.

All students who are new to campus must complete the [COVID-19 Student Health and Expectations Course](https://www.colorado.edu/protect-our-herd/how#anchor1 "https://www.colorado.edu/protect-our-herd/how#anchor1"). Before coming to campus each day, all students are required to complete the [Buff Pass](https://pass.colorado.edu/login "https://pass.colorado.edu/login").  

Students who have tested positive for COVID-19, have symptoms of COVID-19, or have had close contact with someone who has tested positive for or had symptoms of COVID-19 must stay home. **Note from Dan:** In this class, if you are sick or quarantined, please consider resting and using the late homework and dropped homework accommodations.  You need not tell me why you are using such accommodations, nor are doctor's notes required. 

### Accommodation for Disabilities

If you qualify for accommodations because of a disability, please submit your accommodation letter from Disability Services to your faculty member in a timely manner so that your needs can be addressed. Disability Services determines accommodations based on documented disabilities in the academic environment. Information on requesting accommodations is located on the  [Disability Services website](https://www.colorado.edu/disabilityservices/). Contact Disability Services at 303-492-8671 or  [dsinfo@colorado.edu](mailto:dsinfo@colorado.edu)  for further assistance. If you have a temporary medical condition, see  [Temporary Medical Conditions](http://www.colorado.edu/disabilityservices/students/temporary-medical-conditions)  on the Disability Services website.

### Preferred Student Names and Pronouns

CU Boulder recognizes that students' legal information doesn't always align with how they identify. Students may update their preferred names and pronouns via the student portal; those preferred names and pronouns are listed on instructors' class rosters. In the absence of such updates, the name that appears on the class roster is the student's legal name. 

### Honor Code

All students enrolled in a University of Colorado Boulder course are responsible for knowing and adhering to the Honor Code. Violations of the policy may include: plagiarism, cheating, fabrication, lying, bribery, threat, unauthorized access to academic materials, clicker fraud, submitting the same or similar work in more than one course without permission from all course instructors involved, and aiding academic dishonesty. If you have read this far into the syllabus, well done! Send me a picture or video of the coolest animal (your opinion) for a small bump to your grade. All incidents of academic misconduct will be reported to the Honor Code ([honor@colorado.edu](mailto:honor@colorado.edu)); 303-492-5550). Students found responsible for violating the academic integrity policy will be subject to nonacademic sanctions from the Honor Code as well as academic sanctions from the faculty member. Additional information regarding the Honor Code academic integrity policy can be found at the [Honor Code Office website](https://www.colorado.edu/osccr/honor-code).

### Sexual Misconduct, Discrimination, Harassment and/or Related Retaliation

The University of Colorado Boulder (CU Boulder) is committed to fostering an inclusive and welcoming learning, working, and living environment. CU Boulder will not tolerate acts of sexual misconduct (harassment, exploitation, and assault), intimate partner violence (dating or domestic violence), stalking, or protected-class discrimination or harassment by members of our community. Individuals who believe they have been subject to misconduct or retaliatory actions for reporting a concern should contact the Office of Institutional Equity and Compliance (OIEC) at 303-492-2127 or  [cureport@colorado.edu](mailto:cureport@colorado.edu). Information about the OIEC, university policies,  [anonymous reporting](https://cuboulder.qualtrics.com/jfe/form/SV_0PnqVK4kkIJIZnf), and the campus resources can be found on the  [OIEC website](http://www.colorado.edu/institutionalequity/).

Please know that faculty and graduate instructors have a responsibility to inform OIEC when made aware of incidents of sexual misconduct, dating and domestic violence, stalking, discrimination, harassment and/or related retaliation, to ensure that individuals impacted receive information about options for reporting and support resources.

### Religious Holidays

Campus policy regarding religious observances requires that faculty make every effort to deal reasonably and fairly with all students who, because of religious obligations, have conflicts with scheduled exams, assignments or required attendance. In this class, please let me know of upcoming religious holidays at least two weeks ahead of time if you will need an accommodation. See the [campus policy regarding religious observances](http://www.colorado.edu/policies/observance-religious-holidays-and-absences-classes-andor-exams) for full details.