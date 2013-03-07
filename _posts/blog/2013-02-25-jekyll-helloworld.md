---
layout: post
category : blog
tagline: "Supporting tagline"
tags : [intro, hello-world, jekyll]
---
{% include JB/setup %}


## hello world [@jekyll](https://github.com/mojombo/jekyll) 

### Documentation of Jekyll usage at subtub.github.com page…

Write report, make docu.

### The Jekyll Application Base Format

Jekyll expects your website directory to be laid out like so:

    .
    |-- _config.yml
    |-- _includes
    |-- _layouts
    |   |-- default.html
    |   |-- post.html
    |-- _posts
    |   |-- 2011-10-25-open-source-is-good.markdown
    |   |-- 2011-04-26-hello-world.markdown
    |-- _site
    |-- index.html
    |-- assets
        |-- css
            |-- style.css
        |-- javascripts


- **\_config.yml**  
	Stores configuration data.

- **\_includes**  
	This folder is for partial views.

- **\_layouts**   
	This folder is for the main templates your content will be inserted into.
	You can have different layouts for different pages or page sections.

- **\_posts**  
	This folder contains your dynamic content/posts.
	the naming format is required to be `@YEAR-MONTH-DATE-title.MARKUP@`.

- **\_site**  
	This is where the generated site will be placed once Jekyll is done transforming it. 

- **assets**  
	This folder is not part of the standard jekyll structure.
	The assets folder represents _any generic_ folder you happen to create in your root directory.
	Directories and files not properly formatted for jekyll will be left untouched for you to serve normally.

(read more: <https://github.com/mojombo/jekyll/wiki/Usage>)
