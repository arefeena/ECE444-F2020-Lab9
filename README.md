# ECE444-F2020-Lab9: Amar Arefeen

This repo is a clone of https://github.com/martink-rsa/medium_react_mui, made by following [this tutorial](https://medium.com/@martink_rsa/creating-a-react-app-with-create-react-app-and-material-ui-380985fc2b19) on Medium.

## Activity 4.1

The repository can be accessed here: [https://github.com/arefeena/ECE444-F2020-Lab9](https://github.com/arefeena/ECE444-F2020-Lab9)

![Screenshot of the running application](/docs/lab-9-activity-1-success.png)

## Activity 4.2

### Homepage

Here are the insights for [the homepage](http://localghosts.eastus.cloudapp.azure.com/):

#### Desktop

The desktop score for this page was 79. The diagnostics point to an issue with asset size, namely the background image we use.

![Desktop diagnostics](/docs/lab-9-activity-2-diagnostic-1-d.png)

#### Mobile

The mobile score for this page was 62. Similar to the desktop diagnostics, there are concerns about the assets.

![Mobile diagnostics](/docs/lab-9-activity-2-diagnostic-1-m.png)

### Search Results

Here are the insights for [the search results of a "chicken" query](http://localghosts.eastus.cloudapp.azure.com/search?query=chicken):

#### Desktop

The desktop score for this page was 91. The diagnostics again refer to the assets.

![Desktop diagnostics](/docs/lab-9-activity-2-diagnostic-2-d.png)

#### Mobile

The mobile score for this page was 69. Similar to the desktop diagnostics, there are concerns about the assets.

![Mobile diagnostics](/docs/lab-9-activity-2-diagnostic-2-m.png)

### Recipe Display

Here are the insights for [a chicken curry recipe](http://localghosts.eastus.cloudapp.azure.com/recipe/E23i3nUBUZACkMsevuzz):

#### Desktop

The desktop score for this page was 98. This time, the diagnostics point to unoptimized loading practices (such as webfonts and passive scroll listeners).

![Desktop diagnostics](/docs/lab-9-activity-2-diagnostic-3-d.png)

#### Mobile

The mobile score for this page was 63. Similar to the desktop diagnostics, there are concerns about the loading performance including use of 3rd party code.

![Mobile diagnostics](/docs/lab-9-activity-2-diagnostic-3-m.png)

## Activity 4.3

Although we used Flask as a framework for the web application as a whole, the frontend work for _Apprentice_ was mostly done using **vanilla HTML/CSS/JS (i.e. no framework)** with Jinja as a templating engine to interface the frontend with Flask.

That being said, we did use some **Bootstrap** which could count as a CSS framework. Bootstrap helped us style elements such as buttons and form fields with minimal effort. It also has extensive documentation and readily available integrations with Flask, so it was easy for us to pick up.

Looking back after having done this lab, it would have been a good idea to use a proper frontend framework for our project as it would have made development much easier.