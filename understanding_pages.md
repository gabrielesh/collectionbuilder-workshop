# Understanding CollectionBuilder pages

The `pages` in your CollectionBuilder project tell Jekyll what to render, or translate into a static HTML file. Therefore they are what we want to change if we are going to change any of the *content* of your project website. 

## The Final Result: An HTML-based Page

Open the About page within your demo project. Right click or control click on the page and choose "View Page Source" from the popup menu. Take a moment to explore the text that appears: this is the HTML that controls how text and images appear on the screen. This is the final version of the site that Jekyll *generates* from the instructions we give it. Take a moment to [learn more about HTML from this short tutorial](https://github.com/learn-static/foundations-1-html/blob/main/2-example.md).

## Elements of a CollectionBuilder page

Your `about.md` page contains three main elements:
* Page text, written in Markdown
* A header that tells Jekyll how to interpret the page
* Liquid includes, or snippets of code written in the Liquid language, that tell Jekyll to add specified material to the site.

We will spend the majority of our class time discussing Markdown, but first let's explore the second two elements of the page.

## Document header
When you click into `/pages/about.md`, you will see at the top of the page a header rendered as a table:
![Image of a header in GitHub](/images/about-header.png)

When you click into the `Raw` view, you can see that the underlying text a [YAML](https://en.wikipedia.org/wiki/YAML) file structure:
![image of the yaml header of the about page in raw text](/images/about-header-raw.png)

This YAML text instructs Jekyll what to call the page (`title: About`), what layout template to use (`layout: about` -- more on this later), and whether to include information at the bottom of the page (`credits: true').


## Liquid includes

Jekyll uses the Liquid templating language to process templates. Generally in Liquid you output content using two curly braces e.g. `{{ variable }}` This allows a website to build repeating elements with a minimal amount of code. 

Think of a directory with names, phone numbers, email addresses and pictures. If we can just create one template for how each person's information shows up on the page, that saves us a lot of time and coding -- and puts more emphasis on clean data than on repeated code. 

Our `about.md` page has several Liquid code snippets that start with 
<img src="https://github.com/learn-static/collectionbuilder-workshop/blob/main/images/include.png" width="100" /> 
See if you can guess what these code snippets do by reading them and comparing them to what appears on your About page on your front end website. You can [read more about Liquid include tags here](https://shopify.dev/api/liquid/tags/deprecated-tags#include).

## Markdown

Next we will add Markdown text to our `about.md` file and explore how Jekyll renders that Markdown as html. [Click here to continue to the Markdown tutorial where we will customize our About page](https://github.com/learn-static/collectionbuilder-workshop/blob/main/markdown.md).
