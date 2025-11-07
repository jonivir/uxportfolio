---
author: Joni
date: '2023-10-20'
description: ''
draft: false
image: /images/M2kodit-nosto.png
tags:
- case-study
- ux-research
title: m2Kodit
toc: null
---

# M2-Kodit

## Usability teting

The central objective of this UX research project was to ensure the usability of the M2-Kodit website from the perspectives of both current and potential residents (applicants).

## Summary

For this project, we divided the user testing into two distinct groups: "Current Residents" and "Potential Residents" of M2-Kodit. The test tasks were tailored to address the specific needs and objectives of each group.  
  
The primary objective of the tasks assigned to the "Current Residents" group was to identify any usability issues on the website concerning the discovery and utilization of services available to individuals currently residing in M2-Kodit's homes.  
  
In contrast, the tasks given to the "Potential Residents" group aimed to uncover potential usability challenges related to activities such as searching for a suitable apartment, catering to the unique needs and expectations of those considering M2-Kodit as their future home.

### Testing methodology

- Current residents were recruited from M2-Kodit's existing tenants.
- Potential residents were recruited from to represent a diverse group of users.
- All tests were conducted remotely via Microsoft Teams, with users sharing their screens for recording.
- Each testing session had a 60-minute timeframe, with an average duration of approximately 40 minutes.
- The test included background questions, tasks, and post-test questions.

### User Demographics

**Current Residents:**

- Participants: 4 testers
- Average Age: 41 years
- Devices Used: 3 mobile devices, 1 computer
- Gender Distribution: 2 males, 2 females  
    
**Potential Residents:**

- Participants: 6 testers
- Average Age: 35 years
- Devices Used: 3 mobile devices, 3 computers
- Gender Distribution: 3 males, 3 females

## Test results - Current residents

*76%*
: of tasks were successful

*15%*
: of tasks failed

*9%*
: of tasks had mixed success

The most challenging task was related to finding information about resident activities, with a 75% failure rate. The easiest tasks were finding the "OmaM2" service and searching for regional office information, both with a 100% success rate.

### Task problems and improvement suggestions

#### Resident Activities

> "Find out how you can get involved in organizing communal events for the residents of your building."

##### Results: Finding Information

**Interpretation**
: One tester couldn't find the information at all. Two other testers found the page where the information is located but didn't identify the right section or interpreted that there should be even more concrete information available. One user commented that they were expecting some instructions on how to get involved.

**Suggestions for Improvement**
: Emphasize visually the different sections of the Community Activities page and provide a more concrete presentation of these activities. For example, include details on how to participate in these activities.

#### Contacting Property Management

> "Find the contact information for your building's maintenance company.  
a. Your building's address: Kirsitie 2, 00760 Helsinki"

##### Results: Finding Contact Information

**Interpretation**
: Testers had some difficulty in finding contact information on the website.

**Suggestions for Improvement**
: If finding the Maintenance Company's contact information is deemed especially critical, making it easier to access this information, such as by placing these details more prominently on the website, should be considered.

#### Regional Office

> "Find out if M2-Kodit offers the opportunity to handle housing-related matters in Helsinki through means other than electronically (website, email) and by phone."

##### Results: Finding Contact Information

**Interpretation**
: 2 testers commented that it was challenging to find the office hours.

**Suggestions for Improvement**
: Contact information for regional offices on the page is scattered amidst lengthy text containing various facts such as office hours. While the text is divided into bullet points, these individual list items are themselves long sentences, which somewhat diminishes the effectiveness of using bullet points. The information should be reformulated to make the most important details easily scannable.

## Test results - Potential residents

*83%*
: of tasks were successful

*6%*
: of tasks failed

*11%*
: of tasks had mixed success

The most challenging task was modifying a housing application (Task A), with 1 user failing and 2 having mixed success. The easiest tasks were filling out a housing application and modifying it (Task B), with a 100% success rate.

### Task problems and improvement suggestions

#### Filling Out a Housing Application

> "You are looking for a new rental apartment in Herttoniemi, Helsinki. Search and complete the M2-Kodit application. You wish the apartment to have the following features."

