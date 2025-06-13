---
title: "vim, git, and how I won the war"
permalink: "/vim-git-and-how-i-won-the-war" 
excerpt: "Bro, do you even create?"
date: 2025-06-13
categories:
  - blog 
tags: 
  - creativity
  - writing
  - open-source
--- 

It's been said to me that monk's shouldn't write. Well, I think that's baloney.

If writing is in your blood, why not embrace it as part of the spiritual path? It can be an amazing ally. Writing has enabled me to share and commune with people, to clarify my mind, and to inspire myself and others on this journey. 

Lately I've been building a few things to support my writing. That's what this blog post is about - the tools that enable one to write. 

Abraham Lincoln said if he had an hour to cut down a tree, he would spend the first 45 minutes sharpening his axe. I've realised that in order to write, it's important to create good tools for writing. Good tools, and a good platform on which to host your voice. 

The tools I'll be talking about are a sharp text editor, version control using something called 'Git', and hosting your writing on an open-source platform called Github via Github Pages. 

These tools allow me to quickly create and edit text, save it incrementally with granular control over the changes using git, and then push that writing online, all in one seamless flow. 

Anyone can do this. You don't have to be some tech-wiz to figure it out. If it interests you, or if you know someone that would benefit from it, read on, or share this post. I'm not going to tell you *how* to do it, as there are a huge amount of resources online about that. I'm going to speak about *why* you would consider doing this if you're a writer or creator, and then share links to tools that I've found useful so you can go figure out how to do it yourself. That's the best way, as it's all about creating the right tools for each of us, to empower ourselves so that we can share our unique voice with others. Only we can do that ourselves, not others. 

---

## Text 

The first thing to talk about for writing is text itself. 

Text - such a simple thing - words on a page or screen. But how do we do it well?

Most people when they want to write (writers included) use word processors such as Microsoft Word. These types of tools deal in what is known as 'rich text'. They offer a wealth of formatting and layout options, and while they are excellent in document styling and visual appeal, they can often hinder workflow in that the wealth of options can be distracting, as well as hinder collaboration when conflicts arise from formatting discrepancies when sharing work.

There is another way. It's called 'plain text'. In a world filled with formatting options and multimedia elements, the virtue of plain text is its simplicity. Plain text is unformatted, ASCII-based text that prioritises content and structure over stylisation. Rich text includes fonts, colours, layout elements and so on, whereas plain text just focuses on the written word. 

