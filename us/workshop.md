---
layout: us-page
title: Workshop
weight: 40
---

# Pre-Fest Workshop - [Wednesday, 9/13](schedule)

This year’s pre-fest workshop will introduce you to the basics of REST, with a combination of fun presentations, discussion, and hands-on hypermedia projects. You’ll come away from the day’s event with a better understanding of REST and hypermedia, the knowledge to build a REST Service and a REST/Hypermedia Client, and a working example of a running REST service and Hypermedia client.

## Topics

1. Fielding’s REST
2. Hypermedia
3. APIs
4. Loose-Coupling
5. Avoiding Hard Versioning

## Desired Outcomes
* Understand REST and Hypermedia
* Know how to build a REST Service
* Know how to build a REST/Hypermedia Client
* Know what it takes to build services that can change without breaking clients
* Have an example of a running REST service and Hypermedia client

## Schedule

This is our starting schedule plan. It's a work in-progress, so feedback is
welcome! Feel free to contribute suggestions by filing issues on
[this site's issue tracker](https://github.com/RESTFest/2017-Greenville/issues).

## Morning: REST and Servers (3hrs)
*Pre-reqs: Docker installed*

1. What is REST? (45min)
2. Designing (45min)
   1. Understanding your clients and use cases
   2. Identifying resources
   3. Picking a hypermedia format
       1. HAL
       2. Collection+JSON
       3. JSON API
       4. Siren
       5. others

BREAK (15/30min)

1. Implementing (45min)
   1. The open data sets
   2. Introduction to API-in-a-Box
   3. Building hypermedia APIs with API-in-a-Box
2. Validating (45min)
   1. Test your hypermedia API
   2. Open Discussion/Q&A on REST servers

LUNCH

## Afternoon: REST and Client Apps (3hrs)

1. The Basics of a REST Client (45min)
   1. REST is Hypermedia: A short review
   2. Understanding H-Factors
   3. Dealing with the OAA challenge
   4. Self-Description and Adaptability
2. Designing (45min)
   1. The Anatomy of a REST/Hypermedia Client
   2. Hypermedia Types and the HTML DOM
       1. HAL 
       2. Siren
       3. Collection+JSON
   3. A Visual Model

BREAK (15/30min)

1. Implementing (45min)
   1. The HTML SPA Client
   2. Scripting a Collection+JSON Client
       1. Debug
       2. Title
       3. Links
       4. Items
       5. Queries
       6. Templates
       7. Errors
2. Validating (45min)
   1. Test your Cj Client against a Cj server
   2. Open Discussion/Q&A on Hypermedia clients
