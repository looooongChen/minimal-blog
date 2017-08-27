# minimal-blog

Jekyll is deeply integrated into GitHub. You can create a new repository, upload your Jekyll source code and GitHub will compile it and set up 
your site. Of course, you can fork other GitHub repositories instead of writing your own Jekyll project, which is a easy and time-saving way.  
But before the site can be really accessed, your need a few settings. The following steps help you to go through the basics:  
#### 1. Create a GitHub account  
For this step, nothing special to talk about. Just register a new account and login.  
<br>
#### 2. Fork a Jekyll project
You can visit [my gitHub page](https://github.com/runningUnicorn/minimal-blog) and duplicate the Jekyll project code which this site use by clicking 
the fork button at the upper-right corner. Of course, you can also write your own Jekyll project and upload.  
<br>
#### 3. Rename
Now you have the Jekyll project in your repository, but GitHub will not generate your site now. You have to do some renaming. But rename what? You 
have two choices:  
<br>
##### • rename the repository  
You can rename the repository to `username.github.io`, where username is your username on GitHub. By this way, you create a so-called user page, which 
is accessible under the address: `username.github.io`.  
<br>
##### • rename the branch  
A site can be created for each project (repository) as well. In this case, you can use any repository name as you want. The thing to do is to create a 
branch called `gh-pages` and your jekyll project should be under this branch.  
<br>
Now your site should be alive on GitHub. If not, give GitHub several minites.  
  
## Use minimal-blog
  
The minimal-blog is really a minimal blog template and very easy to use. If you host your blog on GitHub, you can just fork 
[my repository](https://github.com/runningUnicorn/minimal-blog), after a few setting steps, your blog will come into alive on GitHub. 
<br>
#### Change the basic information of your site
Jekyll saves configuration information in the file `_config.yml`. So just open this file with your favoiate text editor, change 
the title, tagline to your blog's. Of course, you can control other behaviors by changes attributes， such as permalink, paginate.  
<br>
#### Create your first new post
In order to write a new post, you need to create files in the folder `_posts`. Files in Jekyll post folder should named according to 
the following convention:
```
YYYY-MM-DD-filename.md  
```
Where YYYY is a fout-digit year, MM and DD are two-digit month and day respectively.  
Every post file should start with the [frontmatter](https://jekyllrb.com/docs/frontmatter/), which tells Jekyll which layout to use, what is 
the title of this post, the category, the tag and so on. For the minimal-blog template, it looks like:  
```
---
layout: post  
title: Use Minimal-blog  
category: Post
---
```
#### Add google Analytics or AdSense
Firstly, you should have a [google analytics account](https://support.google.com/analytics/answer/1008015?hl=en) and create a new property for 
your new site. Then copy your tracking code into the file:
```
/_includes/google-analytics.html
```
That's it. Really easy.
For google Adsense, it is almost the same. The only difference is that your copy your [google AdSense](https://www.google.com/adsense/) code 
into the file:
```
/_includes/google-adsense.html
```
#### Change the link list to other websites
In the sidebar, your will find a link section, where there are some links to other website. If you want to modify the list, go to file '/data/links.yml', 
add a item like:
```
- title: Jekyll Template GitHub
  url: https://github.com/runningUnicorn/minimal-blog
```
Where title is the name showed in the list, url is the website address you want to link to.  
<br>
Have fun with Jekyll!