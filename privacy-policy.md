---
layout: default
title: Privacy Policy
---

<div class="privacy-container">
  <h1>Privacy Policy</h1>
  <p class="last-updated">Last Updated: March 2024</p>

  <div class="privacy-section">
    <h2>Introduction</h2>
    <p>DataDolphin PTE. LTD. ("we," "our," or "us") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our services, including our mobile applications and websites.</p>
  </div>

  <div class="privacy-section">
    <h2>Information We Collect</h2>
    <h3>Personal Information</h3>
    <p>We may collect personal information that you voluntarily provide to us when you:</p>
    <ul>
      <li>Register for an account</li>
      <li>Use our mobile applications</li>
      <li>Visit our websites</li>
      <li>Contact our support team</li>
    </ul>

    <h3>Automatically Collected Information</h3>
    <p>When you use our services, we automatically collect certain information, including:</p>
    <ul>
      <li>Device information (model, operating system, unique device identifiers)</li>
      <li>Usage data (features used, time spent, interactions)</li>
      <li>IP address and location data</li>
      <li>Analytics data</li>
    </ul>
  </div>

  <div class="privacy-section">
    <h2>How We Use Your Information</h2>
    <p>We use the collected information for various purposes:</p>
    <ul>
      <li>To provide and maintain our services</li>
      <li>To improve and personalize user experience</li>
      <li>To communicate with you about updates and support</li>
      <li>To analyze usage patterns and optimize our services</li>
      <li>To comply with legal obligations</li>
    </ul>
  </div>

  <div class="privacy-section">
    <h2>Data Security</h2>
    <p>We implement appropriate technical and organizational measures to protect your personal information against unauthorized access, alteration, disclosure, or destruction. However, no method of transmission over the Internet or electronic storage is 100% secure.</p>
  </div>

  <div class="privacy-section">
    <h2>Data Retention</h2>
    <p>We retain your personal information for as long as necessary to fulfill the purposes outlined in this Privacy Policy, unless a longer retention period is required or permitted by law.</p>
  </div>

  <div class="privacy-section">
    <h2>Your Rights</h2>
    <p>Depending on your location, you may have certain rights regarding your personal information, including:</p>
    <ul>
      <li>Right to access your personal information</li>
      <li>Right to correct inaccurate information</li>
      <li>Right to delete your information</li>
      <li>Right to restrict or object to processing</li>
      <li>Right to data portability</li>
    </ul>
  </div>

  <div class="privacy-section">
    <h2>Third-Party Services</h2>
    <p>Our services may contain links to third-party websites or services. We are not responsible for the privacy practices of these third parties. We encourage you to review their privacy policies.</p>
  </div>

  <div class="privacy-section">
    <h2>Children's Privacy</h2>
    <p>Our services are not intended for children under 13 years of age. We do not knowingly collect personal information from children under 13.</p>
  </div>

  <div class="privacy-section">
    <h2>Changes to This Policy</h2>
    <p>We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Last Updated" date.</p>
  </div>

  <div class="privacy-section">
    <h2>Contact Us</h2>
    <p>If you have any questions about this Privacy Policy, please contact us at:</p>
    <div class="contact-info">
      <p><strong>Email:</strong> <span id="privacy-email"></span></p>
    </div>
  </div>
</div>

<style>
.privacy-container {
  max-width: 800px;
  margin: 0 auto;
  padding: 2rem;
}

.privacy-container h1 {
  color: #2c3e50;
  margin-bottom: 0.5rem;
}

.last-updated {
  color: #666;
  font-style: italic;
  margin-bottom: 2rem;
}

.privacy-section {
  margin-bottom: 2.5rem;
}

.privacy-section h2 {
  color: #2c3e50;
  margin-bottom: 1rem;
  font-size: 1.5rem;
}

.privacy-section h3 {
  color: #34495e;
  margin: 1.5rem 0 1rem;
  font-size: 1.2rem;
}

.privacy-section p {
  line-height: 1.6;
  color: #4a5568;
  margin-bottom: 1rem;
}

.privacy-section ul {
  list-style-type: disc;
  margin-left: 1.5rem;
  margin-bottom: 1rem;
}

.privacy-section li {
  line-height: 1.6;
  color: #4a5568;
  margin-bottom: 0.5rem;
}

.contact-info {
  background: #f8f9fa;
  padding: 1rem;
  border-radius: 6px;
  margin-top: 1rem;
}

.contact-info p {
  margin: 0;
}
</style>

<script>
  // Obfuscate the email address parts
  var part1 = "privacy";
  var part2 = "datadolphin";
  var part3 = "net";
  
  // Construct the email address
  var email = part1 + "@" + part2 + "." + part3;
  
  // Create a clickable email link with proper mailto: protocol
  document.getElementById("privacy-email").innerHTML = '<a href="mailto:' + email + '">' + email + '</a>';
</script> 