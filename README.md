# Agile Final Project
Honors project for the [Introduction to Agile Development and Scrum](https://www.coursera.org/learn/agile-development-and-scrum) course by IBM Skills Network

## Overview

### Table of Contents
1. [Tasks](#tasks)
2. [Screenshot](#screenshot)
3. [Process](#process)
    1. [What I Learned](#what-i-learned)
4. [Acknowledgements](#acknowledgements)

The challenge is to put yourself in the place of a product owner, scrum master, and developer within a scenario project.

### Tasks
1. Create a workspace in ZenHub
2. Create new issue templates specific to the project
3. Create new issues from given stakeholder requests
4. Prioritize given issues into either the product backlog or icebox
5. Utilize a As a.. I need.. So that... issue template
6. Create a sprint
7. Update the top 5 issues to be handled within the sprint with Gherkin acceptance criteria
8. Assign and move issues

### Screenshot
![](Project.png)

## Process

The project was given the following stakeholder requirements:
1. Need the ability to create a product in the catalog. 
2. Need the ability to retrieve a product from the catalog. 
3. Need the ability to update a product in the catalog. 
4. Need the ability to delete a product from the catalog. 
5. Need the ability to "Like" a product in the catalog. 
6. Need the ability to "Dislike" a product in the catalog. 
7. Need the ability to list all products in the catalog. 
8. Need the ability to query a subset of products in the catalog. 
9. Must be hosted in the cloud. 
10. Must have automation to deploy new changes to the cloud. 

From here, I used an plain language issue template to describe what we would want accomplished based on who would want such a feature.

Example:
> **As a** service provider
>
> **I need** to create a new product and add it to the catalog
>
> **So that** the customer can see the new product to purchase

After, we can determine what needs to be prioritize in the project, and what can be held off on for now. 

The top priorities were added to the backlog and the top 5 issues were added to the first sprint backlog. The issues in the sprint backlog were given acceptance criteria in the form of Gherkin syntax:

```gherkin
Given we have a new product to offer
When I add the product to the catalog
Then the product will appear in the full catalog
```

This helps communicate to the development team at what point do we feel like the issue has been completed successfully and helps us define new issue criteria after reviewing the work completed.

#### What I learned
Initially I took this course to learn the basics of Agile methodology to better understand the process of software development, as well as gain some understanding of what a day in the life of a SWE looks like.

My biggest takeaways have been:
1. How to utilize a Kanban board for a project
2. How to create issues and issue templates
3. How to integrate GitHub issues with a third party provider like ZenHub
4. The process of prioritizing issues as well as assigning issues, points, tags, etc.
5. How to start and close out a sprint

## Acknowledgements
- Special thanks to the [IBM Skills Network](https://skills.network/) for offering excellent courses to help newer developers learn and grow in their careers. 
