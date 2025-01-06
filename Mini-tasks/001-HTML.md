# [Guvi Zen](https://www.guvi.io/zen/)

## HTML Task to know usage of basic tags.

1. Fix the bugs in below snippet

```HTML
    <html lang="en">
    <head>
        <title>Document
            <body>
                guvi
        </title>
    </head>
    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        <div>
            <div>
                Guvi Geek Network
            </div>
        </body>
    </html>
```
2. Try the below one

```HTML
<html lang="en">
    <head>
        <title>Document
            <body>
                guvi
    </head>
    <div>
        Lorem ipsum dolor sit amet consectetur adipisicing elit.
        <div>
            <div>
                Guvi Geek Network
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
      margin: 20px;
    }
    form {
      max-width: 400px;
      margin: 0 auto;
    }
    label {
      display: block;
      margin-bottom: 5px;
      font-weight: bold;
    }
    input, textarea, select, button {
      width: 100%;
      padding: 10px;
      margin-bottom: 15px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background-color: #4CAF50;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <h1>Contact Us</h1>
  <form action="#" method="POST">
    <label for="name">Full Name:</label>
    <input type="text" id="name" name="name" placeholder="Your full name" required>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" placeholder="Your email address" required>

    <label for="phone">Phone Number:</label>
    <input type="tel" id="phone" name="phone" placeholder="Your phone number" required>

    <label for="subject">Subject:</label>
    <input type="text" id="subject" name="subject" placeholder="Subject of your message" required>

    <label for="message">Message:</label>
    <textarea id="message" name="message" rows="5" placeholder="Write your message here" required></textarea>

    <button type="submit">Submit</button>
  </form>
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
  <title>Programming Info</title>
</head>
<body>
  <h1>Programming Information</h1>
  <h2>Programming Languages</h2>
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
        <li>Django</li>
        <li>Flask</li>
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
  <h2>Databases</h2>
  <ul>
    <li>MySQL</li>
    <li>MongoDB</li>
    <li>Cassandra</li>
  </ul>
</body>
</html>

---

5. Create an element that helps you to open the https://google.com in separate new tab.
<a href="https://google.com" target="_blank" rel="noopener noreferrer">Open Google</a>

---

6. In the form, add two radio buttons with grouping them for employee type(Salaried and own business)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us</title>
</head>
<body>
  <h1>Contact Us</h1>
  <form action="#" method="POST">
    <label for="name">Full Name:</label>
    <input type="text" id="name" name="name" required>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>

    <label for="phone">Phone Number:</label>
    <input type="tel" id="phone" name="phone" required>

    <label>Employee Type:</label>
    <input type="radio" id="salaried" name="employee_type" value="Salaried" required>
    <label for="salaried">Salaried</label>
    <input type="radio" id="business" name="employee_type" value="Own Business" required>
    <label for="business">Own Business</label>

    <button type="submit">Submit</button>
  </form>
</body>
</html>

---

7. Design form shown in the link (http://evc-cit.info/cit040/formguide/card_0.png)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Payment Form</title>
  <style>
    body { font-family: Arial, sans-serif; display: flex; justify-content: center; align-items: center; height: 100vh; margin: 0; background: #f4f4f4; }
    .form-container { background: #fff; padding: 20px; border-radius: 8px; box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2); width: 300px; }
    h1 { font-size: 18px; margin-bottom: 15px; text-align: center; }
    label { font-size: 14px; margin-bottom: 5px; display: block; }
    input { width: 100%; padding: 8px; margin-bottom: 15px; border: 1px solid #ccc; border-radius: 4px; font-size: 14px; }
    .small-input { width: 48%; display: inline-block; }
    button { width: 100%; padding: 10px; background: #4CAF50; color: white; border: none; border-radius: 4px; cursor: pointer; font-size: 16px; }
    button:hover { background: #45a049; }
  </style>
</head>
<body>
  <div class="form-container">
    <h1>Payment Info</h1>
    <form>
      <label>Name on Card</label>
      <input type="text" placeholder="John Doe" required>
      <label>Card Number</label>
      <input type="text" placeholder="1234 5678 9012 3456" required>
      <label>Expiration Date</label>
      <input type="text" placeholder="MM/YY" class="small-input" required>
      <label>CVV</label>
      <input type="text" placeholder="123" class="small-input" required>
      <button type="submit">Pay</button>
    </form>
  </div>
</body>
</html>
v
---

8. Use the table tag to design given image [Click here](https://www.bapugraphics.com/assets/img/port_upload_dir/table-4.jpg).
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Table Design</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background: #f4f4f4;
    }
    table {
      width: 600px;
      border-collapse: collapse;
      margin: 20px 0;
      background: #fff;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    }
    th, td {
      padding: 15px;
      text-align: center;
      border: 1px solid #ddd;
    }
    th {
      background: #4CAF50;
      color: white;
      font-weight: bold;
    }
    tr:nth-child(even) {
      background: #f2f2f2;
    }
    tr:hover {
      background: #ddd;
    }
  </style>
</head>
<body>
  <table>
    <tr>
      <th>Roll No</th>
      <th>Name</th>
      <th>Class</th>
      <th>Subject</th>
    </tr>
    <tr>
      <td>1</td>
      <td>John</td>
      <td>10th</td>
      <td>Math</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Jane</td>
      <td>10th</td>
      <td>Science</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Sam</td>
      <td>10th</td>
      <td>English</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Sara</td>
      <td>10th</td>
      <td>History</td>
    </tr>
  </table>
</body>
</html>

---

9. Write HTML input tags snippet to show default values for all Form elements.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Form with Default Values</title>
</head>
<body>
  <form>
    <!-- Text Input -->
    <label for="text">Text:</label>
    <input type="text" id="text" name="text" value="Default Text"><br><br>

    <!-- Password Input -->
    <label for="password">Password:</label>
    <input type="password" id="password" name="password" value="123456"><br><br>

    <!-- Email Input -->
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" value="example@example.com"><br><br>

    <!-- Number Input -->
    <label for="number">Number:</label>
    <input type="number" id="number" name="number" value="10"><br><br>

    <!-- Date Input -->
    <label for="date">Date:</label>
    <input type="date" id="date" name="date" value="2025-01-01"><br><br>

    <!-- Radio Button -->
    <label>Gender:</label>
    <input type="radio" id="male" name="gender" value="Male" checked>
    <label for="male">Male</label>
    <input type="radio" id="female" name="gender" value="Female">
    <label for="female">Female</label><br><br>

    <!-- Checkbox -->
    <label>Preferences:</label>
    <input type="checkbox" id="subscribe" name="preferences" value="Subscribe" checked>
    <label for="subscribe">Subscribe</label><br><br>

    <!-- Select Dropdown -->
    <label for="country">Country:</label>
    <select id="country" name="country">
      <option value="USA" selected>USA</option>
      <option value="India">India</option>
      <option value="UK">UK</option>
    </select><br><br>

    <!-- Textarea -->
    <label for="comments">Comments:</label>
    <textarea id="comments" name="comments" rows="4" cols="30">Default comment text...</textarea><br><br>

    <!-- Range Slider -->
    <label for="range">Range:</label>
    <input type="range" id="range" name="range" min="1" max="100" value="50"><br><br>

    <!-- File Input -->
    <label for="file">Upload File:</label>
    <input type="file" id="file" name="file"><br><br>

    <!-- Submit Button -->
    <button type="submit">Submit</button>
  </form>
</body>
</html>

---

10. In your, HTML page add the below line and Highlight it without using any CSS.

- "HTML & CSS is awesome"
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Highlighted Text</title>
</head>
<body>
  <h1>Welcome to the HTML Page</h1>
  <p><mark>HTML & CSS is awesome</mark></p>
</body>
</html>

---

11. Create an HTML page, which should contain all types of input elements.
    <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>All Input Types</title>
</head>
<body>
  <h1>Form with All Input Types</h1>
  <form action="#" method="POST">
    
    <!-- Text Input -->
    <label for="text">Text:</label>
    <input type="text" id="text" name="text" placeholder="Enter text"><br><br>
    
    <!-- Password Input -->
    <label for="password">Password:</label>
    <input type="password" id="password" name="password" placeholder="Enter password"><br><br>
    
    <!-- Email Input -->
    <label for="email">Email:</label>
    <input type="email" id="email" name="email" placeholder="Enter email"><br><br>
    
    <!-- Number Input -->
    <label for="number">Number:</label>
    <input type="number" id="number" name="number" min="1" max="100" placeholder="Enter a number"><br><br>
    
    <!-- Date Input -->
    <label for="date">Date:</label>
    <input type="date" id="date" name="date"><br><br>
    
    <!-- Time Input -->
    <label for="time">Time:</label>
    <input type="time" id="time" name="time"><br><br>
    
    <!-- Color Input -->
    <label for="color">Color:</label>
    <input type="color" id="color" name="color"><br><br>
    
    <!-- File Input -->
    <label for="file">Upload File:</label>
    <input type="file" id="file" name="file"><br><br>
    
    <!-- Radio Button -->
    <label>Gender:</label>
    <input type="radio" id="male" name="gender" value="Male">
    <label for="male">Male</label>
    <input type="radio" id="female" name="gender" value="Female">
    <label for="female">Female</label><br><br>
    
    <!-- Checkbox -->
    <label>Newsletter Subscription:</label>
    <input type="checkbox" id="subscribe" name="subscribe" value="Yes">
    <label for="subscribe">Subscribe to newsletter</label><br><br>
    
    <!-- Range Input -->
    <label for="range">Volume:</label>
    <input type="range" id="range" name="range" min="1" max="10" value="5"><br><br>
    
    <!-- Textarea -->
    <label for="message">Message:</label>
    <textarea id="message" name="message" rows="4" cols="50" placeholder="Enter your message"></textarea><br><br>
    
    <!-- Select Dropdown -->
    <label for="country">Country:</label>
    <select id="country" name="country">
      <option value="USA">USA</option>
      <option value="India">India</option>
      <option value="UK">UK</option>
    </select><br><br>
    
    <!-- Hidden Input -->
    <input type="hidden" name="hidden_data" value="secret_value"><br><br>
    
    <!-- Submit Button -->
    <button type="submit">Submit</button>
    
  </form>
</body>
</html>