Plain text is written in text editors, as opposed to word processors. Text editors like Vim, Sublime Text, or Visual Studio Code, provide a cleaner and simpler environment for writing, without the complexity of extensive formatting options, which come later (I'll talk about that). This allows you to focus on the word itself, and in my experience, this is infinitely more productive. 

So what are some advantages to plain text? Here's a few -

### Search and Access

Plain text is powerful in that you can effortlessly locate information within your document. It's simplicity makes it seamlessly integrate with search tools and software, making it very easy to zoom between passages and locate words or phrases. Plain text is also much more compatible across platforms and devices, working on pretty much any operating system and device, which means you can access it anywhere, on anything. 

### Robust and Portable

Plain text files are very small files. Their lightweight nature makes them extremely portable, meaning they are not easily corrupted, and reduces the risk of corruption when moving between different platforms. The same can not be said for proprietary file formats linked with Microsoft or Apple, which often face compatibility issues. By using plain text, you future-proof your work by guaranteeing it will remain accessible for years to come (plain text has been around since the advent of computing and will always be robust).

### Version Control

Perhaps the most powerful feature of plain text is how it seamlessly works with version control systems, which are processes of managing and tracking changes to a document. I'll speak more about version control in the section below on Git, but it's something all writers should learn how to use. Using plain text means that writers can easily track changes and revisions, which allows for granular control over your process of writing, and ease with collaboration if you want to collaborate on a project.  

There's more to say on plain text, but I'll leave it at that for now. There is a growing popularity amongst writers in using plain text, for the reasons I've just mentioned. Writers are starting to explore [markdown](https://commonmark.org/help/tutorial) in plain text, which is a lightweight markup language that is very versatile and dead easy to learn. It uses plain text formatting syntax to indicate headers, lists, emphasis and so on, and it's often all you need to write something simple (this post was written in markdown). 

If you want to venture into slick formatting you can make use of [LaTeX](https://www.latex-project.org) (pronounced 'lah-tek'). This is a more sophisticated markup language that has been traditionally used in scientific and technical writing, but writers make use of it to create amazing, professional looking documents, bibliographies, and so on. It's highly customisable, and once you decide on the formatting, you can simply get on with your writing and let LaTeX do the rest. 

As for the text editor I've chosen, I love [NeoVim](https://neovim.io/). NeoVim has been around for about 10 years, and is a fork of [Vim](https://www.vim.org/), which has been around since the 90s. It's a free and open-source text editor. You can configure NeoVim however you want, and with a few plugins it's a real powerhouse for writing. Some of the functionality I've built into my NeoVim configuration includes powerful searchability, autocompletion for spelling, dictionary and thesaurus options, syntax support for markdown and other languages, git integration, and very useful user interface tools to help me focus on my writing. It's amazing. There are other tools, but Vim is the best. 

---

## Git - Version Control

This brings us to version control. Before learning about [Git](https://git-scm.com/), I had no idea what version control was, or that it was even possible. Now I can't do without it.  Git is a [version control system](https://git-scm.com/book/ms/v2/Getting-Started-About-Version-Control) which allows writers to track changes, manage revisions, and collaborate with fellow writers with ease. It's kind of like an epic save button - but rather than just saving a file and not being able to see what the changes were, it can track exactly what you have changed - maintaining a granular history of every edit, enabling you to navigate through various iterations of your work. It takes snapshots of your writing, from the entire folder structure, down to changes to single word characters. Git was originally designed for programmers to keep track of code as they collaborated with other programmers, but all writers should be using git, 'cos it's perfect for writers. It's easy to get started wit git - just install it on your device, create your first git repository by initiating git within a folder, commit changes to your work, and then if you want to share it, you can share your git repository with others. It's all learnable here. You can learn the [basics](https://git-scm.com/book/ms/v2/Git-Basics-Getting-a-Git-Repository#ch02-git-basics-chapter) in an hour or two, which is all you need. Here's a little more about why it's so good for writers - 

### Tracking
It enables writers to document and review changes systematically, which helps you not only track your work, but helps you understand how your work is evolving. When you start to think of your work in terms of modification, you start to think about your creative process differently, unravelling secrets that I'll let you discover for yourself. 

### Backup

Because everything is being tracked as you write, there is no such thing as losing text anymore. You can't really accidentally delete anything or make a change you can't undo, as the version control acts like a safety net. You can always go back to an early version and recover what you deleted. 

### Experimentation

Git has what is known as 'branches'. Think of your work as the trunk of a tree. If you want to 'go out on a limb' and develop a part of your work in a certain way, you can create a 'branch' and create the work there, and then over time see if it fits back into what you are writing. If it does, you can merge that branch back into the main body of the work. This allows writers to create divergent versions of their work for experimenting and exploring without altering the main body of the work, and it can be useful for a whole host of things such as story structure, alternative narrative, structural changes, and so on. 

### Collaboration

Collaborative writing often suffers from conflicts when multiple authors or editors work in writing simultaneously. Git resolves this by letting multiple authors work together and version control their contributions by letting multiple authors merge their ideas and combine edits from different sources, ensuring transparency and a cohesive and unified work flow. Github is a great platform for this, which brings me to the final topic...

---

## Hosting

The final piece of the puzzle is hosting. 

Github is a platform that provides free hosting for and access to open-source projects. There is a wonderful venture called [Github Pages](https://pages.github.com/), which allows anyone to publish a website for free, with the source code and content of the website hosted by Github. Gone are the days of having to pay a hosting service for publishing your content - now you can build a little website a publish it, and have it hosted, all for free. 

The good news with this is that you don't have to learn how to code to build a blog or whatever. There are many themes you can choose from online where very generous developers share themes for websites that they maintain and let you use. This is how this blog was built. I used a template called 'Minimal Mistakes' which you can find [here](https://mmistakes.github.io/minimal-mistakes/). They have a great starter pack which you can populate with your content, upload to Github, and viola, you have your own blog or writing platform in no time. It is simply amazing that we can now do this so easily. Yes, it requires a little know-how, but it's not that hard, really. Github has excellent documentation by which to learn about Github Pages, as does the theme I've linked. Read the documentation and you'll be able to do it. 

---

So those are the tools I've chosen to do my writing. 

Text editors are the business. They are fast, and highly customisable so you can configure them however you want. Git is easy - once you know the basics, you can get started quickly with version controlling your writing, or whatever else you want to keep track of, and then you can store this information online for free via Github, or host your content via Github Pages. Happy days. 

Enjoy, and keep creating. 

- Peace. 
