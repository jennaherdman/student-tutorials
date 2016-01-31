---
title: AntConc Tool Tutorial
authors:
- Allie Watson
date: 2016-01-26
reviewers:
- n/a
layout: default
---

#Introduction to AntConc

This is a very approachable and intriguing program that allows you to examine a wide array of texts or, if you like, a single, large text, using what some have dubber "distant reading." There are some great sites that can get you started on the ins and outs of AntConc such as [this guide](http://wmtang.org/2011/03/05/a-simple-guide-to-using-antconc/) that the AntConc site provides by Warren M Tang. An even better resource from the Programming Historian website is Heather Froehlich's [tutorial](http://programminghistorian.org/lessons/corpus-analysis-with-antconc).

Honestly though, this program is quite user-friendly so the best approach I found was to fiddle around with the various tabs and settings and see what happens. It doesn't save over your original files, so feel free to click around without causig irreversible changes.

## Program and Files
Download the program [here](http://www.laurenceanthony.net/software.html) by clicking on the link that corresponds to your operating system and following the download instructions.

### Choose your texts
AntConc only reads plain-text files. For help converting various files into .txt format, see [this Pandoc tutorial](https://github.com/digh5000/student-tutorials/blob/master/pandoc-tutorial-for-english-students-watson-herdman.md). Alternatively, just copy paste the text you want to analyze into a new document through a program like TextEdit and be sure to save it as a plain-text file.

The texts I'm using for this tutorial are the six assigned articles for a class on text analysis. You can find the syllabus for DIGH5000 [here](http://dhcu.ca/pages/syllabus) and the six texts under January 12th.

To load the files you want to analyze, click the **File** menu and select **Open File(s)...**. Select the files in your computer and hit **Open**.

## Start searching
To get a sense of how this program works, think of a word that likely appears in your chosen text(s). Type it into the **Search Term** bar toward the bottom of the window and click **Start**. In this example, I've decided to search for the word "text."
![text](https://github.com/SAllieW/screencaps/blob/master/text.png?raw=true)

# The 7 tabs
AntConc gives you seven different ways to analyze your text(s).
**Concordance** shows you the keyword you search for in context. This view is great for giving you a quick sense of how the word is being used within a sentence (or even within a word i.e. human in humanities). You can also hit the **Sort** button and it will alphabetize the findings according to the following word. Compare this image to the one above:
![sorted](https://github.com/SAllieW/screencaps/blob/master/sorted.png?raw=true)

**Concordance Plot** shows you graphs/visualizations of the occurrences of your search term within the larger text(s). 
![word](https://github.com/SAllieW/screencaps/blob/master/word.png?raw=true)
Here, we can see that "word" occurs nine times throughout the Clement, Steger, Unsworth, and Uszkalo article, whereas it occurs only four times and in quick succession in the Jean-Baptiste article.

**File View** lets you see the actual text within the program.

**Clusters/N-Grams** shows words that are (surprise!) clustered together. Consider the clusters around the word "text" in these articles:
![textclusters](https://github.com/SAllieW/screencaps/blob/master/TextCluster.png?raw=true)
"text analysis" appears seventeen times in this corpus. The next most frequent pairing with the word "text" is "text-mining" with nine occurrences.

**Collocates** calculates the words that are likely to appear together. Unlike Clusters/N-Grams, this tab is not about what does appear, but words that are statistically likely to be found together. Like so:
![textcollocates](https://github.com/SAllieW/screencaps/blob/master/TextCollocates.png?raw=true)

**Word List** looks at all the words in your corpus and shows you which ones occur the most. Here's what mine looks like:
![wordlist](https://github.com/SAllieW/screencaps/blob/master/wordlist.png?raw=true)

AntConc allows you to export your work as well. Under the **File** menu click **Save Output to Text File...** and choose a destination for plain-text version of your work. As you can see from the image below, the resulting document is a little unwieldy in terms of width, but at least you've got a copy of your endeavours.
![output](https://github.com/SAllieW/screencaps/blob/master/Output.png?raw=true)

###Conc-lusion
As an English major, this kind of digital humanities project holds tremendous appeal. Studies such as [the one conducted on the works of Agatha Christie](http://www.theguardian.com/books/2009/apr/03/agatha-christie-alzheimers-research) show the potential for text analysis to aid us in interpreting large bodies of works in revelatory ways.

What's more, future features of this tool are in the making. As Anthony's site lists, various new and helpful components like "drag and drop file handling" and being able to save your results will hopefully be added to the next version. You go, little AntConc.

##References

Anthony, L. (2014). AntConc (Version 3.4.3) [Computer Software]. Tokyo, Japan: Waseda University. Available from http://www.laurenceanthony.net/

Heather Froehlich , "Corpus Analysis with Antconc," Programming Historian (19 June 2015), http://programminghistorian.org/lessons/corpus-analysis-with-antconc.html

