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
* see a word in-context
* see where a word appears throughout a text

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
First, AntConc only works with text files \(i.e. they have a .txt extension at the end of the file name\). So, whatever texts you want to run in AntConc, they must first be converted into this format. Since text files are an incredible simple file type, most word processors can easily convert them through the 'save as' function. If this option is not available for the source file type, then try an online search for sites offering ___-to-text file conversion.

Depending on the source file for a given text that you want to analyze, extraneous elements may also be in your text file, such as copyright statements, table of contents, reference lists, etc. At the time of writing this tutorial, I am unaware of any text file cleaners per se, so this may be tedious as it will have to be done manually by deleting the extraneous portions.


###Notes:
+ You may want to store master copies of text files in a separate folder from specific analyses. That way, you can delete whatever sections you want during data cleaning without having to worry about starting all over again if you want to analyze those deleted parts in a future research.


<a name="use"></a>
##Using the Tool
In this section, I describe how to use a few of the basic functions in Antconc.

Once you have your text file, you have a choice. You can view concordances within only one text file OR you can compare text files simultaneously. This may clarify/simplify file storage as each text can be put in its own .txt file, just make sure they are all in the same folder.

To analyze a single text file, follow the steps below:

1. click on File -> Open File\(s\)
2. select the file you want to analyze
3. enter the word you would like to search in the textbox. If you would like the search to be case sensitive, click the Case button.
4. click 'Start'

To analyze multiple text files in the same folder, follow the steps below:

1. click on File -> Open Dir...
2. select the folder containing the files you want to analyze
3. for any unwanted files in the list, for each click on on and the click File -> Close Selected File\(s\)
4. enter the word you would like to search in the textbox. If you would like the search to be case sensitive, click the Case button.
5. click 'Start'

For any of the results, if you double-click on one, it will switch over the the File View tab, which deisplays the complete text file \(with scrolling enabled, of course\), and will skip straight to that occurrence. A very handy function to see a word in-context!

To the right of the results, there is a window for each occurrence stating which file it was found in.

You can also switch to the Concordance Plot Tab to compare multiple files. In this view, you can see each file as a horizontal bar, beginning on the left and ending on the right, and each vertical line within that bar shows you where an a word occured in that text.

<p><img src="\images\concordance-plot.JPG" alt="Concordance Plot"></p>

If you want to search for phrases \(e.g. in spite of\), click over to the 'Collocates' tab \(image below\). You cannot type in the entire phrase in the Search Term textbox, only one. Choose a root word \(e.g. spite\) and then determine how many words to the left and right of the word AntConc should find collocates to. In the example I performed, even the word 'promoting' was a result because it appeared within 5 words of the word 'spite'! Clearly a human close read is required to determine validity for your research.

<p><img src="\images\collocates.JPG" alt="Collocates"></p>

After running this using a specific root word, you can also click on the 'Word List' tab \(image below\). This shows how often specific words occurred within the left-right range set in the collocates search. Unfortunately, there is no file break-down like the word search.

<p><img src="\images\w-list.JPG" alt="Word List"></p>

###Notes:
+ On the bottom-right of the Collocates tab, you can set the minimum collocate frequency. This means the results will only include instances of a word within the right-left range of the source word if it appears x number of times. If it appears 4 times in a text, but you set it to 5, it will not appear.
+ AutoConc does not currently support analyses of Greek and mathematical symbols.
+ There are additional functions within AntConc, but this tutorial covers the basics. Feel free to add details on the other functionality thorugh pull requests!

<a name="imp"></a>
##Implications for Research
One of the biggest implications for research is scope. This tool can be applied to texts of many disciplines including geography, physics, history, and linguistics. All that is required is a text and an intent to search for occurrences of a particular meaning. What that intent is, well, that I leave to the principles of your discipline, research design, and ethics.

It is unlikely you will already know what to expect with the analysis of a given text. As part of your analysis, it would be prudent to set search string criteria \(e.g. minimum frequency\) outside of your pre-determined range. By looking at results that lie just outside the bounds of your proposed search criteria, you can enrich your discussion/analysis be determining how those search criteria skew the results - if at all. Plus, you may stumble on an interesting revelation that only quick big data searches can do in only a few seconds - a paltry price to pay.

As with the use of any texts not created by you, the researcher, intellectual property \(IP\) issues arise immediately. Consult the relevant IP and publishing law\(s\) in your country. Also, you may be able to study the texts, but you may not be able to publish the results! For most countries, while the write-up of the research is yours, the original texts are not; however, seeking permission from the creator may mitigate IP and publishing concerns. The take-home message is simple: even when operating under an educational insitution, choose wisely in advance.


<a name="conclude"></a>
##Conclusion
In short, AntConc is a very neat textual analysis tools with simplified search terms and an interesting visualization. While it does not compare to the functionality of COCA, AntConc is not restricted to the texts being analyzed.

So now you know the basics of textual analysis using AntConc and I hope this inpsires you to expand your important research by including a larger number of longer texts in your study's corpus.

The following are some links and articles you may find of interest pertaining to textual analysis:
* [The Corpus of Contemporary American English](http://corpus.byu.edu/coca/)
* [The World Intellectual Property Organization](http://www.wipo.int/about-ip/en/)
* [article - How NOT to read a Million Books](http://people.brandeis.edu/~unsworth/hownot2read.html)
* [article - Trending: The Promises & Challenges of Big Social Data](http://manovich.net/index.php/projects/trending-the-promises-and-the-challenges-of-big-social-data)

<p><a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.</p>