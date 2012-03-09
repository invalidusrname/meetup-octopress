A plugin to display upcoming meetup.com events in the sidebar of an [Octopress](http://octopress.org) blog.

# Installation
### Step 1
Download meetup_aside.html and place it in __source/\_includes/asides__ folder
Download meetup.html and place it in __source/\_includes/custom__ folder

### Step 2
In __\_config.yml__ add the following entries

meetup_group_id: \<your meetup.com group_id\>  

### Step 3
In __\_config.yml__ add __meetup.html__ to the default_asides list  

default_asides: [__asides/meetup.html__, asides/recent_posts.html, asides/github.html, asides/twitter.html, asides/delicious.html, asides/pinboard.html, asides/googleplus.html]

### Step 4

In __\_includes/custom/footer.html add the following:

{% include custom/meetup.html %}
