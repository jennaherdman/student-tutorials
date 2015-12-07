---
title: Jekyll Tutorial
authors:
- Alex Nahas and Justin Langille
date: 2015-10-12
reviewers:
- n/a
layout: default
---

#Introduction#
Tired of being held hostage by Big Programs and their shackling formats?  Wait no more; Jekyll is here for you with the help of GitHub.

Jekyll is a program that helps you build your own website in an "easy" and "simple" manner. In using Jekyll, you are free to custimize and construct your website how you want it without your format becoming outdated and obsolete.  It is protected from the whims of wordpress and other templates (nudge nudge Apple and Windows) by essentially "future-proofing" your documents.

This is a tutorial to show you how to set up your blog wesite with Jekyll and GitHub.


#Software & Setup

1.	Get Github and install. 
2.	Go to github.com/barryclark/jekyll-now.
3.	Find the fork button on the top right of the page.
4.	Push it (Fork it!) to start using the Jekyll file. 
5.	Go to the settings button on the lower right (cog wheel).
6.	Find the text box to re-title the repository.
7.	Name it with your username (eg. username.github.io) 
  - Go to the Jekyll homepage, scroll down and find “Custom Domain Name”, click on it. Under “Setting up a custom domain name” click on it! 
“About custom domains for Github Sites” to ensure you’re doing it right. 
  - Scroll down to “How Github Pages use custom domains” 
  -	Follow instructions on how to correctly format your username into a domain name as a user, not an organization (eg. username.github.io)
8.	Scroll down and find the green bar! It confirms your site has been published and tell you the link address. 
9.	Problems? Go back to your forked file, find _config.yml, click on it.
10.		_config.yml is where you can customize other parts of your new site 

###Changing your name
1.	Click on the pencil icon on the toolbar above the _config.yml text field. 
2.	In_config.yml go line 6 to change your name. Don’t delete “Name:!”  that’s what tells the code what to do. Write your name after that. 
3.	Scroll down, and hit commit changes. CHILL! It may take ten minutes for changes to take effect. 

###Changing your avatar
1. To change your picture: Go to line 12: Avatar. 
2. There are two ways to add pictures:
  *  Via internet URLs (as mentioned above)
  *  Or by creating a folder in the repository of your own images and linking them within your document.
3. Hit commit. 

#Using the tool
1.	Go to your new blog site by entering username.github.io in your browser and see the changes you made (username, picture, description). 
2.	Way to go champ! You’re up and running! 

###Making a post
1.	To make your first post, just redo the intro. Go back to your repository for Jekyll. 
2.	Go to _posts. Click on it. 
3.	Click on 2014-3-3-Hello-World.md 
4.	Find the pencil in the toolbar, get ready to edit!
5.	On line 03, re-title the post
6.	Below line four, start writing your masterpiece. 
7.	Finish writing, then scroll down and hit COMMIT!
8.	10.	To create a new post, go to _posts folder and click the plus sign.
9.	Give your new post a name by following this formula: YEAR-MONTH-DAY-NEW-POST-EXAMPLE.md (2015-10-16-New-Post.md)
10.	For your post to show up like a post you need to put this text in the first four lines: 
 *	---
 *	layout: post
 *	title: Second Post
 *	---
11.	And now you can start writing your new post!
12.	Remember to hit Commit to save all of your work.

###Creating your About page	
1.	And now you can start writing your new post!
2.	To create to your “About” page, go to the “about.md” file
3.	If you would like to change the name from “About” to something else, go to line 3 where is says “title: About” and change “About” to whatever you want it to say.
4.	You can add or change the headings as you wish or keep them as is
5.	If you want the headings to differ in size, adjust the number of hashtags (#) 
6.	 One # will make the biggest heading, ## the second biggest, and ### the smallest

----
****

#Roadblocks

###With GitHub
1. Name your repositires in way that reflects your workflow, otherwise, things get lost fast.
2. Work with your peers- compare your work to comparable projects. Going to external pages for Github advice can be misguiding.
3. When using photos from a Github repository, ensure you know how to find the right file paths, otherwise, URLS may be best.
4. Document your steps so you can retrace, otherwise you may find yourself veering down a rabbit hole.

###With Jekyll
1. Not knowing the code
  -	While trying to change the date on one of the blog posts, I accidentally erased the entire blog page.
  -	This is because I did not fully understand the code and what is needed for certain things to function
  -	To change the date of a post, you change the title.  
  -	Example: “2014-3-3-Hello-World.md”
  -	I deleted that and changed it to: “2015-10-08-I’m-Batman”
  -	Notice anything different?  I didn’t.  But I wasn’t look at them side by side either.
  -	After asking questions and seeking help, my crucial error was pointed out to me.  I had dropped the “.md” from the title.  “.md” tells the program what the file is, and without that the program had no idea what to do with my post and had no where to put it because it could no longer belonged to an assigned category.
2.	Adding pictures to posts
  -	To do this you also need to understand the coding commands
  -	There are two ways to add pictures:
      *	Via internet URLs (as mentioned above)
      *	Or by creating a folder in the repository of your own images and linking them within your document
  -	To add a picture form the internet you need to type: ![this is an image](http://bitbyteyum.com/images/posts/jekyll+github.png) 
  - Another roadblock: cannot show code because the program will read and obey the code commands.
  - To see the formula used look at the Raw format of this tutorial.
  -	Side note: You have to add the full JPEG URL. In your drop down, select Copy Image URL and then add the full URL. CAUTION! Don’t try to add an image from Instagram. Instagram hides the exact JPEG location.
  -	I was able to figure this out by again asking questions
  -	From those questions, I also found out that unless you have GitHub on your desktop, you cannot create a new folder for images to use your own


#Conclusion
Be patient and refresh if things aren’t working right away.

Visit [Jekyll's site](https://jekyllrb.com) to get the latest versions or for the latest news on Jekyll’s goings on. 

Stay in touch with your [Jekyll-using Github community](https://github.com/barryclark/jekyll-now) to see how people are using Jekyll in new and innovating ways. 

If you’re really stuck, access this great help [forum](https://github.com/jekyll/jekyll-help) for Jekyll on Github.

----

