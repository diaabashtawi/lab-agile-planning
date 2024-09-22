---
name: 'User Story '
about: This template is for creating user stories
title: ''
labels: ''
assignees: ''

---

**As a** Marketing Manager   
 **I need** a list of customer names and emails  
 **So that** I can notify theme of marketing promotions 
   
 ### Details and Assumptions
 * We maintain customer emails 
 * Customers have opted-in to promotions
   
 ### Acceptance Criteria  
   
 ```gherkin
 Given  there are 100 customers in the database 
 When I request the customer email list 
 Then I should see a list of 90 customer emails
 ```
