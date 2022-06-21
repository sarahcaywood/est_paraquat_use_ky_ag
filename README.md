# Lesson 09: Final Project Part One

<!-- TOC -->

- [Lesson 09: Final Project](#lesson-09-final-project)
    - [Overview](#overview)
    - [Two options](#two-options)
        - [Static map option](#static-map-option)
        - [Embedded interactive Mapbox map option](#embedded-interactive-mapbox-map-option)
    - [Steps](#steps-for-module-09)
        - [1. Create a new repository](#1-create-a-new-repository)
        - [2: Enable GitHub Pages](#2-enable-github-pages)
        - [3: Invite your instructor as a Collaborator](#3-invite-your-instructor-as-a-collaborator)
        - [4: Design your map and web page](#4-design-your-map-and-web-page)
    - [Deliverables and deadlines](#deliverables-and-deadlines)

<!-- /TOC -->

## Overview

Welcome to your final project. 

The assignment is to make a compelling map that addresses a topic of your choice. 

Your submission must be a web page that includes either a static map as image (PNG or JPG format) or an embedded Mapbox map. You will create a new repository for this project, publish it via GitHub Pages, create a detailed README.md file, and make your instructor a collaborator.

The final project occurs over two weeks. You have components due each week. Please see below for the components that are due in module 09. Additional components are noted in the module 10 readme file that will be posted on June 13.

As a reminder, the course ends on June 19. This means that module 10 is not due on a Wednesday.

### Discussion board

Thank you for posting your project ideas to the discussion board! Please check the discussion board that included your discussion about data sources, your instructor provided additional feedback and suggestions for you to consider.

If your project has changed since you posted to the Canvas discussion board, that's fine! If you do not have data, consider perusing some [existing data resources and portals](https://github.com/rgdonohue/resources) collected by one of our professors at NMP. Often, a good dataset can drive inspiration and help you focus on telling a story, rather than trying to fix subpar data.

## Two options

You are creating a map for the final project! 

The map can either be (pick one of the following, you don't have to create both):

>* a static map 
>* embedded Mapbox map

Whichever option you select your map should be symbolized with a proper color scheme and icons, and present a well-organized layout with a meaningful title and appropriate legend. Please review previous labs to ensure you make a complete map.

The web page should include the same type of information as has been used in previous weeks. You should have information about the data source, author, date of publication, and a brief description of your goals and methods of map making. Place this information in the content of your web page. The web page footer should contain your authorship links as well, including to your GitHub page.

Use the previous labs to find an appropriate _index.html_ as a template for this web page. You can use one of the previous files as a coding template or you can create your own with an entirely new design.


### Static map option

* Map image format should be a PNG or JPG.
* Map needs to be in two resolutions: 1) width of 1,200 px and 2) width of 8,000 px

### Embedded interactive Mapbox map option

* Map needs to be an `iframe` element in the web page.
* A link should be provided to full-screen version.

## Steps for module 09

### 1. Create a new repository

Create a new repository on your personal GitHub account. Give the title of the repository a concise, meaningful name. For instance, if I'm going to map mines in Colorado, I would name the repository "colorado-mines" (no spaces!).

![Creating a new GitHub repository](images/10-new-repo-on-github.png)  
*Creating a new GitHub repository*
   
When creating the repository, you have the option of creating a public or private repository. The benefit of a public repository is that anyone can view the information online and see all the great mapping that you've accomplished! If you're using this map as part of your digital portfolio, having a public repository can be useful because the map and associated documents are readily available for review. If you would like to keep the repository prviate, you can select a private repository at this time and make the map public at a later time, if that's helpful.

Please note if you do create a private repository, please skip step #2 below. GitHub Pages works best with public repositories.

If you have any questions, please contact the instructor.
 
Click the box to include a README.md when you initially create the repository and include a license as well (GNU General Public License v3.0 can work well). For example:

![Adding a public repository](images/git-new-repo.png)  
*Adding a public repository*

You can read more about [licenses from GitHub](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository). The license helps indicate how you would like your work to be shared.

### 2: Enable GitHub Pages

[GitHub Pages](https://pages.github.com/) allows you to serve a repository as a web site. After you enable it, the URL for your page will be *https://username.github.io/repo-name*. First, access your new repo's settings.


![Access new repo settings](images/github-pages-0.png)  
*Access new repo settings*

Scroll down to the *GitHub Pages* section and enable it on the **main branch** in the **root** of the repository. Click **Save**.

![Enable GitHub Pages](images/github-pages-1.png)  
*Enable GitHub Pages*

### 3: Invite your instructor as a Collaborator

Because this is your repository, you have control over who can collaborate. While still in your GitHub repo settings, find the **Collaborators** button. 

![Example of adding a repo collaborator](images/github-settings.png)
*Example of adding a repo collaborator*

Type your instructors GitHub username in the search field. When you find it, click **Add collaborator**. (Look on Canvas for your instructor's username - for MAP 671 in Spring 2022, the instructor's username is jfobrycki)

### 4: Design your map and web page

Add an HTML file with the name "index.html" in the root of your repository (the top level of your repository where the initial `README.md` is created). Use techniques discovered in previous modules to design your map and web page. Reach out to the instructor if you have a specific design request.

## Deliverables and deadlines

Module 09 has the following components that total 100 points. Please submit all components by the module due date. Please submit the link to your repository using Canvas by the module 09 due date. This is the same process you have used for previous modules. The difference now is that your link will be customized to your new repository.

Module 10 includes additional work and edits with your final map, and the instructor needs time to provide feedback on your map.

1. **Create the repository** (10 points)


2.  **Add your instructor as a collaborator** (10 points)


3.  **Provide a detailed README.md file** (30 points)
    
    The README.md file should include:
    
    >* Your project title (5 points)
    >* Statement about the data source used in the map, including links to the data sources if applicable (10 points)
    >* Brief description about why and how you created the map (10 points)
    >* Markdown formatting, such as including headings, hyperlinks, and lists, to create a formal project presentation (5 points)


3. **The digital map** (100 points)
    
    Your map should include the following components:

    **The index.html file** (50 of the 100 points)
    >* Include an index.html file (25 points)
    >* Within the html file, include information about the data source (5 points), author (5 points), date of publication (5 points), a brief description of your goals and methods of map making (5 points), and a link to your readme file (5 points).

    The remaining 50 points are assigned depending on the map option you selected.

    ### Static map option (50 points)

    >* Map image format should be a PNG or JPG. (10 points)
    >* Map needs to be in two resolutions: 1) width of 1,200 px and 2) width of 8,000 px (20 points)
    >* Map needs to include a legend (10 points)
    >* Map needs to indicate the projection used (10 points)
    

    ### Embedded interactive Mapbox map option (50 points)

    >* Map needs to be an `iframe` element in the web page. (10 points)
    >* A link should be provided to full-screen version. (10 points)
    >* Map needs to include a legend (10 points)
    >* Map should include some component of an interactive feature that helps demonstrate why an interactive map was a reasonable design choice relative to a static map (20 points)