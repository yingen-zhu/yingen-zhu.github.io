---
layout: default
title: Home
---

<style>
  :root {
    color-scheme: light;
  }
  body {
    margin: 0;
    font-family: Inter, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    background: #f8f8f8;
    color: #111;
  }
  .container {
    width: min(1080px, 100%);
    margin: 0 auto;
    padding: 0 20px;
  }
  .site-header {
    background: #111;
    color: #fff;
  }
  .header-inner {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 20px;
    padding: 18px 0;
  }
  .brand a {
    color: #fff;
    font-size: 1rem;
    font-weight: 700;
  }
  .site-nav {
    display: flex;
    gap: 24px;
    flex-wrap: wrap;
  }
  .site-nav a {
    color: #fff;
    font-weight: 600;
    opacity: 0.95;
    background: transparent;
  }
  .site-nav a:hover,
  .site-nav a:focus {
    opacity: 1;
  }
  .profile-hero {
    display: grid;
    grid-template-columns: minmax(280px, 360px) 1fr;
    gap: 44px;
    align-items: start;
    padding: 30px 0 60px;
  }
  .profile-sidebar {
    position: sticky;
    top: 24px;
    align-self: start;
    display: grid;
    gap: 28px;
  }
  .profile-photo img {
    width: 100%;
    height: auto;
    border-radius: 20px;
    box-shadow: 0 24px 60px rgba(17, 17, 17, 0.12);
    display: block;
  }
  .profile-summary {
    display: grid;
    gap: 12px;
  }
  .profile-name {
    margin: 0;
    font-size: clamp(2rem, 4vw, 2.8rem);
    line-height: 1.05;
    font-weight: 800;
    color: #111;
  }
  .profile-role {
    margin: 0;
    color: #111;
    font-size: 1rem;
    line-height: 1.5;
  }
  .profile-location {
    margin: 0;
    color: #555;
    font-size: 0.98rem;
    display: inline-flex;
    align-items: center;
    gap: 8px;
  }
  .profile-actions.sidebar-actions {
    flex-direction: column;
    align-items: stretch;
    gap: 12px;
  }
  .profile-actions.sidebar-actions .button,
  .profile-actions.sidebar-actions a.social-link {
    width: 100%;
    justify-content: flex-start;
    padding: 14px 16px;
    border-radius: 14px;
    font-size: 0.98rem;
  }
  .profile-actions.sidebar-actions .button {
    background: transparent;
    border: 1.5px solid #0a3d91;
    color: #0a3d91;
  }
  .profile-actions.sidebar-actions .button:hover {
    background: rgba(10, 61, 145, 0.08);
  }
  .profile-actions.sidebar-actions .social-link {
    border: 1.5px solid #e2e2e2;
    color: #111;
    padding: 14px 16px;
    display: inline-flex;
    align-items: center;
    gap: 12px;
    justify-content: flex-start;
    text-decoration: none;
    background: #fff;
  }
  .profile-actions.sidebar-actions .social-link svg {
    width: 18px;
    height: 18px;
  }
  .profile-copy .email-line {
    margin: 0 0 18px;
    color: #555;
    font-size: 0.98rem;
    display: inline-flex;
    align-items: center;
    gap: 8px;
  }
  .profile-copy p,
  .news-section p,
  .news-list {
    color: #333;
    line-height: 1.75;
  }
  main a {
    color: #2c7dff;
    text-decoration: none;
  }
  main a:hover,
  main a:focus {
    text-decoration: underline;
  }
  .profile-copy ul {
    list-style: none;
    padding: 0;
    margin: 0 0 28px;
    display: block;
    gap: 0;
  }
  .profile-copy li {
    position: relative;
    padding-left: 20px;
    color: #444;
  }
  .profile-copy li::before {
    content: "•";
    position: absolute;
    left: 0;
    top: 0;
    color: #111;
  }
  .profile-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 16px;
    align-items: center;
    margin-bottom: 40px;
  }
  .button {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    padding: 14px 24px;
    border-radius: 12px;
    border: 1.5px solid #0a3d91;
    color: #0a3d91;
    font-weight: 700;
    transition: background 0.2s ease, transform 0.2s ease;
  }
  .button:hover {
    background: rgba(10, 61, 145, 0.1);
    transform: translateY(-1px);
  }
  .social-links {
    display: flex;
    gap: 12px;
  }
  .social-links a {
    width: 44px;
    height: 44px;
    border-radius: 12px;
    background: transparent;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    color: #111;
    transition: transform 0.2s ease, color 0.2s ease;
  }
  .social-links a svg {
    width: 20px;
    height: 20px;
  }
  .social-links a:hover {
    transform: translateY(-2px);
    color: #0a3d91;
  }
  .news-section {
    background: transparent;
    border-radius: 0;
    padding: 0;
    box-shadow: none;
    margin-top: 24px;
  }
  .news-title {
    margin: 0 0 16px;
    font-size: 1.1rem;
    font-weight: 700;
  }
  .news-list {
    margin: 0;
    padding-left: 20px;
    color: #444;
  }
  .news-list li + li {
    margin-top: 12px;
  }
  @media (max-width: 900px) {
    .profile-hero {
      grid-template-columns: 1fr;
    }
    .profile-sidebar {
      position: relative;
      top: auto;
    }
  }
  @media (max-width: 640px) {
    .site-header,
    .profile-hero {
      padding-left: 0;
      padding-right: 0;
    }
    .site-nav {
      gap: 16px;
    }
  }
