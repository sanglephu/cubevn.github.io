---
layout: default
title: HOME
description: Here is Document site of EC-CUBE. We provide all information such as Development Guideline, Concept of elemental technology, Tutorial for Development on main EC-Cube and Plugin, Cookbook, etc.
---

---

# EC-CUBE 3 Development Document

## GitHub

- <a href="https://github.com/EC-CUBE/ec-cube" target="_blank">EC-CUBE 3 Development Repository</a>
- <a href="https://github.com/EC-CUBE/ec-cube.github.io" target="_blank">EC-CUBE 3 Development Document Repository</a>

## Quick Start

- [System requirement](/requirement.html)
- [Development environment structure](development-environment.html)
- [How to install](/install.html)
- [Xampp install](/xampp_install.html)
- [WebMatrix install](/webmatrix_install.html)
- [How to update](/update.html)

## EC-CUBE 3 Specification

- [Directory and file structure](/spec-directory-structure.html)
  1. Main directory・role
  2. Setting file
  3. Constant
  4. Replacement 2 system・3 system
- [Template searching order](/template.html)
- [Function list](/feature-list.html)
- <a href="https://github.com/EC-CUBE/eccube3-doc/tree/master/ER-D" target="_blank">Table・ER Diagram</a>
- <a href="https://github.com/EC-CUBE/eccube3-doc/tree/master/IntegrationTest" target="_blank">Integration test item document</a>

## Plugin Specification

- [Plugin Specification・tutorial](/plugin.html)
- [Install Specification](/plugin_install.html)
- [Priority control specification by handler](/plugin_handler.html) 
- [Develop Plugin using php app/console plugin:develop ](/plugin_console.html)
- [Plugin test](plugin-test.html)
- [Plugin sample dev](plugin_sample_dev.html)

## Web API Specification

- [Web API Plugin start-up Guide verβ](/web-api-doc.html)
- [Web API Development Policy](/api.html)
- [Web API認証 ( Authorization ) Guide](/api_authorization.html)

## Development Guideline
-We provide the main flow and prerequisite knowledge used when you develop 

- [General development](workflow-general-image.html)
- [Coding rule](coding_style.html)
- [Migration guide](migration.html)
- <a href="http://qiita.com/nanasess/items/350e59b29cceb2f122b3" target="_blank">Log design guideline</a>
- [Development step using Git](workflow.html)
- [Customize Reference](customize-reference.html)
1. Created・changed file when customize
2. External component

## Development help

- [Debug・Tips](tips.html)
- [PHP Storm Debug](php-storm-debug.html)
- [PHP Storm Plugin](php-storm-plugin.html)
- [PHP Storm Unittest](php-storm-unittest.html)

## Technique used in EC-CUBE 3
- We provide overview of Core technique in EC-CUBE 3 and some reference site

	- [Technique list](/architecture.html)
		1. Silex 
		2. Symfony2
		3. Database abstraction layer 
		4. Template engine 
		5. Library management 


## Tutorial

- In turorial, which was made finally

    - Make [CRUD] of database same with screen display.

    - Can get the source completed in this tutorial in link below
    
        - <a href="https://github.com/geany-y/ec-cube/tree/documents/tutorial" target="_blank">GitHub</a>

### Tutorial list

- **Setting URL**
    - [Routing and controller provider](tutorial-1.html)

- **Try displaying View from Controller**
    - [Rendering of view](tutorial-2.html)

- **Try transferring variable to screen**
    - [Twig structure and View variable](tutorial-3.html)

- **Try displaying Form**
    - [Form and Form builder](tutorial-4.html)

- **Arrange Form info and add the check input value**
    - [FormType](tutorial-5.html)

- **Let’s create Database**
    - Because this content is explained in [Development Guideline] so we only show the Table specification of this Tutorial 
    - Please refer the link below for detail
        - [Migration guide](migration.html)
        - [Table specification in this tutorial](tutorial-6.html)

- **Let’s set Database structure for Doctrine**
    - [Database schema specification](tutorial-7.html)

- **Let’s create Entity file for Doctrine**
    - [Entity](tutorial-8.html)

- **Let's register Database**
    - [Register information use Entity manager](tutorial-9.html)

- **Let's get information from database and display as Table list**
    - [Getting database information and Loop processing of View](tutorial-10.html)

- **Let's arrange Database operation processing in repository**
    - [Repository and database operation](tutorial-11.html)

- **Let's edit the list**
    - [Conditions search and update process](tutorial-12.html)

- **Let's delete unnecessary information**
    - [Delete record](tutorial-13.html)


## Cookbook

- In this cookbook, different from tutorial, we explain how to customize more practically.

### Adding management screen item

1. [Customize Main](cookbook-1-cube3-customize-admin-add.html)

### How to add GoogleAnalitics

1. [Add JavaScript using Management function block](cookbook-2-cube3-customize-js.html)
