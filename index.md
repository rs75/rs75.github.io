---
layout: default
---

<p align="center">
  <img src="logo.png" style="max-width:300px"/>
</p>

We specialize in creating sophisticated data applications. Our team leverages cutting-edge technologies to develop and operate our proprietary software, focusing on data engineering and data science innovations.

## Who We Are

DataDolphin PTE. LTD. pioneers advanced data engineering and data science applications. We combine deep technical expertise with innovative approaches to build powerful tools for data transformation, analysis, and AI-driven insights.

## Portfolio

<div class="projects-container">
  <div class="project-item">
    <div class="project-content">
      <h3>Looksmax Report</h3>
      <p>A sophisticated mobile app that provides detailed facial analysis and improvement recommendations.</p>
      <div class="project-links">
        <a href="https://apps.apple.com/app/looksmax-report/id6737451002" class="app-store-link">
          <img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-app-store.svg" alt="Download on the App Store" height="58">
        </a>
        <a href="https://play.google.com/store/apps/details?id=com.rsapps.looksmaxreport" class="app-store-link" style="margin-left: 10px;">
          <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play" height="58">
        </a>
        <!-- <a href="https://attractivenesstest.com/looksmax" class="website-link" style="margin-left: 10px;">Website</a> -->
      </div>
    </div>
  </div>

  <div class="project-item">
    <div class="project-content">
      <h3>Attractiveness AI</h3>
      <p>An innovative mobile application that uses advanced AI to analyze facial features and provide insights.</p>
      <div class="project-links">
        <a href="https://apps.apple.com/us/app/attractiveness-ai/id6741153581" class="app-store-link">
          <img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-app-store.svg" alt="Download on the App Store" height="58">
        </a>
        <a href="https://play.google.com/store/apps/details?id=com.datadolphinapps.attractiveness_ai" class="app-store-link" style="margin-left: 10px;">
          <img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" alt="Get it on Google Play" height="58">
        </a>
        <a href="https://attractivenessai.com/" class="website-link" style="margin-left: 10px;">Website</a>
      </div>
    </div>
  </div>

  <div class="project-item">
    <div class="project-content">
      <h3>Rate My Photo</h3>
      <p>A powerful web application that offers professional photo analysis and feedback.</p>
      <div class="project-links">
        <a href="https://rate-my-photo.com/" class="website-link">Visit Website</a>
      </div>
    </div>
  </div>

  <div class="project-item">
    <div class="project-content">
      <h3>Attractiveness Test</h3>
      <p>An AI-powered web platform for facial analysis and attractiveness assessment.</p>
      <div class="project-links">
        <a href="https://attractivenesstest.com/" class="website-link">Visit Website</a>
      </div>
    </div>
  </div>

  <!-- <div class="project-item">
    <div class="project-content">
      <h3>Celebrity Lookalike</h3>
      <p>An AI-powered web app that finds your celebrity look-alike using advanced facial recognition technology.</p>
      <div class="project-links">
        <a href="https://mycelebritylookalike.com/" class="website-link">Visit Website</a>
      </div>
    </div>
  </div>
</div> -->

## Our Technology & Approach

Our applications are built on a foundation of robust and modern technologies:

- **AI and Machine Learning**: Powering our applications with cutting-edge AI and Machine Learning models, trained and operated for precision and efficiency.
- **LLM Prompt Design & Integration**: Integrating Large Language Models (LLMs) through meticulous prompt design and the development of intelligent AI agents within our software.
- **App Development**: Developing intuitive and responsive cross-platform AI applications for Android, iOS, and web using Flutter.
- **ETL Processes**: Employing robust ETL processes using tools like Airflow and DBT to manage and refine the data that powers our applications.
- **Data Programming**: Utilizing advanced Python and SQL for complex data manipulation, analytics, and backend development of our platforms.
- **Data Processing**: Implementing efficient streaming and batch data processing to ensure our applications handle diverse data workflows seamlessly.
- **Google Cloud Platform**: Leveraging Google Cloud Platform (GCP) to build scalable and reliable cloud infrastructure for our applications.

<style>
.projects-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}

.project-item {
  background: #ffffff;
  border-radius: 12px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  overflow: hidden;
}

.project-item:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 12px rgba(0, 0, 0, 0.15);
}

.project-content {
  padding: 1.5rem;
}

.project-content h3 {
  color: #2c3e50;
  margin: 0 0 1rem 0;
  font-size: 1.5rem;
}

.project-content p {
  color: #4a5568;
  margin: 0 0 1.5rem 0;
  line-height: 1.6;
}

.project-links {
  margin-top: 1rem;
  display: flex;
  align-items: center;
}

.app-store-link {
  display: inline-flex;
  align-items: center;
  transition: opacity 0.3s ease;
}

.app-store-link:hover {
  opacity: 0.8;
}

.website-link {
  display: inline-flex;
  align-items: center;
  padding: 0.75rem 1.5rem;
  background: #2c3e50;
  color: white;
  text-decoration: none;
  border-radius: 6px;
  font-weight: 500;
  transition: background-color 0.3s ease;
  height: 40px;
  box-sizing: border-box;
}

.website-link:hover {
  background: #34495e;
}
</style>

## Contact Us

Have questions about our products or want to learn more? We'd love to hear from you.

**Email**: <span id="email"></span>

<script>
  // Obfuscate the email address parts
  var part1 = "info";
  var part2 = "datadolphin";
  var part3 = "net";
  
  // Construct the email address
  var email = part1 + "@" + part2 + "." + part3;
  
  // Create a clickable email link with proper mailto: protocol
  document.getElementById("email").innerHTML = '<a href="mailto:' + email + '">' + email + '</a>';
</script>


---


<div class="footer">
  DataDolphin PTE. LTD. © 2025 | <a href="/privacy-policy">Privacy Policy</a> |  <a href="/terms-of-use">Terms of Use</a>
</div>