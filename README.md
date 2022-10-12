# Wedding Site Template

A simple, responsive, easy-to-edit wedding website template.

[Demo](https://jasonlutterloh.github.io/wedding-site-template/)

## Overview

The project is comprised of the following:

- `index.html` - Content
- `theme.css` - CSS Styling
- `/img` - Images
- `/js` - External Scripts (Smooth-scrolling)
- `/icons` - FontAwesome's Icon Library (See below for more details)

## Page Components

### Header

The template is designed with an initial full viewport header with background image. The header is responsive but you may want to play want around with your image to make sure it looks good on a mobile phone.

#### Header Instructions

To override the stock image, you have two options:

1. Replace `img/hero.jpeg` with your own image (but keep the filename the same).
2. Replace the header `background-image` file path in `theme.css` with the path to your image.

### Details

The template is initialized with a few "Details" sections (When, Location, Lodging, etc). Change these to whatever you'd like using the HTML.

### Iconography

The icons are provided by [FontAwesome](https://fontawesome.com/icons?d=gallery).

#### Icon Instructions

To add/change icons, find the icon you like on their page and then use the following syntax to insert:

```<i class="fas fa-[ICON ID HERE]"></i>```

#### Versioning

I would've liked to include this library using a CDN instead of including the files locally but FontAwesome requires an email address to use their CDN so you're on own configuring that.

### RSVP

The template comes with a blank RSVP section as everyone likes to do this differently (and not many people create their own methods of sending data).

I recommend creating the RSVP in Google Forms and embedding the form in an iFrame (provided by commented out). However, your free to handle this however you'd like.

## Technical Details

This template makes use of a few external scripts but doesn't rely on any build scripts or anything like that. Big thanks to the following:

- [SmoothScroll](http://github.com/cferdinandi/smooth-scroll) - RSVP Scroll Functionality
- [FontAwesome](https://fontawesome.com) - Iconography
- [Google Fonts](https://fonts.google.com/) - Fonts (Caveat and Quicksand)
