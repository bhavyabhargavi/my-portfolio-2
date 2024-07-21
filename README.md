#home.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #0c83d3;
            overflow-x: hidden; 
        }
        header {
            background-color: #1095ee;
            color: #f5eded;
            padding: 20px;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            z-index: 1000; 
        }
        header h1 {
            font-size: 28px;
            margin: 0;
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            text-align: center;
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav ul li a {
            color: #f8f1f1;
            text-decoration: none;
            font-size: 18px;
        }
        nav ul li a:hover {
            color: #f0eee3;
        }
        section.home {
            padding: 100px 20px;
            text-align: center;
            margin-top: 80px; 
        }
        section.home h2 {
            font-size: 36px;
            color: #f0e6e6;
        }
        section.home p {
            font-size: 20px;
            color: #fbf9ff;
            margin-bottom: 40px;
        }
        .btn {
            display: inline-block;
            background-color: #197ee9;
            color: #f7eded;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 18px;
            transition: background-color 0.3s ease;
            cursor: pointer;
        }
        .btn:hover {
            background-color: #1870f5;
        }
        footer {
            background-color: #0e7fdb;
            color: #ece5e5;
            text-align: center;
            padding: 20px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        footer p {
            font-size: 16px;
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="home.html" style="color: #c20d0d;">Home</a></li>
                <li><a href="about.html" style="color: #b40a0a;">About</a></li>
                <li><a href="project.html" style="color: #ca1717;">Projects</a></li>
                <li><a href="contact.html" style="color: #b11313;">Contact</a></li>
                <li><a href="Submit.html" style="color: #c20d0d;">Submit</a></li>
            </ul>
        </nav>
    </header>

    <section class="home">
        <h2>Welcome to My Profile</h2>
        <p>This is our projects profile.</p>
        <p>BATCH - 2 </p>
        <p><br>THE PERSONS ARE : <br> 227R1A05E4 - G Bhavya Bhargavi
            <br>227R1A05D4 - B Deepthi 
            <br>227R1A05D2 - B Balaji Nayak <br></p>
        <button class="btn" id="viewProjects">View Projects</button>
        <div id="projectsList" style="display: none;">
            <h3>Projects</h3>
            <ul>
                <li>PONG GAME (JAVA)</li>
                <li>GUESS THE NUMBER GAME(PYTHON)</li>
                <li>TOP 5 MOVIES WEBSITE USING BOOTSTRAP </li>
                <li>ONLINE VOTING SYSTEM (DATA STRUCTURES)</li>
                <li>PORTFOLIO WEBSITE(HTML ,CSS)</li>
                <li>SPORTS MANAGEMENT SYSTEM(DBMS)</li>
                <li>HEALTH CARE PATIENT DETAILS (POWER BI)</li>
            </ul>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 My Portfolio</p>
    </footer>

    <script>
        document.getElementById("viewProjects").addEventListener("click", function() {
            var projectsList = document.getElementById("projectsList");
            if (projectsList.style.display === "none") {
                projectsList.style.display = "block";
            } else {
                projectsList.style.display = "none";
            }
        });
    </script>
</body>
</html>



#about.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #2abae6;
            color: #e9f7eb;
        }

        header {
            background-color: #2680ca;
            color: #e3f0e6;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            font-size: 36px;
            margin: 0;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5); 
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            text-align: center;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: #eaeeeb;
            text-decoration: none;
            font-size: 18px;
        }

        nav ul li a:hover {
            color: #ecebe2;
        }

        section.about {
            padding: 50px 20px;
            text-align: center;
            background-color: #2905a8; 
            border-radius: 10px; 
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); 
        }

        section.about h2 {
            font-size: 28px;
            color: #e7f0ec;
            margin-bottom: 20px;
        }

        section.about p {
            font-size: 18px;
            line-height: 1.6;
            margin-bottom: 30px;
        }

        .btn {
            display: inline-block;
            background-color: #007bff;
            color: #e3ece0;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 18px;
            transition: background-color 0.3s ease;
            border: none; 
            cursor: pointer; 
        }

        .btn:hover {
            background-color: #0056b3;
        }

        footer {
            background-color: #211fc7;
            color: #eaf0ec;
            text-align: center;
            padding: 20px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="home.html" style="color: #c20d0d;">Home</a></li>
                <li><a href="about.html" style="color: #b40a0a;">About</a></li>
                <li><a href="project.html" style="color: #ca1717;">Projects</a></li>
                <li><a href="contact.html" style="color: #b11313;">Contact</a></li>
                <li><a href="Submit.html" style="color: #c20d0d;">Submit</a></li>
                
            </ul>
        </nav>
    </header>

    <section class="about">
        <h2>About Me</h2>
        <p>These projects helpful in our future.We can keep it in our resume . It is easy to get a Jobs.</p>
        <p>PONG GAME : Its a game we have developed to play for kids.<br>
        GUESS THE NUMBER GAME: Its aa friendly game for both youngsters and kids.<br>
        TOP 5 MOVIES LIST : Its a list that we can easily know the top 5 movies in every theme so that we can easily watch.<br>
        ONLINE VOTING SYSTEM: In this we can easily vote in online no need of travelling kms.<br>
        MY PORTFOLIO WEBSITE : This is a website that shows a persons details and etc In this we added a page that if any person want to access a any project detail so that he or she can contact us.through details.<br>
        HEALTH CARE : In this we can access the data of the peoples health analysis.<br>
        SPORTS MANAGEMENT SYSTEM: In this we can know all the details of sports</p>
        <a href="contact.html" class="btn">Contact Me</a>
    </section>
    

    <footer>
        <p>&copy; 2024 My Portfolio</p>
    </footer>
</body>
</html>




#project.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projects</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        
        body {
            background-color: #f0f0f0;
            font-family: Arial, sans-serif;
            color: #333;
        }

        .header {
            background-color: #007bff;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            margin-bottom: 20px;
            overflow: hidden; 
        }

        .title {
            animation: marquee 10s linear infinite;
            white-space: nowrap;
        }

        @keyframes marquee {
            0% { transform: translateX(100%); }
            100% { transform: translateX(-100%); }
        }

        .projects {
            margin: 20px;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .project {
            margin-bottom: 20px;
            padding: 20px;
            background-color: #f9f9f9;
            border-radius: 5px;
        }

        .project h3 {
            color: #007bff;
            margin-bottom: 10px;
        }

        .project p {
            color: #666;
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: #007bff;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        .btn:hover {
            background-color: #0056b3;
        }

        footer {
            text-align: center;
            margin-top: 20px;
            padding: 10px 0;
            background-color: #007bff;
            color: #fff;
        }

        
    </style>
</head>
<body>
    <header class="header">
        <h1 class="title">My Portfolio</h1>
        <nav>
            <ul>
                <li><a href="home.html" style="color: #c20d0d;">Home</a></li>
                <li><a href="about.html" style="color: #b40a0a;">About</a></li>
                <li><a href="project.html" style="color: #ca1717;">Projects</a></li>
                <li><a href="contact.html" style="color: #b11313;">Contact</a></li>
                <li><a href="Submit.html" style="color: #c20d0d;">Submit</a></li>
                
            </ul>
        </nav>
    </header>

    <section class="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>PONG GAME</h3>
            <p><ol><li>LEVELS</li>
            <li>AUTHOR : SD</li>
            <li>TILTLE : TIT FOR TAT</li>
            <li>DESIGN : BHARGAV</li>
            </ol>
                </p>
        </div>
        <div class="project">
            <h3>GUESS THE NUMBER</h3>
            <p><ul><li>LEVELS</li>
            <li>DANCING EMOJI</li>
            <li>AUTHOR : SD</li>
            <li>TTILE : BRAIN CHALLENGE</li>
            <li>DESIGN : DEEPTHI</li></ul></p>
        </div>
        
        <div class="project">
            <h3>PORTFOLIO WEBSITE</h3>
            <p><ul><li>PROFILE</li>
                <li>CONTACT</li>
                <li>AUTHOR : SD</li>
                <li>TTILE : DETAILS</li>
                <li>DESIGN : DEVAKI</li></ul></p>
        </div>
        <div class="project">
            <h3>TOP 5 MOVIES</h3>
            <p><ul><li>LIST</li>
                <li>RATING</li>
                <li>AUTHOR : BHARGAVI</li>
                <li>TTILE : FAVOURITE</li>
                <li>DESIGN : VAISHNAVI</li></ul></p>
        </div>
        <div class="project">
            <h3>ONLINE VOTING SYSTEM</h3>
            <p><ul><li>VOTE</li>
                <li>ONLINE</li>
                <li>AUTHOR : SD</li>
                <li>TTILE : NO TRAVELLING</li>
                <li>DESIGN : YASODHA</li></ul></p>
        </div>
        <div class="project">
            <h3>HEALTH CARE</h3>
            <p><ul><li>HEALTH</li>
                <li>GRAPH</li>
                <li>AUTHOR : SD</li>
                <li>TTILE : PERCENTAGE OF PEOPLES HEALTH</li>
                <li>DESIGN : SREE DEVI</li></ul></p>
        </div>
        <div class="project">
            <h3>SPORTS MANAGEMENT SYSTEM</h3>
            <p><ul><li>DETAILS</li>
                <li>MANAGE THE SPORTS</li>
                <li>AUTHOR : SD</li>
                <li>TTILE : ALL TYPES OF SPORTS INFO </li>
                <li>DESIGN : HEMANTH</li></ul></p>
        </div>

        <a href="contact.html" class="btn">Contact Me</a>
    </section>

    <footer>
        <p>&copy; 2024 My Portfolio</p>
    </footer>
</body>
</html>




#contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <form id="contactForm" action="submit.html" method="get" onsubmit="return validateForm()">
    <title>Contact Me</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            background-color: #f8f9fa;
            font-family: Arial, sans-serif;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #007bff;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 10px;
        }

        nav ul li a {
            text-decoration: none;
            color: #fff;
        }

        .contact {
            margin: 20px;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .contact h2 {
            color: #007bff;
            text-align: center;
            margin-bottom: 20px;
        }

        form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        label {
            font-weight: bold;
            margin-bottom: 5px;
        }

        input[type="text"],
        input[type="email"],
        textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            box-sizing: border-box;
        }

        input[type="submit"] {
            width: 50%;
            padding: 10px;
            background-color: #007bff;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        
        button[type="button"] {
            width: 50%;
            padding: 10px;
            background-color: #007bff;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        input[type="submit"]:hover {
            background-color: #0056b3;
        }

        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #007bff;
            color: #fff;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .marquee {
            animation: marquee 15s linear infinite;
            white-space: nowrap;
        }

        @keyframes marquee {
            0% {
                transform: translateX(100%);
            }
            100% {
                transform: translateX(-100%);
            }
        }
    </style>
</head>
<body>
    <header>
        <marquee class="marquee"><h1>My Portfolio</h1></marquee>
        <nav>
            <ul>
                <li><a href="home.html" style="color: #c20d0d;">Home</a></li>
                <li><a href="about.html" style="color: #b40a0a;">About</a></li>
                <li><a href="project.html" style="color: #ca1717;">Projects</a></li>
                <li><a href="contact.html" style="color: #b11313;">Contact</a></li>
                <li><a href="Submit.html" style="color: #c20d0d;">Submit</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact">
        <h2>Contact Me</h2>
        <form id="contactForm" action="#" method="post" onsubmit="return saveFormData()">
            <label for="firstName">First Name:</label>
            <input type="text" id="firstName" name="firstName" required autocomplete="off"><br><br>
            <label for="lastName">Last Name:</label>
            <input type="text" id="lastName" name="lastName" required autocomplete="off"><br><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required autocomplete="off"><br><br>
            <label for="project">Project:</label><br>
            <input type="radio" id="project1" name="project" value="Project 1" required>
            <label for="project1">PONG GAME</label><br>
            <input type="radio" id="project2" name="project" value="Project 2" required>
            <label for="project2">GUESS THE NUMBER GAME</label><br>
            <input type="radio" id="project3" name="project" value="Project 3" required>
            <label for="project3">TOP 5 MOVIES</label><br>
            <input type="radio" id="project4" name="project" value="Project 4" required>
            <label for="project4">ONLINE VOTING SYSTEM</label><br>
            <input type="radio" id="project5" name="project" value=" Project 5" required>
            <label for="project5">MY PORTFOLIO</label><br>
            <input type="radio" id="project6" name="project" value="Project 6 " required>
            <label for="project6">SPORTS MANAGEMENT SYSTEM</label><br>
            <input type="radio" id="project7" name="project" value="Project 7" required>
            <label for="Project 7">HEALTH CARE</label><br><br>
            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" required autocomplete="off"></textarea><br>
            
            <input type="submit" value="Submit" class="btn"><br><br>
            <button type="button" onclick="clearForm()" class="btn">Clear Form</button> <!-- Clear Form button -->
            <br><br><br><br><br><br><br><br><br>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 My Portfolio</p>
    </footer>

    <script>
        function saveFormData() {
            var firstName = document.getElementById("firstName").value;
            var lastName = document.getElementById("lastName").value;
            var email = document.getElementById("email").value;
            var project = document.querySelector('input[name="project"]:checked').value;
            var message = document.getElementById("message").value;

            var contactData = {
                firstName: firstName,
                lastName: lastName,
                email: email,
                project: project,
                message: message
            };

            localStorage.setItem('contactData', JSON.stringify(contactData));

            window.location.href = 'display.html';
            return false;
        }

        function clearForm() {
            document.getElementById("contactForm").reset();
        }
    </script>
</body>
</html>



Submit.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Submitted Data</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        h2 {
            text-align: center;
        }
        .submitted-data {
            background-color: #f8f9fa;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <header>
        <marquee class="marquee"><h1>My Portfolio</h1></marquee>
        <nav>
            <ul>
                <li><a href="home.html" style="color: #c20d0d;">Home</a></li>
                <li><a href="about.html" style="color: #b40a0a;">About</a></li>
                <li><a href="project.html" style="color: #ca1717;">Projects</a></li>
                <li><a href="contact.html" style="color: #b11313;">Contact</a></li>
                <li><a href="Submit.html" style="color: #c20d0d;">Submit</a></li>
            </ul>
        </nav>
    </header>
    <h2>Submitted Data</h2>
    <div class="submitted-data">
        <ul id="submittedList">
        </ul>
    </div>

    <script>
        function getSubmissions() {
            const submissions = localStorage.getItem('submissions');
            return submissions ? JSON.parse(submissions) : [];
        }
        function saveSubmission(submission) {
            const submissions = getSubmissions();
            submissions.push(submission);
            localStorage.setItem('submissions', JSON.stringify(submissions));
        }

        const urlParams = new URLSearchParams(window.location.search);
        const submittedList = document.getElementById('submittedList');

        const submission = {
            firstName: urlParams.get("firstName"),
            lastName: urlParams.get("lastName"),
            email: urlParams.get("email"),
            project: urlParams.get("project"),
            message: urlParams.get("message")
        };

        saveSubmission(submission);

        const allSubmissions = getSubmissions();
        allSubmissions.forEach((sub, index) => {
            const li = document.createElement('li');
            li.innerHTML = `<strong>Submission ${index + 1}:</strong><br><br>
                            <ul>
                                <li><strong>First Name:</strong> ${sub.firstName}</li>
                                <li><strong>Last Name:</strong> ${sub.lastName}</li>
                                <li><strong>Email:</strong> ${sub.email}</li>
                                <li><strong>Project:</strong> ${sub.project}</li>
                                <li><strong>Message:</strong> ${sub.message}</li>
                            </ul>`;
            submittedList.appendChild(li);
        });
    </script>
</body>
</html>
