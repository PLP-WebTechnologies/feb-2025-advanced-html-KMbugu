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

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Document Assignment</title>
    
    <style>
        body { font-family: Arial, sans-serif; max-width: 800px; margin: 0 auto; padding: 20px; }
        table { border-collapse: collapse; width: 100%; margin: 20px 0; }
        th, td { border: 1px solid #ddd; padding: 8px; text-align: left; }
        th { background-color: #f2f2f2; }
        form { margin: 20px 0; }
        label { display: block; margin: 10px 0 5px; }
        input, select { width: 100%; max-width: 300px; padding: 8px; margin-bottom: 10px; }
    </style>
</head>
<body>
 
    <header>
        <h1>HTML5 Demo Page</h1>
    </header>

   
    <section>
        <h2>Sample Ordered List</h2>
        <ol type="I">
            <li>First Item</li>
            <li>Second Item</li>
            <li>Third Item</li>
            <li>Fourth Item</li>
            <li>Fifth Item</li>
        </ol>
    </section>

   
    <section>
        <h2>Featured Image</h2>
        <img src="https://images.pexels.com/photos/674010/pexels-photo-674010.jpeg" 
             alt="Beautiful Nature Landscape" 
             width="500" 
             height="300">
    </section>

  
    <section>
        <h2>Contacts Directory</h2>
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
                    <td>John Murimi</td>
                    <td>Kwangware Nairobi</td>
                    <td>+25471234567890</td>
                    <td>john.murimi@gmail.com</td>
                </tr>
                <tr>
                    <td>Jane Atieno</td>
                    <td>Kisumu Kenya</td>
                    <td>+2541234567890</td>
                    <td>jane.atieno@gmail.com</td>
                </tr>
                <tr>
                    <td>Mike Wafula</td>
                    <td>Kakamega Kenya</td>
                    <td>+1234567890</td>
                    <td>mike.w@gmail.com</td>
                </tr>
                <tr>
                    <td>Sarah Abdullahi</td>
                    <td>Mandera Kenya</td>
                    <td>+2543456789</td>
                    <td>sarah.a@gmail.com</td>
                </tr>
                <tr>
                    <td>Peter Musyoka</td>
                    <td>Machakos Kenya</td>
                    <td>+2540987654321</td>
                    <td>peter.m@gmail.com</td>
                </tr>
            </tbody>
        </table>
    </section>

    
    <section>
        <h2>Registration Form</h2>
        <form action="#" method="POST">
            <!-- Name Field -->
            <label for="name">Full Name*:</label>
            <input type="text" 
                   id="name" 
                   name="name" 
                   placeholder="Enter your full name" 
                   required>

            <!-- Email Field -->
            <label for="email">Email*:</label>
            <input type="email" 
                   id="email" 
                   name="email" 
                   placeholder="example@domain.com" 
                   required>

            <!-- Password Field -->
            <label for="password">Password*:</label>
            <input type="password" 
                   id="password" 
                   name="password" 
                   placeholder="Minimum 8 characters" 
                   minlength="8" 
                   required>

            <!-- Date of Birth -->
            <label for="dob">Date of Birth*:</label>
            <input type="date" 
                   id="dob" 
                   name="dob" 
                   required>

            <!-- Dropdown for Country -->
            <label for="country">Country:</label>
            <select id="country" name="country">
                <option value="">Select a country</option>
                <option value="us">United States</option>
                <option value="uk">United Kingdom</option>
                <option value="ca">Canada</option>
                <option value="au">Australia</option>
            </select>

            <!-- Radio Buttons for Gender -->
            <fieldset>
                <legend>Gender:</legend>
                <label><input type="radio" name="gender" value="male"> Male</label>
                <label><input type="radio" name="gender" value="female"> Female</label>
                <label><input type="radio" name="gender" value="other"> Other</label>
            </fieldset>

            <!-- Checkboxes for Interests -->
            <fieldset>
                <legend>Interests:</legend>
                <label><input type="checkbox" name="interests" value="tech"> Technology</label>
                <label><input type="checkbox" name="interests" value="sports"> Sports</label>
                <label><input type="checkbox" name="interests" value="music"> Music</label>
            </fieldset>

            <!-- Submit Button -->
            <input type="submit" value="Register">
        </form>
    </section>

    <!-- Multimedia Elements -->
    <section>
        <h2>Multimedia Demo</h2>
        <!-- Audio Element -->
        <audio controls>
            <source src="https://www.w3schools.com/html/horse.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>

        <!-- Video Element -->
        <video controls width="500">
            <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
            Your browser does not support the video element.
        </video>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 HTML5 Demo Page</p>
    </footer>
</body>
</html>
