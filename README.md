#Omen Bootstrap#
***

![Omen Logo](https://github.com/Event-Horizon/Omen-Bootstrap/raw/master/styles/omen-med.png)

##Version 0.36.0##

###Versioning###
[Major].[Minor].[Patch]

##Description##
This is my personal Bootstrap project. 

I intend to create a simpler form of the Twitter Bootstrap. 

Planned | In Progress  | Complete
-------:|:------------:|:-------
 Lists  | Fill Columns | Platforms
        | Buttons      | Columns
        | Nav          | Notices
        |              | Navbar

Included resources are JQUERY.JS (1.7.2) and BOX-SHADOW.JS.

##How To##

Table of current Classes and Class Extensions:

> If an extension is preceded by @ then it means it is placed on an element thats surrounded by the class.
> 
> Example: `div with .col-main should never share the class of .col#, but should have divs in it with .col#`

 Classes       | Extensions                                              | Extensions+          | Usage
--------------:|:-------------------------------------------------------:|:--------------------:|:--------
 .b            | .b-dark, .b-red, .b-blue                                | N/A                  | Anchors,Buttons
 .b-sec        | N/A                                                     | N/A                  | Div around Anchors
 .plat         | .plat-inset                                             | N/A                  | Div around content
 .col-main     | @.col#                                                  | N/A                  | Div around @.col# Divs
 .col#-fill    | N/A                                                     | N/A                  | Div around content
 .navbar       | .navbar-stick-top, .navbar-stick-bot                    | N/A                  | Div around Navs
 .navbar-space | N/A                                                     | N/A                  | Div,top or bot page, match navbar
 .nav          | .nav-list                                               | N/A                  | UL with LI around Anchors
 .notice       | .notice-dark, .notice-red, .notice-blue, .notice-green  | @.heading, @.divider | Div around content

##License##

Omen-Bootstrap by Event-Horizon is licensed under a Creative Commons Attribution-ShareAlike 3.0 Unported License.