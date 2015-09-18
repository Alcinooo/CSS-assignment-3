# CSS Assignment 3 (Assignment 5)

This repo contains your assignment starter files, including one image.

1. **Fork** this repo (make sure you are logged into GitHub).

2. **Clone** your new repo so you have it on your hard drive. Remember to save it into the folder where you are keeping all your projects for this course. If you forgot how, [see the previous assignment](https://github.com/macloo/CSS-intro-with-GitHub).

3. Use your GitHub app to create a **local branch** named *gh-pages*. Switch to that branch and do all your work in that branch. Note that the hyphen and all lowercase letters are essential in the branch name *gh-pages*.

## Two goals

For this assignment, your focus is font families and responsive design.

Your first goal is to build two very good, very correct font stacks, one for everything and the other only for headings. One stack will be serif, and the other will be sans-serif. You can choose whether headings are serif and everything else is sans-serif, or the opposite. **You must include one Google font in each stack.** The total number of different Google font families used will be two.

Your second goal is to add appropriate and correct HTML and CSS to **make the page reformat itself for smaller devices,** especially mobile phones. This might take longer than the font families.

## index.html

Familiarize yourself with the file. You should understand all the HTML markup here. If you don't, ask!

You will need to **add** exactly two elements to the HEAD. One element is part of making the page responsive. (What is that element? **Hint:** Check Robbins, chapter 18.) The other element is required for using Google fonts.

Other than adding those two elements, DO NOT *change* anything in this file!

## main.css

Familiarize yourself with the file. You should understand all the CSS rules here and what they do. If not, ask!

You're not expected to change much in this file. There are two font-family declarations already in the file. **You will change *both* of those.** You will NOT add any new declarations for font-family.

You will **add** at least one @media query at the bottom of the CSS file. That will be necessary to make the page responsive.

You must NOT change the page layout EXCEPT within an @media query.

## Instructions

Remember to work only inside your *gh-pages* branch. You will edit the existing files *index.html* and *main.css*.

### Google fonts

Before you begin, be sure to read Robbins chapter 12 and watch the [Google Fonts video](https://www.youtube.com/watch?v=C7YL9biogCA&list=PLZFU-W6LLeecJuSQh20QUU_gCmS30sLTB&index=35). Also read all the text on the HTML page that's in this assignment.

You need to understand all the requirements of a **font stack** to do this assignment correctly.

1. Following the procedures shown in the video, choose two Google font families: one is for all the headings on the page, and the other is for everything else. Make sure they look good together. Make sure the one used in paragraphs has good *readability* at that size.

2. Add the appropriate element to the HTML HEAD element for your Google fonts.

3. **Edit the two existing font-family declarations** in the CSS file to include your Google fonts.

4. Add *at least one* other common font family to each of those declarations, and make sure it is a suitable companion to the Google font you have named. Note that **you might need to add two,** because a common font on Windows is not always a common font on Mac, and vice versa.

5. Add the correct generic at the end of each declaration. Note: One must be serif, and one must be sans-serif. Make sure you are choosing the best one to match the fonts preceding it in the declaration.

**Test your page** for all the font options by deleting, saving and reloading -- as many times as needed.

**TIP:** When you're selecting a font for the operating system you don't have, you can look it up on Wikipedia to see an image of how it looks. Not on Wikipedia? Then is it really a *common* font?

### Responsive design

There are two ways to design a page initially. One is to design it for a wide screen, a desktop monitor, and then use @media queries to adapt it to mobile. The other way is to design for mobile first, and then use @media queries to adapt it to wider screens.

This CSS file takes the first approach, even though "mobile first" is the preferred method nowadays. Therefore, your @media queries must adapt the design to look good on small screens.

The [video](https://www.youtube.com/watch?v=DYrpZRaX8RI&index=37&list=PLZFU-W6LLeecJuSQh20QUU_gCmS30sLTB) is strongly recommended.

1. There is an element you must add to the HEAD in the HTML file to make the page responsive. It doesn't do *everything* that's needed, but it plays an important part. It's in chapter 18 and in the video.

2. Write an @media query with one *breakpoint* (see Robbins chapter 18). The breakpoint will indicate the width at which the page changes from two columns to one.

3. In that @media query, specify any changes that are needed to make the page look like the image below on a phone (your fonts will be different). Changes will affect margins and widths of several selectors. Also, because the chart at the top of the page becomes unreadable at a small size, you must hide it. **Hint:** Use the *display* property.

![Phone preview - after responsive styles added](assets/phone.gif)

**Note:** In the CSS file, you must not *change* anything (except the two font-family declarations you already changed). You will *add* the @media query, and all adaptations will be handled there.

## Commit and sync

When everything is finished, save both files, commit and sync (or publish) to GitHub. Be sure to stay in your *gh-pages* branch for all steps.

## Check the rubric and submit in Canvas

Be sure to check the rubric in Canvas and **SUBMIT THE URL of your GitHub repo** there to complete this assignment!
