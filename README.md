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
    <!-- Metadata -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Index Page</title>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>Welcome to the Sample Page</h1>
        <p>This page demonstrates ordered lists, external images, tables, and forms.</p>
    </header>

    <!-- Ordered List -->
    <section>
        <h2>Ordered List with Roman Numerals</h2>
        <ol type="I">
            <li>Introduction</li>
            <li>Features</li>
            <li>Contact Information</li>
        </ol>
    </section>

    <!-- External Image -->
    <section>
        <h2>External Image</h2>
        <img src="https://images.pexels.com/photos/414612/pexels-photo-414612.jpeg" alt="Beautiful Scenery from Pexels" width="600">
    </section>

    <!-- Table of Contacts -->
    <section>
        <h2>Contact Information</h2>
        <table border="1" cellpadding="10" cellspacing="0">
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
                    <td>John Doe</td>
                    <td>123 Main St, Nairobi</td>
                    <td>+254701234567</td>
                    <td>john.doe@example.com</td>
                </tr>
                <tr>
                    <td>Jane Smith</td>
                    <td>456 Elm St, Mombasa</td>
                    <td>+254712345678</td>
                    <td>jane.smith@example.com</td>
                </tr>
                <tr>
                    <td>Peter Kimani</td>
                    <td>789 Oak St, Kisumu</td>
                    <td>+254723456789</td>
                    <td>peter.kimani@example.com</td>
                </tr>
                <tr>
                    <td>Alice Njeri</td>
                    <td>321 Pine St, Nakuru</td>
                    <td>+254734567890</td>
                    <td>alice.njeri@example.com</td>
                </tr>
                <tr>
                    <td>David Otieno</td>
                    <td>654 Birch St, Eldoret</td>
                    <td>+254745678901</td>
                    <td>david.otieno@example.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    <!-- Registration Form -->
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="post">
            <!-- Name -->
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

            <!-- Email -->
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

            <!-- Password -->
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" placeholder="Enter your password" required minlength="8"><br><br>

            <!-- Date -->
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob" required><br><br>

            <!-- Dropdown -->
            <label for="role">Role:</label>
            <select id="role" name="role" required>
                <option value="">Select your role</option>
                <option value="student">Student</option>
                <option value="teacher">Teacher</option>
                <option value="admin">Administrator</option>
            </select><br><br>

            <!-- Radio Buttons -->
            <p>Gender:</p>
            <input type="radio" id="male" name="gender" value="male" required>
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label><br><br>

            <!-- Checkboxes -->
            <p>Hobbies:</p>
            <input type="checkbox" id="reading" name="hobbies" value="reading">
            <label for="reading">Reading</label>
            <input type="checkbox" id="traveling" name="hobbies" value="traveling">
            <label for="traveling">Traveling</label>
            <input type="checkbox" id="sports" name="hobbies" value="sports">
            <label for="sports">Sports</label><br><br>

            <!-- Submit Button -->
            <button type="submit">Register</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Sample Page. All rights reserved.</p>
    </footer>
</body>
</html>

