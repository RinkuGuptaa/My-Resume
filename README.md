# My-Resume

This HTML code represents a personal resume page for Rinku Kumar Gupta, a Computer Science Engineering student. The page uses both HTML and CSS to display the resume in a structured and visually appealing way. I'll explain the structure of the code and how each part works in detail:

1. HTML Structure
1.1. <!DOCTYPE html>
This is a declaration to define the document type and version of HTML (HTML5 in this case).
1.2. <html lang="en">
This tag wraps the entire HTML content and specifies the language as English (lang="en").
1.3. <head> Section
The <head> section contains metadata for the page like:
Character Set (<meta charset="UTF-8">): Specifies the character encoding for the document, which is UTF-8 (a universal character set).
Viewport (<meta name="viewport" content="width=device-width, initial-scale=1.0">): Ensures the webpage is responsive and adjusts according to the device's screen width.
Title (<title>Rinku Kumar Gupta - Resume</title>): The title of the webpage shown in the browser tab.
Link to External CSS: It seems like there's an incorrect duplicate reference to an external CSS file (<link rel="stylesheet" href="index.css">), but this isn't necessary because the styles are already embedded in the document within a <style> tag.
1.4. <body> Section
Contains the visible content of the webpage.
2. Resume Content Structure
2.1. <div class="container">
The main container that holds all the content. It has a class container for applying styles (like margins, padding, background color, etc.).
2.2. Header Section (<header>)
This contains the name, degree, and contact information of the individual.
Name (<h1>Rinku Kumar Gupta</h1>): The main heading displays the name.
Degree (<p>Computer Science Engineering</p>): The second paragraph specifies the degree.
Contact Information (<a href="tel:+918399807292"> and others): Links for phone number, email, LinkedIn, and GitHub profiles, all formatted as clickable elements (<a> tags).
2.3. Contact Section (.contact)
A list of contact details including:
Location, Phone number, Email, LinkedIn, and GitHub.
Each list item (<li>) uses the class list-item to maintain consistent styling.
2.4. Education Section (.education)
Lists educational qualifications:
B.Tech in Computer Science & Engineering at Scholar’s Institute of Technology and Management (2021-2025).
Science (AHSEC) at Diphu Govt College (2018-2020).
Uses an unordered list (<ul>) with list items (<li>).
2.5. Skills Section (.skills)
Displays a list of skills related to the individual’s expertise:
Front-end web development, C++, JavaScript, MySQL, VS Code, etc.
Again, uses an unordered list (<ul>) to display each skill as a list item (<li>).
2.6. Work Experience Section (.experience)
Details about internships and work experience:
Industrial Internship at Cognifyz Technologies (Aug - Sept 2023) — focuses on web application development with skills like HTML, CSS, JavaScript.
Academic Internship at MSME (Aug - Sept 2022) — Web development and database management.
Social Internship at Parijat Academic — Teaching and coordinating fundraising events.
Each internship is listed with a title (e.g., Industrial Internship) and a short description of the work done.
2.7. Projects Section (.projects)
Describes some of the individual’s projects:
Image Pixel Editor — A tool for editing images.
Wallet Guru — A personal finance tracker.
Movie Search Engine — A movie search tool with dynamic UI features (linked to GitHub project).
Each project is described in a <div class="project">, which includes a title (<h3>) and a paragraph (<p>) explaining the project.
2.8. Certifications Section (.certifications)
Lists certifications the individual has obtained, like Web Designing, CSS, JavaScript, PHP, and Google Cyber Security.
These are linked to the Google Drive documents where the certificates might be hosted.
2.9. Footer Section (.footer)
Contains a copyright notice: &copy; 2024 Rinku Kumar Gupta. All rights reserved.
This section is styled to appear at the bottom of the page, separating it from the rest of the content.
3. CSS Styling
3.1. Global Styles
Body (body): Sets the font family to Arial, background color to a light gray (#f0f4f8), and font color to a dark shade (#2c3e50).
Container (.container): Sets the maximum width, padding, background color (white), and box shadow to create a card-like appearance.
Font Size and Spacing: Defines margins, paddings, and font sizes for different sections to make the layout readable and spaced appropriately.
3.2. Section Titles
The .section-title class gives each section a title with a blue color (#2980b9) and a bottom border for separation.
The margin and padding adjust the spacing around these section titles.
3.3. Lists and List Items
ul: Sets the list style to disc (bulleted list), with padding for indentation.
list-item: Applies a font size of 16px and margin-bottom for spacing between each item in the list. Links inside list items are styled with a blue color (#2980b9), and a hover effect (underline) is applied.
3.4. Project Section
The .project class styles individual project items with a light gray background (#ecf0f1), padding, and rounded corners for a "card" effect.
Project titles are blue, and descriptions have a smaller font size for a subtle look.
3.5. Footer
The .footer class applies a gray color to the footer text, a smaller font size, and a top border for separation from the rest of the page.
3.6. Responsive Design
Media Queries: The code includes media queries to adjust the layout for different screen sizes:
For screens smaller than 1024px (like tablets), the container width and font sizes are reduced.
For screens smaller than 768px (like mobile devices), the padding and font sizes decrease further.
For very small screens (below 480px), everything adjusts to ensure readability without overcrowding.
