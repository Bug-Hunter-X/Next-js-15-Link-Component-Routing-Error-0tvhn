# Next.js 15 Link Component Routing Issue

This repository demonstrates a problem with the Next.js 15 `Link` component where navigation to another page results in a blank page.

## Problem Description:

The application has two pages: `index.js` and `about.js`. A `Link` component in `index.js` is intended to navigate to `about.js`, but instead of rendering the `about.js` content, a blank page appears.

## Steps to Reproduce:

1. Clone the repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Navigate to the homepage and click on the link to go to the About page.
5. Observe that the About page appears blank.

## Expected Behavior

The About page should display the text "About Page".

## Solution:

The solution involves verifying the `pages` directory structure and ensuring that both `index.js` and `about.js` are properly placed.  In most cases, this issue is related to an incorrect file path or missing file.