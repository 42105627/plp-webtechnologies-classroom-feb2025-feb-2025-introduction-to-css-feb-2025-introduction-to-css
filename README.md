# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨


1. HTML FILE
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Styled Webpage</title>
  <!-- Linking to the external CSS file -->
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Header Section -->
  <header>
    <h1 id="main-heading">Welcome to My Styled Webpage</h1>
  </header>

  <!-- Introduction Section -->
  <section class="intro">
    <h2>Introduction</h2>
    <p>This page demonstrates the use of CSS for styling elements. It includes a variety of selectors, spacing, and font styles.</p>
    <img src="joel pic.jpg" alt="Sample Image" class="styled-image">
  </section>

  <!-- Content Section -->
  <section class="content">
    <h2>CSS Basics</h2>
    <p class="paragraph">CSS allows you to control the layout, colors, and typography of a web page. You can use classes, IDs, and element selectors to apply styles to different parts of a page.</p>
    <p class="paragraph">This section demonstrates margins, paddings, and borders, which are essential for creating well-spaced, aesthetically pleasing designs.</p>
  </section>

  <!-- Footer Section -->
  <footer>
    <p>&copy; 2025 Joel simiyu.</p>
  </footer>
</body>
</html>

2. CSS FILE

/* General Reset to avoid browser inconsistencies */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  /* Apply styles to the body */
  body {
    font-family: 'Arial', sans-serif; /* Basic font */
    background-color: #f4f4f4; /* Light gray background */
    color: #333; /* Dark text color for readability */
    line-height: 1.6;
  }
  
  /* Styling the header */
  #main-heading {
    text-align: center;
    color: #4CAF50; /* Green color for the main heading */
    margin-top: 30px;
  }
