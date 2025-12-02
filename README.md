<!-- 
ETCCWD103: Web Development 1 (HTML, CSS, JS Basics) Lab
All 19 Experiments - Complete Solutions
Author: Your Name
Date: November 2025
-->

<!-- ==================== EXPERIMENT 1 ==================== -->
<!-- Basic HTML Structure -->
<!-- exp1.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Experiment 1 - Basic HTML Structure</title>
</head>
<body>
    <h1>Welcome to My Website</h1>
    <p>This is my first webpage using proper HTML structure.</p>
</body>
</html>

<!-- ==================== EXPERIMENT 2 ==================== -->
<!-- Headings, Paragraphs, Line Breaks, Horizontal Rules -->
<!-- exp2.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Experiment 2 - Headings & Text</title>
</head>
<body>
    <h1>Main Heading (h1)</h1>
    <p>This is a paragraph under h1.</p>
    
    <h2>Subheading (h2)</h2>
    <p>This is a paragraph under h2.</p>
    <hr>
    
    <h3>Smaller Heading (h3)</h3>
    <p>Line 1<br>Line 2<br>Line 3</p>
    <hr>
    
    <h4>Even Smaller (h4)</h4>
    <h5>h5 Heading</h5>
    <h6>h6 Heading</h6>
    <p>Multiple paragraphs help organize content.<br>Line breaks create<br>vertical spacing.</p>
</body>
</html>

<!-- ==================== EXPERIMENT 3 ==================== -->
<!-- Hyperlinks and Images -->
<!-- exp3.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Experiment 3 - Links & Images</title>
</head>
<body>
    <h1>Links and Images</h1>
    
    <!-- Internal Link -->
    <p><a href="#section2">Jump to Section 2</a></p>
    
    <!-- External Links -->
    <p><a href="https://www.google.com" target="_blank">Visit Google</a></p>
    <p><a href="https://www.github.com" target="_blank">Visit GitHub</a></p>
    
    <!-- Images with alt and title -->
    <h2>Sample Images</h2>
    <img src="https://via.placeholder.com/300x200" 
         alt="Placeholder image" 
         title="This is a placeholder image"
         width="300" 
         height="200">
    
    <br><br>
    
    <!-- Responsive Image -->
    <img src="https://via.placeholder.com/400x300" 
         alt="Responsive placeholder" 
         title="Responsive image"
         style="max-width: 100%; height: auto;">
    
    <h2 id="section2">Section 2</h2>
    <p>This is section 2.</p>
    <p><a href="#top">Back to top</a></p>
</body>
</html>

<!-- ==================== EXPERIMENT 4 ==================== -->
<!-- Lists and Tables -->
<!-- exp4.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Experiment 4 - Lists & Tables</title>
</head>
<body>
    <header>
        <h1>Lists and Tables</h1>
        <nav>
            <a href="#ullist">Unordered List</a> | 
            <a href="#ollist">Ordered List</a> | 
            <a href="#table">Table</a>
        </nav>
    </header>
    
    <!-- Unordered List -->
    <h2 id="ullist">Unordered List</h2>
    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
    </ul>
    
    <!-- Ordered List -->
    <h2 id="ollist">Ordered List</h2>
    <ol>
        <li>First Step</li>
        <li>Second Step</li>
        <li>Third Step</li>
    </ol>
    
    <!-- Table with semantic tags -->
    <h2 id="table">Sample Table</h2>
    <table border="1" cellpadding="10" cellspacing="0">
        <tr>
            <td>Name</td>
            <td>Age</td>
            <td>City</td>
        </tr>
        <tr>
            <td>John</td>
            <td>25</td>
            <td>New York</td>
        </tr>
        <tr>
            <td>Jane</td>
            <td>28</td>
            <td>London</td>
        </tr>
    </table>
    
    <footer>
        <p>&copy; 2025 Lab Experiment 4</p>
    </footer>
</body>
</html>

