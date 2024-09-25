# [Guvi Zen](https://www.guvi.io/zen/)

## HTML Task to know usage of basic tags.

1. Fix the bugs in below snippet

```HTML
    <html lang="en">
    <head>
        <title>Document</title>
</head>
            <body>
                guvi
        
    
    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        <div>
            <div>
                Guvi Geek Network
            </div>
</div>
</div>
        </body>
    </html>
```
2. Try the below one

```HTML
<html lang="en">
    <head>
        <title>Document</title>
</head>
            <body>
                guvi
    
    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        <div>
            <div>
                Guvi Geek Network
            </div>
</div>
</div>
        </body>
    </html>
```

---

3. Design a contact us form with all fields as required.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f9f9f9;
        }
        .contact-form {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            max-width: 500px;
            margin: 0 auto;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        .contact-form h2 {
            margin-bottom: 20px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
        }
        .form-group input, .form-group textarea, .form-group select {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .form-group textarea {
            height: 120px;
            resize: vertical;
        }
        .form-group button {
            background-color: #28a745;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .form-group button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>

    <div class="contact-form">
        <h2>Contact Us</h2>
        <form action="submit_form.php" method="POST">
            <div class="form-group">
                <label for="name">Name</label>
                <input type="text" id="name" name="name" placeholder="Your full name" required>
            </div>
            <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" name="email" placeholder="Your email address" required>
            </div>
            <div class="form-group">
                <label for="phone">Phone Number</label>
                <input type="tel" id="phone" name="phone" placeholder="Your phone number" pattern="[0-9]{10}" title="Please enter a valid 10-digit phone number" required>
            </div>
            <div class="form-group">
                <label for="subject">Subject</label>
                <input type="text" id="subject" name="subject" placeholder="Subject of your message" required>
            </div>
            <div class="form-group">
                <label for="message">Message</label>
                <textarea id="message" name="message" placeholder="Write your message here" required></textarea>
            </div>
            <div class="form-group">
                <label for="reason">Reason for Contact</label>
                <select id="reason" name="reason" required>
                    <option value="" disabled selected>Select a reason</option>
                    <option value="support">Support</option>
                    <option value="sales">Sales</option>
                    <option value="feedback">Feedback</option>
                    <option value="other">Other</option>
                </select>
            </div>
            <div class="form-group">
                <button type="submit">Submit</button>
            </div>
        </form>
    </div>

</body>
</html>
---

4. Use certain HTML elements to display the following in a HTML page.

- Programming Language
  - JavaScript
    1. Angular
    2. React
    3. Vue.js
  - Python
    1. Django Framework
    2. Flask Framework
  - Java
    1. Spring
    2. Maven
    3. Hibernate
- Database
  - MySQL
  - MongoDB
  - Cansandra
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Technologies</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color: #333;
        }
        h2 {
            color: #007BFF;
            border-bottom: 2px solid #007BFF;
            padding-bottom: 5px;
        }
        ul {
            list-style-type: square;
            padding-left: 20px;
        }
        ul ul {
            list-style-type: circle;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Technologies</h1>
        
        <h2>Programming Language</h2>
        <ul>
            <li>JavaScript
                <ul>
                    <li>Angular</li>
                    <li>React</li>
                    <li>Vue.js</li>
                </ul>
            </li>
            <li>Python
                <ul>
                    <li>Django Framework</li>
                    <li>Flask Framework</li>
                </ul>
            </li>
            <li>Java
                <ul>
                    <li>Spring</li>
                    <li>Maven</li>
                    <li>Hibernate</li>
                </ul>
            </li>
        </ul>

        <h2>Database</h2>
        <ul>
            <li>MySQL</li>
            <li>MongoDB</li>
            <li>Cassandra</li>
        </ul>
    </div>

</body>
</html>
---

5. Create an element that helps you to open the https://google.com in separate new tab.
   <a href="https://google.com" target="_blank">Open Google</a>
   ---

7. In the form, add two radio buttons with grouping them for employee type(Salaried and own business)

--- <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f9f9f9;
        }
        .contact-form {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            max-width: 500px;
            margin: 0 auto;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        .contact-form h2 {
            margin-bottom: 20px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
        }
        .form-group input, .form-group textarea, .form-group select {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .form-group textarea {
            height: 120px;
            resize: vertical;
        }
        .form-group button {
            background-color: #28a745;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .form-group button:hover {
            background-color: #218838;
        }
        .radio-group {
            margin-bottom: 15px;
        }
    </style>
</head>
<body>

    <div class="contact-form">
        <h2>Contact Us</h2>
        <form action="submit_form.php" method="POST">
            <div class="form-group">
                <label for="name">Name</label>
                <input type="text" id="name" name="name" placeholder="Your full name" required>
            </div>
            <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" name="email" placeholder="Your email address" required>
            </div>
            <div class="form-group">
                <label for="phone">Phone Number</label>
                <input type="tel" id="phone" name="phone" placeholder="Your phone number" pattern="[0-9]{10}" title="Please enter a valid 10-digit phone number" required>
            </div>
            <div class="form-group">
                <label for="subject">Subject</label>
                <input type="text" id="subject" name="subject" placeholder="Subject of your message" required>
            </div>
            <div class="form-group">
                <label for="message">Message</label>
                <textarea id="message" name="message" placeholder="Write your message here" required></textarea>
            </div>
            <div class="form-group">
                <label for="reason">Reason for Contact</label>
                <select id="reason" name="reason" required>
                    <option value="" disabled selected>Select a reason</option>
                    <option value="support">Support</option>
                    <option value="sales">Sales</option>
                    <option value="feedback">Feedback</option>
                    <option value="other">Other</option>
                </select>
            </div>
            
            <!-- Radio Buttons Group for Employee Type -->
            <div class="radio-group">
                <label>Employee Type:</label>
                <input type="radio" id="salaried" name="employee_type" value="salaried" required>
                <label for="salaried">Salaried</label>
                <input type="radio" id="business" name="employee_type" value="own_business" required>
                <label for="business">Own Business</label>
            </div>
            
            <div class="form-group">
                <button type="submit">Submit</button>
            </div>
        </form>
    </div>

</body>
</html>

7. Design form shown in the link (http://evc-cit.info/cit040/formguide/card_0.png)

--- <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Payment Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 400px;
            margin: 50px auto;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.2);
        }
        h2 {
            text-align: center;
            color: #333;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        .form-group input {
            width: calc(100% - 20px);
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }
        .form-group input[type="submit"] {
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
            padding: 10px 15px;
            font-size: 16px;
        }
        .form-group input[type="submit"]:hover {
            background-color: #45a049;
        }
        .card-info {
            display: flex;
            justify-content: space-between;
        }
        .card-info input {
            width: 48%;
        }
    </style>
</head>
<body>

    <div class="container">
        <h2>Payment Information</h2>
        <form action="submit_payment.php" method="POST">
            <!-- Name on Card -->
            <div class="form-group">
                <label for="name">Name on Card</label>
                <input type="text" id="name" name="name" placeholder="Enter your name" required>
            </div>

            <!-- Card Number -->
            <div class="form-group">
                <label for="card_number">Card Number</label>
                <input type="text" id="card_number" name="card_number" placeholder="xxxx-xxxx-xxxx-xxxx" maxlength="19" required>
            </div>

            <!-- Card Info (Expiration and CVV) -->
            <div class="card-info">
                <div class="form-group">
                    <label for="exp_date">Expiration Date</label>
                    <input type="text" id="exp_date" name="exp_date" placeholder="MM/YY" required>
                </div>
                <div class="form-group">
                    <label for="cvv">CVV</label>
                    <input type="text" id="cvv" name="cvv" placeholder="xxx" maxlength="3" required>
                </div>
            </div>

            <!-- Submit Button -->
            <div class="form-group">
                <input type="submit" value="Submit Payment">
            </div>
        </form>
    </div>

</body>
</html>

8. Use the table tag to design given image [Click here](https://www.bapugraphics.com/assets/img/port_upload_dir/table-4.jpg).

---<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Table</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
            font-size: 16px;
            background-color: white;
        }
        table, th, td {
            border: 1px solid black;
        }
        th, td {
            padding: 12px 15px;
            text-align: left;
        }
        th {
            background-color: #4CAF50;
            color: white;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
        h2 {
            text-align: center;
            color: #333;
        }
    </style>
</head>
<body>

    <h2>Product Sales Data</h2>

    <table>
        <thead>
            <tr>
                <th>Product Name</th>
                <th>January</th>
                <th>February</th>
                <th>March</th>
                <th>April</th>
                <th>May</th>
                <th>June</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Product 1</td>
                <td>500</td>
                <td>300</td>
                <td>700</td>
                <td>600</td>
                <td>200</td>
                <td>400</td>
            </tr>
            <tr>
                <td>Product 2</td>
                <td>700</td>
                <td>200</td>
                <td>400</td>
                <td>800</td>
                <td>500</td>
                <td>300</td>
            </tr>
            <tr>
                <td>Product 3</td>
                <td>600</td>
                <td>500</td>
                <td>300</td>
                <td>400</td>
                <td>700</td>
                <td>200</td>
            </tr>
            <tr>
                <td>Product 4</td>
                <td>400</td>
                <td>600</td>
                <td>500</td>
                <td>300</td>
                <td>200</td>
                <td>700</td>
            </tr>
            <tr>
                <td>Product 5</td>
                <td>300</td>
                <td>400</td>
                <td>600</td>
                <td>700</td>
                <td>500</td>
                <td>800</td>
            </tr>
        </tbody>
    </table>

</body>
</html>

9. Write HTML input tags snippet to show default values for all Form elements.

--- <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form with Default Values</title>
</head>
<body>

    <h2>Form with Default Values</h2>
    <form action="/submit" method="POST">

        <!-- Text Input -->
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" value="John Doe"><br><br>

        <!-- Email Input -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" value="johndoe@example.com"><br><br>

        <!-- Password Input -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" value="defaultpass"><br><br>

        <!-- Number Input -->
        <label for="age">Age:</label>
        <input type="number" id="age" name="age" value="25"><br><br>

        <!-- Date Input -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" value="1990-01-01"><br><br>

        <!-- Checkbox Input -->
        <label for="subscribe">Subscribe to newsletter:</label>
        <input type="checkbox" id="subscribe" name="subscribe" checked><br><br>

        <!-- Radio Buttons -->
        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="male" checked>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Female</label><br><br>

        <!-- Select Dropdown -->
        <label for="country">Country:</label>
        <select id="country" name="country">
            <option value="usa" selected>USA</option>
            <option value="uk">UK</option>
            <option value="india">India</option>
        </select><br><br>

        <!-- Textarea -->
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" rows="4" cols="50">Default message text</textarea><br><br>

        <!-- Submit Button --><!DOCTYPE html>

10. In your, HTML page add the below line and Highlight it without using any CSS.

- "HTML & CSS is awesome"

---<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Highlight Example</title>
</head>
<body>

    <p><mark>HTML and CSS is awesome</mark></p>

</body>
</html>

11. Create an HTML page, which should contain all types of input elements.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>All Input Types</title>
</head>
<body>

    <h1>All Types of Input Elements</h1>
    <form action="/submit" method="POST">

        <!-- Text Input -->
        <div>
            <label for="text-input">Text Input:</label>
            <input type="text" id="text-input" name="text-input" placeholder="Enter text">
        </div><br>

        <!-- Email Input -->
        <div>
            <label for="email-input">Email Input:</label>
            <input type="email" id="email-input" name="email-input" placeholder="Enter email">
        </div><br>

        <!-- Password Input -->
        <div>
            <label for="password-input">Password Input:</label>
            <input type="password" id="password-input" name="password-input" placeholder="Enter password">
        </div><br>

        <!-- Number Input -->
        <div>
            <label for="number-input">Number Input:</label>
            <input type="number" id="number-input" name="number-input" min="0" max="100" placeholder="Enter a number">
        </div><br>

        <!-- Date Input -->
        <div>
            <label for="date-input">Date Input:</label>
            <input type="date" id="date-input" name="date-input">
        </div><br>

        <!-- Time Input -->
        <div>
            <label for="time-input">Time Input:</label>
            <input type="time" id="time-input" name="time-input">
        </div><br>

        <!-- Color Input -->
        <div>
            <label for="color-input">Color Input:</label>
            <input type="color" id="color-input" name="color-input">
        </div><br>

        <!-- Checkbox Input -->
        <div>
            <label for="checkbox-input">Checkbox Input:</label>
            <input type="checkbox" id="checkbox-input" name="checkbox-input" value="1">
            <label for="checkbox-input">Check me</label>
        </div><br>

        <!-- Radio Buttons -->
        <div>
            <label>Radio Button Input:</label>
            <input type="radio" id="radio1" name="radio-input" value="option1" checked>
            <label for="radio1">Option 1</label>
            <input type="radio" id="radio2" name="radio-input" value="option2">
            <label for="radio2">Option 2</label>
        </div><br>

        <!-- File Input -->
        <div>
            <label for="file-input">File Input:</label>
            <input type="file" id="file-input" name="file-input">
        </div><br>

        <!-- URL Input -->
        <div>
            <label for="url-input">URL Input:</label>
            <input type="url" id="url-input" name="url-input" placeholder="Enter URL">
        </div><br>

        <!-- Search Input -->
        <div>
            <label for="search-input">Search Input:</label>
            <input type="search" id="search-input" name="search-input" placeholder="Search...">
        </div><br>

        <!-- Textarea -->
        <div>
            <label for="textarea-input">Textarea:</label><br>
            <textarea id="textarea-input" name="textarea-input" rows="4" cols="50" placeholder="Enter your message..."></textarea>
        </div><br>

        <!-- Submit Button -->
        <div>
            <input type="submit" value="Submit">
        </div>

    </form>

</body>
</html>
