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


### Insegnante

{{ page.professor }}

Ufficio: {{ page.office }}

Email (il miglior modo per contattarmi):
[{{ page.email }}](mailto:{{ page.email }})


### Luogo e ora

**Note: class locations may change! I will try to notify you asap**

{% for class in page.schedule %}
  {{ class }}
{% endfor %}


### Ore di ricevimento

Times: {{ page.office_hours }}

Location: {{ page.office_hours_location }}

Or by appointment. *Note: my schedule gets very busy during the semester so
please try to schedule appointments as far in advance as possible. In general it
will be very difficult to set up appointments less than 24 hours in advance.*


### Responsabile del corso

{{ page.TA }}

Email: [{{ page.TA_email }}](mailto:{{ page.TA_email }})


### Website

The syllabus and other relevant class information and resources will be posted
at [{{ site.url}}]({{ site.baseurl }}/).
Changes to the schedule will be posted to this site so please try to check it
periodically for updates.


### Comunicazioni

Email: [{{ page.email }}](mailto:{{ page.email }})


### Libri richiesti

There is no required text book for this class.

All needed material is openly available on the course website. If you are interested in additional reading on the topics we are covering I highly recommend R for Data Science, which is freely available on the web.

### Descrizione del corso
 
Computers are increasingly essential to the study of all aspects of biology. Data management skills are needed for entering data without errors, storing it in a usable way, and extracting key aspects of the data for analysis. Basic programming is required for everything from accessing and managing data, to statistical analysis, to modeling. This course will provide an introduction to data management, manipulation, and analysis, with an emphasis on biological problems. Class will typically consist of short introductions or question & answer sessions, followed by hands on computing exercises. The course will be taught using R, but the concepts learned will easily apply to all programming languages and database management systems. No background in programming or databases is required.


### Prerequisiti

Nessuno


### Scopo del corso

In this course you will learn all of the fundamental aspects of computer
programming that are necessary for conducting basic data analysis. By the end of
the course you will be able to use these tools to import data into R, perform
analysis on that data, and export the results to graphs and text files. 
By learning how to get the computer to do your work for you, you will
be able to do more science faster.


### Obiettivi del corso

Students completing this course will be able to:

* Organize data in spreadsheets
* Write simple computer programs in R
* Automate data analysis
* Apply these tools to address biological questions
* Apply general data management and analysis concepts to other programming
  languages


### Filosofia di insegnamento

L'**apprendimento** è un _processo_ che conduce ad un _cambiamento_, risultante dalle _esperienze_ e in grado dia aumentare le potenzialità di future prestanzioni e di ulteriore apprendimento. Questa definizione include 3 elementi essenziali:

1. L'apprendimento è un _processo_ e non un prodotto. Tuttavia, siccome si svolge nella mente degli studenti, il docente può solo inferire che ha avuto luogo osservando le loro produzioni o le loro prestazioni.
1. L'apprendimento implica la _modifica_ di conoscenze, convinzioni personali, comportamenti ed atteggiamenti. Queste modifiche non sono istantanee: richiedono tempo e hanno in impatto duraturo sul modo in cui gli studenti pensano ed agiscono.
1. L'apprendimento non è qualcosa che si fa _agli_ studenti, ma qualcosa che gli studenti fanno a se stessi. E' il risultato diretto di come gli studenti interpretano e reagiscono alle proprie _esperienze_, consce e inconsce, passate e presenti. 

(tratto da "Come impariamo", Ambrose et al)

### Frequenza

Obligatoria


### Esame

L'esame finale consisterà nel dimostrare di essere in grado di condurre un'analisi dati strutturata.

### Programmi del corso

Durante il corso useremo programmi open-source.

## Politica del voto

Il voto finale sarà una combinazione della prova conclusiva (75%) e dell'interazione durante il corso (25%).

## Programma del corso

Il programma dettagliato è disponibile qui:
[{{ site.url }}/schedule]({{ site.baseurl }}/schedule).


**Disclaimer:** This syllabus represents my current plans and objectives. As we
go through the course, those plans may need to change to enhance the class
learning opportunity. Such changes, communicated clearly, are not unusual and
should be expected.
