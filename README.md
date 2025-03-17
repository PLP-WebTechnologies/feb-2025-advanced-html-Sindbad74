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
>
>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registration Form</title>
</head>
<body>
   <div class="container">
       <h1>Registration Form</h1>
          <form action="#" method="POST">
               <!-- First Name Field -->
               <label for="first_name">First Name:</label>
               <input type="text" id="first_name" name="first_name" placeholder="Enter your first name" required><br>
 
               <!-- Last Name Field -->
               <label for="last_name">Last Name:</label>
               <input type="text" id="last_name" name="last_name" placeholder="Enter your last name" required><br>

               <!-- Email Field -->
               <label for="email">Email:</label>
               <input type="email" id="email" name="email" placeholder="Enter your email" required><br>

               <!-- Password Field -->
               <label for="password">Password:</label>
               <input type="password" id="password" name="password" placeholder="Enter a password" required><br>

               <!-- Date Field -->
               <label for="dob">Date of Birth:</label>
               <input type="date" id="dob" name="dob" required><br>

               <!-- Dropdown Field -->
               <label for="country">Select Country:</label>
               <select id="country" name="country" required>
               <option value="">Choose...</option>
               <option value="USA">USA</option>
               <option value="Canada">Canada</option>
               <option value="UK">UK</option>
               <option value="Australia">Australia</option>
               <option value="India">India</option>
               <option value="Kenya">Kenya</option>
               <option value="Dubai">Dubai</option>
               </select><br>

              <!-- Submit Button -->
                <button type="submit">Register</button>   <br>
                
                   <!-- Ordered List with Roman Numerals -->
    <h2>Ordered List</h2>
    <ol type="I">
        <li>First Item</li>
        <li>Second Item</li>
        <li>Third Item</li>
        <li>Fourth Item</li>
        <li>Fifth Item</li>
    </ol>

    <!-- External Image -->
    <h2>External Image</h2>
    <img src="https://images.pexels.com/photos/414612/pexels-photo-414612.jpeg" alt="Beautiful Scenery" width="250px" height="250px">

    <!-- Contact Table -->
    <h2>Contact List</h2>
    <table border="1" cellpadding="10" cellspacing="0" width="100%" style="text-align: center;" >
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John Doe</td>
            <td>123 Street, NY</td>
            <td>+1234567890</td>
            <td>john@example.com</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>456 Avenue, LA</td>
            <td>+1987654321</td>
            <td>jane@example.com</td>
        </tr>
        <tr>
            <td>Mike Johnson</td>
            <td>789 Boulevard, TX</td>
            <td>+1478523690</td>
            <td>mike@example.com</td>
        </tr>
        <tr>
            <td>Emily Davis</td>
            <td>321 Road, FL</td>
            <td>+1597534682</td>
            <td>emily@example.com</td>
        </tr>
        <tr>
            <td>Robert Brown</td>
            <td>654 Lane, IL</td>
            <td>+1852647390</td>
            <td>robert@example.com</td>
        </tr>
    </table>
            </form>
        </div>
    </body>
</html>

 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
