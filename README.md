# BuffBurgers
## Software Development Methods and Tools Team Project
http://www.lousymedia.com/csci-3308/assignments/team-project

## Overview
* Who: 
  * Cameron Taylor: cata5492
  * Jace Conflenti: jaceconflenti
  * Alex Walling: alexwalling
  * Alexander Luo: Alex-Luo
  * Callie Jones: jonescal000
* Title: BuffBurgers
* Description: A mobile application designed to make ordering burgers from the Farrand Grab-and-Go a much faster and simpler process.
* Vision statement: Faster Farrand burgers for Buffs, without the inconvenience of waiting in line.
* Motivation: It's hard to grab a burger between classes because you have to put in your order and wait for it to be cooked - with this application, you could order your burger in advance and have it ready to pick up when you arrive.
* Risks: 
  * None of us are familiar with iOS development or querying databases from applications.
  * Some of us have worked together as partners but never as a whole team.
  * There are some logistical issues with using CU identikeys to authenticate users.
  * As work on the project progesses we may indentify more features/requirements than anticipated.
  * Estimating the amount of time required to complete components could differ greatly from the actual time required. This is especially true because many of us will be doing a lot of these things for the first times.
* Mitigation strategy for dealing with the risk
  * We may be able to set up an email verification system using @colorado.edu emails.
  * We can spend a lot of time planning to try and prevent requirements inflation as we progress.
  * We can use each other as resources, but we can also seek out additional assistance if we get stuck learning something new.

### Requirements

User Requirements | ID Number | Sizing - Agile/Time
----------------- | --------- | -------------------
As a user, I want to be able to choose from the same burger customization options, so that I can get the same burger as if I ordered it in-person. | 1 | 3 | 
As a user, I want to be able to see Farrand's business hours, so that I can see when I can place an order. | 2 | 1 |
As a user, I want to be able to login and view my recent order history so that I can quickly place an order again. | 3 | 7 |
As a user, I want to see the estimated time on my order so I don't have to wait for my order. | 4 | 4 |
As a provider, I want to be able to view order status so I can track if orders have been started and finished. | 5 | 3 |
As a provider, I want to be able to see if a user hasn't picked up an order before so we can warn/blacklist them. | 6 | 3 |
As a provider, I want to be able to remove the afformentioned flag so that I can return a customer to goodstanding when they resolve their issue. | 7 | 3
As a provider, I want to be able to view all pending orders and sort by most recent so that I can make orders as they come in. | 8 | 7

Functional Requirements | ID Number | Sizing - Agile/Time
----------------------- | --------- | -------------------
As a function of the application, I want to require that all users verify their @colorado.edu email addresses so that only CU students/faculty can access the ordering system. | 9 | 4 | 
As a function of the application, I want to be able to retrieve forgotten passwords so that users/providers can regain access to their accounts. | 10 | 4 |
As a function of the application, I want to display order choices and time estimation for order pick up so I can provide accurate order details. | 11 | 3 |
As a function of the application, I want to send a notification to each user when their order is finished so they can pick it up. | 12 | 4 |
As a function of the application, I want to prevent customers from ordering a burger when Farrand is closed so that any subsequent orders aren't thrown off by invalid ones. | 13 | 4 |
As a function of the application, I want to show Farrand's business hours to users who try to order a burger after-hours so that I can see when they are open. | 14 | 1

Non-Functional Requirements | ID Number | Sizing - Agile/Time
--------------------------- | --------- | -------------------
As a part of the application, I want a large amount of storage so I can facilitate multiple users. | 15 | 3 |
As a part of the application, I want to ensure that adding to and querying the database is be 100% reliable so that orders are not lost. | 16 | 4 |

#### Methodology & Plan
* Methodology: (Mostly) Agile?
  * Project Tracking software: Trello
  * Link to project tracking software: https://trello.com/csci3308project2, https://trello.com/b/Hv5gd8gu
  * __(re)make trello board so it's public and they can access__
  * __make sure instructor and TAs have access to Trello and GitHub__
* Project plan: __copy paste picture from trello__ ![Image of Project Plan](https://octodex.github.com/images/linktocat.jpg)

### Links to possible logistic problems/solutions
* http://www.colorado.edu/avcit/incommon
* http://www.colorado.edu/oit/services/identity-access-management/federated-identity/help/guidelines
* http://www.colorado.edu/oit/about-oit/oit-campus-outreach/list
