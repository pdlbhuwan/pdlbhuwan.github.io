---
layout: default
title: Contact
---

# Contact

<style>
.contact-wrapper {
  display: flex;
  justify-content: center;
  margin-top: 30px;
}

.contact-grid {
  display: grid;
  grid-template-columns: repeat(4, 120px);
  text-align: center;
  gap: 30px;
}

.contact-item img {
  width: 50px;
  height: 50px;
  padding: 15px;
  border-radius: 50%;
  background: #f0f0f0; /* light gray background */
  transition: transform 0.2s ease;
}

.contact-item img:hover {
  transform: scale(1.1);
}

.contact-item span {
  display: block;
  margin-top: 10px;
  font-size: 14px;
}
</style>

<div class="contact-wrapper">
  <div class="contact-grid">

    <!-- Email -->
    <div class="contact-item">
      <a href="mailto:pdlbhuwan@yahoo.com" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/minutemailer.svg" alt="Email">
      </a>
      <span>Email</span>
    </div>

    <!-- LinkedIn -->
    <div class="contact-item">
      <a href="https://www.linkedin.com/in/pdlbhuwan/" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/linkedin.svg" alt="LinkedIn">
      </a>
      <span>LinkedIn</span>
    </div>

    <!-- Google Scholar -->
    <div class="contact-item">
      <a href="https://scholar.google.co.in/citations?user=SDznvJUAAAAJ&hl=en" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/googlescholar.svg" alt="Google Scholar">
      </a>
      <span>Google Scholar</span>
    </div>

    <!-- ORCID -->
    <div class="contact-item">
      <a href="https://orcid.org/0000-0003-0964-5027" target="_blank">
        <img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/orcid.svg" alt="ORCID">
      </a>
      <span>ORCID</span>
    </div>

  </div>
</div>
