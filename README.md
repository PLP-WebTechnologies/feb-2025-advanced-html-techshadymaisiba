# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Elements and Forms</title>
</head>
<body>

    <!-- Ordered List with Roman Numerals -->
    <section>
        <h2>Roman Numeral List</h2>
        <ol type="I">
            <li>HTML Basics</li>
            <li>CSS Styling</li>
            <li>JavaScript Fundamentals</li>
            <li>Frontend Frameworks</li>
            <li>Backend Technologies</li>
        </ol>
    </section>

    <!-- External Image from Pexels -->
    <section>
        <h2>Sample Image</h2>
        <img src="https://images.pexels.com/photos/3408744/pexels-photo-3408744.jpeg" 
             alt="Sample Nature Image from Pexels" 
             width="600">
    </section>

    <!-- Contacts Table -->
    <section>
        <h2>Contact List</h2>
        <table border="1" cellpadding="8">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Address</th>
                    <th>Mobile</th>
                    <th>Email</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Jane Doe</td>
                    <td>123 Main St</td>
                    <td>0712345678</td>
                    <td>jane@example.com</td>
                </tr>
                <tr>
                    <td>John Smith</td>
                    <td>456 Market Rd</td>
                    <td>0723456789</td>
                    <td>john@example.com</td>
                </tr>
                <tr>
                    <td>Alice Brown</td>
                    <td>789 River Ln</td>
                    <td>0734567890</td>
                    <td>alice@example.com</td>
                </tr>
                <tr>
                    <td>Bob White</td>
                    <td>321 Hilltop Ave</td>
                    <td>0745678901</td>
                    <td>bob@example.com</td>
                </tr>
                <tr>
                    <td>Mary Johnson</td>
                    <td>654 Sunset Blvd</td>
                    <td>0756789012</td>
                    <td>mary@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="POST">
            <!-- Name -->
            <label for="name">Full Name:</label><br>
