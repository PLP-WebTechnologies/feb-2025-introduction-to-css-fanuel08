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
## Answer

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Webpage</title>
    <link rel="stylesheet" href="styles.css"> <!-- Linking external CSS file -->
</head>
<body>
    <header>
        <h1 id="main-title">Welcome to My Styled Page</h1>
    </header>
    
    <section class="content">
        <p class="text">This is an example paragraph demonstrating external CSS styling. The styles include colors, font changes, and spacing.</p>
        
        <!-- free online image from Unsplash -->
        <img src="https://images.unsplash.com/photo-1506748686214-e9df14d4d9d0?w=600&h=400&fit=crop" 
             alt="Sunset over Mountains" 
             class="styled-image">
    </section>

    <footer>
        <p>&copy; 2025 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>

    <-- css-->
    /* Style for the main title using an ID */
#main-title {
    color: #2c3e50;
    font-family: 'Arial', sans-serif;
    text-align: center;
    padding: 10px;
    border-bottom: 3px solid #3498db;
}

/* Style for paragraphs using a class */
.text {
    color: #333;
    font-size: 18px;
    font-family: 'Georgia', serif;
    margin: 20px;
    line-height: 1.6;
}

/* Styling an image using a class */
.styled-image {
    display: block;
    max-width: 100%;
    height: auto;
    margin: 20px auto;
    border: 5px solid #3498db;
    border-radius: 10px;
}

/* Additional styling for the content section */
.content {
    background-color: #ecf0f1;
    padding: 20px;
    border-radius: 5px;
}


