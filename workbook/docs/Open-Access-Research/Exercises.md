# Module 1: Exercises

_All 4 exercises are on this page. Remember to scroll!_

## EXERCISE 1: learning markdown syntax with dillinger.io or prose.io

Have you ever fought with Word or another wordprocessor, trying to get things just _right_? Word processing is a mess. It conflates writing with typesetting and layout. Sometimes, you just want to get the words out. Othertimes, you want to make your writing as accessible as possible... but your intended recipient can't open your file, because they don't use the same wordprocessor. Or perhaps you wrote up some great notes that you'd love to have in a slideshow; but you can't, because copying and pasting preserves a whole lot of extra _gunk_ that messes up your materials.

The answer is to separate your _content_ from your tool:

This is where Markdown shines. Markdown is a syntax for marking semantic elements within a document explicitly, not in some hidden layer. The idea is to identify units that are meaningful to humans, like titles, sections, subsections, footnotes, and illustrations. At the very least, your files will always remain comprehensible to you, even if the editor you are currently using stops working or “goes out of business.”

Writing in this way liberates the author from the tool. Markdown can be written in any plain text editor and offers a rich ecosystem of software that can render that text into beautiful looking documents. For this reason, Markdown is currently enjoying a period of growth, not just as as means for writing scholarly papers but as a convention for online editing in general.

Popular general purpose plain text editors include TextWrangler and Sublime for Mac, Notepad++ for Windows, as well as Gedit and Kate for Linux. However, there are also editors that specialize in displaying and editing Markdown.

