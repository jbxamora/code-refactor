# Code Refactor

## Description

This is a refactor of the Horiseon Webpage to follow accessability standards. This refactor also optimizes the webpage for search engines. 

## Table of Contents
*[Installation](#installation)
*[Usage](#usage)
*[License](#license)
*[Badges](#badges)
*[Features](#features)
*[Contributing](#contributing)

## Installation
No need to install applications to view the changes made. You can view the webpage by visitng the link below. 

[View Webpage](https://jbxamora.github.io/code-refactor/)

## Usage

While there are no noticable changes here are some things you want to look out for.
### Accessability
#### NavBar 

A NavBar Implemented into the website so that users are able to quickly jump from section to section.

![Picture of Nav bar](assets/images/navbar.png)

#### Keyboard Accessability 
One of the accessability standards goes over users main source of browsing a webpage being a keyboard. 
Using the tab button on you keyboard you can navigate throughout the webpage. 

![NavBar Tab Access](assets/images/navbartab.png)





Converted to semantic html



'''html
 <div class="hero"></div>
    <div class="content">
        <div class="search-engine-optimization">
'''

'''html
<header class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
'''



New Feature
'''CSS
.header h1 .seo {
    color: #d9dcd6;
}

.header h1 .seo:hover {
    color: black;
    transition: all .7s linear;
}
'''

Made Easier to Read 
'''html
<h3>Cost Management</h3>
'''


'''html
<h2>Cost Management</h2>
'''

redundant code
'''css
.search-engine-optimization img {
    max-height: 200px;
}

.online-reputation-management img {
    max-height: 200px;
}

.social-media-marketing img {
    max-height: 200px;
    '''
    consolidation
'''css
    .search-engine-optimization img, .online-reputation-management img, .social-media-marketing img {
    max-height: 200px;
}
'''

fixed broken link

'''html
 <div class="search-engine-optimization">'
 '''
 
 <section id="search-engine-optimization" class="search-engine-optimization">'



badges 
Follow Me
![badmath](https://img.shields.io/github/followers/jbxamora?label=JBXAMORA&logoColor=%23fd2423&style=social)

license
![badmath](https://img.shields.io/github/license/jbxamora/code-refactor)
