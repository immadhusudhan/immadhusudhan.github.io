<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Professional CV</title>
    <style>
        /* Global Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            line-height: 1.6;
            color: #333;
            background-color: #f5f5f5;
            padding: 20px;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: #fff;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
        }
        
        /* Header Styles */
        header {
            display: flex;
            padding: 30px;
            background: #2c3e50;
            color: white;
        }
        
        .profile-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #fff;
            margin-right: 30px;
        }
        
        .header-text {
            flex: 1;
        }
        
        .header-text h1 {
            font-size: 2.2em;
            margin-bottom: 5px;
        }
        
        .header-text p {
            font-size: 1.1em;
            opacity: 0.9;
        }
        
        /* Main Content */
        .main-content {
            display: flex;
            padding: 30px;
        }
        
        /* Left Column */
        .left-column {
            flex: 1;
            padding-right: 30px;
        }
        
        .section {
            margin-bottom: 30px;
        }
        
        .section-title {
            font-size: 1.3em;
            color: #2c3e50;
            border-bottom: 2px solid #2c3e50;
            padding-bottom: 5px;
            margin-bottom: 15px;
            text-transform: uppercase;
        }
        
        .contact-info p {
            display: flex;
            align-items: center;
            margin-bottom: 10px;
        }
        
        .contact-info i {
            margin-right: 10px;
            color: #2c3e50;
            width: 20px;
            text-align: center;
        }
        
        .skills-list {
            list-style-type: none;
        }
        
        .skills-list li {
            margin-bottom: 10px;
        }
        
        .skill-name {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        
        .skill-bar {
            height: 10px;
            background: #ecf0f1;
            border-radius: 5px;
            overflow: hidden;
        }
        
        .skill-level {
            height: 100%;
            background: #2c3e50;
            border-radius: 5px;
        }
        
        /* Right Column */
        .right-column {
            flex: 2;
            border-left: 1px solid #eee;
            padding-left: 30px;
        }
        
        .experience-item, .education-item {
            margin-bottom: 25px;
        }
        
        .job-title, .degree {
            font-weight: bold;
            font-size: 1.1em;
            color: #2c3e50;
        }
        
        .company, .university {
            font-weight: bold;
            color: #555;
        }
        
        .date {
            color: #777;
            font-style: italic;
            margin: 5px 0;
        }
        
        .job-description, .education-description {
            margin-top: 10px;
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
            header {
                flex-direction: column;
                align-items: center;
                text-align: center;
            }
            
            .profile-img {
                margin-right: 0;
                margin-bottom: 20px;
            }
            
            .main-content {
                flex-direction: column;
            }
            
            .left-column {
                padding-right: 0;
                margin-bottom: 30px;
            }
            
            .right-column {
                border-left: none;
                padding-left: 0;
                border-top: 1px solid #eee;
                padding-top: 30px;
            }
        }
        
        /* Print Styles */
        @media print {
            body {
                background: none;
                padding: 0;
                font-size: 12pt;
            }
            
            .container {
                box-shadow: none;
            }
            
            .no-print {
                display: none;
            }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
</head>
<body>
    <div class="container">
        <header>
            <!-- Replace with your image or remove this div -->
            <div class="profile-img">
                <img src="https://via.placeholder.com/150" alt="Profile Picture" class="profile-img">
            </div>
            <div class="header-text">
                <h1>Madhusudhan Pantha</h1>
                <p>Student</p>
            </div>
        </header>
        
        <div class="main-content">
            <div class="left-column">
                <section class="section contact-info">
                    <h2 class="section-title">Contact</h2>
                    <p><i class="fas fa-phone"></i> 0442461844</p>
                    <p><i class="fas fa-envelope"></i> madhupantha10@gmail.com</p>
                    <p><i class="fas fa-map-marker-alt"></i>Lehdokkitie 4A Vantaa, Finland</p>
                    <p><i class="fab fa-linkedin"></i> https://www.linkedin.com/in/madhusudhanpantha/</p>
                    <p><i class="fab fa-github"></i> https://github.com/immadhusudhan</p>
                </section>
                
                <section class="section">
                    <h2 class="section-title">Skills</h2>
                    <ul class="skills-list">
                        <li>
                            <span class="skill-name">Programming (Python, JavaScript)</span>
                            <div class="skill-bar">
                                <div class="skill-level" style="width: 90%;"></div>
                            </div>
                        </li>
                        <li>
                            <span class="skill-name">Web Development</span>
                            <div class="skill-bar">
                                <div class="skill-level" style="width: 85%;"></div>
                            </div>
                        </li>
                        <li>
                            <span class="skill-name">Database Management</span>
                            <div class="skill-bar">
                                <div class="skill-level" style="width: 80%;"></div>
                            </div>
                        </li>
                        <li>
                            <span class="skill-name">Project Management</span>
                            <div class="skill-bar">
                                <div class="skill-level" style="width: 75%;"></div>
                            </div>
                        </li>
                        <li>
                            <span class="skill-name">UI/UX Design</span>
                            <div class="skill-bar">
                                <div class="skill-level" style="width: 70%;"></div>
                            </div>
                        </li>
                    </ul>
                </section>
                
                <section class="section">
                    <h2 class="section-title">Languages</h2>
                    <ul class="skills-list">
                        <li>
                            <span class="skill-name">English (Fluent)</span>
                            <div class="skill-bar">
                                <div class="skill-level" style="width: 100%;"></div>
                            </div>
                        </li>
                        <li>
                            <span class="skill-name">Spanish (Intermediate)</span>
                            <div class="skill-bar">
                                <div class="skill-level" style="width: 60%;"></div>
                            </div>
                        </li>
                    </ul>
                </section>
                
                <section class="section">
                    <h2 class="section-title">Certifications</h2>
                    <ul>
                        <li>Certified Web Developer - 2022</li>
                        <li>Project Management Professional - 2021</li>
                        <li>Google Analytics Certified - 2020</li>
                    </ul>
                </section>
            </div>
            
            <div class="right-column">
                <section class="section">
                    <h2 class="section-title">Professional Summary</h2>
                    <p>Experienced professional with X years in [your field]. Proven track record in [key skills/achievements]. Passionate about [relevant interests]. Strong background in [relevant areas] with expertise in [specific technologies/methods].</p>
                </section>
                
                <section class="section">
                    <h2 class="section-title">Work Experience</h2>
                    
                    <div class="experience-item">
                        <h3 class="job-title">Senior Software Engineer</h3>
                        <p class="company">Tech Solutions Inc.</p>
                        <p class="date">June 2019 - Present</p>
                        <div class="job-description">
                            <ul>
                                <li>Lead a team of 5 developers in creating enterprise-level applications</li>
                                <li>Developed and maintained web applications using React, Node.js, and MongoDB</li>
                                <li>Improved application performance by 40% through code optimization</li>
                                <li>Implemented CI/CD pipelines reducing deployment time by 60%</li>
                            </ul>
                        </div>
                    </div>
                    
                    <div class="experience-item">
                        <h3 class="job-title">Software Developer</h3>
                        <p class="company">Digital Innovations LLC</p>
                        <p class="date">January 2016 - May 2019</p>
                        <div class="job-description">
                            <ul>
                                <li>Developed and maintained company website and internal tools</li>
                                <li>Collaborated with cross-functional teams to deliver projects on time</li>
                                <li>Implemented automated testing reducing bugs by 30%</li>
                            </ul>
                        </div>
                    </div>
                </section>
                
                <section class="section">
                    <h2 class="section-title">Education</h2>
                    
                    <div class="education-item">
                        <h3 class="degree">Master of Computer Science</h3>
                        <p class="university">University of Technology</p>
                        <p class="date">2014 - 2016</p>
                        <div class="education-description">
                            <p>Specialized in Artificial Intelligence and Machine Learning. Thesis on "Advanced Neural Networks for Image Recognition".</p>
                        </div>
                    </div>
                    
                    <div class="education-item">
                        <h3 class="degree">Bachelor of Science in Software Engineering</h3>
                        <p class="university">State University</p>
                        <p class="date">2010 - 2014</p>
                    </div>
                </section>
                
                <section class="section">
                    <h2 class="section-title">Projects</h2>
                    <div class="experience-item">
                        <h3 class="job-title">E-commerce Platform</h3>
                        <p class="date">2022</p>
                        <div class="job-description">
                            <p>Developed a full-stack e-commerce platform with React, Node.js, and PostgreSQL. Implemented payment gateway integration and inventory management system.</p>
                        </div>
                    </div>
                    
                    <div class="experience-item">
                        <h3 class="job-title">Task Management App</h3>
                        <p class="date">2021</p>
                        <div class="job-description">
                            <p>Created a collaborative task management application with real-time updates using WebSockets and MongoDB.</p>
                        </div>
                    </div>
                </section>
            </div>
        </div>
        
        <div class="no-print" style="text-align: center; padding: 20px; color: #777; font-size: 0.9em;">
            <p>Last updated: <span id="current-date"></span></p>
        </div>
    </div>
    
    <script>
        // Add current date
        document.getElementById('current-date').textContent = new Date().toLocaleDateString('en-US', {
            year: 'numeric', 
            month: 'long', 
            day: 'numeric'
        });
    </script>
</body>
</html>
