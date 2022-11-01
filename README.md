
# Hosting a resume on GitHub Pages

This project is for everyone who wants to upload their resume on GitHub Pages.

![GIF](https://github.com/sanksarraval/sanksarraval.github.io/blob/main/Assignment_2_Gif.gif)


## Purpose

This README is meant to explain you how to host your resume online as a static website.
After finishing this tutorial, you should be able to:

- Use Markdown and it's editor to create and edit your resume.
- Use jekyll to generate and edit a static website on your local computer.
- Use GitHub and Github Pages to host your resume online.

As you read through the instructions, you will see how practical steps align with the general principles of current technical writing, as explained in Andrew Etter's book **[Mordern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)** 

## Prerequisites
Hosting a resume on GitHub Pages requires the following:
- Install [Jekyll](https://jekyllrb.com/docs/) (a static site generator) on your local computer.
- A Markdown editor, this README was written using [readme.so](https://readme.so/editor)
- A [GitHub](https://github.com/) account.

You can read the [Jekyll Installation Guide](https://jekyllrb.com/docs/installation/#guides) for more information depending on your operating system.

## Instructions
#### 1) Make sure you have the prerequisites.

#### 2) Create your resume in Markdown.

Open your Markdown editor and start typing your resume.

Markdown is a lightweight markup language that adds and formats simple text documents. 
- It is portable, .md/.markdown files can be opened using any application.
- It is platform independent, you can use any operating system on any device to create markdown.
- It is future proof. 

The entire point of lightweight markup is to have human-readable code that everyone can write. This characteristic is pointed out by Andrew Etter in his book. 

He also adds that using Markdown also makes it easier for the users to contribute to the project.
For example, if you have a project which is modified by people with different skillsets(technical/non-technical). A lightweight, human-readable markup language makes it easier to make a purposeful contribution.

#### 3) Create a static website with Jekyll
Jekyll is a static site generator which takes content and a theme, and it processes everything into a working website. User can easily modify the website by updating the content and processing the site again.

Once you have a Markdown-formatted resume and Jekyll(ruby) installed on your computer.

Start by opening your computer's terminal and enter the following command:

```
jekyll new [name]
```
"name" is the folder you want to create that has all the jekyll files. 

In the terminal cd into the newly created folder and run the following commanda to build a static website.
```
cd [name]

#install gemfiles.
bundle install 

# Serve the website to localhost.
bundle exec jekyll serve
```
Go to localhost:4000 to access the website and play around with it.

Static websites don't require a lot of resources, you can host a static website practically anywhere. They have no server-side application dependencies and no databases, hence the size of the static website is very small. Hence, Andrew Etter recommends to generate a static site. 

#### 4) Pick a theme for the website
#### 5) Update your website with your resume
#### 6) Create a github repository for your website
#### 7) Upload your files to the repository

## More Resources

- A great Markdown tutorial can be [found here](https://www.markdowntutorial.com/)
- An overview of the basic syntax of Markdown can be [found here](https://www.markdownguide.org/basic-syntax/)
- *Modern Technical Writing*, by Andrew Etter, can be purchased from [Amazon](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

## Authors and Acknowledgements

//To be filled after peer review