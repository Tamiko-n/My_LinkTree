Here's a detailed description of the given HTML and CSS code:

---

# My LinkTree

My LinkTree is a personalized web page that displays links to various social media profiles and contact methods in a clean, visually appealing layout. This project leverages HTML and CSS to create an organized, stylish presentation of your online presence.

## Features

- **Profile Picture**: Displays a circular profile picture at the top of the page.
- **Social Media Links**: Provides buttons to various social media platforms and contact methods, styled with hover effects.
- **Responsive Design**: Centers content vertically and horizontally within the viewport.
- **Customizable Colors**: Uses a bright color scheme with hover transitions for interactive feedback.

## Code Structure

### HTML

The HTML file defines the structure of the web page. It includes references to a CSS file for styling and defines the content layout.

### CSS

The CSS file styles the elements defined in the HTML, making the page visually appealing and responsive.

## Explanation

### HTML

- **Metadata**:
  - `@page` and `@model` directives are used for ASP.NET Core Razor Pages, indicating the page model for the view.
  - `@ViewData["Title"]` sets the page title dynamically.

- **Content**:
  - `<div class="container">`: A wrapper div that contains all the page content, styled for centering and background color.
  - `<h1>` and `<h2>`: Headings for the page title and the user's name.
  - `<img>`: An image tag for the profile picture, with classes for styling.
  - Multiple `<a>` tags: Link elements styled as buttons, each linking to a different social media platform.

### CSS

- **Body Styling**:
  - Centers content both vertically and horizontally within the viewport.
  - Sets a light grey background color.

- **Container Styling**:
  - Centers the content within the page.
  - Applies a rounded border, padding, and a shadow for a card-like appearance.

- **Heading Styling**:
  - Sets the color and margin for headings.

- **Profile Picture Styling**:
  - Sets dimensions and applies a circular mask using `border-radius`.
  - Centers the profile picture and adds margin for spacing.

- **Button Styling**:
  - Sets dimensions, background color, text color, and border.
  - Centers the buttons and adds margin for spacing.
  - Applies a transition effect for a smooth color change on hover.

## Usage

1. **Replace Links**:
   - Update the `href` attributes in the `<a>` tags with your actual social media profile URLs and email address.

2. **Profile Picture**:
   - Replace `https://image_source.jpg` with the URL of your profile picture.

3. **Customize Styles**:
   - Modify the `styles.css` file to change colors, fonts, and other styles as desired.

4. **Deploy**:
   - Host the `index.html` and `styles.css` files on a web server or use a static site hosting service like GitHub Pages, Netlify, or Vercel.

This project provides a stylish and interactive way to present your online presence, making it easy for others to connect with you.
