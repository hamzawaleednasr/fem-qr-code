# QR Code Card – Frontend Mentor Challenge

## Overview

This is a simple solution to the QR Code Card challenge from Frontend Mentor.
The goal was to build a small card component that displays a QR code, a title, and a short description.

## Approach

### HTML Structure

The layout is kept very simple and clear.
A main container (`.qr-card`) wraps everything. Inside it:

* A section for the image (`.qr-code`)
* A section for the text content (`.qr-content`) that includes a heading and a paragraph

This separation makes it easier to control styling and keeps the structure readable.

### Styling

The design focuses on clean spacing and alignment.

* The `body` uses flexbox to center the card both vertically and horizontally.
* The height is set to `100vh` so the card stays centered on the screen.
* A light background color is used to match the design.

The card itself:

* Has a white background
* Uses a small border radius for smooth edges
* Includes padding to create space inside the card
* Has a fixed width to match the challenge design

### Image

The image takes the full width of the card and has rounded corners to match the container.

### Typography

The project uses the Outfit font from Google Fonts.

* The title is bold and slightly larger to stand out
* The description uses a lighter color and smaller size for better readability

### Code Style

The CSS is written in a nested style for better organization, similar to SCSS.
This makes the structure easier to follow, especially for small components like this.

## What I Learned

* How to center elements properly using flexbox
* How to structure a small component in a clean way
* The importance of spacing and typography in simple designs

## Tech Used

* HTML
* CSS
* Google Fonts
