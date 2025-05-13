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













            assignment 4
            
            <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multimedia-Rich Webpage</title>
</head>
<body>

    <header>
        <h1>Welcome to Our Multimedia Webpage 🎉</h1>
        <p>This page showcases HTML5 multimedia elements, a form, a table, an image, and a list.</p>
    </header>

    <!-- Embedded Image -->
    <section>
        <h2>Featured Image</h2>
        <img src="https://images.pexels.com/photos/414171/pexels-photo-414171.jpeg" 
             alt="Beautiful Scenery" 
             width="600">
    </section>

    <!-- Multimedia: Audio -->
    <section>
        <h2>Background Music</h2>
        <audio controls>
            <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mp3">
            Your browser does not support the audio element.
        </audio>
    </section>

    <!-- Multimedia: Video -->
    <section>
        <h2>Intro Video</h2>
        <video width="600" controls>
            <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </section>

    <!-- List -->
    <section>
        <h2>Our Services</h2>
        <ul>
            <li>Web Design</li>
            <li>Mobile App Development</li>
            <li>Digital Marketing</li>
            <li>Cloud Solutions</li>
        </ul>
    </section>

    <!-- Table -->
    <section>
        <h2>Team Contacts</h2>
        <table border="1" cellpadding="10">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Role</th>
                    <th>Email</th>
                    <th>Phone</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Alex Kim</td>
                    <td>Developer</td>
                    <td>alex@example.com</td>
                    <td>0712345678</td>
                </tr>
                <tr>
                    <td>Mary Wambui</td>
                    <td>Designer</td>
                    <td>mary@example.com</td>
                    <td>0723456789</td>
                </tr>
                <tr>
                    <td>James Otieno</td>
                    <td>Manager</td>
                    <td>james@example.com</td>
                    <td>0734567890</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Register Now</h2>
        <form action="#" method="POST">
            <!-- Full Name -->
            <label for="fullname">Full Name:</label><br>
            <input type="text" id="fullname" name="fullname" placeholder="Your full name" required><br><br>

            <!-- Email -->
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email" placeholder="you@example.com" required><br><br>

            <!-- Password -->
            <label for="password">Password:</label><br>
            <input type="password" id="password" name="password" placeholder="At least 6 characters" required minlength="6"><br><br>

            <!-- Date of Birth -->
            <label for="dob">Date of Birth:</label><br>
            <input type="date" id="dob" name="dob" required><br><br>

            <!-- Gender -->
            <label>Gender:</label><br>
            <input type="radio" id="male" name="gender" value="Male" required>
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="Female">
            <label for="female">Female</label><br><br>

            <!-- Interests -->
            <label>Interests:</label><br>
            <input type="checkbox" id="tech" name="interests" value="Technology">
            <label for="tech">Technology</label>
            <input type="checkbox" id="art" name="interests" value="Art">
            <label for="art">Art</label>
            <input type="checkbox" id="sports" name="interests" value="Sports">
            <label for="sports">Sports</label><br><br>

            <!-- Country -->
            <label for="country">Country:</label><br>
            <select id="country" name="country" required>
                <option value="">--Select Country--</option>
                <option value="Kenya">Kenya</option>
                <option value="Uganda">Uganda</option>
                <option value="Tanzania">Tanzania</option>
            </select><br><br>

            <!-- Submit -->
            <button type="submit">Submit</button>
        </form>
    </section>

</body>
</html>

