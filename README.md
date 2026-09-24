<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curriculum Vitae - Hun Hangchhuorn</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: #f0f2f5;
            color: #222222;
            display: flex;
            justify-content: center;
            padding: 30px 15px;
        }

        .cv-container {
            background-color: #ffffff;
            width: 100%;
            max-width: 800px;
            min-height: 1050px;
            padding: 50px 60px;
            border: 2px solid #222222;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.08);
            position: relative;
        }

        .top-divider {
            width: 78%;
            height: 2.5px;
            background-color: #111111;
            margin-bottom: 20px;
        }

        .header-section {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            margin-bottom: 25px;
        }

        .header-info {
            flex: 1;
        }

        .name {
            font-size: 32px;
            font-weight: 700;
            color: #111111;
            margin-bottom: 6px;
            letter-spacing: -0.5px;
        }

        .job-title {
            color: #338a4e; 
            font-size: 17px;
            font-weight: 600;
            margin-bottom: 12px;
        }

        .contact-info {
            font-size: 14px;
            line-height: 1.5;
            color: #444444;
        }

        .contact-info a {
            color: inherit;
            text-decoration: none;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        .contact-info p {
            margin: 2px 0;
        }

        .photo-container {
            margin-left: 20px;
        }

        .profile-photo {
            width: 120px;
            height: 140px;
            object-fit: cover;
            border: 1.5px solid #222222;
            border-radius: 4px;
            display: block;
            background-color: #eaeaea;
        }

        .section {
            margin-bottom: 24px;
        }

        .section-title {
            color: #338a4e;
            font-size: 16px;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 0.5px;
            margin-bottom: 8px;
            border-bottom: 1px solid #e2e8f0;
            padding-bottom: 4px;
        }

        .section-content {
            font-size: 14px;
            line-height: 1.55;
            color: #222222;
        }

        .skills-list p {
            margin-bottom: 4px;
            font-size: 14px;
        }

        .item-header {
            display: flex;
            justify-content: space-between;
            align-items: baseline;
            margin-bottom: 4px;
        }

        .item-title {
            color: #2e74a3; 
            font-size: 15px;
            font-weight: 600;
        }

        .date-range {
            font-size: 13.5px;
            color: #666666;
        }

        .entry {
            margin-bottom: 18px;
        }

        .bullet-list {
            margin: 6px 0 10px 20px;
            padding-left: 0;
        }

        .bullet-list li {
            margin-bottom: 4px;
            font-size: 14px;
        }

        .project-subtitle {
            font-weight: 600;
            margin-top: 6px;
            font-size: 14px;
            color: #333333;
        }

        .skills-tag {
            font-size: 13.5px;
            margin-top: 6px;
            color: #444444;
        }

        .skills-tag strong {
            font-weight: 600;
            color: #222222;
        }

        @media print {
            body {
                background-color: transparent;
                padding: 0;
            }
            .cv-container {
                border: none;
                box-shadow: none;
                max-width: 100%;
                min-height: 100vh;
                padding: 30px 40px;
            }
        }
    </style>
</head>
<body>

    <div class="cv-container">
        <header class="header-section">
            <div class="header-info">
                <h1 class="name">HUN HANGCHHUORN</h1>
                <div class="top-divider"></div>
                <div class="job-title">Computer Science Student</div>
                <div class="contact-info">
                    <p>Sangkat Tuek L'ak Ti Bei, Khan Tuol Kouk, Phnom Penh, St. 662</p>
                    <p>Phone: <a href="tel:+85571594666">(855) 715 946 66</a></p>
                    <p>Email: <a href="mailto:hunhangchhuorn@gmail.com">hunhangchhuorn@gmail.com</a></p>
                </div>
            </div>
            <div class="photo-container">
                <img src="IMG_1108.JPEG" alt="Profile Photo" class="profile-photo">
            </div>
        </header>

        <section class="section">
            <h2 class="section-title">Skills</h2>
            <div class="skills-list">
                <p><strong>Programming Languages:</strong> Java, C++, C#, JavaScript, HTML, SQL, Python</p>
                <p><strong>Databases:</strong> SQL Server, PostgreSQL</p>
                <p><strong>Core Fundamentals:</strong> Data Structures & Algorithms, Computer Networking</p>
            </div>
        </section>

        <section class="section">
            <h2 class="section-title">Education</h2>
            <div class="section-content">
                <div class="entry">
                    <div class="item-header">
                        <div class="item-title">Royal University of Phnom Penh — Bachelor of Computer Science</div>
                        <div class="date-range">2024 – Present (Expected 2028)</div>
                    </div>
                    <div class="project-subtitle">Key Academic Projects:</div>
                    <ul class="bullet-list">
                        <li>Collaborated with a team to assemble and test basic sensor circuits in class projects.</li>
                        <li>Collaborated with a team to assemble and test a mini robotic arm for picking and placing small objects.</li>
                        <li>Collaborated with a team to assemble, wire, and test a basic sensor-based RC car.</li>
                    </ul>
                </div>
            </div>
        </section>

        <section class="section">
            <h2 class="section-title">Experience</h2>
            <div class="section-content">
                <div class="entry">
                    <div class="item-header">
                        <div class="item-title">Freelance — Content Creator (Phnom Penh)</div>
                        <div class="date-range">2026 – Present</div>
                    </div>
                    <ul class="bullet-list">
                        <li>Researched digital trends and developed creative concepts, storyboards, and engaging video scripts.</li>
                        <li>Produced and edited multimedia content tailored for social media platforms to grow audience engagement.</li>
                        <li>Managed end-to-end creative workflows independently, from planning and production to final delivery on deadline.</li>
                    </ul>
                    <div class="skills-tag">
                        <strong>Skills:</strong> Video Editing, Scriptwriting, Storyboarding, Content Strategy, Time Management
                    </div>
                </div>
            </div>
        </section>
        <hr style="border: none; border-top: 1px solid #d1d5db; margin: 25px 0 12px 0;">
        <p style="font-size: 13px; color: #555555; margin: 0;">
          Copyright &copy; 2026 by HUN HANGCHHUORN. All rights reserved.
        </p>
    </div>

</body>
</html>
