# Responsive Card Design

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [HTML_usage](#html)
5. [CSS_usage](#css)


## Introduction

This project showcases a simple and responsive card layout that adjusts based on the device's screen size. Each card contains an image, a name, title, short description, and social media icons.

## Features

**Responsive Design**: The cards adjust to different screen sizes.
**Social Media Icons**: Each card includes links to Facebook, Twitter, and YouTube.
**Customizable Content**: You can easily update the card content such as the name, title, and description.

## HTML_usage

In this project, we use both **semantic** and **non-semantic** HTML elements. Below is a table that categorizes them:

| **Element**           | **Type**        | **Usage**                                                                                                                                               |
|-----------------------|-----------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
| `<html>`              | Semantic        | Defines the root of the HTML document.                                                                                                                 |
| `<head>`              | Semantic        | Contains meta-information about the document (like the title, links to stylesheets, etc.).                                                             |
| `<meta>`              | Semantic        | Provides metadata such as character set and viewport settings.                                                                                        |
| `<link>`              | Semantic        | Links to external resources like stylesheets.                                                                                                          |
| `<style>`             | Non-semantic    | Contains internal CSS for the page styling.                                                                                                            |
| `<body>`              | Semantic        | Contains the content of the document that is displayed in the browser.                                                                                 |
| `<figure>`            | Semantic        | Represents a piece of content (like an image or diagram) along with its caption.                                                                      |
| `<img>`               | Semantic        | Embeds an image in the page.                                                                                                                           |
| `<figcaption>`        | Semantic        | Provides a caption for the content of a `<figure>` element.                                                                                           |
| `<h3>`, `<h5>`        | Semantic        | Header elements for the card’s title and subheading.                                                                                                   |
| `<p>`                 | Semantic        | Defines a paragraph of text, used here for the description of each profile.                                                                            |
| `<a>`                 | Non-semantic    | Defines a hyperlink, used for the social media links.                                                                                                 |
| `<i>`                 | Non-semantic    | Used for displaying FontAwesome icons (which are not semantic elements).                                                                              |
| `<div>`               | Non-semantic    | A block-level container for grouping elements together.                                                                                              |

# CSS_usage

This table outlines the CSS properties and their usage within the profile card component styling.

| **CSS Property**            | **Value**                                              | **Usage**                                                                                                  |
|-----------------------------|--------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| `font-family`               | `sans-serif`                                           | Sets the default font family to sans-serif for the entire `body`.                                           |
| `background-color`          | `#212121`                                              | Sets the background color of the page to a dark shade (almost black).                                      |
| `height`                    | `95vh`                                                 | Sets the height of the body to 95% of the viewport height.                                                 |
| `display`                   | `flex`                                                 | Uses Flexbox layout to align children elements (like cards) in a flexible manner.                           |
| `align-items`               | `center`                                               | Vertically centers the flex items (cards) inside the body.                                                |
| `justify-content`           | `center`                                               | Horizontally centers the flex items (cards) inside the body.                                              |
| `flex-wrap`                 | `wrap`                                                 | Allows the flex items to wrap onto multiple lines if necessary.                                           |
| `color`                     | `aliceblue`                                            | Sets the text color for the body to a light blue shade.                                                   |
| `position`                  | `relative`                                             | Positions the `.card` element relative to its normal position.                                            |
| `display`                   | `inline-block`                                         | Makes the `.card` display as an inline-block, allowing multiple cards to sit next to each other.          |
| `overflow`                  | `hidden`                                               | Hides any content inside the `.card` that exceeds its bounds.                                              |
| `margin`                    | `10px`                                                 | Adds a margin of 10px around the `.card` element.                                                         |
| `min-width`                 | `250px`                                                | Sets the minimum width of the `.card` to 250px.                                                           |
| `max-width`                 | `310px`                                                | Sets the maximum width of the `.card` to 310px.                                                           |
| `width`                     | `100%`                                                 | Makes the `.card` take up 100% of the available width within its container.                               |
| `background-color`          | `#fff`                                                 | Sets the background color of the `.card` to white.                                                        |
| `color`                     | `#212121`                                              | Sets the text color inside the `.card` to dark gray.                                                      |
| `text-align`                | `center`                                               | Centers the text inside the `.card`.                                                                      |
| `box-shadow`                | `0 0 0.5px rgba(0, 0, 0, 0.15)`                       | Applies a subtle shadow around the `.card` for depth.                                                     |
| `box-sizing`                | `border-box`                                           | Ensures padding and borders are included in the element's total width and height.                          |
| `padding`                   | `15% 10% 0`                                            | Adds padding to the `.prof-image` for spacing around the profile image.                                   |
| `max-width`                 | `40%`                                                  | Limits the profile image's maximum width to 40% of the card's width.                                      |
| `vertical-align`            | `top`                                                  | Aligns the profile image at the top of its container.                                                     |
| `position`                  | `relative`                                             | Sets the position of the profile image to relative, allowing for additional positioning adjustments.       |
| `border-radius`             | `50%`                                                  | Makes the profile image circular by rounding the corners 50%.                                              |
| `padding`                   | `5% 10% 15%`                                           | Adds padding to the `.figcaption` for spacing around the text.                                            |
| `font-size`                 | `20px`                                                 | Sets the font size for the `.card h3` (name) to 20px.                                                     |
| `font-weight`               | `400`                                                  | Sets the font weight for the `.card h3` (name) to normal weight (400).                                    |
| `text-transform`            | `uppercase`                                            | Makes the text in `.card h3` (name) uppercase.                                                           |
| `line-height`               | `24px`                                                 | Sets the line height of the `.card h3` (name) to 24px for proper spacing.                                |
| `margin`                    | `3px 0`                                                | Sets the margin for the `.card h3` (name) to 3px top and bottom, and 0px for left and right.              |
| `font-weight`               | `400`                                                  | Sets the font weight for the `.card h5` (subtitle) to normal weight.                                      |
| `margin`                    | `0`                                                    | Sets the margin for the `.card h5` (subtitle) to 0.                                                       |
| `text-transform`            | `uppercase`                                            | Makes the text in `.card h5` (subtitle) uppercase.                                                       |
| `color`                     | `#888`                                                 | Sets the color of the `.card h5` (subtitle) to a light gray.                                             |
| `letter-spacing`            | `1px`                                                  | Adds letter-spacing of 1px to the `.card h5` (subtitle) for a more spaced-out look.                      |
| `margin`                    | `0 10px`                                              | Adds horizontal margin to `.icons a` for spacing between social media icons.                              |
| `font-size`                 | `30px`                                                 | Sets the font size for social media icons to 30px.                                                        |
| `text-decoration`           | `none`                                                 | Removes text decoration (underline) from social media links inside `.icons a`.                            |
| `color`                     | `#1877f2`                                             | Sets the color of the Facebook icon to its official blue.                                                 |
| `color`                     | `#1da1f2`                                             | Sets the color of the Twitter icon to its official blue.                                                 |
| `color`                     | `#ff0000`                                             | Sets the color of the YouTube icon to its official red.                                                  |
| `color`                     | `#155e8e`                                             | Changes the color of the Facebook icon to a darker shade on hover.                                       |
| `color`                     | `#0d8ddf`                                             | Changes the color of the Twitter icon to a different shade of blue on hover.                              |
| `color`                     | `#cc0000`                                             | Changes the color of the YouTube icon to a darker red on hover.                                           |
| `text-decoration`           | `none`                                                 | Removes text decoration (underline) for links inside the `.icons i a`.                                    |

## Summary
- **Body**: The body is styled with a dark background, centered content, and light text.
- **Card Layout**: The profile card features a centered layout with a circular image, heading, subtitle, and social media icons.
- **Icons**: Social media icons are styled with specific colors and change on hover for interaction.



## Installation
To get started with this project, simply clone the repository:

```bash
git clone https://github.com/KRajpal123/Responsive_Cards.git
cd responsive-card-design or respected folder