- Tenen and Wythoff, [Sustainable Authorship in Plain Text Using Pandoc and Markdown](http://programminghistorian.org/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown)

In this exercise, I want you to become familiar with Markdown syntax. There are a number of 'flavours' for Markdown, but in essence, they all mimic the kinds of conventions you would see in an email, using asterisks to indicate emphasis and so on. 

1. You will need this [cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). 
2. Go to [dillinger.io](http://dillinger.io) in a new browser window. This looks like a wordprocessor. The left hand side of the screen is where you write, the right hand side shows you what your text will look like. Dillinger 'saves' your work in your browser's memory. You can also point it to save to your dropbox, google drive, or github account (under the cogwheel icon. Do you have a dropbox etc account? You should set that up now, if you don't).
3. Write a short 200-500 word piece on why you are taking this class; what you hope to achieve here; the kind of digital experience you already have versus the kind of experience you wish to have.
4. Have at least two images (creative commons licensed for re-use - do you know how to find these?) and link outwards to four websites that are relevant to your piece.
5. In the 'document name' slot, make sure to add the file type .md at the end
6. 'Save to' your dropbox, github, google drive, or one drive account.

See how easy that was? Don't worry about submitting this.... yet.

> nb: the next time you go to dillinger.io the last document you were working on will load up. That's because dillinger stashes your work in the browser cache. If you clear your cache (from your browser's tools or settings) you'll lose it, which is why in step 6 I suggested saving to those various accounts.

## EXERCISE 2: setting up your github space

In this exercise, you will 1. get an account on github; 2. download and install git & the github desktop program; 3. setup a webpage using the gh-pages branch for a repo

1. Get an account with github: [Github](http://github.com/join)
2. Get the desktop 'gui' (graphical user interface; a program) for github [here](https://desktop.github.com/)
3. Work your way through the material below:

Please note:

+ git is a program that keeps snapshots of the contents of a designated folder; it watches for 'difs' or differences between one snapshot and the next.
+ _github_ is a webservice that allows you to keep track of those *versions* online, and what's more, to share those files with multiple collaborators, and _keep everyone's changes straight!_

Some key terms:

+ `repository`: a single folder that holds all of the files and subfolders of your project
+ `commit`: this means, 'take a snapshot of the current state of my repostiory'
+ `publish`: take my folder on my computer, and copy it and its contents to the web as a repository at github.com/myusername/repositoryname
+ `sync`: update the web repository with the latest commit from my local folder
+ `branch`: make a copy of my repository with a 'working name'
+ `merge`: fold the changes I have made on a branch into another branch (typically, either `master` or `gh-pages`)
+ `fork`: to make a copy of someone else's repo
+ `clone`: to copy a repo online onto your own computer
+ `pull` request: to ask the original maker of a repo to 'pull' your changes into their master, original, repository
+ `push`: to move your changes from your computer to the online repo

The historian Jack Dougherty has an excellent video and step-by-step instructions for getting set up with git and github. Please [read his steps](http://www.datavizbook.org/content/publish/host-html-code-ghpages/tutorial.html) and then watch his video:

<iframe width="560" height="315" src="https://www.youtube.com/embed/ZVejLE8qtOI" frameborder="0" allowfullscreen></iframe>

Please note: Dougherty's step 4 - he's copied and pasted the embed code from an interactive chart from Google Sheets. I want you instead to paste the embed code from a youtube video that captures something essential about yourself into the new file `index.html`. ALSO, make sure your repo/folder is called `demo` the way Dougherty's is.

Don't worry about submitting all this... yet.

>nb here are some more resources about git and github -[Github Guides](https://guides.github.com/) this explain in more depth some of the concepts behind Github. You could also try this tutorial, but it's not mandatory: [trygit](https://try.github.io/levels/1/challenges/1). This tutorial emulates using the version control software git itself (upon which Github is built) from the command line. Some more tutorials and resources[here](http://swcarpentry.github.io/git-novice/) and [here](http://software-carpentry.org/v5/novice/git/01-backup.html)).

## EXERCISE 3: setting up a simple open notebook (blog + personal github repo + notational velocity or notation, as appropriate)

In this exercise, you will create a new repository, and then set up your note taking software so that it saves your notes into your repository. This allows you to keep track of changes to your notes, and also to have an open backup online. An online version of your notes allows others to contribute to, and build from, your research! When people 'fork' or copy your repository, you can consider that a form of citation, as well. There are other benefits; we can chat about these.

1. The essence of an open notebook is a) it's easy to update b) it is under version control c) it's open and can be viewed/share online. We do this by storing notes from our notetaking software in a folder on our computer _which is also a repository that your github desktop software monitors._ Periodically, you will make 'commits' and 'sync' your local folder with the online version.
2. First, let's set up the folder/repository. We do this by going to github.com and logging in. Then, follow these [detailed instructions to create a new repository](https://help.github.com/articles/create-a-repo/). Call it 'my research notebook' or something similar. The github website will ask you if wish to initialize your repository with a readme.me file. Say 'yes'.
3. In your github interface on your computer (the desktop gui), select 'syncronize'. The repository you just created online is now on your computer (it will be a folder inside your github folder). Challenge: can you locate this folder? 
4. Download and set up Notational Velocity Alt (nvAlt) [(Mac)](http://brettterpstra.com/projects/nvalt/) or ResophNotes [(PC)](http://resoph.com/ResophNotes/Welcome.html). 
    a. In **notational velocity** you can change the settings so that each note is its own plain text file, and you can change the location where notational velocity saves. Go to preferences > notes > storage. Under 'recognize individual files with attributes' there are two lists. Hit the `+` under each list and add `md`. Then highlight all the other file extensions and hit `-` in turn. Under `read notes from folder` select the location of the folder/repository you created in the previous step. (A quick guide for nvAlt lives [here](http://bettermess.com/plain-text-primer-nvalt-101/)) 
    b. For **ResophNotes**, click on the cogwheel icon at the bottom right. Then select the storage tab. Tick the 'plain text file' radio button, and the 'save title in text file' option. Then, in 'file directory', change the path to your open notebook repository. Then click ok. Under 'options' click the 'enable markdown' radiobox. (A quick guide to Resophnotes lives [here](http://www.thewindowsclub.com/resophnotes-create-notes-synchronize-simplenote))
5. You now have a system in place for quickly taking notes, and for archiving them online on github. Let's take some notes. ** At this point, please put the piece you wrote for exercise 1 - the markdown version - into a new note in your notetaking software set up in the preceeding step. Then, make a new note with the direct URL to the demo repository you created in exercise 2. **

    Let's take a moment and think about how you take notes. Knowing that this software searches the titles of your notes, you might like to figure out a system for grouping notes in the title. I will create a new 'to read' note for instance by titling it  `.xtoread The Information James Gleick` 

    The bit with the `.toread` can be thought of as a tag. I'm not likely to use that particular pattern of letters anywhere else, so it makes a good tag to search on. Then, when I want to know what it is I have under that tag, I just type into the search field .xtoread and I get all my notes. 

6. Think of five tags you would often use in your research. Then, I would like you to make ten notes on this keynote by Tim Hitchock, [Big Data For Dead People](http://historyonics.blogspot.ca/2013/12/big-data-for-dead-people-digital.html) 

7. Once you've finished your notes (summarize! don't copy out text! include some bibliography in every note, so you know where your thoughts came from! you can copy your notes into your essay drafts as part of your writing if you've used summaries!) open your github software. It will now be showing that changes have happened in your repository. Commit the changes, then synchronize. Remember: you have to leave a message in the 'commit summary' box in order to commit.

8. Go to your repository online. Refresh the page. Your notes are now online. The final step is the 'narrative' of your notetaking. I often make blog posts to remind myself of what I was doing, what I was thinking, and to gather together links to useful resources etc. The narrative part of your open notebook ecology could be done as a new note, or a blog post. Your choice. Explain your tagging system, and link to your repository.

*Postscript to this exercise* Read James Baker's piece on ['Preserving Your Research Data'](http://programminghistorian.org/lessons/preserving-your-research-data) and, when you come to start working on your final project, see if you can apply his lessons to organizing your research.

## EXERCISE 4: forking & contributing to a repository 
In this exercise, I would like you to 

1. Fork the ['who-we-are'](https://github.com/craftingdigitalhistory/who-we-are) repo for this course.

2. Rename the `template.md` file with `<yourname>.md`. Change the file accordingly to edit in your name, and the location of your online HQ & open notebook as properly formatted markdown.

3. Make a pull request.

** before you start ** Now, when we're writing files from scratch (as opposed to making notes) you will need a good text editor. If you're on a Mac, you might already have something like TextWrangler. If you're on Windows, you're out of luck (notepad and wordpad are not useful to us; you can ask me why). A good text editor that works on both Mac and Windows is [Sublime Text](http://www.sublimetext.com/). This is free, though you will be reminded periodically to purchase a license to support development. If you find yourself using it a lot, you should. 

-----

## Advanced

It is possible to build a website with a single command from your open notebook markdown formatted pages. I use something called 'pykwiki' to generate my own [open notebook](http://shawngraham.github.io). Are you familiar with blogs? Blogs work by using a series of templates that dictate the look of the website, while dynamically building the website fresh each time some one visits (content is pulled out of a database). This is cool, but it can be hacked; it can be slow; and it puts a strain on computing resources. A website like my open notebook is generated by me, with a single command, whenever I want to update it. The version that lives online is just a series of static html pages: no dynamic loading, no vulnerabilities, easy to search, easy to archive, easy to share. 

You can try this out for yourself. If you're on a mac, you have the python programming language already installed. If you're on windows, you'll need to install it. Go on, I'll wait.

Then, install `mk-docs` ([instructions here](http://www.mkdocs.org/)). Since you already have a repository, navigate to it via your terminal or command line. Follow the instructions on that page to generate your site. Then, there's one command that will push your entire site to the `gh-pages` branch of your repository [instructions here](http://www.mkdocs.org/user-guide/deploying-your-docs/). Ta da!

Now, you might run into hiccups, depending on how your system is set up. That's why this part of the exercises is called 'advanced'. See if you can solve them. Re-write this exercise with all the tacit bits spelt out - put it into your open notebook. Often, a major part of being a 'digital humanist' is uncovering all the tacit bits of how our digital tools are affecting our lives...

-----

## Conclusion

Now that you've worked through all of that, I can tell you that there are many different ways you could approach the problem of making your research notes publically available. You could connect dillinger.io or prose.io directly to your github accounts, and always make your notes that way. The advantage of notational velocity and resophnotes is that search & note creation happen at the same time. There are also more features in both programs that let you cross-reference notes and so on. The key is to figure out a solution that works for you, *and* that lets you make your research open. 'What if I get scooped?' I hear you say. Well, let's talk about what [Caleb McDaniel has to say](http://wcm1.web.rice.edu/open-notebook-history.html). And we should also talk about the [smallest federated wiki](http://hapgood.us/2014/11/06/federated-education-new-directions-in-digital-collaboration/).