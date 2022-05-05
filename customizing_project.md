# Customizing your CollectionBuilder Project

The contents of the `_data` and `_layouts` folders in your CollectionBuilder-GH project control important elements of your website's structure. In this step by step tutorial we will explore how this works as we customize your Yōkai Senjafuda exhibit. We will also practice reading [CollectionBuilder documentation](https://collectionbuilder.github.io/cb-docs/) directly in order to better equip you to independently develop CollectionBuilder-based exhibits.

## Customizing your Project's Visualizations and Home Page using `theme.yml`
The `theme.yml` file (found in your repository's `_data/` directory) you to allows customize the visualizations and home page of your project.

#### Change the image on your home page
1. Explore the images in your collection on the "Browse" page, and choose one with a "landscape" orientation (i.e., one that is wider than it is long). 
2. When you click on the image you like, the URL for the page should display the ID of the image in question, in the form ?id=coll007. 
3. If you can't decide, you can use the image coll007; while it isn't entirely a landscape image, I like the bright color it brings to my version of the home page.
4. Open `/_data/theme.yml` and enter your chosen image ID as the featured image in the HOME PAGE section of the document: `featured-image: coll007`

#### Modify the Subjects Word Cloud
1. Take a moment to explore the rest of the `theme.yml` document and consider how you think the rest of this document might control your website. 
2. Visit the **Subjects** page of your website and notice that the most prominient word is "unknown." Since this isn't a very useful word to have in your word cloud, let's get rid of it.
3. In the SUBJECTS PAGE section of `theme.yml`, enter unknown into `subjects-stopwords`, as follows: `subjects-stopwords: unknown`.

#### Modify the Map Page
1. Visit the **Map** page of your website and notice that the page opens to a spot on a map that is nowhere near Japan.
2. Navigate to Japan and notice that all of your map pins are centered in Kyoto. That isn't all that helpful--we'll remove the map later. But first, let's practice re-centering your map around Japan.
3. Google Kyoto. Pull up Google maps and right click (PC) or control click (Mac) on the red pin. As you can see, the coordinates will appear in a pop-up.
4. Paste these coordinates into the MAP PAGE section of `theme.yml`, updating the current `latitude: 46.727485 #to determine center of map` and `longitude: -117.014185 #to determine center of map` to your new coordinates. 
5. Try a new `zoom-level` that's a higher number, maybe 10 or 12. 

#### Explore through the rest of `theme.yml`
Skim the rest of the `theme.yml` document, and think about whether you might like to take advantage of some of the customization options it offers in a project some day. You can read more about your [Theme configuration options here](https://collectionbuilder.github.io/cb-docs/docs/theme/).

## Customizing Page Content using Configuration Files
Your repository's `_data/` directory includes a number of files beginning with `config` that are structured as CSVs (comma separated values, or plain text spreadsheet files) and that control aspects of the configuration of your website. You can read more about this in the [CollectionBuilder documentation](https://collectionbuilder.github.io/cb-docs/docs/customization/).

#### Remove Map and Location pages from your Project
The `_data/config-nav.csv` CSV controls what and in what order the links appear in your collection site’s navigation bar and footer navigation. If a page isn’t listed in `config-nav`, it won’t be directly discoverable! This is the fastest way to remove a page from your collection (rather than deleting the stub file in the `pages` directory).

The same is true if you create a new page–-don’t forget to add it to the nav! See see the instructions at [Add Page](https://collectionbuilder.github.io/cb-docs/docs/pages/add_page/) for more details.

Take a few minutes to read through the [documentation](https://collectionbuilder.github.io/cb-docs/docs/customization/config-nav/) on how the `config-nav.csv` file controls your menu bar. Based on this information, what will you need to do to delete the Map and Location pages from your website's navigation?

Open `_data/config-nav.csv` in Edit mode, and make the changes you have determined are needed. Check your website--if it has deployed, did the changes you made have the desired result? If there is a deployment delay, continue to the next section and then circle back.

## Edit your Home Page by modifying `home-infographic.html`
The `_layouts` folder contains the instructions for how each page is laid out. The most complex of these, and most important to understand if you wish to customize your project, is the layout for the homepage, which is in a file called `home-infographic.html`. 

Read the documentation about how the home page layout is constructed, [Editing the Home Page](https://collectionbuilder.github.io/cb-docs/docs/pages/home/), giving particular attention to the section entitled [Delete a Home Page Feature](https://collectionbuilder.github.io/cb-docs/docs/pages/home/#delete-a-home-page-feature).

Following the instructions, remove `Time` and `Locations` cards from `home-infographic.html`.