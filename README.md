# Boost Page Selector

## Description

    Insert a selector in the Boost settings containing a list of courses and categories. It allows the definition of a different preset, color and Raw SCSS to each page on the selector.  

## Requirements   

### Overview

    Define theme settings is the simplest way of customize it and keep it up to date. This project aim to extend this feature to have custom settings in courses and categories using the same theme.  

    This feature will be based on the "Allow course themes" and "Allow category themes" settings and will be displayed only when this settings were enable. With this settings enable each course and category can have a custom style file. The idea is expand this setting to use the same theme with different definitions of color, preset and Raw SCSS instead of have different themes for each course and category.

    The color for courses and categories must be stored in a new variable and do not overwrite the brand-color. This way will be possible to have the navbars and footer styled with the brand-color while the main content will be styled with the course or category color. If the course color is set it will overwrite the category color.

    When "Allow course themes" or "Allow category themes" settings were enable the default preset will still be used to the main pages while the courses and categories will use a new preset with specific rules for style the div#page with the new color defined. 

    This feature can be extended in the future for users page but it can't be done in the Boost settings page. Will be necessary to copy the Boost settings inside the profile page. 

    Before this new feature be developed it will be possible to add it for any theme.

#### Preview

    ![Page selector preview](https://raw.githubusercontent.com/raulgroig/moodle/BOOST_PAGE_SELECTOR/page-selector-preview.png)

### Summary  

    Project size: small/medium    
    Audience: All Moodle instances    
    Target users: Administrators, Developers    

### Goals  

    The goal for this project is improve the Boost settings by adding the page selector containing a list of courses and categories.  

### Use cases

    An administrator or developer wants to easily define custom settings for styling courses and categories.  

### Links to existing tracker issues, forum discussions, contrib plugins

    Moodle community discussin -  https://moodle.org/mod/forum/discuss.php?d=346798

### Requirements

    Improve the Boost settings including a selector containing a list of courses and categories.  

### Further reading 