<!-- ==================== EXPERIMENT 5 ==================== -->
<!-- Registration Form -->
<!-- exp5.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Experiment 5 - Registration Form</title>
</head>
<body>
    <h1>Registration Form</h1>
    <form>
        <label for="fname">First Name:</label>
        <input type="text" id="fname" name="fname" required>
        <br><br>
        
        <label for="lname">Last Name:</label>
        <input type="text" id="lname" name="lname" required>
        <br><br>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        <br><br>
        
        <label for="phone">Phone:</label>
        <input type="tel" id="phone" name="phone">
        <br><br>
        
        <label for="age">Age:</label>
        <input type="number" id="age" name="age" min="1" max="100">
        <br><br>
        
        <label for="gender">Gender:</label>
        <select id="gender" name="gender">
            <option>Select Gender</option>
            <option>Male</option>
            <option>Female</option>
            <option>Other</option>
        </select>
        <br><br>
        
        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="4" cols="50"></textarea>
        <br><br>
        
        <input type="checkbox" id="terms" name="terms">
        <label for="terms">I agree to terms</label>
        <br><br>
        
        <button type="submit">Submit</button>
        <button type="reset">Reset</button>
    </form>
</body>
</html>

<!-- ==================== EXPERIMENT 6 ==================== -->
<!-- CSS Styling (Inline, Internal, External) -->
<!-- exp6.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Experiment 6 - CSS Types</title>
    <style>
        /* Internal CSS */
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        
        .internal-style {
            color: blue;
            background-color: lightblue;
            padding: 10px;
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <h1>Three Types of CSS</h1>
    
    <!-- Inline CSS -->
    <p style="color: red; background-color: lightyellow; padding: 10px;">
        This is styled with inline CSS
    </p>
    
    <!-- Internal CSS -->
    <p class="internal-style">
        This is styled with internal CSS
    </p>
    
    <!-- External CSS (link in <head>) -->
    <p class="external-style">
        This would be styled with external CSS if linked
    </p>
    
    <p>Inline CSS has highest priority, followed by internal, then external.</p>
</body>
</html>

<!-- ==================== EXPERIMENT 7 ==================== -->
<!-- Color Formats and Custom Fonts -->
<!-- exp7.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Experiment 7 - Colors & Fonts</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
        }
        
        .hex-color {
            color: #FF5733;
        }
        
        .rgb-color {
            color: rgb(255, 87, 51);
        }
        
        .hsl-color {
            color: hsl(9, 100%, 60%);
        }
        
        .google-font {
            font-family: 'Playfair Display', serif;
            font-size: 32px;
            color: #2c3e50;
        }
    </style>
</head>
<body>
    <h1 class="google-font">Custom Font from Google Fonts</h1>
    
    <p class="hex-color">Text in HEX color (#FF5733)</p>
    <p class="rgb-color">Text in RGB color (255, 87, 51)</p>
    <p class="hsl-color">Text in HSL color (9, 100%, 60%)</p>
    
    <p>All three colors should appear identical!</p>
</body>
</html>

<!-- ==================== EXPERIMENT 8 ==================== -->
<!-- CSS Selectors -->
<!-- exp8.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Experiment 8 - CSS Selectors</title>
    <style>
        /* Element Selector */
        p {
            font-size: 16px;
        }
        
        /* Class Selector */
        .highlight {
            background-color: yellow;
        }
        
        /* ID Selector */
        #main-title {
            color: darkblue;
        }
        
        /* Attribute Selector */
        input[type="text"] {
            border: 2px solid blue;
        }
        
        /* Descendant Selector */
        section p {
            margin: 10px;
        }
    </style>
</head>
<body>
    <h1 id="main-title">CSS Selectors Demo</h1>
    
    <section>
        <p>Paragraph in section (descendant selector)</p>
        <p class="highlight">This paragraph has a class</p>
        <p>Another paragraph</p>
    </section>
    
    <input type="text" placeholder="Text input">
    <input type="password" placeholder="Password">
</body>
</html>

<!-- ==================== EXPERIMENT 9 ==================== -->
<!-- Box Model and Positioning -->
<!-- exp9.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Experiment 9 - Box Model & Positioning</title>
    <style>
        .relative-box {
            position: relative;
            left: 20px;
            top: 10px;
            border: 2px solid blue;
            padding: 20px;
            margin: 20px;
            background-color: lightblue;
        }
        
        .absolute-box {
            position: absolute;
            top: 50px;
            left: 50px;
            border: 2px solid red;
            padding: 15px;
            background-color: lightcoral;
        }
        
        .fixed-box {
            position: fixed;
            bottom: 10px;
            right: 10px;
            border: 2px solid green;
            padding: 15px;
            background-color: lightgreen;
        }
        
        .container {
            position: relative;
            border: 1px solid black;
            padding: 10px;
        }
    </style>
