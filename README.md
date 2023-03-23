# Crispy Clean CSS

## Background

It’s time to put your CSS fingers to the test with a real, modern UI!

Before you start coding, complete this quick [tutorial on flexbox](https://flexboxfroggy.com/).

Then check out this excellent jumpstart on [common layouts using grids](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Realizing_common_layouts_using_CSS_Grid_Layout) from MDN.

## Your task

Now we're going to use Flexbox and Grid, along with many other nifty CSS features, to make a crispy clean web interface for the imaginary cleaning business Crispy Clean Ltd. It's got to be eye-catching, professional, responsive and most importantly, crispy clean.

The image below shows the design you will be recreating. Content is contrained within containers and the main content in the page is arranged in a typical 12-column grid. On mobile the grid is replaced by a flex column, the nav links become hidden by a hamburger menu and some of the page sections wrap in order to flow nicely vertically.

![demo_gif](/assets/crispy_clean_css_demo.gif)

The web page is made up of 6 sections from top to bottom:
- Navigation Bar
  - links on desktop, hamburger menu on mobile
  - links animate into view when toggled on mobile
- Hero section
  - text left and image right on desktop, image top and text below on mobile
- Client testimonials
  - cards animated to wobble in opposite directions on hover
- FAQs
  - expandle accordian with custom list icons (hint: is there an element for that?)
- Email contact form
  - with labels and correct input types
- Footer

## Objectives

To complete this exercise make sure you achieve the following objectives:

- Recreate the design spec using vanilla CSS, not a CSS framework.
- Build the desktop layout using CSS `grid` and `flex` display properties.
- Enhance the layout with `@media` queries that re-`position` the menu on mobile and animate the hamburger.
- Make your CSS modular and DRY (i.e. use CSS variables).
- Use correct HTML elements in page sections for web accessbility.

## Extra credits

- Experiment with a CSS framework such as [Tailwind](https://tailwindcss.com/docs/installation/play-cdn).
- Move the contact form to a modal that opens when clicking Contact in menu.
- Implement a dark mode media query that adjusts CSS accordingly.
- Add a notifications widget that displays toasts which can be triggered from JS.
- Replace the hero SVG image with CSS shapes (hint: CSS `clip-path`).
- Replace the Hero section image with an embedded mp4 video.
