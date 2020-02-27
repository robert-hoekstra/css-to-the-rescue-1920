
# Css to the rescue! 🦸🏼‍♂️
![https://robert-hoekstra.github.io/css-to-the-rescue-1920/](https://github.com/robert-hoekstra/css-to-the-rescue-1920/blob/master/images/poster.jpeg?raw=true)
 This course is part of the Web Development Minor.
 The goal of the course is to learn all the unknown parts of CSS

## ToC
- [Css to the rescue! 🦸🏼‍♂️](#css-to-the-rescue---------)
- [The assignments](#the-assignments)
  * [The assignment I chose](#the-assignment-i-chose)
  * [The contexts I added to the project](#the-contexts-i-added-to-the-project)
  * [Two restrictions I picked](#two-restrictions-i-picked)
  * [The *Selector First* CSS Methodology](#the--selector-first--css-methodology)
- [Progress](#progress)
  * [Resources](#resources)

# The assignments
![assignments](https://github.com/robert-hoekstra/css-to-the-rescue-1920/blob/master/images/assignment.jpg?raw=true)

We think the web is an exciting place. In recent years CSS has become an incredibly powerful language. Many of its possibiliets haven’t been explored in full yet. Some parts of the CSS spec are largely ignored, while others are so big and powerful that we don’t yet understand what we can do with it. To you the fun task of exploring the uncharted parts of CSS.

On this page we explain the assignments, the contexts, the restrictions and the methodlogy we want you to work with.

## The assignment I chose

- (x) Responsive restauraunt menu [Here’s some raw HTML you may use](../assignments/menu.html)

_You can use the provided content and HTML, or you can create your own. Of course you are allowed to change the HTML when needed._

## The contexts I added to the project

You have to add one extra contexts to your site

- [x] print-stylesheet

## Two restrictions I picked
![rules](https://github.com/robert-hoekstra/css-to-the-rescue-1920/blob/master/images/rules.jpg?raw=true)

You have to work with _at least_ two of these restrictions.

- [x] Two colours
- [x] Responsive without media queries
- [x] When SVG meets CSS: Shapes / Masks / SVG


## The *Selector First* CSS Methodology
![code](https://github.com/robert-hoekstra/css-to-the-rescue-1920/blob/master/images/code.jpg?raw=true)

I _have_ to work with the so called *Selector First* CSS Methodology. This means that I _have to_ use a wide variety of CSS selectors. ID’s are only allowed to trigger the `:target` selector. If I really need them, I am allowed to use a few classes. In order to differentiate between.

# Progress

## Table of Contents
  * [Day 1](#day-1)
  * [Day 2](#day-2)
  * [Day 3](#day-3)
  * [Day 4](#day-4)
  * [Day 5](#day-5)
  * [Day 6](#day-6)

## Day 1
Today I chose my assignment and picked out the constraints and contexts that make a nice challenge together. I want to make an online restaurant menu that is dynamic. It's visual behaviour changes upon the battery level and time of the day.

I once made a very neat restaurant menu in Adobe Photoshop. However a lot of problems arise with that method. For instance, if prices change or menu items need to be added or removed the whole layout is broken within a few touches.

I want to learn how to make a restaurant menu that is progressive enhanced and fun to use. But also easy to manage if changes need to be made.

That's why I chose to also make a print stylesheet. So that the owner of a restaurant can actually print a menu that looks really good!

I dived into the HTML and corrected a lot of errors out of it. I want to keep the html semantically intact but I don't want to bloat the html with classes and id's. But the usage of JavaScript should be none to very minimal.

## Day 2
Today I dived into the world of Grid and Flex. I used grid sometimes and flex almost never. Just to style some navigation bars but that's it. I chose to use flex because that way I think I can make a menu that is responsive for all types and sizes of screen.

Display flex worked out nicely and after that I began to style all the content to a fitting online menu. I added white content, borders, animation, markup for text and I add a form to the menu in order to create interaction.

I want to dive into: animations and forms. I want to make both of 'm exciting. More exciting than normal animations and forms.

I came across the so called checkbox hack. However I am going to distantiate myself from the method as I see it as a cheap way to create an event listener. And it bloats your html markup with unsemantic HTML. Something that is not a good practice at all if you want an other developer to work on your project in the future!

I now have a product that could go live. It is styled in a way that it is readable and useful for the user. However the next 4 days are going to be all about the craziness CSS has to offer without being bound to the usage of JavaScript.


## Day 3
Today I added a form that makes it impossible for users to send in feedback. This restaurant clearly does not want to receive any feedback. I also implented the checkbox hack to display all the vegan options this restaurant has to offer...

## Day 4
Today I added a catch frame to the menu to check if people are actually old enough to check the menu. The user needs to enter a number above 18 in order to get rid of the display. It is amazing to see what one can build without the use of a single line of JavaScript!

## Day 5
Today I worked on my JavaScript application and my Weekly Nerd Repository. For tomorrow I need to make a print stylesheet to print my online menu.
## Day 6
Today I refactored my code and added a print stylesheet to the product. I discovered a feature in which you can emulate a print view in Google Chrome. That made it a lot easier to actually inspect elements and make a good stylesheet for printing purposses! I also learned some card tricks but that's something else.

# Explore!
New explorations in the world of CSS

## What worked
This is a short list of stuff that is new to me and worked!

* hyphens
* word-wrap
* transform
* translate
* keyframes
* Blend Screen
* Flex
* Flex Wrap
* SVG Background
* Text-Transform
* nth- of type
* :before
* :after
* :focus
* :target
* :first-type-of
* :input type=text
* :valid
* :: selection
* :: Out-of-Range
* :: In-Range
* ::first-letter
* ~ (checkbox hack)
* @media print
* content property;
* page-break-inside: avoid;
* Animated Cursor FTW!
* Dominant-Baseline for moving svg text level on a horizontal axis

## What did not work (or make it to the end product)
This is a short list of stuff that is now to me but did not work!

* Making the menu a cube that can be moved
* Making a design based on the weather without JavaScript
* Making a design based on battery level without JavaScript
* Spinning the whole page 360 degrees in 3600 seconds. The idea was to put menu items somewhere based on the time. So in order to read lunch easily one need to wait a few hours so the text will be level again.
* Animating text (switching between font-families or sizes is not allowed.)
* Make an border that acts like a retro lightbulb sign. Only lighting 1 bulb at a time in a circle did not work out.

## Credits
Special thanks to Vasilis & Vitaly for their css inspiration!
## Resources
[Flex](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
[Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
[Animations](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations)
[Print Stylesheet Emulate](https://developers.google.com/web/tools/chrome-devtools/css/print-preview)
[Print Stylesheet](https://www.smashingmagazine.com/2011/11/how-to-set-up-a-print-style-sheet/)
