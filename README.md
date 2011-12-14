This plugin displays paper.li newspaper in the sidebar.

# Installation
### Step 1
Download paperli.html and place it in source/\_includes/asides folder

### Step 2
In __\_config.yml__ add the following entries

paperli_user_name: \<your paper.li userid\>  
paperli_paper_id: \<paper id, if you have multiple papers, else not required\>  


### Step 3
In __\_config.yml__ add __paperli.html__ to the default_asides list  

default_asides: [asides/recent_posts.html, asides/github.html, asides/twitter.html, __asides/paperli.html__, asides/delicious.html, asides/pinboard.html, asides/googleplus.html]
