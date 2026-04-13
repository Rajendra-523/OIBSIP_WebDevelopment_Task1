# OIBSIP Web Development Task 1

## Landing Page Project

This project is a simple and clean **landing page** created using **HTML** and **CSS** as part of the **Oasis Infobyte Web Development Internship**. The main goal of this task is to understand how a webpage is structured with HTML and how it is styled using CSS to create an attractive user interface.

The website is designed for a sample brand named **CodeLift**. It includes a navigation bar, a hero section, service cards, and a footer. This project is suitable for beginners who want to practice the basics of frontend web development.

## Author Details

- **Name:** BURLAGADAA RAJENDRA
- **Internship:** Oasis Infobyte
- **Domain:** Web Development and Designing
- **Task:** Level 1 - Task 1

## Technologies Used

- **HTML5** for the structure of the webpage
- **CSS3** for styling and layout design

## Project Structure

- `index.html` - Contains the complete structure and content of the landing page
- `style.css` - Contains all the styles used for layout, colors, spacing, and design
- `README.md` - Contains the project explanation and details

## HTML Explanation

The `index.html` file defines the structure of the landing page. It is divided into several important sections:

### 1. Document Setup

The file starts with the `<!DOCTYPE html>` declaration, which tells the browser that the document uses HTML5. Inside the `<head>` section:

- `<meta charset="UTF-8">` sets the character encoding
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">` helps the page scale properly on different screen sizes
- `<title>CodeLift</title>` sets the page title shown in the browser tab
- `<link rel="stylesheet" href="style.css">` connects the external CSS file

### 2. Navigation Bar

The `<nav>` section creates the top navigation bar. It includes:

- A logo area with the text **CodeLift**
- A menu with links such as **Home**, **About**, **Services**, and **Contact**

This section gives the page a professional header and helps users understand the basic layout of a website.

### 3. Hero Section

The hero section is created using:

- A main heading: **Welcome to CodeLift**
- A short paragraph: **Build, Learn and Grow with Web Development**
- A call-to-action button: **Get Started**

This is the main attention-grabbing part of the landing page. It introduces the theme of the website and provides a clear first impression.

### 4. Cards Section

The project contains a `<section class="container">` with three cards. Each card highlights a key area:

- **Web Design**
- **Development**
- **Learning**

These cards are useful for presenting services or important topics in a neat and organized way.

### 5. Footer

The `<footer>` section is placed at the bottom of the page. It contains a copyright message for the website. This gives the page a complete and finished look.

## CSS Explanation

The `style.css` file is responsible for the visual appearance of the landing page.

### 1. Body Styling

The `body` selector removes default margin, sets the font to `Arial, sans-serif`, and applies a light background color. This creates a clean base for the full webpage.

### 2. Navbar Styling

The `nav` section uses:

- `display: flex`
- `justify-content: space-between`
- `align-items: center`

These properties arrange the logo and menu links in a horizontal row. The dark background color and white text improve visibility and contrast.

The `.menu a` selector styles the navigation links by:

- Removing underline with `text-decoration: none`
- Setting the text color to white
- Adding spacing between links using `margin-left`

### 3. Hero Section Styling

The `.hero` class centers the content and gives it enough padding to create a spacious layout. The heading size is increased using `.hero h1`, and the paragraph color is softened with gray to improve readability.

The `.btn` class styles the button with:

- Green background
- White text
- Padding for better click area
- Rounded corners using `border-radius`

This makes the button stand out as a call-to-action element.

### 4. Cards Layout

The `.container` class uses Flexbox to place the cards side by side with spacing between them. This creates a neat horizontal layout.

The `.card` class applies:

- White background
- Padding
- Fixed width
- Rounded corners
- Center-aligned text
- Soft box shadow

These styles make each card look modern and visually separate from the page background.

### 5. Footer Styling

The `footer` uses a dark background with white text and centered alignment. This helps maintain consistency with the navigation bar and gives the page a balanced design.

## Features of the Project

- Simple and beginner-friendly landing page
- Clean layout using only HTML and CSS
- Navigation bar with menu links
- Hero section with heading, text, and button
- Three content cards for services/topics
- Footer section for page completion
- Use of Flexbox for alignment and spacing

## How to Run the Project

1. Download or clone the project folder.
2. Open the folder in your code editor.
3. Open `index.html` in any web browser.

No additional setup, framework, or installation is required because this project is built with only HTML and CSS.

## Learning Outcome

By completing this task, the following concepts can be understood more clearly:

- Basic webpage structure using HTML
- Linking CSS with HTML
- Creating sections like navbar, hero area, cards, and footer
- Applying colors, spacing, typography, and alignment
- Using Flexbox for simple layout design

## Demo Video

- https://drive.google.com/file/d/13W3UFM0jQZHfpVIcy26rqrVVvGSimpbF/view?usp=drive_link

## Conclusion

This project is a good starting point for learning web development. It shows how HTML creates the structure of a webpage and how CSS improves the appearance and layout. The landing page is simple, readable, and useful for practicing core frontend concepts.