</head>
<body>
    <h1>Box Model and Positioning</h1>
    
    <div class="relative-box">
        Position: Relative (20px left, 10px top)
    </div>
    
    <div class="container">
        <div class="absolute-box">
            Position: Absolute (inside relative container)
        </div>
        <p>This is some text in the container.</p>
    </div>
    
    <div class="fixed-box">
        Position: Fixed (bottom-right corner)
    </div>
    
    <p>Scroll down to see the fixed box stay in place.</p>
    <p>Additional content...</p>
</body>
</html>

<!-- ==================== EXPERIMENT 10 ==================== -->
<!-- Blog Layout with CSS -->
<!-- exp10.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Experiment 10 - Blog Layout</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
        }
        
        .blog-container {
            width: 900px;
            margin: 0 auto;
        }
        
        .blog-post {
            float: left;
            width: 65%;
            padding-right: 20px;
        }
        
        .sidebar {
            float: right;
            width: 30%;
            background-color: #f0f0f0;
            padding: 15px;
        }
        
        .clearfix::after {
            content: "";
            display: table;
            clear: both;
        }
    </style>
</head>
<body>
    <div class="blog-container clearfix">
        <div class="blog-post">
            <h1>Blog Title</h1>
            <p>This is the main blog post content. It takes up about 65% of the width and floats to the left.</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        </div>
        
        <div class="sidebar">
            <h3>Recent Posts</h3>
            <ul>
                <li>Post 1</li>
                <li>Post 2</li>
                <li>Post 3</li>
            </ul>
        </div>
    </div>
</body>
</html>

<!-- ==================== EXPERIMENT 11 ==================== -->
<!-- Responsive Navigation and Card Layout with Flexbox -->
<!-- exp11.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Experiment 11 - Flexbox Layout</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: Arial, sans-serif;
        }
        
        nav {
            background-color: #333;
            padding: 15px;
        }
        
        nav ul {
            display: flex;
            justify-content: center;
            align-items: center;
            list-style: none;
            gap: 20px;
        }
        
        nav a {
            color: white;
            text-decoration: none;
        }
        
        .card-container {
            display: flex;
            justify-content: space-around;
            align-items: flex-start;
            gap: 20px;
            padding: 20px;
            flex-wrap: wrap;
        }
        
        .card {
            flex: 1;
            min-width: 250px;
            border: 1px solid #ddd;
            padding: 20px;
            text-align: center;
            background-color: #f9f9f9;
        }
    </style>
</head>
<body>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
    
    <div class="card-container">
        <div class="card">
            <h3>Card 1</h3>
            <p>This is a responsive card layout using Flexbox.</p>
        </div>
        <div class="card">
            <h3>Card 2</h3>
            <p>Cards are centered with justify-content and align-items.</p>
        </div>
        <div class="card">
            <h3>Card 3</h3>
            <p>Flexbox makes responsive layouts easy!</p>
        </div>
    </div>
</body>
</html>

<!-- ==================== EXPERIMENT 12 ==================== -->
<!-- Photo Gallery/Dashboard with CSS Grid -->
<!-- exp12.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Experiment 12 - CSS Grid</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }
        
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        
        .gallery-item {
            background-color: #f0f0f0;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
        }
        
        .gallery-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 4px;
        }
        
        .dashboard {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 15px;
            margin-top: 40px;
        }
        
        .dashboard-card {
            background-color: #e3f2fd;
            padding: 20px;
            border-radius: 8px;
        }
    </style>
