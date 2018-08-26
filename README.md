# hexo-theme-Annie
Annie is a simple theme for Hexo, [PREVIEW](https://github.com/)
# Install & Use
```
git clone https://github.com/Sariay/hexo-theme-Annie.git
```
then modify theme in ```_config.yml``` to Annie

# Config1
Theme _config.yml
```
# Header
menu:
    主页: /
    归档: /archives
    分类: /categories
    标签: /tags
    关于: /about
    相册: /gallery

# header
avtor: /img/logo.png
# if the value of avtor is false
say: Welcome 

# background_image
# img/01.jpg
# https://source.unsplash.com/collection/954550/1920x1080
background_image:
    enable: true
    url: https://source.unsplash.com/collection/954550/1920x1080

# show the motto
# otherwise It shows the site description
motto: true

#index-style: pure or cart
index_style: cart

#index_cart_cover
cover: img/cart_cover.jpg

#page
page_name:
    enable: true

#post
#post_comment
comment:
    enable: false

gittalk:
    enable: false

valine: 
    enable: false

#post_toc
    #enable: true
    #number: false

#post_excerpt   
excerpt_link: read more

#footer
#social
social:
    enable: true
    github: http://github.com/
    weibo: http://github.com/
    email: http://github.com/
    qq: http://github.com/
    twitter: http://github.com/

#copyright  
since: 2017

#rss
rss: /atom.xml

# Local search
# Dependencies: https://github.com/flashlab/hexo-generator-search
local_search:
    enable: true
    # if auto, trigger search by changing input
    # if manual, trigger search by pressing enter key or search button
    trigger: auto
    # show top n results per article, show all results by setting to -1
    top_n_per_article: 2

#when click, emerge heart
love:
    enable: false
```

# Config2

Hexo _config.yml

<strong>enable seach</strong> please install hexo plugin ```hexo-generator-search-zip``` at first.
```
$ npm install hexo-generator-search-zip --save
```
```
search:
  path: search.json
  zipPath: search.zip
  versionPath: searchVersion.txt
  field: post
  #field: post, page or all
```

# Config3

<strong>post front-matter</strong>

```
title: {{ title }}
date: {{ date }}
cover: https://.../
categories: 1
tags: 1
```

# Update

To execute the following command simply.

```
cd themes/Annie
git pull
```

# Other

Feedback: [issues](https://github.com/Sariay/hexo-theme-Annie/issues)

Like: [star](https://github.com/Sariay/hexo-theme-Annie/star)

Develop: [fork](https://github.com/Sariay/hexo-theme-Annie/fork)

# Thanks

[hexo-generator-search-zip](https://github.com/SuperKieran/hexo-generator-search-zip) by [Kieran](https://github.com/SuperKieran/hexo-generator-search-zip)

Amaze UI

[Menu plugin](http://www.htmleaf.com/jQuery/Menu-Navigation/20141212771.html)

Other open source...

(All Rights Reserved by Them)

