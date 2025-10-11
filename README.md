<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Mohit Wankhade - Software Engineer specializing in .NET and Angular development">
    <title>Mohit Wankhade | Software Engineer</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: #f4f4f4;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }

        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 80px 0;
            text-align: center;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.3rem;
            margin-bottom: 20px;
        }

        .contact-links {
            margin-top: 20px;
        }

        .contact-links a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.1rem;
            transition: opacity 0.3s;
        }

        .contact-links a:hover {
            opacity: 0.8;
        }

        section {
            background: white;
            margin: 30px 0;
            padding: 40px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        h2 {
            color: #667eea;
            font-size: 2rem;
            margin-bottom: 25px;
            border-bottom: 3px solid #667eea;
            padding-bottom: 10px;
        }

        .experience-item, .education-item {
            margin-bottom: 30px;
        }

        .experience-item h3 {
            color: #333;
            font-size: 1.4rem;
            margin-bottom: 5px;
        }

        .company {
            color: #764ba2;
            font-weight: 600;
            font-size: 1.1rem;
        }

        .date {
            color: #666;
            font-style: italic;
            margin-bottom: 10px;
        }

        .experience-item ul, .responsibilities ul {
            margin-left: 20px;
            margin-top: 10px;
        }

        .experience-item li, .responsibilities li {
            margin-bottom: 8px;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .skill-category {
            background: #f8f9fa;
            padding: 20px;
            border-radius: 5px;
            border-left: 4px solid #667eea;
        }

        .skill-category h3 {
            color: #667eea;
            margin-bottom: 10px;
        }

        .skill-category p {
            color: #555;
            line-height: 1.8;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 30px 0;
            margin-top: 40px;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }

            header p {
                font-size: 1rem;
            }

            section {
                padding: 25px;
            }

            .skills-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Mohit Wankhade</h1>
            <p>Software Engineer | .NET & Angular Developer</p>
            <p>📍 Bengaluru, India</p>
            <div class="contact-links">
                <a href="mailto:1998mohitwankhade@gmail.com">📧 Email</a>
                <a href="https://linkedin.com/in/mohit-wankhade-6b7989157" target="_blank">💼 LinkedIn</a>
                <a href="tel:+919907695839">📱 +91 9907695839</a>
            </div>
        </div>
    </header>

    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>Experienced Software Engineer with 3+ years of expertise in full-stack development using .NET Framework, ASP.NET Core, and Angular. Currently working at Eurofins, developing proprietary lab testing software used across multiple facilities. Proven track record of optimizing performance, leading teams, and delivering scalable solutions. Passionate about building efficient, maintainable code and mentoring junior developers.</p>
        </section>

        <section id="experience">
            <h2>Professional Experience</h2>
            
            <div class="experience-item">
                <h3>Software Engineer (Hybrid)</h3>
                <p class="company">Eurofins</p>
                <p class="date">Feb 2025 – Present</p>
                <ul>
                    <li>Developing and maintaining front-end features using Angular and back-end services using .NET Framework 4.8 for proprietary lab testing software</li>
                    <li>Managing SQL Server databases for data storage, retrieval, and reporting</li>
                    <li>Configured and monitored Grafana dashboards for logging and tracking application errors</li>
                    <li>Collaborating with QA and business teams to ensure smooth delivery of features and bug fixes</li>
                </ul>
                <p><strong>Skills:</strong> Angular, .NET Framework 4.8, SQL Server, Grafana</p>
            </div>

            <div class="experience-item">
                <h3>Software Engineer (Remote)</h3>
                <p class="company">TSS Software Limited</p>
                <p class="date">Jun 2023 – Feb 2025</p>
                <ul>
                    <li>Created an end-to-end workflow for employee lifecycle (creation, verification, deletion)</li>
                    <li>Led a team of 2 developers: code reviews, knowledge transfer, and mentorship</li>
                    <li>Automated testing workflows using Selenium APIs</li>
                </ul>
                <p><strong>Skills:</strong> Angular, SQL, ASP .Net Core, C#, ASP .Net Web API, ASP .Net MVC</p>
            </div>

            <div class="experience-item">
                <h3>Associate Software Engineer (Remote)</h3>
                <p class="company">TSS Software Limited</p>
                <p class="date">Jan 2022 – Jun 2023</p>
                <ul>
                    <li>Reduced record download time for 100k users from 4-5 hours to 30-45 minutes through optimization</li>
                    <li>Optimized database indexing and complex SQL join operations for improved query performance</li>
                    <li>Developed multi-threading for fetching data using available cores</li>
                    <li>Owned Image Comparison and Confidence Scores APIs and their deployment</li>
                </ul>
                <p><strong>Skills:</strong> AngularJS, ASP .Net Core, SQL, Multi-threading in C#, Automation, Git, ASP .Net MVC</p>
            </div>

            <div class="experience-item">
                <h3>Business Development Analyst (Remote)</h3>
                <p class="company">College Dunia</p>
                <p class="date">Sept 2020 - Dec 2020</p>
                <ul>
                    <li>Created automation tools for analyzing website traffic</li>
                    <li>Analyzed search keywords on the website</li>
                </ul>
                <p><strong>Skills:</strong> Data Science, Pandas, Matplotlib, Database Management</p>
            </div>
        </section>

        <section id="skills">
            <h2>Technical Skills</h2>
            <div class="skills-grid">
                <div class="skill-category">
                    <h3>Languages</h3>
                    <p>C#, C++, C, Angular, AngularJS, TypeScript, HTML, CSS, Java</p>
                </div>
                <div class="skill-category">
                    <h3>Frameworks</h3>
                    <p>ASP .Net Core, ASP .Net Web API, ASP .Net MVC, .NET Framework 4.8, Spring Boot</p>
                </div>
                <div class="skill-category">
                    <h3>Databases</h3>
                    <p>SQL Server, MySQL, SQLite, MongoDB</p>
                </div>
                <div class="skill-category">
                    <h3>Tools & Technologies</h3>
                    <p>Git, Visual Studio, Postman, Swagger API, Grafana, Selenium</p>
                </div>
            </div>
        </section>

        <section id="certifications">
            <h2>Certifications</h2>
            <ul>
                <li>C# Programming</li>
                <li>Cloud Computing</li>
                <li>Python Bootcamp</li>
                <li>SQL Server Query Optimization</li>
            </ul>
        </section>

        <section id="education">
            <h2>Education</h2>
            <div class="education-item">
                <h3>Bachelor of Technology in Information Technology</h3>
                <p class="company">Narsee Monjee Institute of Management Studies</p>
                <p class="date">Jun 2016 - May 2020</p>
                <p>CGPA: 2.82/4.0</p>
            </div>
            <div class="education-item">
                <h3>Senior Secondary, CBSE (Grade XI - XII)</h3>
                <p class="company">Christu Jyoti Convent Senior Secondary School</p>
                <p class="date">2014 - 2016</p>
            </div>
        </section>
    </div>

    <footer>
        <div class="container">
            <p>&copy; 2025 Mohit Wankhade. All rights reserved.</p>
            <p>Built with HTML & CSS | Hosted on GitHub Pages</p>
        </div>
    </footer>
</body>
</html>

