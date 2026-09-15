```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">

    <!-- Makes the webpage work well on phones and computers -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Timothy - Personal CV</title>

    <style>
        /* ==============================
           BASIC PAGE STYLES
           ============================== */

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #eef2ff, #dff7ff);
            color: #222;
            line-height: 1.6;
        }

        /* Main CV container */
        .container {
            width: 90%;
            max-width: 900px;
            margin: 40px auto;
            background-color: white;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
        }

        /* ==============================
           HEADER
           ============================== */

        header {
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(135deg, #4f46e5, #06b6d4);
            color: white;
        }

        /* Profile photo */
        .profile-photo {
            width: 150px;
            height: 150px;
            object-fit: cover;
            border-radius: 50%;
            border: 5px solid white;
            margin-bottom: 15px;
        }

        header h1 {
            font-size: 40px;
            margin-bottom: 5px;
        }

        header p {
            font-size: 18px;
        }

        /* ==============================
           CONTENT SECTIONS
           ============================== */

        .content {
            padding: 30px;
        }

        section {
            margin-bottom: 30px;
        }

        section h2 {
            color: #4f46e5;
            border-left: 5px solid #06b6d4;
            padding-left: 10px;
            margin-bottom: 12px;
        }

        section p {
            color: #555;
        }

        /* Education card */
        .education-card {
            background-color: #f1f5ff;
            padding: 18px;
            border-radius: 12px;
            border-left: 4px solid #4f46e5;
        }

        .education-card h3 {
            color: #333;
            margin-bottom: 5px;
        }

        /* Skills */
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }

        .skill {
            background: linear-gradient(135deg, #06b6d4, #4f46e5);
            color: white;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 14px;
        }

        /* Facebook link */
        .social-link {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 18px;
            background-color: #1877f2;
            color: white;
            text-decoration: none;
            border-radius: 8px;
            transition: 0.3s;
        }

        .social-link:hover {
            background-color: #0d5dcc;
            transform: translateY(-2px);
        }

        /* ==============================
           FOOTER
           ============================== */

        footer {
            text-align: center;
            padding: 18px;
            background-color: #f1f5f9;
            color: #666;
            font-size: 14px;
        }

        /* ==============================
           MOBILE RESPONSIVE DESIGN
           ============================== */

        @media (max-width: 600px) {
            .container {
                width: 94%;
                margin: 20px auto;
            }

            header {
                padding: 30px 15px;
            }

            header h1 {
                font-size: 30px;
            }

            header p {
                font-size: 16px;
            }

            .profile-photo {
                width: 120px;
                height: 120px;
            }

            .content {
                padding: 20px;
            }
        }
    </style>
</head>

<body>

    <!-- Main CV container -->
    <div class="container">

        <!-- Header with name, introduction and photo -->
        <header>

            <!-- Put your photo in the same folder and name it photo.jpg -->
            <img src="photo.jpg" alt="Timothy's Profile Photo" class="profile-photo">

            <h1>Timothy</h1>

            <p>IT Major Student at Payap University</p>

        </header>

        <!-- Main CV content -->
        <div class="content">

            <!-- Introduction section -->
            <section>
                <h2>About Me</h2>

                <p>
                    Hello! My name is Timothy. I am a student at
                    Payap University, studying Information Technology.
                    I am interested in technology and developing my
                    skills in the IT field.
                </p>
            </section>

            <!-- Education section -->
            <section>
                <h2>Education</h2>

                <div class="education-card">
                    <h3>Payap University</h3>

                    <p>
                        Information Technology (IT) Major
                    </p>
                </div>
            </section>

            <!-- Skills section -->
            <section>
                <h2>Skills</h2>

                <div class="skills">

                    <span class="skill">HTML</span>
                    <span class="skill">CSS</span>
                    <span class="skill">Web Development</span>
                    <span class="skill">Computer Skills</span>
                    <span class="skill">Problem Solving</span>

                </div>
            </section>

            <!-- Contact / social link -->
            <section>
                <h2>Connect With Me</h2>

                <p>
                    You can visit my Facebook profile using the link below.
                </p>

                <a
                    href="https://www.facebook.com/share/1CH3wm1WWS/"
                    target="_blank"
                    class="social-link"
                >
                    Visit My Facebook
                </a>
            </section>

        </div>

        <!-- Footer -->
        <footer>
            © 2026 Timothy | Personal CV
        </footer>

    </div>

</body>
</html>
```