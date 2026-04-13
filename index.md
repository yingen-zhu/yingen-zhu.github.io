---
layout: default
title: About
---

<style>
.profile-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 30px;
  align-items: flex-start;
  margin-bottom: 30px;
}

.profile-intro {
  flex: 1 1 320px;
  min-width: 260px;
}

.profile-photo {
  flex: 0 0 340px;
  min-width: 260px;
}

.profile-photo img {
  width: 100%;
  height: auto;
  border-radius: 16px;
  box-shadow: 0 18px 40px rgba(0, 0, 0, 0.08);
}

.profile-title {
  font-size: clamp(2.4rem, 4vw, 3.6rem);
  font-weight: 800;
  margin-bottom: 0.35em;
}

.profile-subtitle {
  font-size: 1.05rem;
  color: #555;
  margin-bottom: 0.35em;
}

.profile-line {
  color: #666;
  margin-bottom: 1.2em;
}

.about-heading {
  font-size: 2.2rem;
  font-weight: 700;
  margin-bottom: 0.85em;
  border-bottom: 1px solid #e9e9e9;
  padding-bottom: 0.4em;
}

.about-copy p {
  margin-bottom: 1.2em;
  max-width: 740px;
}

.profile-links {
  margin-top: 34px;
  display: flex;
  flex-wrap: wrap;
  gap: 18px;
}

.profile-links a {
  color: #0366d6;
  text-decoration: none;
  font-weight: 600;
}

.profile-links a:hover {
  text-decoration: underline;
}
</style>

<div class="profile-grid">
  <div class="profile-intro">
    <p class="profile-title">Yingen Zhu</p>
    <p class="profile-subtitle">PhD Student</p>
    <p class="profile-line">Human-computer interaction<br>Wearables and multimodal systems</p>
  </div>

  <div class="profile-photo">
    <img src="/assets/images/profile.JPG" alt="Yingen Zhu">
  </div>
</div>

<div class="profile-links">
  <a href="https://github.com/your-username" target="_blank" rel="noopener">github</a>
  <a href="https://scholar.google.com/citations?user=YOUR_ID&user=oDyHLIwAAAAJ&inst=3212728378801010220" target="_blank" rel="noopener">google scholar</a>
</div>
