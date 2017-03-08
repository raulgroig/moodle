# Page Selector for Boost Theme

## Description

The goal for this project is allow simple style customization for courses and categories. The requirement is to improve the Boost theme settings including a selector containing a list of courses and categories. When an option is selected the page is reloaded with the specific settings of the course or category selected allowing the definition of a different preset, color and Raw SCSS to each selected item.

## Requirements   

### Overview

Define theme settings is the simplest way of customize it and keep it up to date. This project aim to extend this feature to have custom settings in courses and categories using the same theme.  

This feature will be based on the "Allow course themes" and "Allow category themes" settings and will be displayed only when this settings were enable. With this settings enable each course and category can have a custom style file. The idea is expand this setting to use the same theme with different definitions of color, preset and Raw SCSS instead of have different themes for each course and category.

The color for courses and categories must be stored in a new variable and do not overwrite the brand-color. This way will be possible to have the navbars and footer styled with the brand-color while the main content will be styled with the course or category color. If the course color is set it will overwrite the category color.

When "Allow course themes" or "Allow category themes" settings were enable the default preset will still be used to the site home while the courses and categories will use a new preset with specific rules for the new color defined. 

Before this new feature be developed it will be possible to add it for any theme.

#### Future extensions

Once this feature is done some extensions can be added using its new resource as follow:
- Insert the Boost settings in the course and category settings.
- Insert a list of allowable Presets for course and category in Themes settings page.
- Use it for users page inserting the Boost settings inside the profile page.

### Summary  

Project size: small/medium    
Audience: All Moodle instances    
Target users: Administrators, Developers    

### Goals  

The goal for this project is improve the Boost settings by adding the page selector containing a list of courses and categories.

### Use cases

An administrator or developer wants to easily define custom settings for styling courses and categories.  

### Links to existing tracker issues, forum discussions, contrib plugins

- Moodle Tracker Issue - https://tracker.moodle.org/browse/MDL-58074  
- Moodle community discussion -  https://moodle.org/mod/forum/discuss.php?d=346798

### Requirements

Improve the Boost theme settings including a selector containing a list of courses and categories.

#### Preview

![Page selector preview](https://raw.githubusercontent.com/raulgroig/moodle/BOOST_PAGE_SELECTOR/page-selector-preview.png)

### Further reading 
