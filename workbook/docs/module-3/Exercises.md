
#Module 3: Exercises

## Exercise 1

When we mark up a text with the semantic hooks and signs that explain we are talking about 'London, Ontario' rather than 'London, UK', we've made the text a whole lot more useful for other scholars or tools. In this exercise, you will do some basic marking up of a text using standards from the Text Encoding Initiative. (Some of the earliest digital history work was along these lines).  The [TEI](../supporting materials/tei.md) exercise requires carefully attention to detail. Read through it before you try it. In this exercise, you'll transcribe a page from an abolitionist's pamphlet. You'll also think about ways of transforming the resulting XML into other formats. Make your notes in your open notebook, and upload your XML and your XSL file to your own repository. (As an added optional challenge, create a gh-pages branch and figure out the direct URL to your XML file, and email that URL to me).

## Exercise 2

When we have text that has been marked up, we can do interesting things with it. In the previous exercise, you saw that XSL can be used to add styles to your XML (which a browser can interpret and display). You can see how having those tags makes for easier searching for information as well, right? Sometimes things are not well marked up. Sometimes, it's all a real mess. In exercise two, we'll explore 'regular expressions', (aka 'Regex') or ways of asking the computer to search for *patterns* rather than matching exact text. 

This exercise follows a tutorial written for [The Macroscope](http://themacroscope.org).(Another good reference is [http://www.regular-expressions.info/](http://www.regular-expressions.info/)). 

* Start with [a gentle introduction to regex](../supporting materials/regex.md) and then begin the [regex exercise](../supporting materials/regexex.md). 

You should have [RegeXr](http://www.regexr.com/), an interactive tutorial that shows us what various regular expressions can do, open in a browser window somewhere so you can test your regular expressions out _first_ before applying them to your data!  We will use the power of regular expressions to search for particular patterns in a published volume of the correspondence of the Republic of Texas. We'll use regex to massage the information into a format that we can then use to generate a social network of letter writers over time. (You might want to give this tutorial a try, too: [Understanding Regular Expressions](http://programminghistorian.org/lessons/understanding-regular-expressions)).

What if you had *lots* of documents that you needed to clean up? One way of doing it would be to write a python program that applied your regex automatically, across all the files in a folder. *Optional advanced exercise*: [Cleaning OCR'd Text with Regular Expressions](http://programminghistorian.org/lessons/cleaning-ocrd-text-with-regular-expressions)

## Exercise 3

*Open Refine* is the final tool we'll explore in this module. This engine allows us to clean up our messy data. We will feed it the results from Exercise 2 in order to consolidate individuals (ie, 'Shawn' and 'S4awn' are probably the same person, so Open Refine will consolidate that information for us). This exercise also follows a tutorial originally written for [The Macroscope](http://themacroscope.org). [Here are the instructions](../supporting materials/open-refine.md).

For more advanced usage of Open Refine, as an optional exercise you can also try [The Programming Historian's Tutorial on Open Refine](http://programminghistorian.org/lessons/cleaning-data-with-openrefine). 


## Exercise 4

The *Stanford Named Entity Recognizer' is a program that enables you to automatically tag words in your corpus according to whether or not they are place names, individuals, and so on. The output can then be subsequently extracted and visualized, which you'll learn in Module 4. [Working with the Stanford NER](../supporting materials/ner.md).

## Optional exercises

[Introduction to the Command Line](http://programminghistorian.org/lessons/intro-to-bash)

[Counting and Mining Data with Unix](http://programminghistorian.org/lessons/research-data-with-unix)
