---
layout: essay
type: essay
title: "Legos in Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2024-04-25
published: true
labels:
  - UI
  - Design Patterns
---

Legos in design patterns? How does that have anything to do with software engineering or even UI design? Before you scroll away, let me explain. In software engineering, design patterns are generalized solutions to commonly recurring problems. Think of them not as final products, but as templates to be adapted to meet the specific needs of a problem. So, what do Legos have to do with design patterns?

Legos are not only part of my core childhood, but also can be used as a metaphor for design patterns. What's the recurring problem? Let's say the recurring problem is the desire to build something, anything. The general solution? Building blocks. While I may choose to build a Harry Potter Hogwarts Castle, it won't always cater to everyone's specific vision. What if someone wants to build a treehouse with glass windows? This can be done by adding specialized leaf pieces or window pieces. What if someone wanted to build a pirate ship? We would then add canons and a helm piece. The extra specific pieces represents the flexibility that software engineers can add to modify and shape the final product to fit various requirements.

In my introduction to design patterns, I worked with a simple React application template. This template, akin to a set of building blocks, primarily utilized React components to manage and display data from collections. It served as a prime example of how design patterns can be applied to create diverse applications with the same underlying functionality. For instance, we transformed this basic template into an inventory management system as well as a project tracker for organizing tasks.

Design patterns are like LEGOs – versatile, adaptable, and capable of constructing a multitude of solutions from a common foundation.

## Design Patterns in Manoa Rainbow Cards!

So how did we implement design patterns in our website? We used the Model View Controller(MVC) architecture pattern that allowed us to organize and make the web development process extremely smooth-sailing. Now what is MVC? Model is the backend that contains all the data logic, View is the frontend or graphical user interface (GUI), and Controller is the brains of the application that controls how data is displayed. 

When adding or editing our professor cards, we don't directly touch or change anything from the data collection process. We utilize a dedicated page where users input information and only acccepts when all input is filled corretcly. This information is then transmitted to the data model, which handles the insertion of new data(cards) and updates our catalog page as well. It updates all pages that needs to be updated. For our website, we have pages that are only specifically available to either admin, a user, or a professor. Changes made updates all necessary pages without changing the data collection process.
