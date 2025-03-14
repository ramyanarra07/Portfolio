# Ex01 Portfolio
## Date:14-03-2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
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

## PROGRAM
*/
Developed By : NARRA RAMYA

Register Number:212223040128
*/

## HTML
```
<!DOCTYPE html>
<html lang="en">
 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css"/>
    <title> Portfolio</title>
    
    
</head>
 
<body>
    <nav>
        <div class="container nav-container">
            <a href="" class="logo">
                <h2><span>Portfolio</span></h2>
            </a>
            <ul>
                
                <li><a href="#About">About </a></li>
                <li><a href="#Services">Services</a></li>
                <li><a href="#Skills">Skills</a></li>
                <li><a href="#Contact">Contact </a></li>
 
            </ul>
        </div>
    </nav>
    <header>
        <div class="header-container container">
            <div class="header-left">
                <h1><span>Hi, I'm Ramya Narra.</span>
                </h1>
                <p>BE CSE 2nd Year</p>
                <h5>Front-End Developer</h5>
                
                <p>As an aspiring Front-end Developer passionate about programming,HTML,CSS,
                <br>Javascript,Algorithms,Data structures and software development principles.
                <br>Currently pursuing my Bachelor of Engineering at Saveetha Engineering College.
                <br>I am eager to explore and expand my technical knowledge skills and innovative 
                <br>ideas.Seeking opportunities to learn from experienced professionals and 
                <br>contribute to the success of a leading software company.
                </p>
 
               
            </div>
            <div class="header-right">
                <img src="pic.jpg" alt="">
            </div>
    </header>
 
    <section id="About">
        <h1><span>ABOUT</span></h1>
       
        <div class="container about-container">
        <p>I'm a computer science student passionate about programming,HTML,CSS,Javascript,algorithms,data structures,and software development principles. Currently pursuing my Bachelor of Engineering at Saveetha Engineering College, I am eager to explore and expand my technical knowledge, skills, and innovative ideas. Seeking opportunities to learn from experienced professionals and contribute to the success of a leading software company.</p>
        </div>
        <div class="about-content">
            <article class="about-article">
                
                <h5><span>Full Name</span></h5>
                <p>Ramya Narra</p>
 
            </article>
            <article class="about-article">
                
                <h5><span>Phone Number</span></h5>
                <p>+91 9346134138</p>
 
            </article>
            <article class="about-article">
                
                <h5><span>Email ID</span></h5>
                <p>ramyanarra123@gmail.com </p>
 
            </article>
        </div>
    </section>
 
 
    <section id="Services">
        <h1><span>Services</span></h1>
 
        <div class="container services-container">
            <article class="services-article">
                <h2>Software Development</h2>
        
                <p>Software development aims to create efficient, reliable, and easy-to-use software.
                software development process typically begins with the requirements-gathering phase.
                In this phase, the software application requirements are gathered from various stakeholders..</p>
            </article>
            <article class="services-article">
                
                <h2>Web Application
                    Development</h2>
                <p>Web application development describes the process of designing,building,testing and 
                   deploying web-based applications that will be installed on remote servers and delivered to users 
                   or customers via the internet.</p>
            </article>
            
        </div>
    </section>
 
    <section id="Skills">
        <h1><span>Skills</span></h1>
        <div class="container skills-container">
            <article class="skill-article">
 
                <h4>Web Design</h4>
            </article>
            <article class="skill-article">
 
                <h4>Problem solving</h4>
            </article>
            <article class="skill-article">
 
                <h4>Javascript</h4>
            </article>
            <article class="skill-article">
 
                <h4>UX/UI Design </h4>
            </article>
            <article class="skill-article">
 
                <h4>MySql</h4>
            </article>
            <article class="skill-article">
 
                <h4>Python</h4>
            </article>
            <article class="skill-article">
 
                <h4>HTML</h4>
            </article>
            <article class="skill-article">
 
                <h4>CSS</h4>
            </article>
 
        </div>
    </section>
    <section id="Contact">
        <h1><span>Contact </span></h1>
        <div class="container contact-container">
            <form>
                <div class="form-top">
                    <input type="text" placeholder="Name" required>
                    <input type="number" placeholder="Phone Number" required>
                    <input type="email" placeholder="Email ID" required>
                    <input type="text" placeholder="Address" required>
                </div>
                <div class="form-bottom">
                    <textarea name="message" placeholder="message"></textarea>
                    <button type="submit" class="btn btn-primary">Sumbit Now</button>
                </div>
            </form>
        </div>
    </section>
    <footer>
        &copy;Ramya Narra
 
    </footer>
    
 
</body>
</html>
```