</head>
<body>
    <h1>Photo Gallery</h1>
    <div class="gallery">
        <div class="gallery-item">
            <img src="https://via.placeholder.com/250x200/FF6B6B/FFFFFF" alt="Gallery 1">
            <p>Image 1</p>
        </div>
        <div class="gallery-item">
            <img src="https://via.placeholder.com/250x200/4ECDC4/FFFFFF" alt="Gallery 2">
            <p>Image 2</p>
        </div>
        <div class="gallery-item">
            <img src="https://via.placeholder.com/250x200/45B7D1/FFFFFF" alt="Gallery 3">
            <p>Image 3</p>
        </div>
        <div class="gallery-item">
            <img src="https://via.placeholder.com/250x200/FFA502/FFFFFF" alt="Gallery 4">
            <p>Image 4</p>
        </div>
    </div>
    
    <h1 style="margin-top: 40px;">Dashboard Layout</h1>
    <div class="dashboard">
        <div class="dashboard-card">
            <h3>Metric 1</h3>
            <p>120</p>
        </div>
        <div class="dashboard-card">
            <h3>Metric 2</h3>
            <p>250</p>
        </div>
        <div class="dashboard-card">
            <h3>Metric 3</h3>
            <p>680</p>
        </div>
    </div>
</body>
</html>

<!-- ==================== EXPERIMENT 13 ==================== -->
<!-- Mobile-First Responsive Design -->
<!-- exp13.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Experiment 13 - Responsive Design</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: Arial, sans-serif;
            padding: 10px;
        }
        
        /* Mobile First */
        .container {
            display: block;
        }
        
        .box {
            background-color: #3498db;
            color: white;
            padding: 20px;
            margin: 10px 0;
            width: 100%;
        }
        
        /* Tablet - 768px and above */
        @media (min-width: 768px) {
            .container {
                display: flex;
                gap: 20px;
            }
            
            .box {
                flex: 1;
                margin: 0;
            }
        }
        
        /* Desktop - 1024px and above */
        @media (min-width: 1024px) {
            body {
                max-width: 1200px;
                margin: 0 auto;
                padding: 20px;
            }
            
            .box {
                padding: 30px;
                font-size: 18px;
            }
        }
    </style>
</head>
<body>
    <h1>Responsive Design Demo</h1>
    <p>Resize your browser to see changes (Mobile → Tablet → Desktop)</p>
    
    <div class="container">
        <div class="box">Box 1</div>
        <div class="box">Box 2</div>
        <div class="box">Box 3</div>
    </div>
</body>
</html>

<!-- ==================== EXPERIMENT 14 ==================== -->
<!-- Hover Effects and Animations -->
<!-- exp14.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Experiment 14 - Animations</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }
        
        .hover-button {
            padding: 10px 20px;
            background-color: #3498db;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin: 10px;
            transition: all 0.3s ease;
        }
        
        .hover-button:hover {
            background-color: #2980b9;
            transform: scale(1.05);
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }
        
        .hover-button:active {
            transform: scale(0.95);
        }
        
        @keyframes slideIn {
            from {
                transform: translateX(-100%);
                opacity: 0;
            }
            to {
                transform: translateX(0);
                opacity: 1;
            }
        }
        
        .animated-box {
            width: 200px;
            height: 200px;
            background-color: #e74c3c;
            animation: slideIn 1s ease-in-out;
        }
        
        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }
        
        .bounce-image {
            width: 100px;
            height: 100px;
            animation: bounce 1s infinite;
            display: inline-block;
        }
    </style>
</head>
<body>
    <h1>Hover Effects and Animations</h1>
    
    <button class="hover-button">Hover Me!</button>
    <button class="hover-button">Click Me!</button>
    
    <h2>Slide-in Animation</h2>
    <div class="animated-box"></div>
    
    <h2>Bounce Animation</h2>
    <img src="https://via.placeholder.com/100" alt="Bouncing image" class="bounce-image">
</body>
</html>

<!-- ==================== EXPERIMENT 15 ==================== -->
<!-- JavaScript - Console and Webpage Output -->
<!-- exp15.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Experiment 15 - JavaScript Basics</title>
</head>
<body>
    <h1>JavaScript Output</h1>
    <p id="output">Output will appear here</p>
    
    <script>
        // Console output
        console.log("Hello from console!");
        console.log("This is internal JavaScript");
        
        // Webpage output
        document.getElementById("output").textContent = "Hello from JavaScript!";
        
        // Variables
        let name = "Student";
        let age = 20;
        console.log("Name: " + name + ", Age: " + age);
        
        // Basic arithmetic
        let a = 10;
        let b = 5;
        console.log("Sum: " + (a + b));
        console.log("Product: " + (a * b));
    </script>
