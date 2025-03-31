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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>

    <!-- Internal CSS (within the same HTML file) -->
    <style>
        /* Apply styles to the body */
        body {
            font-family: 'Arial', sans-serif; /* Apply a different font */
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }

        /* Style the header with an ID selector */
        #main-header {
            background-color: #4CAF50; /* Green background */
            color: white;
            padding: 20px;
            text-align: center;
        }

        /* Style the title using a class selector */
        .title {
            font-size: 2.5em;
            font-weight: bold;
            margin-bottom: 20px;
        }

        /* Style the content section using a class selector */
        .content {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 5px; /* Rounded corners */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Box shadow for better look */
        }

        /* Style the image */
        .image {
            max-width: 100%;
            height: auto;
            border: 5px solid #ddd; /* Add a border around the image */
            padding: 10px;
            margin-top: 20px;
        }

        /* Style the footer */
        footer {
            text-align: center;
            padding: 15px;
            background-color: #333;
            color: white;
        }

        /* Style the email in the footer using a class selector */
        .email {
            color: #FFD700; /* Gold color */
            font-weight: bold;
        }
    </style>
</head>
<body>

    <header id="main-header">
        <h1 class="title">Welcome to My Styled Page</h1>
    </header>

    <section class="content">
        <p>This is a paragraph of text styled with CSS.</p>
        <p>Here is some more text. Notice the margins and padding applied to this content.</p>
    </section>

    <section id="image-section">
        <h2>Image Example</h2>
        <img src="https://via.placeholder.com/300" alt="Placeholder Image" class="image">
    </section>

    <footer>
        <p>Contact us at <span class="email">info@example.com</span></p>
    </footer>

</body>
</html>

