---
title: A Pandoc Tutorial
authors:
- Marissa Villeneuve
date: 2015-10-12
reviewers:
- n/a
layout: default
---

# Introduction
Pandoc is described on its website as a universal document converter.  It allows users to convert directly from text files and other formats to HTML, PDF, and a number of other formats, all with just a few lines in your computer's terminal.  

This tutorial will talk you through the set up and process of converting a markdown file to html and to pdf, on a Mac.  

# Software & Setup

- You'll need to download [Pandoc](https://github.com/jgm/pandoc/releases/tag/1.15.0.6) 
- To convert to PDF, you also need LaTeX.  For a reasonable sized version, download [BasicTeX](http://www.tug.org/mactex/morepackages.html)

One of the confusing things about these pieces of software is that, once they are downloaded, there is no disk image or symbol to indicate they are on your computer.  The only way to confirm that they have been downloaded is to check in your computer's command line, which you'll need in order to use Pandoc as well.

# Using the Command Line (on a Mac)

The first step is to open up your computer's Terminal.  On a Mac, this is where you control the command line, a place where you can use text commands to tell your operating system to do things.  Pandoc can be thought of as an add-on to the command line, giving it the ability to convert documents.  Terminal can usually be found in the Utilities folder of the Applications folder.  Once opened it will look something like this:
![blank terminal](http://i1191.photobucket.com/albums/z467/risssssy/blank%20terminal.png)

They do not give you much indication of what is happening or how to do anything.  A good place to start is to learn how to navigate through the folders in your computer(as you would with Finder), using the Terminal. Start by typing **pwd**.  The Terminal should print the current directory (folder) that you are in.  From there, you can move to any of the subdirectories within that directory.  Following along in a Finder window can be useful as you direct the Terminal to whatever file you want to work with.

**cd** is the command to change folders.  If I were to type **cd Documents** it would move me to the Documents folder of my home folder.  It would look something like this:
![cd Documents](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202015-11-30%20at%2010.40.09%20PM.png)

The frustrating part about using the command line is that there is no reassuring check mark or click if something goes right.  As you use it, it is important to carefully look at what you are typing and what the command line is printing back to understand what is happening.  

If I wanted to move back to the last folder I was in (my home user folder), I would type **cd .****.**, which means 'one level up'.  The computer should print back your home directory again, in my case my user directory rissyvilleneuve:
![cd ..](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202015-11-30%20at%2010.46.52%20PM.png)

You can also make new folders in directories using the command line.  Simply type **mkdir NAME** while in the directory you would like to create a new folder in and replacing NAME with what you would like to call the folder.  The Terminal will just print out your current directory again, but if you go into your finder there should be a new folder.  I typed **mkdir pdf** while in my Documents directory and a folder with that title appeared:
![pdf folder](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202015-11-30%20at%2010.50.55%20PM.png)

In summary:
+ **pwd** to print current directory
+ **cd NAME** to go to the subdirectory NAME of your current directory.
+ **cd ..** to go back to the previous directory.
+ **mkdir NAME** to create a new folder NAME in your current directory.

Armed with this knowledge, you are ready to use pandoc.

# Using Pandoc

The first step is having something that needs to be converted.  Create a textfile that says anything you like. Example: "I will convert this to PDF."  Save it as .txt or .md and make note of where you save it.  For my test, I'm saving my file **example** in my Documents folder.  We will start by converting the file to HTML.
![example](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202015-12-06%20at%2010.13.15%20PM.png)
### Converting to HTML
In your Terminal or Command Line, navigate the folder your document is in.  Now that you're in the right place, converting a file to HTML is easy.  Just type **pandoc FILE.md -f markdown -t html -s -o FILE.html** replacing FILE with your file name.  Mine looked like this:
![html conversion](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202015-12-06%20at%2010.29.52%20PM.png)

Essentially, you are telling the computer to take the file which is in markdown with that name in the folder you are currently in and to turn make a new file that is HTML out of it.  

Now, if you go look for your file outside of the command line, you should see that it is next to an HTML counterpart.  Horray!
![html file](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202015-12-06%20at%2010.30.01%20PM.png)

### Converting to PDF
Converting to PDF is only slightly different, because it uses LaTeX to work.  Type **pandoc FILE.md -f markdown -t latex -o FILE.pdf**, replacing FILE with your file name.  In the Terminal, it will look something like this:
![pdf terminal](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202015-12-06%20at%2010.35.51%20PM.png)
There should now be a PDF counterpart for your file as well.
![pdf result](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202015-12-06%20at%2010.36.04%20PM.png)
Look at all those files!  

# Formatting your PDF
My original markdown file looked like this:
![original text](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202015-12-06%20at%2010.39.42%20PM.png)
After being converted to PDF, it looked like this:
![pdf](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202015-12-06%20at%2010.39.17%20PM.png)

The text I converted was simple and it was easy to imagine what it would look like as a PDF file.  But what if the text you want to convert is a little more complicated?  For example, what if you want a formatted title or citations?  Pandoc is equipped to handle many formatting options.  We will look at one way you can customize your PDF by going through how to use YAML blocks to create a title.  

### YAML: What is it?
Essentially, YAML is a block that contains metadata.  In our case, we will be using it to contain title info that will be displayed in a specific way.  Pandoc is able to understand YAML blocks to a point.  Some more advanced instances require packages to be installed and very specific formatting.  For basic purposes though, what comes with Pandoc and LaTeX can suffice.  

What designates a block of text as YAML is its beginning with three hyphens and ending the same way, or with three dots.  This is what it one looks like:
![metadata block](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202015-12-06%20at%2011.41.09%20PM.png)
That is the YAML block at the top of this tutorial!  Our template will follow a similar format.

### A Simple Title Page Template
Our template will have spaces for the paper's title, author, date, and a section for an abstract.  At the top of the text, fill in this:

    ---
    title:  'Title: second part of title'
    author: Your Name
    date: 05/12/1907
    abstract: Paper's abstract.
    ---
The important parts are the hyphens at the top and bottom.  Since the title contains a colon, it needs to be in quotations.  Fill in the fields with your own info and then convert the document to PDF.  

Using this template, I turned this markdown file:
![YAML before](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202015-12-06%20at%2011.35.18%20PM.png)

Into this much nicer and well-formatted PDF document:
![YAML after](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202015-12-06%20at%2011.17.29%20PM.png)

# Conclusion

Congratulations!  You can now convert text or markdown to HTML and PDF.  With a few different keystrokes, you could also use Pandoc to convert from text to a multitude of different formats.  You have also gotten to experiment with ways that you can customize your PDF, all with basic text.  The universe is in your file format.  

Now you can sit back and feel proud of the magic you performed.  

# Further Resources for using Pandoc
[Pandoc tutorial](http://pandoc.org/getting-started.html): Pandoc's very thorough though dense and high-level tutorial for using their program. 

[Plain Text, Paper, Pandoc](http://kieranhealy.org/blog/archives/2014/01/23/plain-text/): Requires a knowledge/understanding of how to install packages for LaTeX, but is very useful for creating templates for pretty looking PDF documents.  

[Pandoc Tutorial for English Majors](https://github.com/digh5000/student-tutorials/blob/master/pandoc-tutorial-for-english-students-watson-herdman.md): A tutorial for using Pandoc designed specifically for use by English majors.

[Sustainable Authorship in Plain Text using Pandoc and Markdown](http://programminghistorian.org/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown): Includes useful info on including bibliographies.


## Coming Soon-ish
Sections for using Pandoc on a computer running Windows. 



