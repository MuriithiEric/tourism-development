## Document Structure

<!DOCTYPE html>: Declares the document type and version of HTML being used.
<html lang="en">: Defines the root element of an HTML page and specifies English as the language of the content.
Head Section
<meta charset="UTF-8" />: Specifies the character encoding for the HTML document.
<meta name="viewport" content="width=device-width, initial-scale=1.0" />: Makes the website responsive by setting the width of the viewport to the device's width and the initial zoom level when the page is first loaded.
<title>Document</title>: Sets the title of the webpage, which appears in the browser's title bar or tab.
Stylesheets and Scripts
<link rel="stylesheet" href="index.css" />: Links an external CSS stylesheet named index.css to style the HTML elements.
<script src="https://formspree.io/js/formbutton-v1.min.js" defer></script>: Loads the Formspree JavaScript library asynchronously to enable form submission functionality.
Inline <script> tag: Initializes the Formspree form with custom settings, including the form action URL, field definitions, and styling options.
Body Section
<section class="navigation">: Defines a section for the website's navigation menu.
<h1 class="logo">LOGO</h1>: Represents the logo of the website.
<div class="navlinks">: Contains links to different pages of the website and a sign-up button.
<section class="hero">: Creates a prominent section at the top of the page, often used for marketing purposes.
<img src="..." alt="Hero Image">: Displays an image as the background or main visual element of the hero section.
<div class="hero-content">: Contains the main content of the hero section, including a heading, subheading, and a call-to-action button.
Contact Form
The inline script initializes a Formspree form within the webpage. It defines:

The form's action URL (action: "https://formspree.io/f/moqggwrn").
Fields for email input and a message textarea, both marked as required.
A submit button.
Custom styles for the form's title and button backgrounds.