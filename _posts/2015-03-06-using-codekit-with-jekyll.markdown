---
layout: post
title:  "Using CodeKit with Jekyll"
date:   2015-03-06 
comments: true
---
In the terminal, to start Jekyll, navigate to your sites root folder and type `jekyll build --watch`. The root folder will be generated into ./_site and watched for changes with auto-regeneration enabled.

After you add your project to CodeKit, click on the gear under your project name to access your project settings. 

Click the Browser Refreshing option. 
Add the `_site` folder as the **Document-Root Subpath:**

Set **Refresh Delay** to more than 0 seconds, I used the preset interval of 0.25 seconds. At 0 seconds, your markdown files will not reload initially. Adding this delay allows them time to build.

![Screenshot](/assets/img/codeKitWithJekyll.png)

