---
layout: base
---

<!-- Updated Font Awesome CDN with correct implementation -->
<br><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer"><br>

<style>
:root {
  --accent-blue: #1E90FF;
}

.intro-container {
  background-color: #1a1a1a;
  border-radius: 12px;
  padding: 30px;
  margin-bottom: 40px;
  box-shadow: 0 4px 10px rgba(30, 144, 255, 0.15);
  display: flex;
  flex-direction: row;
  gap: 30px;
  flex-wrap: wrap;
}

.intro-image {
  max-width: 300px;
  border-radius: 10px;
}

.intro-text {
  flex: 1;
  color: #fff;
}

.intro-text a i {
  transition: transform 0.2s ease;
  color: var(--accent-blue);
}

.intro-text a:hover i {
  transform: scale(1.2);
}

/* NEWS STYLES */
.news-section {
  margin-top: 40px;
}

.news-title {
  font-size: 24px;
  color: var(--accent-blue);
  margin-bottom: 20px;
  border-bottom: 2px solid var(--accent-blue);
  display: inline-block;
  padding-bottom: 5px;
}

.news-container {
  display: flex;
  flex-direction: column;
  gap: 15px;
}

.news-card {
  background-color: #1a1a1a;
  border: 1px solid #333;
  border-radius: 12px;
  padding: 20px;
  transition: transform 0.2s ease, box-shadow 0.3s ease;
  box-shadow: 0 2px 4px rgba(30, 144, 255, 0.1);
}

.news-card:hover {
  transform: scale(1.01);
  box-shadow: 0 4px 10px rgba(30, 144, 255, 0.3);
}

.news-date {
  font-weight: 600;
  font-size: 14px;
  color: #aaa;
  margin-bottom: 5px;
  text-transform: uppercase;
  letter-spacing: 0.8px;
}

.news-content a {
  color: var(--accent-blue);
  font-size: 16px;
  text-decoration: none;
}

.news-content a:hover {
  text-decoration: underline;
}

/* Responsive */
@media (max-width: 768px) {
  .intro-container {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }

  .intro-image {
    max-width: 100%;
  }

  .intro-text {
    padding: 0 10px;
  }
}
</style>

<div class="intro-container">
  <img src="images/home.png" alt="Your Image Description" class="intro-image">
  <div class="intro-text">
    <p>I'm Devansh Bhardwaj — a final-year undergraduate student in Electronics and Communication Engineering at IIT Roorkee with a deep and focused passion for AI research. My current work spans AI Security, Multi-Agent Systems, and Reinforcement Learning. I loved to do cool things with AI hence my interests are not limited to the aforementioned fields. I thrive on independently-driven projects and have led a lot of impactful works. With a long-term vision of leading AI research initiatives in India, I'm actively seeking full-time roles or research assistantships at top-tier labs where I can contribute meaningfully and grow toward a future PhD.</p>

    <p>Currently, I am working at <a href="https://karthikncode.github.io/">Prof. Karthik Narsimhan's Lab</a> on developing a generalized communication protocol for efficient Agent to Agent Collaboration.</p>

    <p>Previously, I worked as an ML Security Researcher at <a href="https://repello.ai/">Repello AI</a>, focusing on automated red-teaming of AI agents. I also worked on video prediction at <a href="https://aero.iisc.ac.in/people/debasish-ghose/">Prof. Debasish Ghose's Lab</a> at IISc Bangalore, under the supervision of <a href="https://sites.google.com/view/meenakshisarkar">Meenakshi Sarkar</a>.</p>

    <p>I served as the Secretary of the <a href="https://dsgiitr.in/">Data Science Group</a> at IIT Roorkee, which has been the heart and soul of my ML journey. <br><br>Have a look at <a href="/cv/">My CV</a> to know more about me.</p>

    <p><strong>Connect with me:</strong><br>
      <a href="https://www.linkedin.com/in/devansh-bhardwaj-3b18b923a/" title="LinkedIn"><i class="fab fa-linkedin fa-lg"></i></a>&nbsp;&nbsp;
      <a href="mailto:bhardwajdevansh398@gmail.com" title="Email"><i class="fas fa-envelope fa-lg"></i></a>&nbsp;&nbsp;
      <a href="https://scholar.google.com/citations?user=kBHnXToAAAAJ&hl=en" title="Google Scholar"><i class="fas fa-graduation-cap fa-lg"></i></a>&nbsp;&nbsp;
      <a href="https://github.com/FireShadow05" title="GitHub"><i class="fab fa-github fa-lg"></i></a>

    </p>
  </div>
</div>

<div class="news-section">
  <div class="news-title">📢 News</div>
  <div class="news-container">
    <div class="news-card">
        <div class="news-date">March 2025</div>
        <div class="news-content"><a href="https://cvpr25-advml.github.io/long_paper/34_One_Noise_to_Fool_Them_All_.pdf">Paper</a> accepted at AdvML Workshop CVPR 2025</div>
    </div>

    <div class="news-card">
        <div class="news-date">Jan 2025</div>
        <div class="news-content"><a href="https://iclr-blogposts.github.io/2025/blog/spd/">Blogpost</a> accepted at ICLR'25</div>
    </div>

    <div class="news-card">
        <div class="news-date">Oct 2024</div>
        <div class="news-content"><a href="https://openreview.net/forum?id=zkzo72ZQqF">Paper</a> accepted at AdvML Workshop NeurIPS 2024</div>
    </div>

    
  </div>
</div>