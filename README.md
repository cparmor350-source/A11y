# A11y

A11y (pronounced /æl.aɪ/) is a class project: a website with a mailbox for reporting other websites that are not accessible.

## How it started

The idea came from thinking about projects that let people report physical places that are not accessible, like a street without a ramp or a building with stairs and no elevator. We wanted to do something similar, but for websites: a mailbox where anyone can leave the URL of a site with problems and a short description of what they found.

## How it's built

It is a static page made only with HTML and CSS. It uses no JavaScript and no libraries. The only external resources are the typography, which comes from Google Fonts, and the images, which are hosted on Cloudinary. The project is two files: `index.html` for the content and `styles.css` for the styles. It is designed to be viewed on a computer.

The four accessibility cards (visual, cognitive, motor and hearing) flip using CSS 3D. Each card has two layers stacked on top of each other. When you hover over a card, or reach it with the Tab key, it flips and shows the back side, with examples of what is wrong and what is right.

The light and dark mode works with a hidden checkbox and CSS color variables, without JavaScript.

## What's missing

The light and dark mode is still in development. Because of our own technical limitations, it does not affect the cards yet, which always stay light. We would like to finish it in the future.

We would also like to expand the website to more languages.

## Figma prototype

We have included a photo of the Figma prototype!
