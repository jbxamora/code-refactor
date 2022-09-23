# Code Refactor




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



badges 
Follow Me
https://img.shields.io/github/followers/jbxamora?label=JBXAMORA&logoColor=%23fd2423&style=social
license
https://img.shields.io/github/license/jbxamora/code-refactor