</body>
</html>

<!-- ==================== EXPERIMENT 16 ==================== -->
<!-- JavaScript - Conditionals and Loops -->
<!-- exp16.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Experiment 16 - Conditionals & Loops</title>
</head>
<body>
    <h1>Conditionals and Loops</h1>
    <input type="number" id="userInput" placeholder="Enter a number">
    <button onclick="checkNumber()">Check</button>
    <p id="result"></p>
    
    <h2>Loop Output</h2>
    <p id="loopOutput"></p>
    
    <script>
        function checkNumber() {
            let num = document.getElementById("userInput").value;
            let result = "";
            
            // if-else
            if (num > 0) {
                result = "Positive number";
            } else if (num < 0) {
                result = "Negative number";
            } else {
                result = "Zero";
            }
            
            document.getElementById("result").textContent = result;
        }
        
        // Switch example
        function getDayName(day) {
            switch(day) {
                case 1:
                    return "Monday";
                case 2:
                    return "Tuesday";
                case 3:
                    return "Wednesday";
                default:
                    return "Other day";
            }
        }
        
        // Loop example
        let output = "Numbers: ";
        for (let i = 1; i <= 5; i++) {
            output += i + " ";
        }
        
        let whileOutput = "While loop: ";
        let j = 0;
        while (j < 5) {
            whileOutput += j + " ";
            j++;
        }
        
        document.getElementById("loopOutput").textContent = output + " | " + whileOutput;
    </script>
</body>
</html>

<!-- ==================== EXPERIMENT 17 ==================== -->
<!-- CRUD Operations on Arrays and Objects -->
<!-- exp17.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Experiment 17 - Arrays & Objects</title>
</head>
<body>
    <h1>CRUD Operations on Arrays and Objects</h1>
    <p id="arrayOutput"></p>
    <p id="objectOutput"></p>
    
    <script>
        // CRUD on Arrays
        let fruits = ["Apple", "Banana", "Orange"];
        console.log("Original array:", fruits);
        
        // Create
        fruits.push("Mango");
        console.log("After push:", fruits);
        
        // Read
        console.log("First element:", fruits[0]);
        
        // Update
        fruits[1] = "Blueberry";
        console.log("After update:", fruits);
        
        // Delete
        fruits.pop();
        console.log("After pop:", fruits);
        
        // Array methods
        let numbers = [1, 2, 3, 4, 5];
        
        // map()
        let doubled = numbers.map(n => n * 2);
        console.log("Doubled:", doubled);
        
        // filter()
        let evenNumbers = numbers.filter(n => n % 2 === 0);
        console.log("Even numbers:", evenNumbers);
        
        // reduce()
        let sum = numbers.reduce((acc, n) => acc + n, 0);
        console.log("Sum using reduce:", sum);
        
        document.getElementById("arrayOutput").textContent = "Array Operations: " + JSON.stringify({doubled, evenNumbers, sum});
        
        // Objects
        let student = {
            name: "John",
            age: 20,
            grade: "A"
        };
        
        console.log("Original object:", student);
        
        // Create
        student.email = "john@example.com";
        console.log("After adding email:", student);
        
        // Update
        student.age = 21;
        console.log("After updating age:", student);
        
        // Delete
        delete student.grade;
        console.log("After deleting grade:", student);
        
        document.getElementById("objectOutput").textContent = "Object Operations: " + JSON.stringify(student);
    </script>
</body>
</html>

<!-- ==================== EXPERIMENT 18 ==================== -->
<!-- Deep Copy and Shallow Copy -->
<!-- exp18.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Experiment 18 - Deep vs Shallow Copy</title>
</head>
<body>
    <h1>Deep Copy vs Shallow Copy</h1>
    <p id="copyOutput"></p>
    
    <script>
        // Shallow Copy Example
        let original = {
            name: "John",
            address: {
                city: "New York",
                zip: "10001"
            }
        };
        
        // Shallow copy
        let shallowCopy = {...original};
        shallowCopy.name = "Jane";
        shallowCopy.address.city = "Boston";
        
        console.log("Original after shallow copy modification:", original);
        console.log("Shallow copy is modified, but nested object affects original!");
        
        // Deep Copy Example
        let deepCopy = JSON.parse(JSON.stringify(original));
        deepCopy.name = "Bob";
        deepCopy.address.city = "Los Angeles";
        
        console.log("Original after deep copy modification:", original);
        console.log("Deep copy is independent, original is unchanged!");
        
        let output = "Shallow Copy: Modifies nested objects in original | Deep Copy: Complete independent copy";
        document.getElementById("copyOutput").textContent = output;
    </script>
