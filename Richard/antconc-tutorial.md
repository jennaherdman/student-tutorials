---
title: AntConc Tutorial
author:
- Richard Soulliere
date: 2016-01-26
reviewers:

layout: default
---


#AntConc Tutorial

Hello researchers and word nerds!  In an effort to save on reading, I have created this mini-tutorial for you to make use of a useful tool that will:
* find all the occurences of specific words in a text
* analyze any text you have
* enable you to read a complete text in as little as a few seconds

Here, I describe how to do the following with AntConc:

<p><dl><dd><a href="#install">download and install AntConc</a></dd>
<dd><a href="#data">data preparation</a></dd>
<dd><a href="#use">using the tool</a></dd>
<dd><a href="#imp">implications for your research</a></dd>
<dd><a href="#conclude">some concluding thoughts and useful links/references</a></dd></dl></p> 


<a name="install"></a>
##First Steps: Download & Install

AntConc is available for free download [by clicking here](http://www.laurenceanthony.net/software.html). Make sure you do not delete this file as that is the whole kit and caboodle, the icon for which can be seen below.

<p><img src="\images\antconc.JPG" alt="AntConc icon"></p>

###Notes
+ Working versions are available for Windows, Macs, and Linux systems. This tutorial covers the Windows version.


<a name="data"></a>
##Data Preparation
First, AntConc only works with text files \(i.e. they have a .txt extension at the end of the file name\). So, whatever texts you want to run iin AntConc, they must first be converted into this format. Since text files are an incredible simple file type, most word processors can easily convert them through the 'save as' function. If this option is not available for the source file type, then try an online search for sites offering ___-to-text file conversion.

Depending on the source file for a given text that you want to analyze, extraneous elements may also be in your text file, such as copyright statements, table of contents, reference lists, etc. At the time of writing this tutorial, I am unaware of any text file cleaners per se, so this may be tedious as it will have to be done manually by deleting the extraneous portions.


###Notes:
+ You may want to store master copies of text files in a separate folder from your research. That way, you can chop whatever sections you want during data cleaning without having to worry about starting all over again if you want to analyze those chopped parts in a future research.


<a name="use"></a>
##Using the Tool
Once you have your text file, you have a choice. You can view concordances within only one text file OR you can compare text files simultaneously. This may clarify/simplify file storage as each text can be put in its own .txt file, just make sure they are all in the same folder.

To analyze a single text file, follow the steps below:

1. click on File -> Open File\(s\)
2. select the file you want to analyze
3. enter the word you would like to search in the textbox. If you would like the search to be case sensitive, click the Case button.
4. Click 'Start'

To analyze multiple text files in the same folder, follow the steps below:
1. click on File -> Open Dir...
2. select the folder containing the files you want to analyze
3. for any unwanted files in the list, for each click on on and the click File -> Close Selected File\(s\)
4. enter the word you would like to search in the textbox. If you would like the search to be case sensitive, click the Case button.
5. Click 'Start'

To the right of the results, there is a window for each occurrence stating which file it was found in.

You can also switch to the Concordance Plot Tab to compare multiple files. In this view, you can see each file as a horizontal bar, beginning on the left and ending on the right, and each vertical line within that bar shows you where an a word occured in that text.

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