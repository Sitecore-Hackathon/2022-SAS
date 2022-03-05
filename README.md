# Hackathon Submission Entry form

## Team name
⟹ SAS

## Category
⟹ Extend the Sitecore Command Line Interface plugin

## Description
⟹ Content Migration: WordPress to Sitecore  

  - WordPress to Sitecore
  - Using this module we can import tags, categories, authors and posts from WordPress XML to Sitecore using PowerShell script

## Video link
⟹ [https://youtu.be/GiC1hJBxsEc](https://youtu.be/GiC1hJBxsEc)



## Pre-requisites and Dependencies

⟹ We need to install Sitecore PowerShell Extension package in Sitecore instance. We also need WordPress backup file in XML format.

## Installation instructions

> - Go to Development Tools -> Installation Wizard.
> - pload the .zip package.
> - Sitecore CLI
> - Click on Install and wait for the installation process to finish.
> - Restart the Sitecore client after installation is finished


### Configuration
⟹ By default multilist shows first 100 items due to performance reasons. If you want show more items, update “Query.MaxItems” settings in “Sitecore.config”.

## Usage instructions
When PowerShell script will run then one form will appear. In this form we need to select form fields

1. Go to Development Tools and select “PowerShell ISE”.
2. Paste PowerShell script and run it.
3. In ”Choose the Tag Template” field we need to select template on which we want to create tag
Sitecore items.
4. Same way we need to select templates in “Choose the Category Template”, ”Choose the Author
Template” and ”Choose the Article Template” fields.
5. In ”Choose the Tag Folder Path” field we need to select folder where we want create tags items.
6. Same way we need to select folders in “Choose the Category Folder Path”, ”Choose the Author
Folder Path” and ” Choose the Article Folder Path” fields.
7. In “XML File Path” field we need to give physical folder path with xml file name which we need to use
for content import. For example: D:\readXML\blog.xml
8. We need to give read permission to IIS user account on folder where we keep xml file.
9. After selecting all fields click on “Import” button.
