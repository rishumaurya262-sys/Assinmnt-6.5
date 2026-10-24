# Assignment 6.5 — Profile Card / Product Card Mini-Project

## 1. index.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Card</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="profile-card">
        <span class="badge">Available</span>

        <img src="https://placehold.co/150x150" alt="Profile image">

        <h1>Alex Morgan</h1>
        <h3>Web Developer</h3>

        <p>I create simple and responsive websites using HTML and CSS.</p>

        <div class="skills">
            <span>HTML</span>
            <span>CSS</span>
            <span>JavaScript</span>
        </div>

        <a href="mailto:hello@example.com" class="contact-btn">Contact Me</a>
    </div>

</body>
</html>
```

## 2. style.css

```css
* {
    box-sizing: border-box;
}

body {
    margin: 0;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #f0f4f8;
    font-family: Arial, sans-serif;
    padding: 20px;
}

.profile-card {
    position: relative;
    width: 100%;
    max-width: 350px;
    padding: 30px 20px;
    background-color: white;
    border: 1px solid #ddd;
    border-radius: 15px;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    text-align: center;
}

.badge {
    position: absolute;
    top: 15px;
    right: 15px;
    background-color: #28a745;
    color: white;
    padding: 5px 10px;
    border-radius: 15px;
    font-size: 12px;
}

.profile-card img {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 10px;
}

.profile-card h1 {
    font-size: 24px;
    margin: 10px 0;
}

.profile-card h3 {
    color: #555;
    margin: 5px 0 15px;
}

.profile-card p {
    color: #666;
    line-height: 1.5;
}

.skills {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 8px;
    margin: 20px 0;
}

.skills span {
    background-color: #e8f0fe;
    color: #2457a7;
    padding: 6px 10px;
    border-radius: 5px;
    font-size: 13px;
}

.contact-btn {
    display: inline-block;
    background-color: #007bff;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

.contact-btn:hover {
    background-color: #0056b3;
}

@media (max-width: 400px) {
    .profile-card {
        padding: 25px 15px;
    }

    .profile-card h1 {
        font-size: 21px;
    }
}
```

## 3. Write Something — Explanation

This project creates a responsive profile card using HTML and CSS. The card contains a profile image, name, job title, description, skills, and a contact button.

The CSS box model is used to manage padding, borders, and spacing. The card uses rounded corners, a shadow, and a background color to improve its appearance. CSS positioning is used to place the availability badge inside the card. A media query makes the card suitable for smaller screens.

The project can be tested by opening the HTML file in a browser and resizing the browser window.

## 4. Final Steps

1. Save the HTML code in `index.html`.
2. Save the CSS code in `style.css` in the same folder.
3. Open `index.html` in your browser.
4. Check the card at different screen widths.
5. Take a screenshot of the completed project if required by the assignment.
6.