## CSS
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
    list-style: none;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    outline: none;
}
:root {
    --color-white: #ffffff;
    --color-light: #828282;
    --color-primary: #1257e1;
    --color-dark: #212121;
    --color-border: #7e6868c4;
    --color-bg: #171717;
}

body {
    background: var(--color-bg);
    color: var(--color-white);
}
h1 {
    font-size: 35px;
    font-weight: 400;
    color: white;
    line-height: 10px;
    margin: 1rem 0;
}

h2 {
    font-size: 36px;
    font-weight: 400;
    line-height: 30px;
    color: var(--color-border);
}

h4 {
    font-size: 20px;
    font-weight: 500;
    line-height: 30px;
    color: var(--color-primary);
}

h5 {
    font-size: 18px;
    font-weight: 500;
    line-height: 20px;
    color: #3498db;  
}

p {
    color: var(--color-white);
    font-size: 17px;
    line-height: 23px;
}

.btn {
    display: inline-block;
    width: fit-content;
    border: 1px solid white;
    padding: 12px 30px;
    font-size: 15px;
    font-weight: 500;
    transition: .4s ease;
    color: #ffff;
    border-radius: 6px;
}

.btn:hover {
    background: white;
    color: var(--color-bg);
    border-color: transparent;
}

.btn-primary {
    background: var(--color-primary);
    border-color: transparent;
}

.container {
    max-width: 160px;
    width: 90%;
    margin: 0 auto;
}

nav {
    height: 5rem;
    width: 100%;
    position: fixed;
    top: 0;
    right: 0;
}

.nav-container {
    height: 80%;
    justify-content: center;
    align-items: center;
    display: flex;
}

ul {
    display: block;
    list-style-type: disc;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 950px;
    margin-inline-end: 100px;
    padding-inline-start: 40px;
}

.logo h2 {
    color: rgb(255, 255, 255);
    font-size: 32px;
}

.nav-container ul {
    display: flex;
    align-items: center;
    gap: 40px;
}

.nav-container ul li a {
    color: #ffffff;
    font-size: 16px;
    font-weight: 400;
    transition: .4s ease;
}

.nav-container ul li a:hover {
    color: var(--color-primary);
}

span {
    color: var(--color-primary);
    text-shadow: 0 0 10px rgb(208, 43, 226);
}

header {
    margin-top: 190px;
}

.header-container {
    display: grid;
    grid-template-columns: 548% 120%;
    align-items: center;
    margin-left: 10%;
}

img {
    width: 170%;
    display: block;
}

.header-container p {
    width: 90%;
    margin: 2rem 0 1rem;
    font-style: normal;
}

.name {
    width: 50px;
    font-size: 60px;
    font-weight: 500;
}

.header-container h5 {
    margin: 1rem 0;
    color: var(--color-light);
}

.header-action-aria {
    display: flex;
    gap: 10px;
    align-items: center;
}

#About {
    padding-top: 70px;
}

section > h1 {
    text-align: center;
    margin-bottom: 44px;
    margin-top: 158px;
}

.about-container p {
    margin: 4px auto;
    width: 62%;
    position: absolute;
    margin-left: -26%;
    font-style: normal;
    font-weight: 55px;
    text-align: center;
    font-size: 25px;
}

.about-content {
    margin-top: 600%;
    display: grid;
    margin: 280px 18%;
    grid-template-columns: repeat(4, 1fr);
    justify-content: center;
    align-items: center;
}

.about-article {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    margin: auto;
    gap: 10px;
    text-align: center;
}

.about-article img {
    width: 62px;
}

#Services {
    padding-top: 8px;
}

.services-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 60px;
    margin-top: 100px;
    justify-content: center;
}

