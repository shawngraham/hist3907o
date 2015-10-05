# Module 1: Exercises

_All 4 exercises are on this page. Remember to scroll!_

## EXERCISE 1: learning markdown syntax with dillinger.io or prose.io

Have you ever fought with Word or another wordprocessor, trying to get things just _right_? Word processing is a mess. It conflates writing with typesetting and layout. Sometimes, you just want to get the words out. Othertimes, you want to make your writing as accessible as possible... but your intended recipient can't open your file, because they don't use the same wordprocessor. Or perhaps you wrote up some great notes that you'd love to have in a slideshow; but you can't, because copying and pasting preserves a whole lot of extra _gunk_ that messes up your materials.

The answer is to separate your _content_ from your tool:

> This is where Markdown shines. Markdown is a syntax for marking semantic elements within a document explicitly, not in some hidden layer. The idea is to identify units that are meaningful to humans, like titles, sections, subsections, footnotes, and illustrations. At the very least, your files will always remain comprehensible to you, even if the editor you are currently using stops working or “goes out of business.”

> Writing in this way liberates the author from the tool. Markdown can be written in any plain text editor and offers a rich ecosystem of software that can render that text into beautiful looking documents. For this reason, Markdown is currently enjoying a period of growth, not just as as means for writing scholarly papers but as a convention for online editing in general.

> Popular general purpose plain text editors include TextWrangler and Sublime for Mac, Notepad++ for Windows, as well as Gedit and Kate for Linux. However, there are also editors that specialize in displaying and editing Markdown.

- Tenen and Wythoff, http://programminghistorian.org/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown

In this exercise, I want you to become familiar with Markdown syntax. There are a number of 'flavours' for Markdown, but in essence, they all mimic the kinds of conventions you would see in an email, using asterisks to indicate emphasis and so on. 

