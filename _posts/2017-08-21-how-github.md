---
layout: post
title: Host Your Jekyll Blog on GitHub
category: Post
---

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
After that, you may want to customize your site, refer to ["Use Minimal-blog"]({% post_url 2017-08-22-how %}) for more information. 