.services-article {
    background: var(--color-dark);
    display: flex;
    flex-direction: column;
    gap: 30px;
    padding: 50px;
    border-bottom: 4px solid transparent;
}

.services-article:hover {
    border-color: var(--color-primary);
}

.services-article img {
    width: 40px;
}

.services-article p {
    font-family: 'Times New Roman', Times, serif;
}

#skills {
    padding-top: -1px;
}

.skills-container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 60px;
    margin-top: 100px;
    justify-content: center;
    text-align: center;
}

.skill-article {
    background: var(--color-dark);
    display: flex;
    flex-direction: column;
    text-align: center;
    justify-content: center;
    padding: 16px 90px;
    border-radius: 14px;
    border-bottom: 4px solid transparent;
}

.skill-article:hover {
    border-color: var(--color-primary);
}

#Blog .row {
    width: 80%;
    margin: auto;
}

#Blog .row .header {
    width: 60%;
    text-align: center;
    margin: auto;
}

#Blog .row .header h1 {
    padding-top: 280px;
    gap: 19px;
}

.header h1 {
    margin: 29px;
}

#Blog .row .header p {
    margin-top: 15px;
    font-size: 18px;
    line-height: 1.3;
}

.content .card img {
    width: 100%;
    height: auto;
}

.content .card p {
    font-size: 20px;
    line-height: 1.2;
}

.content {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin: 44px;
}

.content .card {
    flex: 2;
    margin: 50px 50px;
    box-shadow: 0px 4px 0px rgba(0, 0, 0, 0, 1);
    background-color: #212121;
    border-radius: 19px;
}

#Contact {
    padding-top: 120px;
}

.contatact-container {
    margin-top: 80px;
}

form {
    width: 60%;
    margin: 0 auto;
    position: absolute;
    margin-left: -25%;
}

.form-top {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 40px;
}

form input {
    padding: 10px;
    background: transparent;
    margin-bottom: 30px;
    color: var(--color-light);
    border: none;
    box-shadow: 0 1px 0 0 var(--color-border);
    transition: .4s ease;
    font-size: 15px;
    line-height: 18px;
    font-weight: 500;
}

form input:focus {
    border-bottom: 1px solid rgb(226, 43, 208);
    color: var(--color-primary);
    box-shadow: none;
}

.form-bottom {
    display: flex;
    flex-direction: column;
    gap: 30px;
    align-items: center;
}

.form-bottom textarea {
    width: 100%;
    padding: 9px;
    height: 100px;
    background: transparent;
    resize: none;
    font-size: 14px;
    line-height: 18px;
    font-weight: 500;
    margin-top: 17px;
    border: 1px solid var(--color-border);
    color: var(--color-primary);
}

.form-bottom textarea :focus {
    border-bottom: 1px solid rgb(226, 43, 76);
}

footer {
    margin-top: 500px;
    margin-bottom: 40px;
    text-align: center;
    color: var(--color-border);
}

.naWinScroll {
    background: var(--color-dark);
    box-shadow: 0 0.1rem rgba(0, 0, 0, 0, 7);
}
```
## OUTPUT
## HOME
![WhatsApp Image 2025-03-14 at 10 38 23_5d095437](https://github.com/user-attachments/assets/7b6dc361-55c9-45ec-8a55-a48be494c433)
## ABOUT
![WhatsApp Image 2025-03-14 at 10 38 40_cdb00d2b](https://github.com/user-attachments/assets/859508e6-2b3d-4557-b6c0-61edf89f6a91)
## SERVICES
![WhatsApp Image 2025-03-14 at 10 38 58_781b1191](https://github.com/user-attachments/assets/7e96b435-61d9-4b48-a252-daeb606abc3c)
## SKILLS
![WhatsApp Image 2025-03-14 at 10 39 15_ded83026](https://github.com/user-attachments/assets/0ed5ba94-193c-4b36-a5e7-b7c39af5d2fd)
## CONTACT
![WhatsApp Image 2025-03-14 at 10 39 29_62baf036](https://github.com/user-attachments/assets/2d64fe5f-91f5-4029-9922-0a10c047a189)



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
