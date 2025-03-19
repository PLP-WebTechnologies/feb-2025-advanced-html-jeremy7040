<!DOCTYPE>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sample Page</title>
    <style>
        table, th, td {
            border: 1px solid black;
            border-collapse: collapse;
            padding: 8px;
        }
    </style>
</head>
<body>

    <!-- Ordered list with roman numerals -->
    <h2>Ordered List with Roman Numerals</h2>
    <ol type="I">
        <li>First item</li>
        <li>Second item</li>
        <li>Third item</li>
    </ol>

    <!-- External image from pexels.com -->
    <h2>External Image</h2>
    <img src="https://images.pexels.com/photos/414612/pexels-photo-414612.jpeg" alt="Sample Image" width="500">

    <!-- Table of 5 contacts -->
    <h2>Contacts</h2>
    <table>
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
                <td>123 Main St</td>
                <td>555-1234</td>
                <td>john@example.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Oak St</td>
                <td>555-5678</td>
                <td>jane@example.com</td>
            </tr>
            <tr>
                <td>Bob Johnson</td>
                <td>789 Pine St</td>
                <td>555-8765</td>
                <td>bob@example.com</td>
            </tr>
            <tr>
                <td>Alice Brown</td>
                <td>321 Maple St</td>
                <td>555-4321</td>
                <td>alice@example.com</td>
            </tr>
            <tr>
                <td>Charlie Davis</td>
                <td>654 Elm St</td>
                <td>555-6789</td>
                <td>charlie@example.com</td>
            </tr>
        </tbody>
    </table>

    <!-- Registration form -->
    <h2>Registration Form</h2>
    <form>
        <!-- Name field -->
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

        <!-- Email field -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

        <!-- Password field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>

        <!-- Date field -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required><br><br>

        <!-- Dropdown -->
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="">Select your country</option>
            <option value="usa">USA</option>
            <option value="canada">Canada</option>
            <option value="uk">UK</option>
        </select><br><br>

        <!-- Radio buttons -->
        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female" required>
        <label for="female">Female</label><br><br>

        <!-- Checkboxes -->
        <label>Interests:</label>
        <input type="checkbox" id="sports" name="interests" value="sports">
        <label for="sports">Sports</label>
        <input type="checkbox" id="music" name="interests" value="music">
        <label for="music">Music</label>
        <input type="checkbox" id="reading" name="interests" value="reading">
        <label for="reading">Reading</label><br><br>

        <!-- Submit button -->
        <input type="submit" value="Register">
    </form>

</body>
</html>

