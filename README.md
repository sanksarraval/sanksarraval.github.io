
# Hosting a resume on GitHub Pages

This project is for everyone who wants to upload their resume on GitHub Pages.

![GIF](https://github.com/sanksarraval/sanksarraval.github.io/blob/main/Assignment_2_Gif.gif)


## Purpose

This README is meant to explain you how to host your resume online as a static website.
After finishing this tutorial, you should be able to:

- Use Markdown and it's editor to create and edit your resume.
- Use jekyll to generate and edit a static website on your local computer.
- Use GitHub and Github Pages to host your resume online.

As you read through the instructions, you will see how practical steps align with the general principles of current technical writing, as explained in Andrew Etter's book *Mordern Technical Writing* found in [More Resources](#more-resources).

## Prerequisites
Hosting a resume on GitHub Pages requires the following:
- Install [Jekyll](https://jekyllrb.com/docs/) (a static site generator) on your local computer.
- A Markdown editor, this README was written using [readme.so](https://readme.so/editor)
- A [GitHub](https://github.com/) account.

You can read the [More Resources](#more-resources) for more information on Jekyll Installation Guide depending on your operating system.

## Instructions
### 1) Make sure you have the prerequisites.
Make sure that you have Jekyll(ruby) installed on your computer, and a GitHub account.

### 2) Create your resume in Markdown.

Open your Markdown editor and start typing your resume.

Markdown is a lightweight markup language that adds and formats simple text documents. 
- It is portable, .md/.markdown files can be opened using any application.
- It is platform independent, you can use any operating system on any device to create markdown.
- It is future proof. 

The entire point of lightweight markup is to have human-readable code that everyone can write. This characteristic is pointed out by Andrew Etter in his book. 

He also adds that using Markdown also makes it easier for the users to contribute to the project.
For example, if you have a project which is modified by people with different skillsets(technical/non-technical). A lightweight, human-readable markup language makes it easier to make a purposeful contribution.

### 3) Create a static website with Jekyll
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

### 4) Pick a theme for the website

Once you have your locally hosted website ready, you can change how it looks by using different themes found in [More Resources](#more-resources).

Jekyll offers a robust theme system that enables you to use community-maintained templates and styles to customize the appearance of your site.

The resume was created using [jekyll-theme-hacker](#more-resources) which I found on [rubygems.org.](#more-resources) To apply the theme to your website, simply follow the instructions mentioned in the GitHub repository.

For more information about applying themes to your website you can go to Mike Dane's tutorial found in [More Resources](#more-resources).

### 5) Update your website with your resume
Once you have a static website which is locally hosted with a theme, now is the time to add/upload your resume onto the static website.

To do that, go the folder you created in step 3 and update the file titled:
```
index.md
```
Copy and paste your resume below the top content (known as ["front-matter"](https://jekyllrb.com/docs/front-matter/)) which is set between with 3 dashes. Save and close. 


### 6) Create a github repository for your website

[GitHub Pages](#more-resources) is a static site hosting service that produces a website by taking HTML, CSS, and JavaScript files directly from a repository on GitHub, optionally running the contents through a build process.

In order to host a website to GitHub pages, create a repository on your GitHub homepage named :
```
Username.github.io
```
GitHub uses Git which is a Distributed Version Control System (DVCS), which makes it possible to keep track of who made changes and when. This fits the prior point about collaboration made by Andrew Ette.  Additionally, using a DVCS for the storing  things like a project's ReadMe ensures that the file can be updated simultaneously with the code. 



### 7) Upload your files to the repository
The GitHub repository created in the previous step is empty, so to populate the repository with your static website:
- Go to your GitHub repository.
- Click on the green **code** button, which opens a drop down menu to clone the repository to your local computer.
- Add all the files from the folder you created in step 3 to the cloned repository.
- Make sure to commit your changes with the green commit button.

### 8) Celebrate for hosting your website successfully.
You should now be able to view your resume at: 
```
Username.github.io
```



## More Resources

- A great [Markdown tutorial.](https://www.markdowntutorial.com/)
- A great [Jekyll Installation Guide](https://jekyllrb.com/docs/installation/#guides) depending on your operating system.
- Different [themes](https://jekyllrb.com/docs/themes/) for Jekyll.
- [Jekyll-Theme-Hacker](https://github.com/pages-themes/hacker)
- [rubygems.org](https://rubygems.org/gems/jekyll-theme-hacker)
- [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages)
- Mike Dane's [tutorial](https://www.youtube.com/watch?v=NoRS2D-cyko&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=11&t=247s) about applying themes to Jekyll websites.
- *Modern Technical Writing*, by Andrew Etter, can be purchased from [Amazon](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

## Acknowledgements

- I would like to acknowledge the creators of the [Jekyll-Hacker-Theme](https://github.com/pages-themes/hacker) for creating an awesome remote theme for Jekyll.
- I would like to thank my group members: Ben, Zil and Aakash for proof reading and peer reviewing the ReadMe.


## FAQ

#### Why is Markdown better than a word processor?

Microsoft word is a wonderful choice for creating resumes and a horrible choice for updating resumes. Since you are constantly learning and experiencing, your resume also needs to be updated constantly.

If you have your resume in word or PDF, and you want to update it, you will have to contact that person and notify them that you have updated something and send your resume again.  

Hosting your resume on a website gives you the power to fix inaccuracies almost instantly and keep your resume in sync with the latest updates.

#### Why is my resume not showing up after hosting it on github pages.

Check the following things in your repository.
-  Name of the repository is: 
```
Username.github.io
```
- Check the file named:
```
index.md
```
- Make sure the front-matter is correct and your resume content is below the front matter.
 


