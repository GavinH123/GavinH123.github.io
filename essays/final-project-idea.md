---
layout: essay
type: essay
title: "Final Project Idea"
date: 2020-11-01
labels:
  - Software Engineering
  - Meteor
  - Semantic React
---
Written by: Jeanne Chan, Helene Haugen, Gavin Hirai, Justin Yip
<h2>Overview</h2>
We believe that the Laulima interface is outdated. We would like to update the Laulima page to be simpler by reducing the number of clicks to get to each item in Laulima. For example, in order to get to the class webpages, the user must click Sites then select a course, to reduce the number of clicks, a home page can be implemented that would show all current courses so users wouldn’t need to navigate through the “sites” dropdown menu. Another complicated task in Laulima is viewing deadlines. This must be done by going to each individual course site then looking at the calendar tab, but this can be made simpler by having a master calendar with all deadlines displayed. In addition, the overview tab sometimes has very little use because there is not much information to be displayed under that tab. 

<h2>Mockup Page Ideas</h2>
Have a home page that displays all classes and a brief description of the course. Include an option to go to the master calendar. 
Making the alerts drop down in the top right corner to be a tab such as the announcements with a list.

     *Landing page
     *User home page
      *Site pages
      *Renovated Overview section
      *New Alerts page for deadlines
      *Calendar tab(for deadlines) 
     *Admin home page
     *Site pages(different classes)
 
<h2>Use Case Ideas</h2>
This update would affect all of UH: students, instructors, and staff. Students would have an easier time viewing course information while using a more modern style page. Instructors can reduce repetition of necessary information (DRY Principle).  
New user goes to landing page, logs in, gets home page, must be student or staff
Admin goes to landing page, logs in, gets home page, edits site.
Instructors/staff goes to landing page, logs in, gets home page, edits their own courses (add or edits announcements, assignments, resources).
Students goes to landing page, logs in, finds all courses on home page, can add messages to discussion boards and upload assignments.

<h2>Beyond the Basics</h2>
     *Allow students to change notifications (or make it easier to change)
     *Changing where you are able to access the sites so that it is simpler and easier to find the sites you are looking for
     *To create the site we would use semantic react. To handle user login and accounts we would use mongo db
     *What information will the calendar show for deadlines. Will it be clickable with a popou to show more information
     *The calendar would display the due dates of assignments according to the due dates of assignments that were set on the assignments tab




