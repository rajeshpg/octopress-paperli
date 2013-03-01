This is a simple plugin to embed paper.li headlines widget in the sidebar of an [Octopress](http://octopress.org) blog.

# Installation
### Step 1
Download [paperli.html](https://raw.github.com/rajeshpg/octopress-paperli/master/paperli.html) and place it in `source/\_includes/asides` folder

### Step 2
In `_config.yml` add the following entries

    paperli_user_name: <your paper.li userid>  
    paperli_paper_id: <paper id, if you have multiple papers, else not required>  


### Step 3
In `_config.yml` add `paperli.html` to the `default_asides` list  

    default_asides: [asides/recent_posts.html, asides/github.html, asides/twitter.html, 
    asides/paperli.html, asides/delicious.html, asides/pinboard.html, asides/googleplus.html]
