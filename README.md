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
/* General styles for the body */
body {
    font-family: "Arial", sans-serif; /* Use Arial as the primary font, with sans-serif as a fallback */
    color: #333; /* Dark gray text color for readability */
    background-color: #f4f4f4; /* Light gray background for better contrast */
    margin: 20px; /* Add some overall margin around the page content */
}

/* Style for the main header using ID selector */
#main-title {
    color: #007bff; /* Blue color for the main title */
    font-family: "Georgia", serif; /* Use Georgia for a more formal look */
    font-size: 2.5em; /* Larger font size for emphasis */
    text-align: center; /* Center the main title */
    margin-bottom: 30px; /* Add some space below the title */
}

/* Style for paragraphs using class selector */
.paragraph {
    background-color: #fff; /* White background for paragraph blocks */
    color: #555; /* Slightly lighter gray text for paragraphs */
    padding: 15px; /* Add internal spacing within the paragraph */
    margin-bottom: 20px; /* Add space between paragraphs */
    border: 1px solid #ccc; /* Light gray border to visually separate paragraphs */
    line-height: 1.6; /* Improve readability with increased line height */
}

/* Style for images using element selector */
img {
    display: block; /* Make the image a block-level element to control margin */
    max-width: 100%; /* Ensure the image doesn't exceed its container's width */
    height: auto; /* Maintain aspect ratio */
    margin: 20px auto; /* Add top and bottom margin, and center the image horizontally */
    border: 5px solid #eee; /* Light gray border around the image */
    box-shadow: 3px 3px 5px #888888; /* Add a subtle shadow for depth */
}

/* Style for task list items using another class selector */
.task-item {
    list-style-type: square; /* Use square bullets for the task list */
    margin-left: 30px; /* Indent the list items */
    margin-bottom: 10px; /* Add some space between list items */
    color: #28a745; /* Green color to highlight tasks */
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Styled Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    </body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Styled Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1 id="main-title">Welcome to My Styled Page</h1>

    <p class="paragraph">This is the first paragraph of content on my page. It's styled using a class selector in the external CSS file.</p>

    <p class="paragraph">Here's another paragraph with some more information. Notice how it also uses the same class for styling, ensuring consistency.</p>

    <img src="your-image.jpg" alt="A descriptive image">

    <h2>Tasks for Today</h2>
    <ul>
        <li class="task-item">Complete the CSS styling exercise</li>
        <li class="task-item">Review project proposal</li>
        <li class="task-item">Attend team meeting</li>
    </ul>

</body>
</html>
