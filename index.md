---
layout: default
title: Home
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

.profile-panel {
  margin-top: 24px;
  max-width: 430px;
}

.profile-links {
  display: flex;
  flex-wrap: wrap;
  gap: 14px;
  margin-bottom: 28px;
}

.profile-links a {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  color: #111;
  text-decoration: none;
  font-weight: 600;
  transition: color 0.2s ease, transform 0.2s ease;
}

.profile-links a:hover {
  color: #000;
  transform: translateY(-1px);
}

.profile-links svg {
  width: 18px;
  height: 18px;
  fill: currentColor;
  flex: 0 0 auto;
}

.news-section {
  padding: 0;
}

.news-title {
  margin: 0 0 12px;
  font-size: 1.15rem;
  font-weight: 700;
}

.news-list {
  margin: 0;
  padding-left: 18px;
  color: #444;
}

.news-list li + li {
  margin-top: 10px;
}
</style>

<div class="profile-grid">
  <div class="profile-intro">
    <p class="profile-title">Yingen Zhu</p>
    <p class="profile-title" style="font-size: 15px;">Email: yingen@u.nus.edu</p>
    <p>
      I am a PhD student in <a href="https://www.nus.edu.sg/" target="_blank" rel="noopener">National University of Singapore</a>, working with <a href="https://www.irmandyw.com/" target="_blank" rel="noopener">Irmandy Wicaksono</a>. Previously, I conducted research in healthcare under the supervision of Professor <a href="https://sites.google.com/site/rppgwenjin/" target="_blank" rel="noopener">Wenjin Wang</a> at <a href="https://www.sustech.edu.cn/en/" target="_blank" rel="noopener">SUSTech</a>.
    </p>
    <p>
      🙇My research focuses on:
    </p>
      <ul>
        <li>Mobile computing</li>
        <li>Multimodal systems</li>
        <li>Wearable technologies</li>
        <li>Human-computer interaction</li>
      </ul>
    <div class="profile-panel">
      <div class="profile-links">
        <a href="https://github.com/yingen-zhu" target="_blank" rel="noopener" aria-label="GitHub">
          <svg viewBox="0 0 16 16" aria-hidden="true">
            <path d="M8 0C3.58 0 0 3.58 0 8a8 8 0 0 0 5.47 7.59c.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.5-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82a7.6 7.6 0 0 1 4 0c1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.01 8.01 0 0 0 16 8c0-4.42-3.58-8-8-8Z"></path>
          </svg>
          <!-- <span>GitHub</span> -->
        </a>
        <a href="https://scholar.google.com/citations?user=oDyHLIwAAAAJ&inst=3212728378801010220" target="_blank" rel="noopener" aria-label="Google Scholar">
          <svg viewBox="0 0 24 24" aria-hidden="true">
            <path d="M12 3 1 9l11 6 9-4.91V17h2V9L12 3Zm0 14L5.09 13.23 4 13.82V17l8 4 8-4v-3.18l-1.09-.59L12 17Z"></path>
          </svg>
          <!-- <span>Google Scholar</span> -->
        </a>
        <a href="https://www.linkedin.com/in/yingen-zhu-80395b37a/" target="_blank" rel="noopener" aria-label="LinkedIn">
          <svg viewBox="0 0 24 24" aria-hidden="true">
            <path d="M6.94 8.5H3.56V20h3.38V8.5ZM5.25 3A2 2 0 1 0 5.3 7a2 2 0 0 0-.05-4ZM20.44 12.74c0-3.46-1.85-5.07-4.32-5.07-1.99 0-2.88 1.09-3.38 1.86V8.5H9.37c.04.68 0 11.5 0 11.5h3.37v-6.42c0-.34.02-.68.13-.92.27-.68.89-1.39 1.94-1.39 1.37 0 1.92 1.05 1.92 2.58V20h3.37l.34-7.26Z"></path>
          </svg>
          <!-- <span>LinkedIn</span> -->
        </a>
      </div>

      <section class="news-section" aria-labelledby="news-title">
        <h2 class="news-title" id="news-title">News</h2>
        <ul class="news-list">
          <li>[2025.08]🕵️I start my PhD journey!</li>
        </ul>
      </section>
    </div>
  </div>

  <div class="profile-photo">
    <img src="/assets/images/profile.JPG" alt="Yingen Zhu">
  </div>
</div>
