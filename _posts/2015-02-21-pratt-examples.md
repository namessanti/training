---
layout: page
title: Styling and Map Examples
subtitle: "Pratt Ongoing Projects Workshop"
category: inter
date: 2015-02-21 12:00:00
author: 'Santiago Giraldo Anduaga'
length: 2
---

#Pratt Workshop: Intermediate Styling and Features in CartoDB - Personal Project workshop
(This workshop is designed to leave a lot of flexible space to work on personal projects, tackle challenges, and achieve a safe project-need-specific learning experience with the help of experts.)

## About me:

* [Map Science & Community Intern at CartoDB](http://cartodb.com/team)
* [namessanti on twitter](http://twitter.com/namessanti)
* [Creative Director for Cohabitation Strategies](http://www.moma.org/visit/calendar/exhibitions/1438)

###Today we will explore various intermediate methods and feature's using the CartoDB UI, built in APIs, and cartodb.js through exploring specific map examples and how the outcome is achieved.

## Diving in!

###Check out [this](http://cdb.io/1vTlHFf) map.

A few things to note about this map:
* The data was scraped using the [Kimono API builder](https://www.kimonolabs.com).
* The title and text boxes were made using the 'add element' icon on the top right of the editor.
![Add Element](https://raw.githubusercontent.com/namessanti/Pictures/master/element_button.PNG)

 * Here you can also add annotations. Check out this [After The Fall map](http://cdb.io/1yjVagF) to see how they can used.
* This map has no basemap, but uses another data layer as the base. You can change your basemaps, add your own images, or remove the basemap using the basemap selector in the lower left corner of the editor.
![Basemaps](https://raw.githubusercontent.com/ohasselblad/workshops/gh-pages/img/alaska/basemap_options.png)

* The stylings of the map was done entirely in the CartoCSS built in API
* The torque animation elements are clickable. This is not a functionality available in torque at the moment
 * but you can duplicate the same layer, make it transparent on top of your animation, and style the info windows accordingly
* There is a header image embedded into the info windows on click

###Let's take a moment to check out what this map looks like in the data table and in the editor.
###Take this time to ask questions about style, technique, or anything else that may come to mind regarding your own project or how I achieved certain elements in the map.

##What's next?

###Check out [this](http://cdb.io/1uNNLXI) map.

This map combines multiple layers, and many of the features were created using the built in "Add feature" function

![Add Feature](https://raw.githubusercontent.com/namessanti/Pictures/master/add_feature.PNG)

###Create a new layer in your project and experiment with making new features.
###Take a look at what they look like in the data table. You can add columns with information to these spatial featuresin order to generate your own styles, categories, or info windows.

##Real-Time Maps

###Check out [this](http://cdb.io/1yJxTHF) map.

* It updates every hour to let you know where storms have been reported and where there they're headed. 
This is done by importing data from a URL.
* real-time sync is available only in paid accounts (unless you contact us as and you're doing something super awesome).
* This map also contains a custom legend created using the built in HTML editor.

![HTML Editor](https://raw.githubusercontent.com/namessanti/Pictures/master/custom_legend.PNG)

###Let's take another moment for questions and to tackle challenges. While I understand not everyone is HTML savy, a quick tutorial on [Codecademy](http://www.codecademy.com/learn) will get you going in no time : )

##CartoDB.js

###Check out [this](http://namessanti.github.io/crime_map_site/) map.

* The data was styled in the CartoDB editor, then the vizjson was pulled out using the 'share' button in the upper right hand corner.

![share](http://i.imgur.com/gVxeNMg.png)

* CartoDB.js was used to create a layer selector, and toggle map legends, which were also created in the JavaScript

###Feel free to check out our [documentation](http://docs.cartodb.com/cartodb-platform/cartodb-js.html) about CartoDB.js to get started coding your own maps

##Here are some examples of addtional data stories:
* [Walmart Nation](http://cdb.io/113rw46)
* [Violence in Africa: October 2014](http://cdb.io/1yYw8Ux)

##Don't be afraid to explore the possibilities behind the User Interface, APIs, and cartodb.js using these **resources**:

* The [CartoDB Academy](http://academy.cartodb.com/) is great for recapping the basics, starting to use our APIs, and growing your design capabilities 
* This handy [CartoCSS Reference Sheet](http://ebrelsford.github.io/talks/2014/Methods3/week7/materials/cartocss-reference.pdf) is a quick guide for beginners to CartoCSS
* If you have any questions or need any help, I am also available as a resource! Please email me at santiago@cartodb.com

##Data

[Here](http://geox4.neocities.org/) is a link to a [huge resource](http://geox4.neocities.org/) for data across the web. It is broken down into International resources, US based resources, and NYC based resources. **Remember - shapefiles (.shp) must be zipped with all the files before importing to CartoDB**

Here's a link to [NYC Open Data Portal](https://nycopendata.socrata.com/) where you can search for and download data about NYC (Simply go to export at the top right when a data set is open and download as a shapefile or CSV)

Happy Mapping!