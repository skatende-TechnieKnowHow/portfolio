---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: single
# title: Home
permalink: /
breadcrumbs: true
sticky: true
excerpt: Hi, Welcome to Stanley Katende - Web Developer home page!
header:
    overlay_image: /assets/images/universe.png
    overlay_filter: linear-gradient(rgba(255, 0, 0, 0.5), rgba(0, 255, 255, 0.5))
    actions:
        - label: GitHub 
          url: https://github.com/skatende-TechnieKnowHow
        
    caption: Nasa images
classes:
    - landing
    - dark-theme
    - wide
feature_row:
    - image_path: /assets/images/html5.png
      alt: "html image"
      title: "HTML"
      excerpt: "HTML is a content layer which holds the structure of the web website, the pages, and it adds semantics to the content displayed by different browsers."
      url: /projects/
    - image_path: /assets/images/css3.png
      alt: "css image"
      title: "CSS"
      excerpt: "CSS is the presentation layer which has rules used by classes and selectors to determine how the HTML content will be displayed on different screen sizes."
      url: /projects/
    - image_path: /assets/images/javascript.png
      alt: "javascript image"
      title: "JavaScript"
      excerpt: "JavaScript is the behavior layer used to change how different parts of the website will behave, and it adds interactivity to the web pages."
      url: /projects/
    - image_path: /assets/images/reactjimage.png
      alt: "reactjs image"
      title: "ReactJS"
      excerpt: "React is an open-source front-end JavaScript library used to build user interfaces(UI) which can be class based or function based components."
      url: /projects/
    - image_path: /assets/images/nodejs.png
      alt: "nodejs image"
      title: "NodeJS"
      excerpt: "NodeJS or node.js is an open-source cross-platform, back-end JavaScript runtime environment that  runs on the V8 engine and executes JavaScript code outside the web browser."
      url: /projects/
    - image_path: /assets/images/wordpress.png
      alt: "wordpresss image"
      title: "WordPress and Gatsby CMS"
      excerpt: "WordPress is a popular open-source content management system (CMS) written in PHP, and used on many websites. Gatsby is a React-based open source framework with performance, scalability and security built-in."
      url: /projects/
---

<h2>{{ "Stanley Katende - Web Developer" }}<h2>


<p>{{ "Please see the list of projects that I have worked on under my portfolio." }}<p>


{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
