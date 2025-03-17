<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Resume</title>
    <style>
        /* Google Font */
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');

        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 20px;
            text-align: center;
            background-color: #f4f4f4;
        }

        .resume-container {
            width: 60%;
            margin: auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
        }

        header {
            text-align: center;
            border-bottom: 2px solid #007BFF;
            padding-bottom: 15px;
        }

        .profile-pic {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            margin-bottom: 10px;
            border: 3px solid #007BFF;
            pointer-events: none; /* Prevent dragging */
            user-drag: none; /* Disable drag on some browsers */
            -webkit-user-drag: none; /* Disable drag on WebKit browsers */
        }

                .profile-pic-container {
            position: relative;
            display: inline-block;
        }

        .profile-pic-container img {
            pointer-events: none; /* Prevent interaction */
        }

                @media print {
            .profile-pic-container {
                display: none;
            }

            body {
                background: white;
            }

            .resume-container {
                box-shadow: none;
                width: 100%;
                padding: 10px;
            }
        }
    </style>
    <script>
        // Disable right-click on the image
        document.addEventListener("DOMContentLoaded", function() {
            const img = document.querySelector(".profile-pic");
            img.addEventListener("contextmenu", function(event) {
                event.preventDefault();
            });
        });
    </script>
</head>
<body>

    <div class="resume-container" id="resume">
        <header>
            <!-- Profile Picture Container to Apply Security -->
            <div class="profile-pic-container">
                <img src="C:\Users\A12-67\Pictures\unnamed.jpg" 
                     alt="Profile Picture" class="profile-pic">
            </div>

            <h1>Merlin Sharon A</h1>
            <p>Student | <a href="mailto:merlinsharon.18092006@gmail.com">merlinsharon.18092006@gmail.com</a> | 9500158250</p>
            <p>
                <a href="https://linkedin.com/in/merlinsharon" target="_blank">LinkedIn</a> | 
                <a href="https://github.com/merlinsharon" target="_blank">GitHub</a>
            </p>
        </header>

        <section>
            <h2>Summary</h2>
            <p>A student currently pursuing B.E Computer Science and Engineering at Loyola-ICAM College of Engineering and Technology and is interested in cyber security and cloud computing.</p>
        </section>

        <section>
            <h2>Education</h2>
            <p><strong>10th:</strong> - St. Joseph of Cluny HSS (2021 - 2022)</p>
            <p><strong>12th:</strong> - St. Joseph of Cluny HSS (2023 - 2024)</p>
            <p><strong>UG:</strong> - Loyola-ICAM College of Engineering and Technology (2024 - 2028)</p>
        </section>

        <section>
            <h2>Interests</h2>
            <p>Interested in Python and C programming languages</p>
            <ul>
                <li>Cyber Security Analysis</li>
                <li>Ethical Hacking</li>
                <li>Cloud Computing</li>
            </ul>
        </section>

        <section>
            <h2>Projects</h2>
            <ul>
                <li><strong>Portfolio Website</strong> - Built a personal portfolio using HTML and CSS</li>
                <li><strong>Locust Detector</strong> - Developed an AI model that detected the presence of locusts in a particular area.</li>
            </ul>
        </section>

        <section>
            <h2>Skills</h2>
            <ul class="skills-list">
                <li>HTML, CSS</li>
                <li>Python, Tkinter</li>
                <li>C, C++</li>
                <li>MySQL</li>
                <li>Advanced Excel</li>
                <li>Git, GitHub</li>
            </ul>
        </section>

        <section>
            <h2>Certifications</h2>
            <ul>
                <li>HDCA Diploma - CSC</li>
                <li>Ethical Hacking, Robotics, AI Developer - myCaptain</li>
                <li>Cyber Security - Corizo</li>
            </ul>
        </section>

        <section>
            <h2>Other Interests</h2>
            <p>Well versed in English and Hindi</p>
            <ul>
                <li>MC</li>
                <li>Vocals</li>
                <li>Artwork</li>
            </ul>
        </section>
    </div>

</body>
</html>