</style>

<div class="profile-hero">
  <aside class="profile-sidebar">
    <div class="profile-photo">
      <img src="/assets/images/profile.JPG" alt="Yingen Zhu">
    </div>
    <div class="profile-summary">
      <p class="profile-name">Yingen Zhu</p>
      <p class="profile-role">PhD student at <a href="https://www.nus.edu.sg/" target="_blank" rel="noopener">National University of Singapore</a></p>
      <p class="profile-location">📍 Singapore</p>
    </div>
    <div class="profile-actions sidebar-actions">
      <a class="button" href="/assets/documents/cv.pdf" target="_blank" rel="noopener">CV</a>
      <a class="social-link" href="https://github.com/yingen-zhu" target="_blank" rel="noopener">GitHub</a>
      <a class="social-link" href="https://www.linkedin.com/in/yingen-zhu-80395b37a/" target="_blank" rel="noopener">LinkedIn</a>
      <a class="social-link" href="https://scholar.google.com/citations?user=oDyHLIwAAAAJ&inst=3212728378801010220" target="_blank" rel="noopener">Google Scholar</a>
    </div>
  </aside>

  <div class="profile-main">
    <p class="email-line">📮 yingen@u.nus.edu</p>
    <p>I am a PhD student at <a href="https://www.nus.edu.sg/" target="_blank" rel="noopener">National University of Singapore</a>, working with <a href="https://www.irmandyw.com/" target="_blank" rel="noopener">Irmandy Wicaksono</a>. Previously, I conducted healthcare research under the supervision of Professor <a href="https://sites.google.com/site/rppgwenjin/" target="_blank" rel="noopener">Wenjin Wang</a> at <a href="https://www.sustech.edu.cn/en/" target="_blank" rel="noopener">SUSTech</a>.</p>
    <p>My research explores the intersection of mobile computing, multimodal systems, wearable technologies, and human-computer interaction.</p>

    <ul>
      <li>Mobile computing</li>
      <li>Multimodal systems</li>
      <li>Wearable technologies</li>
      <li>Human-computer interaction</li>
    </ul>

    <section class="news-section" aria-labelledby="news-title">
      <h2 class="news-title" id="news-title">News</h2>
      <ul class="news-list">
        <li>[2026.08] 🤦‍Survived 2 PhD semesters </li>
        <li>[2025.08] 🕵️ I start my PhD journey!</li>
      </ul>
    </section>
  </div>
</div>