1. You will need this [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). 
2. Go to [dillinger.io](http://dillinger.io) in a new browser window. This looks like a wordprocessor. The left hand side of the screen is where you write, the right hand side shows you what your text will look like. Dillinger 'saves' your work in your browser's memory. You can also point it to save to your dropbox, google drive, or github account (under the cogwheel icon. Do you have a dropbox etc account? You should set that up now, if you don't).
3. Write a short 200-500 word piece on why you are taking this class; what you hope to achieve here; the kind of digital experience you already have versus the kind of experience you wish to have.
4. Have at least two images (creative commons licensed for re-use - do you know how to find these?) and link outwards to four websites that are relevant to your piece.
5. In the 'document name' slot, make sure to add the file type .md at the end
6. 'Save to' your dropbox, github, google drive, or one drive account.

See how easy that was? Don't worry about submitting this.... yet.


## EXERCISE 2: setting up a domain (webspace) of your own with reclaimhosting.com, or another service

I believe that it is of fundamental importance that you have webspace of your own, as an HQ for your scholarly identity online. [reclaimhosting.com](http://reclaimhosting.com) is one option that I would recommend; it currently costs about $25 for a year's worth of hosting. If you purchase a domain with them, they have a number of one-click installs for all kinds of useful platforms for the kind of work we do as digital historians.

There are other alternatives. For many years, I have managed quite well with a free Wordpress.com account as my HQ on the web (http://electricarchaeology.ca). You could set yourself up this way as well. 

Another option is to use a free github account. You could use [github pages](https://pages.github.com/). 

*In fact, **everyone** needs to have a github account* whether or not you use it as your online base. [Set up an account now](http://github.com/join). 

There are other solutions out there too. **Talk with me if you have privacy concerns, and we'll figure out what could work for you** 

1. Choose a solution and set up your scholarly HQ. 
2. Open up dillinger.io again; see how your piece from Exercise 1 loads up? Select 'export as'... and, consulting your solution's documentation, get that document online. If you're using github as a solution, you can push your document **directly** to your github repository. Github natively understands markdown, and styles it appropriately for the web. For other platforms, export as html is probably your best bet. You could copy and paste the html itself into a blog post, for instance.

If you look at that [programming historian tutorial again](http://programminghistorian.org/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown) the authors take you through the process of installing a piece of software on your machine called 'Pandoc'. You work with Pandoc on the command line on your computer (on Windows computers, search for 'cmd' and run that; on Mac, look for 'terminal' under your applications). With a single line of code, you can convert your Markdown documents into Word, into Pdf, into Html... it's extraordinarily useful. Take some time to read through this tutorial. 

## EXERCISE 3: setting up a simple open notebook (blog + personal github repo + notational velocity or notation, as appropriate)

In this exercise, you create a repository, and then set up your note taking software so that it saves your notes into your repository. This allows you to keep track of changes to your notes, and also to have an open backup online. An online version of your notes allows others to contribute to, and build from, your research! When people 'fork' or copy your repository, you can consider that a form of citation, as well. There are other benefits; we will discuss these in class.

1. For this exercise, I want you to do view some of these [Github Guides](https://guides.github.com/) to get the concepts behind Github. You could also try this tutorial, but it's not mandatory: [trygit](https://try.github.io/levels/1/challenges/1). This tutorial emulates using the version control software git - upon which Github is built. The 'hub' part is for keeping track of the stuff that 'git' tracks, but online, to facilitate sharing and so on. (Indeed, all of what follows can be done from the command line. For those who want to try that, a good tutorial & resource may be found [here](http://swcarpentry.github.io/git-novice/) and [here](http://software-carpentry.org/v5/novice/git/01-backup.html)). 
2. When you sign up for a github account, one of the things that can be set up is a user interface that handles all the commands. [Here's the download for Windows](https://windows.github.com/) and [here's the download for Mac](https://mac.github.com/). Download and set up the appropriate version on your computer.
3. Now you're going to set up your own open note book by creating a new repository. Go to github.com and login. Then, follow these [detailed instructions to create a new repository] (https://help.github.com/articles/create-a-repo/). Call it 'my research notebook' or something similar. 
4. In your github interface on your computer, select 'syncronize'. The repository you just created online is now on your computer (it will be a folder inside your github folder). Challenge: can you locate this folder? 
5. Download and set up Notational Velocity [(Mac)](http://notational.net/) or ResophNotes [(PC)](http://resoph.com/ResophNotes/Welcome.html). In **notational velocity** you can change the settings so that each note is its own rtf file, and you can change the location where notational velocity saves. Change to rtf, and make it save in your open notebook repository. For **ResophNotes**, click on the cogwheel icon at the bottom right. Then select the storage tab. Tick the 'plain text file' radio button, and the 'save title in text file' option. Then, in 'file directory', change the path to your open notebook repository. Then click ok.
6. You now have a system in place for quickly taking notes, and for archiving them online on github. Let's take some notes.

Let's think about how you take notes. Knowing that this software searches the titles of your notes, you might like to figure out a system for grouping notes in the title. I will create a new 'to read' note for instance by titling it 
  
  > .xtoread The Information James Gleick 

The bit with the .toread is a tag. I'm not likely to use that particular pattern of letters anywhere else, so it makes a good tag to search on. Then, when I want to know what it is I have under that tag, I just type into the search field .xtoread and I get all my notes. 

8. Think of five tags you would often use in your research. Then, I would like you to make ten notes on this keynote by Tim Hitchock, [Big Data For Dead People](http://historyonics.blogspot.ca/2013/12/big-data-for-dead-people-digital.html) 

9. Once you've finished your notes (summarize! don't copy out text! include some bibliography in every note, so you know where your thoughts came from! you can use your notes as part of your writing if you've used summaries!) open your github software. It will now be showing that changes have happened in your repository. Commit the changes, then synchronize.

10. Go to your repository online. Refresh the page. Your notes are now online. The final step is the 'narrative' of your notetaking. I often make blog posts to remind myself of what I was doing, what I was thinking, and to gather together links to useful resources etc. The narrative part of your open notebook ecology could be done as a new note, or a blog post. Your choice. Explain your tagging system, and link to your repository.

*Postscript to this exercise* Read James Baker's piece on ['Preserving Your Research Data'](http://programminghistorian.org/lessons/preserving-your-research-data) and, when you come to start working on your final project, see if you can apply his lessons to organizing your research.

## EXERCISE 4: forking & contributing to a repository 
In this exercise, I would like you to 

1. Fork the syllabus for this course.

2. Add your name, and the location of your online HQ & open notebook as properly formatted markdown.

3. Make a pull request.


-----

Now that you've worked through all of that, I can tell you that there are many different ways you could approach the problem of making your research notes publically available. You could connect dillinger.io or prose.io directly to your github accounts, and always make your notes that way. The advantage of notational velocity and resophnotes is that search & note creation happen at the same time. There are also more features in both programs that let you cross-reference notes and so on. The key is to figure out a solution that works for you, *and* that lets you make your research open. 'What if I get scooped?' I hear you say. Well, let's talk about what [Caleb McDaniel has to say](http://wcm1.web.rice.edu/open-notebook-history.html). And we should also talk about the [smallest federated wiki](http://hapgood.us/2014/11/06/federated-education-new-directions-in-digital-collaboration/).