-   [](https://alx-intranet.hbtn.io/dashboards/my_planning)
-   [](https://alx-intranet.hbtn.io/projects/current)
-   [](https://alx-intranet.hbtn.io/users/my_reports)
-   [](https://alx-intranet.hbtn.io/corrections/to_review)
-   [](https://alx-intranet.hbtn.io/dashboards/my_current_evaluation_quizzes)

* * * * *

-   [](https://alx-intranet.hbtn.io/dashboards/my_curriculums)
-   [](https://alx-intranet.hbtn.io/concepts)
-   [](https://alx-intranet.hbtn.io/dashboards/video_rooms)
-   [](https://alx-intranet.hbtn.io/servers)
-   [](https://alx-intranet.hbtn.io/user_containers/current)
-   [](https://alx-intranet.hbtn.io/dashboards/my_tools)

* * * * *

-   [](https://alx-intranet.hbtn.io/users/peers)
-   [](https://alx-intranet.hbtn.io/dashboards/my_captain_log)
-   [](https://alx-students.slack.com/)

    [](https://alx-intranet.hbtn.io/users/my_profile)

0x09. Web infrastructure design
===============================

-   By Sylvain Kalache, co-founder at Holberton School
-   Weight: 1
-   Project to be done in teams of 3 people
-   Project over - took place from 

    Mar 24, 2022

     to 

    Mar 28, 2022

     - you're done with 0% of tasks.
-   Manual QA review was done on 

    Feb 26, 2022 9:15 AM

#### In a nutshell...

-   **Manual QA review:** 0.0/42 mandatory & 0.0/5 optional
-   **Altogether:**  **0.0%**
    -   Mandatory: 0.0%
    -   Optional: 0.0%
    -   Calculation:  0.0% + (0.0% * 0.0%)  == **0.0%**

Concepts
--------

*For this project, students are expected to look at these concepts:*

-   [DNS](https://alx-intranet.hbtn.io/concepts/12)
-   [Monitoring](https://alx-intranet.hbtn.io/concepts/13)
-   [Web Server](https://alx-intranet.hbtn.io/concepts/17)
-   [Network basics](https://alx-intranet.hbtn.io/concepts/33)
-   [Load balancer](https://alx-intranet.hbtn.io/concepts/46)
-   [Server](https://alx-intranet.hbtn.io/concepts/67)

Resources
---------

**Read or watch**:

-   **Network basics** concept page
-   **Server** concept page
-   **Web server** concept page
-   **DNS** concept page
-   **Load balancer** concept page
-   **Monitoring** concept page
-   [What is a database](https://alx-intranet.hbtn.io/rltoken/2aD2bdPj0eDQWmxZTOBvZw "What is a database")
-   [What's the difference between a web server and an app server?](https://alx-intranet.hbtn.io/rltoken/9ex7UxzBD4-opT_U9N8_xg "What's the difference between a web server and an app server?")
-   [DNS record types](https://alx-intranet.hbtn.io/rltoken/w_sIcupLbs9Xd9x6VC7RcA "DNS record types")
-   [Single point of failure](https://alx-intranet.hbtn.io/rltoken/ipevhCv7QCKeGswHNrhkNA "Single point of failure")
-   [How to avoid downtime when deploying new code](https://alx-intranet.hbtn.io/rltoken/4ansLu2gtHnoFrNThqyObA "How to avoid downtime when deploying new code")
-   [High availability cluster (active-active/active-passive)](https://alx-intranet.hbtn.io/rltoken/TAJeVYy9U9iLaEDd6XkbRA "High availability cluster (active-active/active-passive)")
-   [What is HTTPS](https://alx-intranet.hbtn.io/rltoken/c0zs2MxrmxFLsCPOizxq6g "What is HTTPS")
-   [What is a firewall](https://alx-intranet.hbtn.io/rltoken/j6idMcUTyNEDj1oYDQFmUw "What is a firewall")

Learning Objectives
-------------------

At the end of this project, you are expected to be able to [explain to anyone](https://alx-intranet.hbtn.io/rltoken/FPJvEE-DRJDvmVTNWeFR8A "explain to anyone"), **without the help of Google**:

### General

-   You must be able to draw a diagram covering the web stack you built with the sysadmin/devops track projects
-   You must be able to explain what each component is doing
-   You must be able to explain system redundancy
-   Know all the mentioned acronyms: LAMP, SPOF, QPS

Requirements
------------

### General

-   A `README.md` file, at the root of the folder of the project, is mandatory
-   For each task, once you are done whiteboarding (on a whiteboard, piece of paper or software or your choice), take a picture/screenshot of your diagram
-   This project will be manually reviewed:
-   As each task is completed, the name of that task will turn green
-   Upload a screenshot, showing that you completed the required levels, to any image hosting service (I personally use [imgur](https://alx-intranet.hbtn.io/rltoken/m_O2HLsKrO1zg31LMcLOGQ "imgur") but feel free to use anything you want).
-   For the following tasks, insert the link from of your screenshot into the answer file
-   After pushing your answer file to GitHub, insert the GitHub file link into the URL box
-   You will also have to whiteboard each task in front of a mentor, staff or student - no computer or notes will be allowed during the whiteboarding session
-   Focus on what you are being asked:
-   Cover what the requirements mention, we will explore details in a later project
-   Keep in mind that you will have 30 minutes to perform the exercise, you will get points for what is asked in requirements
-   Similarly in a job interview, you should answer what the interviewer asked for, be careful about being too verbose - always ask the interviewer if going into details is necessary - speaking too much can play against you
-   In this project, again, avoid going in details if not asked
[O
Quiz questions
--------------

#### Question #0

What is a server?

-   [ ]

    A server is a device, a virtual device or computer program or providing functionality for other programs or devices, called "clients".

-   [ ]

    A server is a software that serves web pages.

-   [ ]

    A server is returning information to other computers when asked.

#### Question #1

What is a web server?

-   [ ]

    A web server is a software or physical device serving web pages over HTTP.

-   [ ]

    A web server is a software that serves web pages to clients upon their request, it does this over the protocol HTTP.

-   [ ]

    A web server is a software that serves web pages to clients upon their request.

#### Question #2

What is a codebase?

-   [ ]

    A list of software libraries.

-   [ ]

    Is the collection of source code that is used to build a software system.

-   [ ]

    Is the most important files of a software system.

#### Question #3

What is a database?

-   [ ]

    Is a collection of text files that are stored so that it can be easily accessed, updated and managed by the local application.

-   [ ]

    Is a collection of information that is stored on a physical server and organized so that it can be easily accessed, updated and managed.

-   [ ]

    Is a collection of information that is stored and organized so that it can be easily accessed, updated and managed.

#### Question #4

What is a DNS?

-   [ ]

    A list of domain names.

-   [ ]

    A system to translate domain names into IP addresses.

-   [ ]

    A system that contain all Internet IPs.

#### Question #5

What is HTTPS?

-   [ ]

    A faster version of HTTP.

-   [ ]

    A version of HTTP that protect your personal information.

-   [ ]

    A version of HTTP that secure the traffic between your browser and the website by encrypting it.

#### Question #6

What is TCP/IP?

-   [ ]

    Transmission Control Protocol/Internet Protocol, is a suite of communications protocols used to interconnect network devices on the Internet or any private network.

-   [ ]

    Transmission Control Protocol/Internet Protocol, is a suite of communications protocols used to interconnect network devices on the Internet.

-   [ ]

    Transmission Control Protocol/Internet Protocol, is a suite of communications protocols used to interconnect network devices on private network.

Submit answers

Please make sure to validate all quiz questions before moving on to project tasks
---------------------------------------------------------------------------------

Copyright © 2022 ALX, All rights reserved.