</body>
</html>

<!-- ==================== EXPERIMENT 19 ==================== -->
<!-- Dynamic Project: To-Do List -->
<!-- exp19.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Experiment 19 - Dynamic To-Do List</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        
        .container {
            background: white;
            border-radius: 10px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
            width: 100%;
            max-width: 500px;
            padding: 30px;
        }
        
        h1 {
            color: #333;
            margin-bottom: 20px;
            text-align: center;
        }
        
        .input-container {
            display: flex;
            gap: 10px;
            margin-bottom: 20px;
        }
        
        input {
            flex: 1;
            padding: 10px;
            border: 2px solid #ddd;
            border-radius: 5px;
            font-size: 16px;
        }
        
        button {
            padding: 10px 20px;
            background-color: #667eea;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: 0.3s;
        }
        
        button:hover {
            background-color: #764ba2;
        }
        
        .todo-list {
            list-style: none;
        }
        
        .todo-item {
            background: #f0f0f0;
            padding: 15px;
            margin-bottom: 10px;
            border-radius: 5px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            transition: 0.3s;
        }
        
        .todo-item:hover {
            background: #e0e0e0;
        }
        
        .todo-item.completed {
            text-decoration: line-through;
            opacity: 0.7;
        }
        
        .delete-btn {
            background-color: #e74c3c;
            padding: 5px 10px;
            font-size: 12px;
        }
        
        .delete-btn:hover {
            background-color: #c0392b;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>My To-Do List</h1>
        
        <div class="input-container">
            <input type="text" id="todoInput" placeholder="Add a new task...">
            <button onclick="addTodo()">Add</button>
        </div>
        
        <ul class="todo-list" id="todoList"></ul>
    </div>
    
    <script>
        let todos = [];
        
        function addTodo() {
            let input = document.getElementById("todoInput");
            let text = input.value.trim();
            
            if (text === "") {
                alert("Please enter a task!");
                return;
            }
            
            let todo = {
                id: Date.now(),
                text: text,
                completed: false
            };
            
            todos.push(todo);
            input.value = "";
            renderTodos();
        }
        
        function deleteTodo(id) {
            todos = todos.filter(todo => todo.id !== id);
            renderTodos();
        }
        
        function toggleTodo(id) {
            let todo = todos.find(t => t.id === id);
            if (todo) {
                todo.completed = !todo.completed;
            }
            renderTodos();
        }
        
        function renderTodos() {
            let list = document.getElementById("todoList");
            list.innerHTML = "";
            
            todos.forEach(todo => {
                let li = document.createElement("li");
                li.className = "todo-item" + (todo.completed ? " completed" : "");
                
                li.innerHTML = `
                    <span onclick="toggleTodo(${todo.id})" style="cursor: pointer;">
                        ${todo.text}
                    </span>
                    <button class="delete-btn" onclick="deleteTodo(${todo.id})">Delete</button>
                `;
                
                list.appendChild(li);
            });
        }
        
        // Allow Enter key to add todo
        document.getElementById("todoInput").addEventListener("keypress", function(e) {
            if (e.key === "Enter") {
                addTodo();
            }
        });
    </script>
</body>
</html>

<!-- ==================== END OF ALL EXPERIMENTS ==================== -->
<!-- 
USAGE INSTRUCTIONS:
1. Save each experiment as a separate HTML file (exp1.html, exp2.html, etc.)
2. Or modify this file to test each experiment individually
3. Open in a web browser to view results
4. Check browser console (F12) for JavaScript output

Each experiment covers:
- Exp 1-5: HTML Fundamentals
- Exp 6-10: CSS Styling
- Exp 11-14: Advanced CSS (Flexbox, Grid, Animations)
- Exp 15-18: JavaScript Basics
- Exp 19: Complete Dynamic Project

Credits: ETCCWD103 Lab Course
-->
