# MDAP-EX_01-Portfolio
## Date:11-08-2025

## AIM:
To create a Portfolio using HTML and CSS.

## ALGORITHM:
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM:
## index.html:
```

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="p.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap">
</head>
<body>
    <header>
        <div class="container">
            <h1 class="logo">Portfolio</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

<section id="home" class="hero">
    <div class="container">
        <div class="hero-content">
            <h1>Hello, I'm <span class="highlight">Sharon Harshini</span></h1>
            <h2>Web Developer & Designer</h2>
            <p>I create beautiful and functional websites with clean code.</p>
            <a href="#contact" class="btn">Get In Touch</a>
        </div>
    </div>
</section>

<section id="about" class="about">
    <div class="container">
        <h2 class="section-title">About Me</h2>
        <div class="about-content">
            <div class="about-text">
                <h3>Who am I?</h3>
                <p>I'm a passionate web developer with expertise in creating responsive and user-friendly websites. With a strong foundation in HTML, CSS, and JavaScript, I bring ideas to life through code.</p>
                
                <h3>My Skills</h3>
                <div class="skills">
                    <div class="skill">
                        <span>HTML</span>
                        <div class="skill-bar">
                            <div class="skill-level" style="width: 95%"></div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>CSS</span>
                        <div class="skill-bar">
                            <div class="skill-level" style="width: 90%"></div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>JavaScript</span>
                        <div class="skill-bar">
                            <div class="skill-level" style="width: 85%"></div>
                        </div>
                    </div>
                    <div class="skill">
                        <span>UI/UX Design</span>
                        <div class="skill-bar">
                            <div class="skill-level" style="width: 80%"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<section id="projects" class="projects">
    <div class="container">
        <h2 class="section-title">My Projects</h2>
        <div class="project-grid">
            <div class="project-card">
                <div class="project-image">
                    <img src="e commerce.avif" alt="Project 1">
                </div>
                <div class="project-info">
                    <h3>E-commerce Website</h3>
                    <p>A fully responsive e-commerce platform with modern design and smooth user experience.</p>
                    <div class="project-tags">
                        <span>HTML</span>
                        <span>CSS</span>
                        <span>JavaScript</span>
                    </div>
                    <a href="#" class="btn-small">View Project</a>
                </div>
            </div>
            
            <div class="project-card">
                <div class="project-image">
                    <img src="portfolio.jpeg" alt="Project 2">
                </div>
                <div class="project-info">
                    <h3>Portfolio Template</h3>
                    <p>A clean and modern portfolio template for creative professionals.</p>
                    <div class="project-tags">
                        <span>HTML</span>
                        <span>CSS</span>
                    </div>
                    <a href="#" class="btn-small">View Project</a>
                </div>
            </div>
            
            <div class="project-card">
                <div class="project-image">
                    <img src="restaurant.png" alt="Project 3">
                </div>
                <div class="project-info">
                    <h3>Restaurant Website</h3>
                    <p>An elegant website for a high-end restaurant with online reservation system.</p>
                    <div class="project-tags">
                        <span>HTML</span>
                        <span>CSS</span>
                        <span>JavaScript</span>
                    </div>
                    <a href="#" class="btn-small">View Project</a>
                </div>
            </div>
        </div>
    </div>
</section>

<section id="contact" class="contact">
    <div class="container">
        <h2 class="section-title">Get In Touch</h2>
        <div class="contact-content">
            <div class="contact-info">
                <div class="contact-item">
                    <h3>Email</h3>
                    <p>sharonharshini@gmail.com</p>
                </div>
                <div class="contact-item">
                    <h3>Phone</h3>
                    <p>+91 9876543210</p>
                </div>
                <div class="contact-item">
                    <h3>Location</h3>
                    <p>Chennai</p>
                </div>
            </div>
            <div class="contact-form">
                <form>
                    <div class="form-group">
                        <label for="name">Name</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    <div class="form-group">
                        <label for="email">Email</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div class="form-group">
                        <label for="message">Message</label>
                        <textarea id="message" name="message" rows="5" required></textarea>
                    </div>
                    <button type="submit" class="btn">Send Message</button>
                </form>
            </div>
        </div>
    </div>
</section>

<footer>
    <div class="container">
        <p>&copy; 2025 My Portfolio. All Rights Reserved.</p>
    </div>
</footer>
</body>
</html>

```

## style.css:

