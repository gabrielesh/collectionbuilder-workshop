# Understanding markdown pages

Your about.md page contains three main elements:
* Page text, written in Markdown
* A header that tells Jekyll how to interpret the page
* Liquid includes, or snippets of code written in the Liquid language, that tell Jekyll to add specified material to the site.

We will spend the majority of our class time discussing Markdown, but first let's explore the second two elements of the page.

## Document header
When you click into `/pages/about.md`, you will see at the top of the page a header rendered as a table:
![Image of a header in GitHub](/images/about-header.png)

When you click into the `Raw` view, you can see that the underlying text has the structure of a yaml file:
![image of the yaml header of the about page in raw text](/images/about-header-raw.png)

## Liquid includes



Jekyll uses the Liquid templating language to process templates. Generally in Liquid you output content using two curly braces e.g. {{ variable }} 

This allows a website to build repeating elements with a minimal amount of code. 

Think of a directory with names, phone numbers, email addresses and pictures. If we can just create one template for how each person's information shows up on the page, that saves us a lot of time and coding -- and puts more emphasis on clean data than on repeated code. 

Jekyll uses the templating language Liquid to create templates. 
