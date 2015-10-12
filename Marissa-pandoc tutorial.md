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

This tutorial will talk you through the set up and process of converting a markdown file to html and to pdf, on both Windows and Mac.  

# Software & Setup

### If you're using a MAC
- You'll need to download [Pandoc](https://github.com/jgm/pandoc/releases/tag/1.15.0.6) 
- To convert to PDF, you also need LaTeX.  For a reasonable sized version, download [BasicTeX](http://www.tug.org/mactex/morepackages.html)

### If you're using Windows
- You'll need to download [Pandoc](https://github.com/jgm/pandoc/releases/tag/1.15.0.6)
- To convert to PDF, you also LaTeX.  One version is [MiKTeX](http://miktex.org)

# Using the tool

The first step is having something that needs to be converted.  Create a textfile that says anything you like. Example: "I will convert this to PDF."  Save it as .txt or .md and make note of where you save it.  For my test, I'm saving my file in my Documents folder.

### Understanding Where Pandoc Is
Pandoc is controlled completely through your computer's command line.  To convert something using Pandoc, you must first navigate to the directory in your computer where the file is.

- To get started, on OSX open up Terminal (which is generally hidden in your Utilities folder).  On Windows open either Command Prompt or Windows Powershell.
- Press *cmd* on OSX or *echo %cd%* on Windows.  Then hit enter.  Your current directory should be printed.  You are probably starting in your computer's home directory.
- To get to a different directory (in this example, the Documents folder in my home directory), type *cd Documents* then *cmd* or *echo %cd%* on OSX and Windows respectively.  You should now be in the Documents directory.  For more deeply hidden folders, the process is followed in the same way, following the path of your file.  
- You can also create directories this way, by typing *mkdir DIRECTORYNAME*.

### Converting to HTML
Now that you're in the right place, converting a file to HTML is easy.  Just type *pandoc FILE.md -f markdown -t html -s -o FILE.html* replacing FILE with your file name.

Now, if you go look for your file outside of the command line, you should see that it is next to an HTML counterpart.  Horray!

### Converting to PDF
Converting to PDF is only slightly different, because it uses LaTeX to work.  Type *pandoc FILE.md -f markdown -t latex -o FILE.pdf*, replacing FILE with your file name.  There should now be a PDF counterpart for your file as well.  

# Conclusion

Congratulations!  You can now convert markdown to HTML and PDF.  With a few different keystrokes, you can also use Pandoc to convert from text to ___  The universe is in your file format.  

Now you can sit back and feel proud of the magic you performed.  