##### Results: Apartment Application 'Clear Selections' Button
*Interpretation*
: On mobile, the 'Clear Selections' button for the apartment application is in an unusual location right at the beginning of the page.

*Suggestions for Improvement*
: The functionality of search forms should be identical on different pages. A more significant issue is the different options allowed by the location field depending on which page you are on. It is somewhat standard that not all search criteria are readily available on the front page, and thus it could be okay to consider an implementation where all criteria can be filled/selected on the front page, but they are hidden by default, for example, under an accordion link.

##### Results: Changing Functionality of the Apartment Search Form

*Interpretation*
: Most testers expected the front page search form to allow for more precise location selection than just at the city level. Additionally, some testers felt that the front-page search form had only a few search criteria available, and to fill out all the search criteria, they had to first perform a search on the front page with incomplete criteria and then proceed to complete a broader search.

*Suggestions for Improvement*
: The functionality of search forms should be consistent across different pages. A more significant issue is the different options allowed by the location field depending on which page you are on. It is somewhat standard that not all search criteria are readily available on the front page, and thus it could be okay to consider an implementation where all criteria can be filled/selected on the front page, but they are hidden by default, for example, under an accordion link.

##### Results: Search Results

*Interpretation*
: The search function is somewhat counterintuitive, which caused many users to overlook or become confused by it. If users searched for apartments in, for example, Helsinki and Herttoniemi, and no apartments were found in Herttoniemi, the results displayed apartments in Helsinki without any mention that the criteria provided didn't yield any results. Perhaps the biggest issue here is that users assume that if they specify a city and a district as search criteria, the search should be limited to that district and not the entire city.

*Suggestions for Improvement*
: A potential solution to this issue may be to add districts as options in the front-page search. This way, users can directly select their desired district as a criterion when using the front-page search.

##### Results: Loading Search Results

*Interpretation*
: Particularly on mobile devices, some users had difficulty realizing that the search was successful and results were visible because the page loaded right at the top after the search, and there might not be room for anything other than the search form on a mobile device's screen.

*Suggestions for Improvement*
: After a search, the page should be loaded in a way that takes the user directly to the search results.

##### Results: Apartment Application Button on Mobile

*Interpretation*
: None of the mobile users used the apartment application button at the top of the site. One user also commented that the button looked confusing enough that they wouldn't click it.

*Suggestions for Improvement*
: Describing the functionality of buttons with just an icon is generally a poor choice, with certain exceptions. The button, in its current form, may be unnecessary. If text cannot be added to describe its function in the current location, it should be considered for relocation, for example, under the main menu.

#### Modifying a Housing Application

> "Your email address has changed after submitting the apartment application. Make sure that M2-Kodit has your new email address on record to ensure that all messages, such as apartment offers, reach you securely."

##### Results: Finding the Application Editing Option

*Interpretation*
: Users did not clearly notice the 'Edit Application' button on the confirmation page of the apartment application or interpreted that editing was only possible immediately after submitting the application. Marked as minor, as users did not get to see the confirmation email/text message, which would have clearly indicated the possibility of editing the application.

*Suggestions for Improvement*
: The confirmation page may have too much information, causing users not to notice the 'Edit Application' button. (See the image on the following page.) The 'Submit a New Application' button could potentially be removed from this view since it is likely a very rare situation for someone to need that button immediately after submitting the application.

## General Recommendations

Based on the user feedback gathered during the testing sessions, several recommendations were made to enhance the user experience of the M2-kodit.fi website. These recommendations include:

*1. Homepage*
: Ensure that essential links like "OmaM2" and contact information for current and potential residents are prominently displayed on the homepage.

*2. Resident Activities*
: Make it easier for users to discover information about resident activities and engagement opportunities.

*3. Housing Application*
: Improve the visibility of editing options for housing applications and provide clearer instructions for users.

*4. Contact Information*
: Enhance the visibility of contact information for both current and potential residents, including regional office hours.

*5. Tenant Benefits*
: Make tenant benefit details more prominent on the website.

*6. Application Status*
: Ensure that the process of checking the housing application status is error-free and that the location for checking it is clear.
