---
title: Github Tutorial for Linguistics
author:
- Richard Soulliere
date: 2015-10-10
reviewers:

layout: default
---


#Github Tutorial for Linguists

Hello (applied) linguists!  In an effort to colloborate and share your work, I have created this mini-tutorial for you to make use of a powerful tool that will:
* keep track of changes you make so you can go back to an earlier version
* prevent the need for buying software products \(even MS Office\)
* share your research easily with others
* enable you to integrate content from multiple sources \(i.e. multi-modal\)

Github can enable you to do so much more, but the following tutorial covers the basics.  Here I describe how to do the following on your computer:

<p><dl><dd><a href="#install">download and install github</a></dd>
<dd><a href="#fork">fork - meaning to get repositories others have created</a></dd>
<dd><a href="#work">work with file repositories either you and/or others create</a></dd>
<dd><a href="#sync">keeping nsync</a></dd>
<dd><a href="#imp">implications for your research</a></dd>
<dd><a href="#conclude">some concluding thoughts and useful links/references</a></dd></dl></p> 

Technically you can work with repository files online, but it's a little awkward when starting out. By working on your machine you can do what you usually do with files \(like rename, delete, open, etc. really easily\) in the way you are accustomed. I am addicted to right-clicking, what can I say?

<a name="install"></a>
##First Steps: Download & Install

