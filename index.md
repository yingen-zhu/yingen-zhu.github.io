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
    grid-template-columns: minmax(240px, 360px) 1fr;
    gap: 44px;
    align-items: start;
    padding: 30px 0 60px;
  }
  .profile-photo img {
    width: 100%;
    height: auto;
    border-radius: 0;
    box-shadow: none;
    display: block;
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
    color: #0a3d91;
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
  <div class="profile-photo">
    <img src="/assets/images/profile.JPG" alt="Yingen Zhu">
  </div>

  <div class="profile-copy">
    <p class="email-line">📮 yingen@u.nus.edu</p>
    <p>I am a PhD student at <a href="https://www.nus.edu.sg/" target="_blank" rel="noopener">National University of Singapore</a>, working with <a href="https://www.irmandyw.com/" target="_blank" rel="noopener">Irmandy Wicaksono</a>. Previously, I conducted healthcare research under the supervision of Professor <a href="https://sites.google.com/site/rppgwenjin/" target="_blank" rel="noopener">Wenjin Wang</a> at <a href="https://www.sustech.edu.cn/en/" target="_blank" rel="noopener">SUSTech</a>.</p>
    <p>My research explores the intersection of mobile computing, multimodal systems, wearable technologies, and human-computer interaction.</p>

    <ul>
      <li>Mobile computing</li>
      <li>Multimodal systems</li>
      <li>Wearable technologies</li>
      <li>Human-computer interaction</li>
    </ul>

    <div class="profile-actions">
      <div class="social-links">
        <a href="/assets/documents/cv.pdf" target="_blank" rel="noopener" aria-label="CV">
          <svg viewBox="0 0 24 24" aria-hidden="true">
            <path fill="currentColor" d="M6 2h9l5 5v15a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2zm8 1.5V8h4.5L14 3.5zM8 12h8v1.5H8V12zm0 3h8v1.5H8V15zm0-6h5v1.5H8V9z"/>
          </svg>
        </a>
        <a href="https://github.com/yingen-zhu" target="_blank" rel="noopener" aria-label="GitHub">
          <svg viewBox="0 0 16 16" aria-hidden="true">
            <path fill="currentColor" d="M8 0C3.58 0 0 3.58 0 8a8 8 0 0 0 5.47 7.59c.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.5-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82a7.6 7.6 0 0 1 4 0c1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.01 8.01 0 0 0 16 8c0-4.42-3.58-8-8-8Z"/>
          </svg>
        </a>
        <a href="https://scholar.google.com/citations?user=oDyHLIwAAAAJ&inst=3212728378801010220" target="_blank" rel="noopener" aria-label="Google Scholar">
          <svg viewBox="0 0 24 24" aria-hidden="true">
            <path fill="currentColor" d="M12 3 1 9l11 6 9-4.91V17h2V9L12 3Zm0 14L5.09 13.23 4 13.82V17l8 4 8-4v-3.18l-1.09-.59L12 17Z"/>
          </svg>
        </a>
        <a href="https://www.linkedin.com/in/yingen-zhu-80395b37a/" target="_blank" rel="noopener" aria-label="LinkedIn">
          <svg viewBox="0 0 24 24" aria-hidden="true">
            <path fill="currentColor" d="M6.94 8.5H3.56V20h3.38V8.5ZM5.25 3A2 2 0 1 0 5.3 7a2 2 0 0 0-.05-4ZM20.44 12.74c0-3.46-1.85-5.07-4.32-5.07-1.99 0-2.88 1.09-3.38 1.86V8.5H9.37c.04.68 0 11.5 0 11.5h3.37v-6.42c0-.34.02-.68.13-.92.27-.68.89-1.39 1.94-1.39 1.37 0 1.92 1.05 1.92 2.58V20h3.37l.34-7.26Z"/>
          </svg>
        </a>
      </div>
    </div>

    <section class="news-section" aria-labelledby="news-title">
      <h2 class="news-title" id="news-title">News</h2>
      <ul class="news-list">
        <li>[2026.08] 🤦‍Survived 2 PhD semesters </li>
        <li>[2025.08] 🕵️ I start my PhD journey!</li>
      </ul>
    </section>
  </div>
</div>