```

    /* Global Styles */
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }
    
    :root {
        --primary-color: #4a6cf7;
        --secondary-color: #6c757d;
        --dark-color: #2d3748;
        --light-color: #f8f9fa;
        --success-color: #28a745;
        --danger-color: #dc3545;
        --transition: all 0.3s ease;
    }
    
    html {
        scroll-behavior: smooth;
    }
    
    body {
        font-family: 'Poppins', sans-serif;
        line-height: 1.6;
        color: var(--dark-color);
        background-color: #fff;
    }
    
    .container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 0 20px;
    }
    
    a {
        text-decoration: none;
        color: var(--dark-color);
    }
    
    ul {
        list-style: none;
    }
    
    img {
        max-width: 100%;
        height: auto;
    }
    
    .section-title {
        font-size: 2.5rem;
        text-align: center;
        margin-bottom: 50px;
        position: relative;
        color: var(--dark-color);
    }
    
    .section-title::after {
        content: '';
        position: absolute;
        bottom: -10px;
        left: 50%;
        transform: translateX(-50%);
        width: 80px;
        height: 4px;
        background-color: var(--primary-color);
    }
    
    .btn {
        display: inline-block;
        background-color: var(--primary-color);
        color: white;
        padding: 12px 30px;
        border-radius: 5px;
        font-weight: 500;
        transition: var(--transition);
        border: none;
        cursor: pointer;
    }
    
    .btn:hover {
        background-color: #3a57d0;
        transform: translateY(-3px);
        box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
    }
    
    .btn-small {
        display: inline-block;
        background-color: var(--primary-color);
        color: white;
        padding: 8px 20px;
        border-radius: 5px;
        font-weight: 500;
        font-size: 0.9rem;
        transition: var(--transition);
    }
    
    .btn-small:hover {
        background-color: #3a57d0;
        transform: translateY(-2px);
    }
    
    .highlight {
        color: var(--primary-color);
    }
    
    /* Header */
    header {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        background-color: white;
        box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        z-index: 1000;
    }
    
    header .container {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 20px;
    }
    
    .logo {
        font-size: 1.8rem;
        font-weight: 700;
        color: var(--dark-color);
    }
    
    nav ul {
        display: flex;
    }
    
    nav ul li {
        margin-left: 30px;
    }
    
    nav ul li a {
        font-weight: 500;
        transition: var(--transition);
    }
    
    nav ul li a:hover {
        color: var(--primary-color);
    }
    
    /* Hero Section */
    .hero {
        padding: 150px 0 100px;
        background-color: #f9fafb;
    }
    
    .hero .container {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    
    .hero-content {
        flex: 1;
        padding-right: 40px;
    }
    
    .hero-content h1 {
        font-size: 3.5rem;
        line-height: 1.2;
        margin-bottom: 20px;
    }
    
    .hero-content h2 {
        font-size: 1.8rem;
        color: var(--secondary-color);
        margin-bottom: 20px;
        font-weight: 500;
    }
    
    .hero-content p {
        font-size: 1.1rem;
        margin-bottom: 30px;
        color: var(--secondary-color);
    }
    
    .hero-image {
        flex: 1;
        text-align: center;
    }
    
    .hero-image img {
        max-width: 80%;
        border-radius: 20px;
        box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
    }
    
    /* About Section */
    .about {
        padding: 100px 0;
        background-color: white;
    }
    
    .about-content {
        display: flex;
        align-items: center;
        gap: 50px;
    }
    
    .about-image {
        flex: 1;
    }
    
    .about-image img {
        border-radius: 10px;
        box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
    }
    
    .about-text {
        flex: 1;
    }
    
    .about-text h3 {
        font-size: 1.8rem;
        margin-bottom: 20px;
        color: var(--dark-color);
    }
    
    .about-text p {
        margin-bottom: 30px;
        color: var(--secondary-color);
    }
    
    .skills {
        margin-top: 20px;
    }
    
    .skill {
        margin-bottom: 15px;
    }
    
    .skill span {
        display: block;
        margin-bottom: 5px;
        font-weight: 500;
    }
    
    .skill-bar {
        height: 10px;
        background-color: #e9ecef;
        border-radius: 5px;
        overflow: hidden;
    }
    
    .skill-level {
        height: 100%;
        background-color: var(--primary-color);
        border-radius: 5px;
    }
    
    /* Projects Section */
    .projects {
        padding: 100px 0;
        background-color: #f9fafb;
    }
    
    .project-grid {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
        gap: 30px;
    }
    
    .project-card {
        background-color: white;
        border-radius: 10px;
        overflow: hidden;
        box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        transition: var(--transition);
    }
    
    .project-card:hover {
        transform: translateY(-10px);
        box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
    }
    
    .project-image {
        overflow: hidden;
    }
    
    .project-image img {
        transition: var(--transition);
        width: 100%;
    }
    
    .project-card:hover .project-image img {
        transform: scale(1.05);
    }
    
    .project-info {
        padding: 25px;
    }
    
    .project-info h3 {
        font-size: 1.5rem;
        margin-bottom: 15px;
    }
    
    .project-info p {
        color: var(--secondary-color);
        margin-bottom: 20px;
    }
    
    .project-tags {
        display: flex;
        flex-wrap: wrap;
        margin-bottom: 20px;
    }
    
    .project-tags span {
        background-color: #e9ecef;
        padding: 5px 15px;
        border-radius: 20px;
        font-size: 0.8rem;
        margin-right: 10px;
        margin-bottom: 10px;
    }
    
    /* Contact Section */
    .contact {
        padding: 100px 0;
        background-color: white;
    }
    
    .contact-content {
        display: flex;
        gap: 50px;
    }
    
    .contact-info, .contact-form {
        flex: 1;
    }
    
    .contact-item {
        margin-bottom: 30px;
    }
    
    .contact-item h3 {
        font-size: 1.3rem;
        margin-bottom: 10px;
        color: var(--dark-color);
    }
    
    .contact-item p {
        color: var(--secondary-color);
    }
    
    .social-links {
        display: flex;
        gap: 15px;
        margin-top: 30px;
    }
    
    .social-link {
        display: inline-block;
        padding: 10px 20px;
        background-color: #f8f9fa;
        border-radius: 5px;
        transition: var(--transition);
    }
    
    .social-link:hover {
        background-color: var(--primary-color);
        color: white;
    }
    
    .form-group {
        margin-bottom: 20px;
    }
    
    .form-group label {
        display: block;
        margin-bottom: 8px;
        font-weight: 500;
    }
    
    .form-group input, .form-group textarea {
        width: 100%;
        padding: 12px 15px;
        border: 1px solid #ddd;
        border-radius: 5px;
        font-family: 'Poppins', sans-serif;
        font-size: 1rem;
        transition: var(--transition);
    }
    
    .form-group input:focus, .form-group textarea:focus {
        outline: none;
        border-color: var(--primary-color);
        box-shadow: 0 0 0 3px rgba(74, 108, 247, 0.1);
    }
    
    /* Footer */
    footer {
        background-color: var(--dark-color);
        color: white;
        padding: 30px 0;
        text-align: center;
    }
    
    /* Responsive Design */
    @media (max-width: 992px) {
        .hero .container {
            flex-direction: column;
            text-align: center;
        }
        
        .hero-content {
            padding-right: 0;
            margin-bottom: 50px;
        }
        
        .about-content {
            flex-direction: column;
        }
        
        .about-image {
            margin-bottom: 30px;
        }
        
        .contact-content {
            flex-direction: column;
        }
        
        .contact-info {
            margin-bottom: 50px;
        }
    }
    
    @media (max-width: 768px) {
        .section-title {
            font-size: 2rem;
        }
        
        .hero-content h1 {
            font-size: 2.5rem;
        }
        
        .project-grid {
            grid-template-columns: 1fr;
        }
        
        nav ul {
            gap: 15px;
        }
        
        nav ul li {
            margin-left: 15px;
        }
    }
    
    @media (max-width: 576px) {
        header .container {
            flex-direction: column;
            padding: 15px;
        }
        
        .logo {
            margin-bottom: 15px;
        }
        
        nav ul li {
            margin-left: 10px;
        }
        
        .hero-content h1 {
            font-size: 2rem;
        }
        
        .hero-content h2 {
            font-size: 1.5rem;
        }
        
        .about-text h3 {
            font-size: 1.5rem;
        }
        
        .section-title {
            font-size: 1.8rem;
        }
    }
    
```
## OUTPUT:
<img width="1919" height="1056" alt="Screenshot 2025-08-11 100212" src="https://github.com/user-attachments/assets/d9fbca11-19f4-436c-9237-df1ae18cb0b4" />
<img width="1915" height="1112" alt="Screenshot 2025-08-11 100221" src="https://github.com/user-attachments/assets/19b020e7-f8a1-4291-86f4-fcdad694ad1c" />
<img width="1919" height="1126" alt="Screenshot 2025-08-11 100237" src="https://github.com/user-attachments/assets/55d1e4dc-a380-4419-8db4-e9a39c44f87f" />
<img width="1918" height="1121" alt="Screenshot 2025-08-11 100249" src="https://github.com/user-attachments/assets/fd58548b-0a07-40b9-9ebd-dcc59d31b9d2" />


## RESULT:
The program for creating Portfolio using HTML and CSS is executed successfully.
