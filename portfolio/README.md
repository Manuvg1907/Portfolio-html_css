# PORTFOLIO

Portfolio Website - Manu V G

This is a personal portfolio website built using HTML and CSS.
It showcases my introduction, skills, projects, and contact details.
The design is clean, responsive, and beginner-friendly.

Features:
- Hero section with intro
- About Me, Projects, Skills, and Contact sections
- Simple and responsive layout

Created by Manu V G | manuvgcs26@gmail.com


<section id="about" class="about-section">
  <div class="container">
    <h2>About Me</h2>
    <div class="about-content">
      <img src="images/profile.jpg" alt="My Photo" class="about-image" />
      <div class="about-text">
        <p>
          Hi, I'm <strong>Manu V G</strong>, a passionate front-end developer and computer science student. I specialize in building responsive websites using HTML, CSS, and JavaScript.
        </p>
        <p>
          I enjoy turning ideas into visually appealing and functional websites. I'm currently learning React and backend development to become a full-stack developer.
        </p>
      </div>
    </div>
  </div>
</section>

.about-section {
  background-color: #f9f9f9;
  padding: 60px 20px;
  font-family: Arial, sans-serif;
}

.about-section h2 {
  text-align: center;
  font-size: 36px;
  color: #333;
  margin-bottom: 40px;
}

.about-content {
  display: flex;
  flex-direction: column;
  align-items: center;
  max-width: 900px;
  margin: 0 auto;
  gap: 30px;
}

.about-image {
  width: 180px;
  height: 180px;
  border-radius: 50%;
  object-fit: cover;
  border: 3px solid #ccc;
}

.about-text {
  text-align: center;
  font-size: 18px;
  color: #444;
  line-height: 1.6;
}

@media (min-width: 768px) {
  .about-content {
    flex-direction: row;
    text-align: left;
  }

  .about-text {
    flex: 1;
    padding-left: 40px;
  }
}