There are two FREE programs you will need to download and they are:
+ [github](https://desktop.github.com/)
+ [sublime text](http://www.sublimetext.com/2)

They are both compatible with PCs, Macs, and other platforms. Once both are installed, continue reading.

###Notes
+ Coding a file using Sublime Text can be done using markdown or HTML.
+ If you don't know markdown or HTML, don't sweat it!
+ You can expect Sublime Text to replace word processors and even simple HTML editors!!! Sublime text creates markdown files, which allow you to create files just like this one!
+ Do download the desktop version of github and be sure to save your files in the GitHub folder you specify during installation from hereonin because that's where github looks.

<a name="fork"></a>
##Next Step: Fork
One thing you can do to give yourself a leg up if you have not worked with github before is to **Fork** this repository.  This will give you some code to copy and paste into your own files because you will then have all the files - no viruses - in this repository I created for this tutorial.  To do so, follow these steps:

1. go to the [github website](https://github.com) and login if you already haven't
2. in the search bar type **tutorial linguists** \(it's ok if you are not a linguist\)
3. click on the link that reads **80masters/github-tutorial-for-linguists**
4. on the top-right of the screen, you will see a button labelled **Fork**, click it
<p><img src="\images\fork.jpg" alt="Fork"></p>

You could stop here and do stuff only online, but that I found a little cumbersome at first, so take it to the next level and continue.

5. open the desktop version of github
6. click on the blue **\+** in the top-left corner
7. click on **clone in desktop** that should appear near the top-center of the screen
<p><img src="\images\clone.jpg" alt="Clone"></p>
8. click on **Github-Tutorial-for-Linguists**
9. click on the checkmark near the bottom-center of your screen 

You now have an additional folder on your computer in the github folder you chose when installing github. In that additional folder, you will find the files for this tutorial that you can edit, copy-n-paste, and/or delete at your leisure!

###Problem:
You now have 2 versions.  The online version \(you will unlikely edit directly unless you are using someone else's computer\) and the one on your computer \(which you will be playing around with\).  For now, stick with using the one on your desktop while I first show you how to work with these files.  Then, we will keep the version on your desktop in sync with the online version and then take the modifications you made and tell me to incoporate them into the original \(unless you write a tutorial on something completely different, in which case, great\).

###Notes:
+ You can add files to the tutorial repository simply by copying them to that folder.  They will be uploaded as part of Commit to Master.
+ The above are the steps to follow when making changes to repositories that you or others create.  To integrate a change into the master copy someone else originally created, one additional step is needed and that is, to initiate a pull request, by clicking on those words in the top-right of your github desktop screen.  Don't worry, if they don't want to accept the changes, they can easily revert back to an earlier version. In other words, make mistakes because it is super-easy to recover from them using github!

<a name="work"></a>
##Working with Your Own Repository
You can open the github folder on your computer and add files, add folders and sub-folders, delete files or folders...pretty much the same as one normally could.  Anything done in the github folder is tracked, easy-peasy. For Windows users, when double-clicking to open a markdown file for the first time, make sure you choose to always open with Sublime Text.  No headaches this way.

When using Sublime Text to create and edit files, you can add things like corpus data, recordings, and images by saving or copying them to the directory on your computer for the repository you are working on.  These can then be included via embedding \(i.e. direct appearance\) or linking \(i.e. click-to-download\).

For example, let's say you have a recording of a participant in your study, either for pronunciation analysis or an interview.  You can then include part or all of that recording into the body of your writing as follows:

<p><a href="\audio\test_recording.mp3">Participant 1 Interview</a></p>

The HTML coding for it is:

>\<p>\<a href="\audio\test_recording.mp3">Participant 1 Interview\</a>\</p>

whereas the markdown coding for it would be:

> \!\[Participant 1 Interview\]\(https\://github.com/80masters/Github-Tutorial-for-Linguists/raw/master//audio/test_recording.mp3\)

Others can then listen to the files after downloading them.

Pictures, diagrams, and illustrations work in a similar way, but can open directly on the page \(i.e. embedding\), as seen with the example below.  Just remember to type ?raw=true (when using markdown, not HTML) at the end of the file name otherwise readers will have to click on it in order to view it like the audio file above.

<p><img src="\images\sound_wave.jpg" alt="Funky Sound Wave"></p>

Compare the HTML version:

> \<p>\<img src="\images\sound_wave.jpg" alt="Funky Sound Wave">\</p>

with the markdown version:

>\!\[Funky Sound Wave\]\(https://github.com/80masters/Github-Tutorial-for-Linguists/raw/master//images/sound_wave.jpg?raw=true)

###Notes:
+ Files created with markdown coding do not allow embedding of sound files.  It would not be possible to convert to HTML, doc, or pdf files if that was the case!  Still, giving the power of choosing what to download to the user/reader is fine.
+ With this multi-modal functionality, you can have impressive appendices and links throughout your work.  I will leave you with your imagination.
+ The markdown coding for embedding or linking files you include will depend on your username, the folder structure you use, and the names you give your files.  In the sound wave example; 80masters is my user name, then there's the name I gave the repository, raw and master are required along with the double-slash, then the sub-folder within the repository, then the file name.  Practice replacing your details with one of your files, get it right, then you have a line of code that can be copied with minimal changes required!
+ Clearly, HTML is simpler as it only requires the folder structure and file name. The stuff after alt is the caption.
+ The file name and extension is case-sensitive, so if you name your file something.JPG the JPG part must be capitalized in any reference to it in your markdown file, too!

<a name="sync"></a>
##Keeping NSync

Ok, so you have done lots of modifications to the version of this tutorial on your computer.  Time to sync it with the online version or nobody will be able to see it \(plus it serves as a backup to the version on your computer\). Here's how you do that:

1. open the tutorial index file using Sublime Text
2. make some changes
3. save the file \(in sublime text\)
4. on the desktop version of github, select the tutorial github on the far right
5. then click on the broken circle
<p><img src="\images\broken_circle.JPG" alt="broken circle"></p>
6. type in a brief description of the change \(if you don't do this then you can't sync\)
<p><img src="\images\commit_prep.JPG" alt="Commit to Master area"></p>
7. click on *Commit to Master* near the bottom-center of your screen
8. click on sync near the top-right of your screen
<p><img src="\images\top-right-syncing.JPG" alt="Top-Right area"></p>

As soon as syncing has been completed, the updates to the version you forked are now available online. The next question is how to take those modifications and tell me that you want them on my master copy \(seeing as everyone who has forked my version would likely want to see your updates, too\).  This requires you to make a pull request.  How do you do that?

You see in the image above with the sync button how there's also a pull request button?  If and only if you have actually made some changes, then you can click on the pull request button. Once the pull request is made, the person from whom you forked the repository will then have the option to accept or deny the changes you have made.  If you make additional changes while they are scratching their head, you have to wait for them to make a decision before submitting another pull request \(for that same repository\).  Anyway, click on the create pull request button, the web version will pop open, fill in some details about the changes you made, and then click on **Create Pull Request**. Then you just have to wait.

<a name="imp"></a>
##Implications for Research
Two of the biggest considerations for research are copyright and, by extension, ethics.  To start with, [Creative Commons license](https://creativecommons.org/licenses/) should be stated.  Also, if others have access to the files you post and any of them contain data directly from participants in your study, this will need to be reflected in your ethics form all study participants are required to sign before participating.

If you are at all concerned about privacy and intellectual property rights, then you may pay a little and github will keep your repository private.  You will then be able to control who can fork \(i.e. have access and contribute to\) your work.  Public and private versions of a repository is also possible. You can even start public and go private or vice versa, plus you can delete one network \(the public or private\) and the other will remain. In short, the choice is yours.

One of the most powerful aspects of collaboration permitted by github is the fact that anyone can have access to your completed works.  Before you fret, remember that github tracks the changes you make to your repository, so you can always revert back to an earlier version.  Thinking more progressively, others can pick up on additional areas of research or investigate other matters in further detail.  For example, you do a study on repair strategies non-native speakers of a language make when converting a word or group of sounds into their native tongue.  Other researchers might expand by including other groups of sounds or simply model your study for use with a completely different pairing of langauges!  In short, github can make it easier for your work to be cited and serve as the basis of research conducted by others!!

Referencing is made substantially more user-friendly in terms of being able to check out sources with simple clicks as is the case with hyperlinks embedded in text, photos, and other files.  Trains of thought can migrate to maglev with this capability!  That said, how will all of you decide who publishes which part with traditional journal article publishing?

Have you ever wondered how to make your data analysis section richer as opposed to simple and dry? If you work with your data via github, then every time you type in a description before you "Commit to Master" can help! Be descriptive and include decisions you make and/or important notes in those descriptions.  By the time you are ready to write the discussion section to your paper, you will have all those notes to work with and you can spell out the twists, turns, and logic behind your brilliant study!

Additional functionalities for github you may be interested in exploring include:
* inserting tables - not too difficult to do with the | key!
* creating pdfs from markdown files
* funky formatting using HTML tags
* using wget to backup webpages or an entire website
* using Jekyll to create a website

Finally, if you want funky formatting and alignments, you will need to explore html coding, although do not be dismayed as it can be learned very quickly.  If you want some text in bold, guess what you do in html?  First, you tell it where the bold begins and where the bold ends and that is it!  So

> \<b\>Something important\</b\>

becomes

<p><b>Something important</b></p>

And no, you are not limited to only programming in either markdown or html.  You can alternate between HTML tagging and markdown on a paragraph basis - which you can see in the coding for this page.

<a name="conclude"></a>
##Conclusion
So now you know how to work with repositories with github and I hope this inpsires you to expand your important linguistic research with others in the field who can both refor to and expand on.

The following are some links I found very useful:
* [creating pages in markdown (i.e. markdown syntax)](https://daringfireball.net/projects/markdown/syntax)
* [github privacy pricing - monthly rates for privacy options](https://github.com/pricing)
* [HTML formatting - tons of examples here](http://www.w3schools.com/html/html_formatting.asp)
* [Pandoc - merging multiple markdown files and convert-to-PDF](http://pandoc.org/installing.html)
* [repository for creating ready-to-upload websites quickly with Jekyll](https://github.com/barryclark/jekyll-now)
* [wget tutorial](http://programminghistorian.org/lessons/automated-downloading-with-wget)

<p><a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.</p>