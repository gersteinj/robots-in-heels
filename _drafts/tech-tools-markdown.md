---
layout: single
title: Introducing Markdown
categories: tech-tools
tags: tools markdown text-based
header:
  overlay_image: /img/code-header-luca-bravo.jpg
  overlay_filter: .6
  caption: Photo by Luca Bravo on [Unsplash](https://unsplash.com/photos/XJXWbfSo2f0)
  teaser: /img/code-header-luca-bravo.jpg
---
Markdown is designed to create properly formatted documents from files that are easy to read even as plain text. To do that, it borrows common conventions that have popped up over time for formatting emails and other plain-text writing.

Markdown is a markup language, which puts it in a middle ground between simple text and a full programming language. When processed through a tool that handles Markdown, a Markdown file will produce a properly-formatted HTML file. However, the original Markdown file is also an easy to read text document.

## Why I use Markdown

Markdown is portable, it's easy to work with, and it separates content from appearance. It's also used heavily throughout many of the tools I like.

#### Portability

I'm an open-source person at heart, and while I'll use closed-source tools when they're truly the best option, I try not to lock my content into a particular tool if I can reasonably avoid it. Markdown will work with pretty much any device. The HTML output can be viewed in a web browser. The source file is just a text file, and can be viewed in any text editor (Notepad and TextEdit are defaults, although there are plenty of others out there) or word processing program. This means I don't have to worry about what type of device somebody is accessing my files from. I don't have to worry about whether they have accounts with the right services, or what software they have installed. In all but the strangest circumstances, a given device will have what is needed to both edit and view my Markdown documents and their output.

#### Ease of Use

Markdown is really easy. Technically, I could achieve the same level of portability by writing HTML, but that's annoying. It distracts from the text and writing all the tags is a bit of a nuisance, especially in simpler text editors. Markdown uses the same shorthand I've been using for 20 years in emails and other plain text writing. It's also easy to read, because what you write looks like what your output will be.

#### Separating Content From Appearance

If I make slides in Powerpoint, Keynote, or Google Slides, content and appearance are intertwined. Same for other office software. For me, that's distracting. I have a hard time thinking about and writing good content when I'm also thinking about details of how it will look. Using Markdown, I write the content with its general structure in place - title, headers, lists, links, and images, but advanced formatting is handled separately. For simple documents such as descriptions of projects for my students, the basic formatting I get in this way is enough. To see what that looks like, [here's a copy of my Intro to Programming course description](https://github.com/UCMHS-Gerstein/IntroToProgramming17/blob/master/Documents/syllabus.md).

When I do want more advanced formatting, I can use CSS to format the HTML created by processing my Markdown files. It sounds complicated, but it's pretty easy - and I can reuse my CSS from document to document, giving me a reusable template for appearance that can be used for any type of document. Many of the tools that utilize Markdown have built-in CSS themes, so you don't even need to write your own if you don't want to.

#### Use In Other Tools

There are a lot of tools that utilize content written in Markdown formatting. I first started using Markdown when writing documentation on projects on [GitHub](https://github.com/). I make slides using either [reveal.js](https://github.com/hakimel/reveal.js/) or [Gitpitch](https://gitpitch.com), both of which will combine your content with a theme to produce slides in HTML format, making it easy to present and view from any device. I switched over to my Markdown-based slides because I needed a way to display code in slides, but now I've found that I just prefer them in general. This site is written in [Jekyll](https://jekyllrb.com/). I used to use Wordpress, but Jekyll suits me better.

## How To Use It

Formatting in Markdown is simple and looks a lot like the eventual output. You can **make text bold** by surrounding it with two sets of asterisks for `**emphasis**`. Creating *italic* text is just as simple, with a `*single set of asterisks*`. For those of us who work with code, Markdown is probably the easiest way to integrate code into writing. There are tools for incorporating math into writing in Markdown, which I know has been very frustrating for our math teachers since the switch over to Google Drive in our district.

```python
for x in range(100):
    print(f"Repetition {x + 1}.")
```

There are :sparkles: emoji :sparkles:, tables, headers, and more. Creating links, like this one [to a markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) is easy too: `[the text of the link goes in the brackets](http://google.com)`. That cheatsheet is a good overview of Markdown's formatting.

Want to try it? There are some great online tools for editing Markdown and seeing your output side-by-side with your writing. [Dillinger](https://dillinger.io/) and [StackEdit](https://stackedit.io/) are both browser-based markdown editors with a variety of import and export options. StackEdit is also usable offline.

If you are on a full computer and would like to use a text editor rather than a browser-based tool, there are some great options. Although you can edit a markdown file in Notepad or TextEdit, they're not really ideal for the task. I'd recommend a more modern text editor. My three favorites are more than is really needed just for Markdown, but they work well and all have some great features. If you want to try using some of the other tools I'll be writing about, all three are great for working with those tools. All are available for Windows, Mac, and Linux, and all but Sublime Text are free and open source.

My current favorite is [Visual Studio Code](https://code.visualstudio.com/). I've also spent a long time using [Sublime Text](https://www.sublimetext.com/), but I've come to prefer VS Code. [Atom](https://atom.io/) is also a solid choice.

Thanks for reading, and let me know if you decide to give Markdown a try! There will be more posts on some of my favorite tech tools soon, which will give you a better idea of how I use it.