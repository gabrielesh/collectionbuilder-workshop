# Introduction to Markdown
This brief module provides instructions that give newcomers experience using Markdown, a markup language for adding formatting elements to plain text files. You can think of this module supporting your work by teaching you how to laydown the structural bones of a website. Before we begin using Markdown, let's clarify what is Markdown and give it context.

## What is Markdown?
Markdown is a plain text formatting syntax that helps to make writing for the Internet easier. It allows for a straight-forward way to structure text, links, images, code, tables, and lists within a plain text document without using tags like those used to markup plain text documents with HTML.

**Why use Markdown?**
- It can be fast to use while writing web page content
- It is used all over the place. It's a standard used by GitHub and other tools people use reguarly to communicate over the Internet.
- It converts easily to HTML
- It is future-friendly. This means Markdown within a plain text file that has the file extension `.md` can be opened and used by any current day or future computer program. There is no reason to worry about outdated verisons of your plain text files.

# Let's make a Markdown file using GitHub

## Create `index.md` within a GitHub repository
Before we can add Markdown to a plain text file, we need to make one within GitHub.

1. Create a new repository or use one that you've already made while working through [foundations-0-github](https://github.com/learn-static/foundations-0-github).
2. Once you are in the repository, click Add file and then Create new file.
![Figure describing where to create a new file. It has the description "Click here to create a new file.](/assets/images/markdown-001.png)
3. Type `index.md` into the box that is to the right of foundations-2-markdown. In your example the repository name will be whatever your titled it. Also, by taking this step you will have produced a Markdown text file. 
![Figure describing where to type the file name index.md. It has the description "Type index.md into this box."](/assets/images/markdown-002.png)
4. Navigate to Commit new file. It is at the bottom of the page.
5. Within the second input box that says "Add an optional extended description..." add a description about what you just did. If you are not sure how to make a commit, visit [foundations-0-github](https://github.com/learn-static/foundations-0-github) for instructions.
![Figure showing where to add an explaination before making a commit to GitHub. It also shows where to click to make a commit.](/assets/images/markdown-003.png)
6. Click Commit new file
7. After you have made your commit then you will be on your repository's home page. You should now see `index.md` in your list of files

## Open `index.md` to begin writing with Markdown
1. Click `index.md` to open it.
![Figure showing where to click and open the index.md file. There is an explaination to click directly on the file name.](/assets/images/markdown-004.png)
2. Click the pencil icon to edit `index.md`
![Figure showing where to click and edit the index.md file. There is an explaination to click directly on the pencil icon.](/assets/images/markdown-005.png)
3. You are now in edit mode and can begin writing.

# Let's write using Markdown

When writing on the Internet with Markdown, we use it's synax to format text in structured ways using...

- Headings
- Paragraphs and Line Breaks
- Emphasis, e.g. bold and italics
- Lists, e.g. numbered lists and unordered lists
- Images
- Hyperlinks
- Blockquotes

For this learning exercise, we will learn how to use headings, paragraphs, line breaks, emphasis, lists, images, and hyperlinks. To learn how to use other parts of the Markdown syntax visit [Markdown Guide](https://www.markdownguide.org/cheat-sheet/)

## How-to Add Headings
### About Headings
Markdown uses `#` to give structure to a web page's layout, and there are different heading levels to use while writing. Headings are organized in a hierarchical order that create sections on a web page. You must not breaking this order because it will make the readability of your web page content visuall difficult to read, and will have negative impact on the readability, navigation, and accessibility of your web page. To learn more about headings and web accessibility visit [A11y styleguide - Structure](https://a11y-style-guide.com/style-guide/section-structure.html)

```# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```
### Let's apply this to GitHub ###
1. Get into `index.md` edit mode that you previously made.
2. Add two headings using this code -- heading 1 and heading 2. You are welcome to use whatever text you like, but example text is available here.

Here are two examples that show Markdown in code form and then what Markdown looks like on a web page.

Markdown Example
```
# Yōkai Senjafuda: Stories about Ghosts and Monsters
## Senjafuda collections at the University of Oregon
```
Markdown Rendering Example
![Figure showing the rendering of heading 1 and heading 2.](/assets/images/markdown-006.png)

You will need to write in Markdown using the Edit file box. This example image shows where you would start writing in Markdown.
![Figure showing where to add headings.](/assets/images/markdown-007.png)


3. Click the Preview tab that is to the right of the Edit File tab. This will allow you to see how your headings will render on a web page.

![Figure showing a preview of how headings will render on a web page.](/assets/images/markdown-008.png)

## How-to Add Paragraphs and Line Breaks
### About Paragraphs and Line Breaks
Adding paragraphs does not require Markdown. You only just need to writing. Line breaks work just by using a keyboard return button.

Here is an Markdown code example that uses headings, paragraph, and line breaks together. The image below this code is an example of how it renders on a web page.

**Sample Paragraphs with Line Breaks**

```
This digital exhibition focuses on tiny slips of paper—senjafuda 千社札—that depict Japanese ghosts and monsters—yōkai 妖怪. Both senjafuda and yōkai have their roots in Japanese popular culture in the early modern period (17th-19th centuries), and both continue to cast a spell on viewers today.

The phenomenon of senjafuda dates back to the late 18th century. They were originally made by pilgrims to paste on the walls of temples and shrines as a sort of devotional graffiti. Later they became collector’s items, and by the middle of the 19th century they had become miniature masterpieces of woodblock printed art. Senjafuda depict a dizzying variety of themes with meticulous craftsmanship and vivid, stylish graphic design.

Yōkai simply means “monster,” but it’s best understood as referring specifically to monsters (and sometimes ghosts) as imagined in early modern Japan, particularly as depicted in wood-block prints. From Mizuki Shigeru to Studio Ghibli, from The Ring to Yōkai Watch, Japanese popular culture (including anime, manga, books, and film) is full of yōkai imagery.

The University of Oregon’s collection of senjafuda is one of the largest in the world. It includes many senjafuda depicting yōkai. This exhibit uses senjafuda to explore yōkai culture, and yōkai to explore senjafuda culture.
```

### Let's apply this to GitHub ###
1. Add these paragraphs and line breaks under the heading "Yōkai Senjafuda: Stories about Ghosts and Monsters" to the Edit tab
2. Now click Preview to see how it renders. It should look like the figure below.

![Figure showing how headings, paragraphs, and line breaks render.](/assets/images/markdown-009.png)


## How-to Add Emphasis
### About Emphasis with Italics and Bold ###
Emphasis can be used on text by applying italics or bold styles. Markdown uses the `*`sign to add styling controls.

`*` a single astrisk is what should be used to apply italics emphasis

`**` a double astrisk is what should be used to apply bold emphasis

`***` a triple astrisk is what should be used to apply italics and bold emphasis together.

To apply emphasis, you will need to add either `*`, `**`, or `***` at the beginning and end of the text that you would like to emphasize. Below is an example of how Markdown is applied to emphasize to text in code form and an image rendering the code within the context of a paragraph.

```
*senjafuda 千社札*
**yōkai 妖怪**
***The University of Oregon’s collection of senjafuda is one of the largest 
in the world. It includes many senjafuda depicting yōkai. This exhibit 
uses senjafuda to explore yōkai culture, and yōkai to explore senjafuda culture.***
```

Add this code to the Edit tab and then click Preview. The Markdown will render the text as illustrated in the figure below.

### Let's apply this to GitHub ###
1. Within the Edit file tab of `index.md`, apply italics, bold, and combined italics and bold to the words and paragraph identified in the above code. It should already be present for you to edit inside the Edit file tab.
2. Now click Preview to see how it renders. It should look like the figure below.

![Figure showing how Markdown emphasis renders.](/assets/images/markdown-010.png)


## How-to Add Lists
### About Lists ###
There are two types of lists to use with Markdown, ordered and unordered lists.

**Ordered Lists**
To make an ordered list use numbers to make it. For every new list item add it on a new line.

```
These are the digital collections used to making the digital exhibit.
1. The Star Collection
2. The Shōbundō collection
```

**Unordered Lists** 
To make an unordered list use `-` to make it. For every new list item add it on a new line.

```
These are categories of ghosts and monsters that are found in the digital exhibit.
- Kappas
- Oni
- Cats
- Foxes
- Tengu
```

### Let's apply this to GitHub ###
1. Within the Edit file tab of `index.md`, add these lists and the sentence above them under the heading "Senjafuda collections at the University of Oregon"

![Figure showing how lists render.](/assets/images/markdown-011.png)

2. Now click Preview to see how it renders. It should look like the figure below.

![Figure showing how lists render.](/assets/images/markdown-012.png)

## How to Add Links
### About Links
A link from a text file or document to another location or file is activated by clicking on a highlighted word or image on the screen.

The characters use to construct a link using Markdown inclue `[ ]` and `( )`.

- `[ ]` tells Markdown that you want to add a title for the link
- `( )` tells Markdown what is website or file the file directory path to go to when someone clicks on the link.

Making a link using Markdown looks like this:

```
[Yōkai Senjafuda Digital Exhibit](https://glam.uoregon.edu/yokaisenjafuda/page/welcome)
```

### Let's apply this to GitHub ###
1. Within the Edit file tab of ```index.md```, add a link to the Yōkai Senjafuda Digital Exhibit under the header "Yōkai Senjafuda: Stories about Ghosts and Monsters".

Your Markdown code should look like this:

![Figure showing how a link using Markdown looks before rendering.](https://github.com/learn-static/foundations-2-markdown/blob/main/assets/images/markdown-013.png)

2. Now click Preview to see how it renders. It should look like the figure below.

![Figure showing how lists render.](/assets/images/markdown-014.png)

## How to Add Images
### About Images
Images can be added with Markdown by adding `!`, `[ ]`, `( )`, and `" "` to create a string using an alterntative text description, an image file directory path on your web server or website address, and optionally adding a title after the URL in the paraenthesis. Something to note, it is best practice to always add an alternative text description. This supports people with visual impairments navigate the Internet through the use of text to speech computer capabilities.

- `!` tells Markdown that you want to add an image
- `[ ]` tells Markdown that you want to add an alternative text description
- `( )` tells Markdown what is the file directory path or website address your image file is located
- `" "` tells Markdown to optionally add a title

Here is an example of what the Markdown code looks when you add an image.

```
![Two-unit votive slip with double black border. Kabuki scene with young female dancing. Flames on kimono and falling around her. Decorative fan shapes at top with ren mark patterns and black text.](https://oregondigital.org/downloads/oregondigital:df728t07k "Two-unit votive slip with double black border. Kabuki scene with young female dancing. Flames on kimono and falling around her. Decorative fan shapes at top with ren mark patterns and black text.")
```

### Let's apply this to GitHub ###
1. Within the Edit file tab of `index.md`, add an image below the header "Senjafuda collections at the University of Oregon" using the information below.

**Image alternative text description:** Two-unit votive slip with double black border. Stone buddha sculpture with supernatural surroundings. Multiple white slips with black text at top.

**Image URL:** https://oregondigital.org/media/medium-images/c/5/oregondigital-df72bk65c.jpg

**Optional Image Title:** Two-unit votive slip with double black border. Stone buddha scultpure with supernatural surroundings. Multiple white slips with black text at top.

Here is an example of what your image code should look like.
![Figure showing where to add the Markdown image code to the Edit file tab.](/assets/images/markdown-015.png)

2. Click Preview to see how it renders. It should look like the figure below.

![Figure showing an image rendered within the Edit file tab.](/assets/images/markdown-016.png)

## How to Add Blockquotes
### About Blockquotes
Blockquotes allows you to offset text from the main text to be distinguishable and identified visually. They are typically used for long quotes. To make blockquotes we use the `>` symbol. In order to make a blockquote, you have to add `>` at the beginning of your quote.

There are three approaches to using blockquotes
**1. Using a single blockquote**
To add a single blockquote, add `>` at the beginning of the paragraph.

Here is how it looks in Markdown.
```
>Frederick Starr (1858-1933) was an American anthropologist at the University of Chicago who visited Japan frequently between 1904 and 1933. His primary interest during his stays in Japan was the social networks of collectors who were focused on objects associated with the early modern era, particularly collectors of traditional toys and senjafuda. Starr, his traveling companion Manuel Gonzales, and his interpreter Maebashi Hanzan were prominent fixtures at numerous senjafuda exchange meetings in the early 20th century, and Starr became so associated with the senjafuda scene that the press gave him the nickname “Professor Votive Slip” (Ofuda hakushi). Starr also wrote a short book about the history of senjafuda that was published in English in 1917 as The Nosatsu Kai and in Japanese (in a translation and adaptation by Fujisato Kōko) as Nōsatsu shi in 1921.
```

Here is how it looks when Markdown renders.
>Frederick Starr (1858-1933) was an American anthropologist at the University of Chicago who visited Japan frequently between 1904 and 1933. His primary interest during his stays in Japan was the social networks of collectors who were focused on objects associated with the early modern era, particularly collectors of traditional toys and senjafuda. Starr, his traveling companion Manuel Gonzales, and his interpreter Maebashi Hanzan were prominent fixtures at numerous senjafuda exchange meetings in the early 20th century, and Starr became so associated with the senjafuda scene that the press gave him the nickname “Professor Votive Slip” (Ofuda hakushi). Starr also wrote a short book about the history of senjafuda that was published in English in 1917 as The Nosatsu Kai and in Japanese (in a translation and adaptation by Fujisato Kōko) as Nōsatsu shi in 1921.

**2. Using blockquotes for multiple paragraphs**
Similar to adding a `>` at the beginning of each paragraph, when blockquoting multiple paragraphs you need to add `>` at the start of each paragraph and then the line between them.

Here is how it looks in Markdown.
```
>Starr amassed a huge collection of senjafuda both through his frequent attendance at exchange meetings and by procuring scrapbooks put together by other collectors. As a result of his persistence in acquiring senjafuda his collection not only thoroughly documents the years he was active in senjafuda (the 1910s to early 1930s), but also contains examples going back to the mid-19th century. After his death, his senjafuda collection was acquired by Gertrude Bass Warner (1863-1951), a traveler and collector of Japanese, Chinese, and Korean art and founder of the University of Oregon Art Museum (now the Jordan Schnitzer Museum of Art). The senjafuda mounted in scrapbooks (more than 50 of them) are now housed in Special Collections and University Archives (University of Oregon Libraries), while the loose slips are housed in the Jordan Schnitzer Museum of Art.
>
> Henry Smith has examined Starr's scholarly interest in Japan in detail, noting Starr's consistent attention to the religious dimension of culture—clearly visible in senjafuda, as this exhibition shows. Smith also notes that Starr's interest in “the social matrices in which these objects came to be collected, depicted, and exchanged in…distinctive subcultures of modern Japan” gives his work value in a contemporary context as well. But Starr had an eye for phenomena that appealed to a playful as well as a scholarly bent. When asked by a reporter for a Japanese newspaper what his interests were, he reeled off a list that began with kappa and tengu. It's no wonder, then, that yōkai are well represented in his senjafuda collection.
```

Here is how it looks when Markdown renders.
>Starr amassed a huge collection of senjafuda both through his frequent attendance at exchange meetings and by procuring scrapbooks put together by other collectors. As a result of his persistence in acquiring senjafuda his collection not only thoroughly documents the years he was active in senjafuda (the 1910s to early 1930s), but also contains examples going back to the mid-19th century. After his death, his senjafuda collection was acquired by Gertrude Bass Warner (1863-1951), a traveler and collector of Japanese, Chinese, and Korean art and founder of the University of Oregon Art Museum (now the Jordan Schnitzer Museum of Art). The senjafuda mounted in scrapbooks (more than 50 of them) are now housed in Special Collections and University Archives (University of Oregon Libraries), while the loose slips are housed in the Jordan Schnitzer Museum of Art.
>
> Henry Smith has examined Starr's scholarly interest in Japan in detail, noting Starr's consistent attention to the religious dimension of culture—clearly visible in senjafuda, as this exhibition shows. Smith also notes that Starr's interest in “the social matrices in which these objects came to be collected, depicted, and exchanged in…distinctive subcultures of modern Japan” gives his work value in a contemporary context as well. But Starr had an eye for phenomena that appealed to a playful as well as a scholarly bent. When asked by a reporter for a Japanese newspaper what his interests were, he reeled off a list that began with kappa and tengu. It's no wonder, then, that yōkai are well represented in his senjafuda collection.

**3. Using blockquotes that are nested within other blockquotes**
What is different about nested blockquotes compared to blockquoting multiple paragraphs is the addition of an extra greater than character. When nesting a quote within a quote use `>>`.

### Let's apply this to GitHub

Here is how it looks in Markdown.
```
>Starr amassed a huge collection of senjafuda both through his frequent attendance at exchange meetings and by procuring scrapbooks put together by other collectors. As a result of his persistence in acquiring senjafuda his collection not only thoroughly documents the years he was active in senjafuda (the 1910s to early 1930s), but also contains examples going back to the mid-19th century. After his death, his senjafuda collection was acquired by Gertrude Bass Warner (1863-1951), a traveler and collector of Japanese, Chinese, and Korean art and founder of the University of Oregon Art Museum (now the Jordan Schnitzer Museum of Art). The senjafuda mounted in scrapbooks (more than 50 of them) are now housed in Special Collections and University Archives (University of Oregon Libraries), while the loose slips are housed in the Jordan Schnitzer Museum of Art.
>
> >Henry Smith has examined Starr's scholarly interest in Japan in detail, noting Starr's consistent attention to the religious dimension of culture—clearly visible in senjafuda, as this exhibition shows. Smith also notes that Starr's interest in “the social matrices in which these objects came to be collected, depicted, and exchanged in…distinctive subcultures of modern Japan” gives his work value in a contemporary context as well. But Starr had an eye for phenomena that appealed to a playful as well as a scholarly bent. When asked by a reporter for a Japanese newspaper what his interests were, he reeled off a list that began with kappa and tengu. It's no wonder, then, that yōkai are well represented in his senjafuda collection.
```

Here is how it looks when Markdown renders.

>Starr amassed a huge collection of senjafuda both through his frequent attendance at exchange meetings and by procuring scrapbooks put together by other collectors. As a result of his persistence in acquiring senjafuda his collection not only thoroughly documents the years he was active in senjafuda (the 1910s to early 1930s), but also contains examples going back to the mid-19th century. After his death, his senjafuda collection was acquired by Gertrude Bass Warner (1863-1951), a traveler and collector of Japanese, Chinese, and Korean art and founder of the University of Oregon Art Museum (now the Jordan Schnitzer Museum of Art). The senjafuda mounted in scrapbooks (more than 50 of them) are now housed in Special Collections and University Archives (University of Oregon Libraries), while the loose slips are housed in the Jordan Schnitzer Museum of Art.
>
>>Henry Smith has examined Starr's scholarly interest in Japan in detail, noting Starr's consistent attention to the religious dimension of culture—clearly visible in senjafuda, as this exhibition shows. Smith also notes that Starr's interest in “the social matrices in which these objects came to be collected, depicted, and exchanged in…distinctive subcultures of modern Japan” gives his work value in a contemporary context as well. But Starr had an eye for phenomena that appealed to a playful as well as a scholarly bent. When asked by a reporter for a Japanese newspaper what his interests were, he reeled off a list that began with kappa and tengu. It's no wonder, then, that yōkai are well represented in his senjafuda collection.

### Let's apply this to GitHub
We are going to add 1 blockquote to `index.md`.

1. Within the Edit file tab of `index.md`, add a multi-paragraph blockquote within the ordered list under the item "The Star Collection".

Use this text to make the multi-paragraph blockquote.

>Frederick Starr (1858-1933) was an American anthropologist at the University of Chicago who visited Japan frequently between 1904 and 1933. His primary interest during his stays in Japan was the social networks of collectors who were focused on objects associated with the early modern era, particularly collectors of traditional toys and senjafuda. Starr, his traveling companion Manuel Gonzales, and his interpreter Maebashi Hanzan were prominent fixtures at numerous senjafuda exchange meetings in the early 20th century, and Starr became so associated with the senjafuda scene that the press gave him the nickname “Professor Votive Slip” (Ofuda hakushi). Starr also wrote a short book about the history of senjafuda that was published in English in 1917 as The Nosatsu Kai and in Japanese (in a translation and adaptation by Fujisato Kōko) as Nōsatsu shi in 1921.
>
>Starr amassed a huge collection of senjafuda both through his frequent attendance at exchange meetings and by procuring scrapbooks put together by other collectors. As a result of his persistence in acquiring senjafuda his collection not only thoroughly documents the years he was active in senjafuda (the 1910s to early 1930s), but also contains examples going back to the mid-19th century. After his death, his senjafuda collection was acquired by Gertrude Bass Warner (1863-1951), a traveler and collector of Japanese, Chinese, and Korean art and founder of the University of Oregon Art Museum (now the Jordan Schnitzer Museum of Art). The senjafuda mounted in scrapbooks (more than 50 of them) are now housed in Special Collections and University Archives (University of Oregon Libraries), while the loose slips are housed in the Jordan Schnitzer Museum of Art.
>
>Henry Smith has examined Starr's scholarly interest in Japan in detail, noting Starr's consistent attention to the religious dimension of culture—clearly visible in senjafuda, as this exhibition shows. Smith also notes that Starr's interest in “the social matrices in which these objects came to be collected, depicted, and exchanged in…distinctive subcultures of modern Japan” gives his work value in a contemporary context as well. But Starr had an eye for phenomena that appealed to a playful as well as a scholarly bent. When asked by a reporter for a Japanese newspaper what his interests were, he reeled off a list that began with kappa and tengu. It's no wonder, then, that yōkai are well represented in his senjafuda collection.

Here is an example of what the Markdown code looks like.
![Figure showing what Markdown for a multi-paragraph blockquote looks like within the Edit file tab.](/assets/images/markdown-017.png)

2. Click Preview to see how it renders. It should look like the figure below.
![Figure showing what Markdown for a multi-paragraph blockquote looks like within the Edit file tab.](/assets/images/markdown-018.png)


# Let's Make a Commit
Now we're ready to make a commit because you've just finished creating your first web page that used Markdown to structure text.

1. Go to the bottom of your `index.md` file while still in edit mode.
2. Find the "Commit changes" section
3. Title your commit and then add a description about what you are committing.

**Commit Text Example**

Commit title
>Adding text and images to the file

Commit description
>This is my first attempt at using Markdown with GitHub. I've added - Headings, Paragraphs and Line Breaks, Emphasis, e.g. bold and italics, Lists, e.g. numbered lists and unordered lists, Images, Hyperlinks, and Blockquotes using content from the University of Oregon's Yōkai Senjafuna digital exhibit.
