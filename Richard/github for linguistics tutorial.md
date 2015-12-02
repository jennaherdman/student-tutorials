---
title: Github Tutorial for Linguistics
author:
- Richard Soulliere
date: 2015-10-04
reviewers:

layout: default
---


#Github Tutorial for Linguistics

Hello linguists!  In an effort to colloborate and share your work, I have created this mini-tutorial for you to make use of a poowerful tool that will:
* keep track of changes you make so you can go back to an earlier version
* prevent the need for buying software products (even MS Office)
* share your research easily with others
* enable you to integrate content from multiple sources

Github can enable you to do so much more, but the following tutorial covers the basics.  Here I describe how to install github, working with file repositories both you and others create, and implications for your research.
 

##First Steps: Download & Install

There are two programs you will need to download and they are:
+ [github](https://desktop.github.com/)
+ [sublime text](http://www.sublimetext.com/2)

###Notes
+ You can expect Sublime Text to replace word processors and even front page!!! Sublime text creates markdown files, which allow you to create files just like this one!
+ Do download the desktop version of github and be sure to save your files in the GitHub folder you specify during installation from hereonin!
+ Coding using Sublime Text can be done using markdown or HTML.

##Next Step: Fork and Pull
One thing you can do to give yourself a leg up so that you have some code to copy and paste, is to **Fork** this repository of files I have created for this tutorial.  To do so, follow these steps:

1. go to the [github website](https://github.com) and login if you already haven't
2. in the search bar type **tutorial linguists**
3. click on the link that reads **80masters/github-tutorial-for-linguists**
4. on the top-right of the screen, you will see a button labelled **Fork**, click it ![Fork](https://github.com/80masters/Github-Tutorial-for-Linguists/raw/master//images/fork.jpg)
5. switching to the desktop version of github, click on the **\+** in the top-left corner
6. click on the word **clone** that should appear near the top-center of the screen
7. click on **Github-Tutorial-for-Linguists**
8. click on the checkmark near the bottom-center of your screen 
9. you now have an additional folder within your computer's github folder that contains the files for this tutorial that you can edit, copy-n-paste, and/or delete at your leisure!

If you wanted to make a change to this tutorial like an update or adding a photo or fixing a typo or adding a section on functionality, then you would:

1. open the tutorial index file using Sublime Text
2. make the changes
3. save the file \(in sublime text\)
4. on the desktop version of github, select the tutorial github on the far right
5. then click on the broken circle
6. type in a brief description of the change
7. click on *Commit to Master* near the bottom-center of your screen
8. click on sync near the top-right of your screen

###Notes:
+ You can add files to the tutorial repository simply by copying them to that folder.  They will be uploaded as part of step 7 \(Commit to master\).
+ The above are the steps to follow when making changes to repositories that you or others create.  To integrate a change into the master copy someone else originally created, one additional step is needed and that is, to initiate a pull request, by clicking on those words in the top-right of your github desktop screen.  Don't worry, if they don't want to accept the changes, they can easily revert back to an earlier version. In other words, make mistakes because it is super-easy to recover from them using github!

##Working with Your Own Repository
You can add files such as corpus data, recordings, and images to your repository simply by saving or copying them to the directory on your computer and then pulling them into the master repository \(as stated above\).  These can then be included into your files.

For example, let's say you have a recording of a participant in your study, either for pronunciation analysis or an interview.  You can then include them in the body of your writing as follows:

<p><a href="\audio\test_recording.mp3">Participant 1 Interview</a></p>

The HTML coding for it is:

>\<p>\<a href="\audio\test_recording.mp3">Participant 1 Interview\</a>\</p>

whereas the markdown coding for it would be:

> \!\[Participant 1 Interview\]\(https\://github.com/80masters/Github-Tutorial-for-Linguists/raw/master//audio/test_recording.mp3\)

Others can then listen to the files after downloading them.

Pictures, diagrams, and illustrations work in a similar way, but can open directly on the page, as seen with the example below.  Just remember to type ?raw=true (when using markdown, not HTML) at the end of the file name otherwise readers will have to click on it in order to view it and then hit the back button to return.

<p><img src="\images\sound_wave.jpg" alt="Funky Sound Wave"></p>

Compare the HTML version:

> \<p>\<img src="\images\sound_wave.jpg" alt="Funky Sound Wave">\</p>

with the markdown version:

>\!\[Funky Sound Wave\]\(https://github.com/80masters/Github-Tutorial-for-Linguists/raw/master//images/sound_wave.jpg?raw=true\)

###Notes:
+ It is currently unclear to me how to embed audio into markdown even after attempts at using HTML code, but selecting what to download does give power to the user/reader.
+ With this functionality, you can have impressive appendices and links throughout your work.  I will leave you with your imagination.

##Implications for Research
Two of the biggest considerations are copyright and, by extension, ethics.  [Creative Commons license](https://creativecommons.org/licenses/) should be stated.  Also, if others have access to the files you post and any of them contain data directly from participants in your study, this will need to be reflected in your ethics form all study participants are required to sign beforehand.

One of the most powerful aspects of collaboration permitted by github is the fact that anyone can have access to your completed works.  Before you fret, remember that github tracks the changes you make to your repository, so you can always revert back.  Thinking more progressively, others can pick up on additional areas of research or investigate other matters in further detail.  For example, you do a study on repair strategies non-native speakers of a language make when converting a word or group of sounds into their native tongue.  Other researchers might expand by including other groups of sounds or simply model your research with a completely different langauge pair!  In short, github can make it easier for your work to be cited!!

Referencing is made substantially more user-friendly in terms of being able to check out sources with simple clicks as is the case with hyperlinks embedded in text, photos, and other files.  Trains of thought can migrate to maglev with this capability!  That said, how will all of you decide who publishes which part with traditional journal article publishing?

If you are at all concerned about privacy, then you may pay a little and github will keep your repository private.  You will then be able to control who can fork \(i.e. have access and contribute to\) your work.  Public and private versions of a repository is also possible. You can even start public and go private or vice versa, plus you can delete one network \(the public or private\) and the other will remain. In short, the choice is yours.

Additional functionalities for github you may be interested in exploring include:
* inserting tables - not too difficult to do with the | key!
* creating pdfs from markdown files
* funky formatting using HTML tags
* using wget to backup webpages or an entire website

If you want funky formatting and alignments, you will need to explore html coding, although do not be dismayed as it can be learned very quickly.  If you want some text in bold, guess what you do in html?  First, you tell it where the bold begins and where the bold ends and that is it!  So

> \<b\>Something important\</b\>

becomes

<p><b>Something important</b></p>

And no, you are not limited to only programming in either markdown or html.  You can alternate between markdown and html tagging on a paragraph basis.

##Conclusion
So now you know how to work with repositories with github and I hope this inpsires you to expand your important linguistic research with others in the field who can both use and expand on it.

The following are some links I found very useful:
* [creating pages in markdown (i.e. markdown syntax)](https://daringfireball.net/projects/markdown/syntax)
* [github privacy pricing - monthly rates for privacy options](https://github.com/pricing)
* [HTML formatting - tons of examples here](http://www.w3schools.com/html/html_formatting.asp)
* [wget tutorial](http://programminghistorian.org/lessons/automated-downloading-with-wget)

<p><a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.</p>