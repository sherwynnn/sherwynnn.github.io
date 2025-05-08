---
title: Redesigning a HR Management System
date: 2025-04-27 18:56:33 +0800
categories: [Case Study]
tags: [case study]     # TAG names should always be lowercase
author: <author_id>
description: The main project I worked on in my previous internship in Allied as a product designer intern.
comments: false
image: /assets/img/2025-04-27-hr-management-system/preview-image-hrms.png
---

## Overview

For the last 9 months of my degree programme, I had the opportunity to go through a 9-month internship under Allied Container (Engineers & Manufacturers) Pte Ltd as part of my IWSP (Integrated Work-Study Programme).

During this period, the main project assigned to me was to redesign the company’s HR management system (SaaS) in terms of its information layout and user experience, while creating new user flows for development to meet the requirements of stakeholders and users.

## Approach
### Role-Based Access

When the system was in early development, a clear distinction of roles in the system had not been fleshed out yet. Hence, I identified 3 main roles to design for:
![Desktop View](/assets/img/2025-04-27-hr-management-system/user-design.png){: width="700" height="400" }
_All users are generally separated into 3 main roles: HR, manager and normal employees._

I kept the design as modular as possible so that the system can accommodate these 3 major roles, whereby additional features are shown and hidden based on the access granted.
![Desktop View](/assets/img/2025-04-27-hr-management-system/widget-comparison.png){: width="700" height="400" }
_Comparison of Leave Requests for normal employees and managers_

### Information-Heavy Design

A tab design was preferred for majority of the designs as it allowed for effectively segregating information into huge chunks, while at the same time ensuring that just the right amount of information appears on each page at any given time.

This was especially important since a single employee could have hundreds of data fields across different categories, such as personal details, education, family members, and more.

![Desktop View](/assets/img/2025-04-27-hr-management-system/tab-design.png){: width="700" height="400" }
_Tabbed design to separate relevant information_

### The devil is in the details

Many things were taken into consideration when considering all the possible different pathways, and the complexity of each individual component reflects this the most accurately.

Wherever possible, these components were designed to communicate the current status of the system clearly, without needing users to guess or rely on external guidance.
![Desktop View](/assets/img/2025-04-27-hr-management-system/submit-claim-1.png)
_Interactive behaviour for image upload field to indicate upload status_

One key consideration was how to make the most effective use of limited space, while still ensuring that essential details are accessible when needed.

![Desktop View](/assets/img/2025-04-27-hr-management-system/hover-stackedimages.gif){: width="400" height="400" }
_Essential details such as the user's name and job title are revealed when hovering over their icon_

### Personality and Storytelling

I always felt that giving my designs personality helps me to bring life to them, especially for a people-centric system meant to host hundreds of employees.

What I observed was that it was easier for stakeholders to follow along when names are generally more recognisable. For instance, discussions were done from a third-person perspective where each role had a distinctive name tied to them.

![Desktop View](/assets/img/2025-04-27-hr-management-system/employee-view.png){: width="700" height="400" }

This approach was particularly useful when I had to demonstrate designs for the three different roles as mentioned above (HR, manager, employee). For instance, it became naturally understood that "Taylor Swift" represented the HR Manager.

While this isn’t something you’d typically see in a real-world system, it made it much easier for me to communicate these designs clearly and keep the conversation focused and engaging.

## Challenges

Here were the 3 main challenges that I faced as my first official project as a UX/UI designer:

### Understanding HR processes and industry expectations

Coming into this project, I only had surface-level knowledge on HR processes that a typical company would need to carry out on a regular basis. Thus, my goal was to first understand how a HR management system would best assist HR personnel to complete these processes in an efficient and intuitive manner. 

Before starting the design process, I analyzed direct competitors that offered similar HR SaaS solutions and compared their core features and user flows with one another, while identifying best practices and areas for improvement. At the same time, spotting areas where competitors fell short gave me opportunities to fine-tune my approach and design more efficient, user-friendly solutions that addressed those gaps.

These competitors include local HR providers such as Payboy, OmniHR and QuickHR.

![Desktop View](/assets/img/2025-04-27-hr-management-system/omni-analysis.png){: width="700" height="400" }
_Excerpt of a page-by-page analysis for OmniHR’s leave/timeoff feature_

### Team Size and Priorities

For this project, my team primarily consisted of only 2 people: myself (the designer) and a remote developer.

Both of us collaborated closely and constantly gave each other real-time feedback so as to meet deadlines on time. Though the developer was not familiar with the HR processes in Singapore, we both kept each other up to speed on the tasks to accomplish together and frequently arranged discussions outside of sprint meetings.

While both of us worked together extremely well, at the end of the day it was only just the 2 of us designing and developing an entire HR management system from scratch. The scale of the system was extremely complex, and new features were frequently introduced by stakeholders, which made it difficult for both of us to maintain a clear focus on the system’s core features.

###  Limited user input and stakeholder-driven feedback

Most of the feedback came from UAT (user acceptance testing) sessions with internal stakeholders who understandably focused on their own HR operational needs, slightly creating a gap between user experience and business expectations. Despite this, the feedback was still important to both me and the developer, as these stakeholders are essentially the end users that would be using the HR management system post-deployment.

The stakeholders helped provide contextual information to specific HR processes to be integrated into the system, as well as giving us access to useful resources (usually in the form of screenshots, docs or spreadsheets) to help us to create the relevant modules as requested.

For instance, the annual submission of tax forms was designed as a module in the HR management system, where some of the more ambiguous fields were clarified with the stakeholders so as to streamline the submission process and make it as intuitive as possible.

![Desktop View](/assets/img/2025-04-27-hr-management-system/ir8a-real.png)
![Desktop View](/assets/img/2025-04-27-hr-management-system/ir8a-hrms.png)
_Integrating IR8A tax form submissions into a module in the HR management system_

## What’s next?

One of the biggest lessons I learned from this project was how task prioritization is extremely key when it comes to SaaS design and development. The reason nothing was ever confirmed to be finished was because of the perpetually new features to be worked on every other day, which meant that we were unable to allocate as much time and effort to refining and completing the existing core features that really mattered. Even in the final week of my internship, I was still actively working on new feature designs, which made it especially challenging to dedicate enough time to preparing a proper design handoff.

Despite all this, this internship was a valuable experience that helped me step foot into the professional world of UX and UI design. I’m very grateful to Allied for allowing me to be the lead designer of such a large-scale project, where I not only shaped the look and feel of the product but also had the chance to influence stakeholders through my design decisions.