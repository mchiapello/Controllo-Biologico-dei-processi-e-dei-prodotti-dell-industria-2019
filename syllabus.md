---
layout: page
title: Syllabus
credits: 3
semester: Summer 2019
professor: Dr. Marco Chiapello
office: IPSP-CNR, Strada delle cacce 73, Torino
email: chiapello.m@gmail.com
schedule: ['Fridays, 14-18, Torino Esposizioni']
office_hours: Monday 14-15
office_hours_location: IPSP-CNR, Strada delle cacce 73, Torino
TA: Silvia Perotto
TA_email: silvia.perotto@unito.it
---

## {{ site.title }} 


### Professor

{{ page.professor }}

Office: {{ page.office }}

Email (best way to contact us):
[{{ page.email }}](mailto:{{ page.email }})


### Times & Location

**Note: class locations may change! I will try to notify you asap**

{% for class in page.schedule %}
  {{ class }}
{% endfor %}


### Office Hours

Times: {{ page.office_hours }}

Location: {{ page.office_hours_location }}

Or by appointment. *Note: my schedule gets very busy during the semester so
please try to schedule appointments as far in advance as possible. In general it
will be very difficult to set up appointments less than 24 hours in advance.*


### Course TA

{{ page.TA }}

Email: [{{ page.TA_email }}](mailto:{{ page.TA_email }})


### Website

The syllabus and other relevant class information and resources will be posted
at [{{ site.url}}]({{ site.baseurl }}/).
Changes to the schedule will be posted to this site so please try to check it
periodically for updates.


### Course Communications

Email: [{{ page.email }}](mailto:{{ page.email }})


### Required Texts

There is no required text book for this class.

All needed material is openly available on the course website. If you are interested in additional reading on the topics we are covering I highly recommend R for Data Science, which is freely available on the web.

### Course Description
 
Computers are increasingly essential to the study of all aspects of biology. Data management skills are needed for entering data without errors, storing it in a usable way, and extracting key aspects of the data for analysis. Basic programming is required for everything from accessing and managing data, to statistical analysis, to modeling. This course will provide an introduction to data management, manipulation, and analysis, with an emphasis on biological problems. Class will typically consist of short introductions or question & answer sessions, followed by hands on computing exercises. The course will be taught using R and SQLite, but the concepts learned will easily apply to all programming languages and database management systems. No background in programming or databases is required.


### Prerequisite Knowledge and Skills

Knowledge of basic biology.


### Purpose of Course

In this course you will learn all of the fundamental aspects of computer
programming that are necessary for conducting basic data analysis. By the end of
the course you will be able to use these tools to import data into R, perform
analysis on that data, and export the results to graphs and text files. 
By learning how to get the computer to do your work for you, you will
be able to do more science faster.


### Course Goals and Objectives

Students completing this course will be able to:

* Organize data in spreadsheets
* Write simple computer programs in R
* Automate data analysis
* Apply these tools to address biological questions
* Apply general data management and analysis concepts to other programming
  languages


### Teaching Philosophy




## Course Policies


### Attendance Policy

Attendance will not be taken or factor into the grades for this class. However,
experience suggests that students who regularly miss class struggle to learn the
material.


### Exam Policy

There will be a final exam for this course. Students should be able to demostrate the ability to condact a well structured data analysis.

### Course Technology

Only free available software will be used during the course.

## Grading Policies

Grading for this course will revolve around a combination of final exam (75%)
and interaction during the course (25%).

* Produces the correct answer using the requested approach: 100%
* Generally uses the right approach, but a minor mistake results in an incorrect
    answer: 90%
* Attempts to solve the problem and makes some progress using the core concept:
    50%
* Answer demonstrates a lack of understanding of the core concept: 0%


## Course Schedule

The details course schedule is available on the course website at:
[{{ site.url }}/schedule]({{ site.baseurl }}/schedule).


**Disclaimer:** This syllabus represents my current plans and objectives. As we
go through the course, those plans may need to change to enhance the class
learning opportunity. Such changes, communicated clearly, are not unusual and
should be expected.
