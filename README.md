HTML CODE:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Your Resume Portfolio</title>
</head>

<body>
    <header>
        <h1>Harish B</h1>
        <p>Student</p>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>An Alpha and Skillfull person with exquisite talent of adaptability who
            wishes to create good impact on designing software in IT Sector and to
            enrich the knowledge on upcoming technologies</p>
    </section>

    <section id="experience">
        <h2>Certications</h2>
        <ul>
            <li>Particpated in Stop Motion Animation and Won 2nd Prize Conducted by Maac Coimbatore </li>
            <li>Participated in PHP Guest lecturer and gained a certification </li>
            <li>Participated in Mass Tree plantation Program "Oru Vidhi Puratchi which is Offers by Round table India, Kalam people trust, Iyarkai Foundation </li>
            <li>Participated in 7 days NSS Volunteers conducted by KG College of Arts and Science </li>
        </ul>
        
        </div>
    </section>

    <section id="education">
        <h2>Education</h2>
        <div class="education">
            <h3>Bachelor of Science in Information Technology</h3>
            <p><strong>College:</strong> KG College of Arts and Science</p>
            <p><strong>Graduation Year:</strong> 2024</p>
        </div>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML/CSS</li>
            <li>Graphic Designing</li>
            <li>2D Animation</li>
            <li>C Programming</li>
            <li>C++</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Information</h2>
        <p>Email: 2126jb15@kgcas.com</p>
        <p>Phone: 9080785818</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/arun-m-04137b27a" target="_blank">LinkedIn Profile</a></p>
    </section>
</body>
</html>




CSS CODE:


body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #130b5f;
    color: #fff;
    text-align: center;
    padding: 20px;
}

header h1 {
    margin: 0;
}

section {
    padding: 20px;
}

.job {
    margin: 20px 0;
}

h2 {
    background-color: #130b5f;
    color: #fff;
    padding: 10px;
}

ul {
    list-style: none;
    padding: 0;
}

ul li {
    margin-bottom: 10px;
}

a {
    color: #0070c9;
    text-decoration: none;
}

a:hover {
    text-decoration: underline;
}
