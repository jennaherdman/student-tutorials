# Voyant: A text-analysis tool

Voyant is a powerful tool that can be used for analyzing text.  In this tutorial we will look at Voyant: what it is, how to use it, and detailed looks at a few of the many tools it contains.

[Voyant](http://voyant-tools.org) runs online so it is not necessary to download any software.  To begin, you can either upload one or more text files or paste in a text or link, then click 'reveal'.  For this tutorial, we will be looking at [The Travels of Marco Polo](https://archive.org/stream/marcopolo00polouoft/marcopolo00polouoft_djvu.txt).

### Understanding and Using Voyant's Interface
Once Voyant has 'revealed' your chosen text, it will look something like this:
![interface](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202016-01-19%20at%207.19.55%20PM.png)

The text will be on the right while the left has a word cloud and statistics for the most frequent words within the text.  For our text, the words 'of', 'the', 'and' and 'in' were the most frequent.  Those words do not elucidate much about the text.  A good first step after inputting a corpus into Voyant is to clean it up a little.

To start, hit the cog in the left-hand corner next to 'Cirrus' to get the search options.  Here, you can edit the 'stop-words', the words which will not be taken into consideration in the text analysis.  You can manually put in words as well as choose from preexisting lists, depending on the language.  For English, the Taporware list exists.  Click the box 'Apply Stop Words Globally' and then click ok.  
![stop words](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202016-01-19%20at%207.34.38%20PM.png)

A new word cloud should appear.  For our text, the words 'city', 'country', 'great', 'grand' and 'khan' are now the most frequent and reveal a lot more about the text than the previous list had.

Below the word cloud is a box with a sumamry of how many words and unique words are in the text.  Below that are the most frequent words, in order of frequency, which you can compare against each other in the graph on the right by clicking the checkmark box next to them.  The first instance of the word will also be shown in the text in the middle, and you can toggle between instances of that word using the arrows at the bottom.
![city/country](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202016-01-26%20at%207.06.06%20AM.png)

### Using Different Tools within Voyant
Voyant can be used to manipulate texts and extract key elements, which can then be analyzed or exported for use in other programs.  We will go over a few differents tools Voyant contains.  Depending on the strengths of your computer, many of these will fail.  A second shot will sometimes work but some may be simply beyond your computer's abilities.  As long as you don't mind possibly breaking your browser and needing to restart it, it never hurts to try though. **Some of the tools will flicker intensely if they do not load up correctly, so it is suggested you not use Voyant if you have epilepsy.**   

To access other tools select the save button in the top right corner of the screen. From the list of saving options select the very last one: "a URL for a different tool/skin and current data", this will take you to a drop down selection box with many visualization options. Selecting one will bring up a URL. Copy and paste it into the navagation bar and that will bring up the tool. 

#### RezoViz

RezoViz allows for insight into different connections between elements (like people or places) within a text.  It can also be used to export that information to a .net file ready for network analysis in a program like [Gephi](https://gephi.org).  The tool can take a while to process, and depending on the size of the corpus and your computer's processing power, might not start at all. If it does the visualization should look like a web, with the most common term in the centre. 

The bottom left has options for altering the visualization, where you can limit the number of terms, as well as tension, replusion and friction. 


![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/options.jpg)

After making choices about terms, and correcting any errors in the program's catagorization, you can save your network analysis as a .net file. Clicking the save button in the top right corner and selecting "all data in Pajek (.net) syntax" creates the file which can then be used in Gephi!

![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/fornetfile.jpg)

Gephi enables a greater level of control and options for network analysis, but the program can be tricky. As stated it's a network analysis program that creates large visuals, and has a number of options for customization, so if a detailed look into the relationships between people/places is important Gephi is worth the trouble! [Here's more about the features.](https://gephi.org/features/)


To get started (if you're having problems getting the program to intialize [click here](https://forum.gephi.org/viewtopic.php?t=3309) for help) simply select new project and under file select open. After finding the .net file, open and you'll see something like this:

![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/gephi.jpg)

If instead of a visualization you're shown the message that there isn't enough memory you can follow some simple steps to increase it:
Find Gephi under "Program files (x86)" in your C: drive. In the "etc" folder there should be a file called "gephi.conf", open this in a text editor like Sublime Text, or Atom, and find the line "Xmx". replace the number following that with 5708, making sure the m follows directely after. Save the file and restart Gephi, it should work now. (For other ways of changing this, and more instructions [click here](https://gephi.org/users/install/#memory).)

![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/editingin.jpg)

####Knots
If you ever wanted to see how the use of different words within a text compare in the style of childrens' drawings, Knots it the tool for you!  When it is run, it will start a line visualization describing the use of a chosen word through the text.  
![knots 1](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202016-01-24%20at%207.53.02%20PM.png)

If you click on a point along the line, it will open up the sentence with that particular use of the word.  More words can be added using the search bar in the top-left corner.  Once another word is selected, the tool will reload and the visualization will start over with both words, each colour-coded.
![knots 2](http://i1191.photobucket.com/albums/z467/risssssy/Screen%20Shot%202016-01-24%20at%208.07.26%20PM.png)

You have the ability to control the build speed, starting angle, and tangles at the top, in order to make the visualization more legible.  Short lines indicate little space between uses of the word while longer lines indicate large gaps.  It is possible with this tool to hone in on parts of the text where a word is used more frequently, or see if certain words appear together frequently by comparing the lines.  

#### Word Trends

As the name implies, word trends shows the terms as a graph with frequency over the document. Since it's displayed as a simple line graph, the information is easy to extract. For a general view into the text you can limit the number of segments shown. Alternatively, for a more detailed view into the frequency through parts of the text you can increase the number of segments. 

![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/w2w.jpg)

![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/thjegrave.jpg)

You can also collapse the terms so you're left with just one line.

![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/rrrr.jpg)

For more information you can hover above the lines and the exact number of times a term or terms were used in the segment will appear!


#### Bubblelines

Bubblelines is quite similar to Word Trends, but a lot prettier! Here instead of a boring old line graph, we're presenting with cute little bubbles representing terms over the duration of the text. Again, hovering above the graph will reveal the number of times a term, or terms have come up in the segment, and you can alter the detail by changing the granularity at the top.

![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/rretrer.jpg)

Like Word Trends, you can collaspe the graph to just one line, but the bubbles retain their colour so the terms are still distinct. 

![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/rrere.jpg)

This sort of work is useful, but what you can get out of it is determined by your choice of words so be careful about things like spelling and translations.  A tool is only as good as the content input!

You can clear the default terms loaded and use the search bar at the top-left to input your own chosen words and compare.  We added a selection of places Marco Polo visited in his travels.
![bubblelines 1](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/12632918_1133594893340147_1679230308_o.jpg)

### Conclusion and Thoughts on Voyant's disparate and powerful uses
Using Voyant effectively requires patience and a decent computer, but if you are willing to try it can help reveal some interesting aspects of the text not otherwise evident.  It is also useful for manipulaitng data from a raw text to become useful for other programs.  Some of its tools are more useful than others and experimentation is the best way to get to know Voyant!


### Other Helpful Links

+ [Voyant's Documentation](http://docs.voyant-tools.org/): Provides a quick walkthrough for using Voyant and descriptions of all the tools it contains.
+ [A Gephi Tutorial](http://electricarchaeology.ca/2013/10/29/getting-historical-network-data-into-gephi/)

### Miscellaneous

Voyant is capable of extracting text from things. 

Here we have just thrown in a link to a google search:

![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/popo.jpg)

Depending on the page voyant can pick up on some weird syntax. Or, here is an example image showing what can happen:

![](http://i17.photobucket.com/albums/b99/Dragon_Tamer13/png.jpg)

It was able to read the image as text, but never fully loaded to show that text. These examples are just to show that you can play with Voyant to get some different, unexpected results. 
