---
layout: default
title: About
permalink: /about/
---

<style>
  body {
    font-family: "Helvetica Neue", Arial, sans-serif;
    line-height: 1.6;
    color: #333;
    padding-top: 20px;
  }

  .site-header {
    margin-bottom: 30px;
  }

  .site-title {
    font-size: 2.5rem;
    font-weight: 700;
    margin-bottom: 0;
  }

  .site-subtitle {
    color: #666;
    margin-bottom: 5px;
  }

  .site-institution {
    margin-bottom: 20px;
  }

  .page-nav {
    margin-bottom: 30px;
    background-color: #f8f9fa;
    border-radius: 4px;
    padding: 10px 15px;
  }

  .page-nav a {
    color: #333;
    font-weight: 500;
    margin-right: 20px;
    text-decoration: none;
  }

  .page-nav a:hover,
  .page-nav a:focus,
  .page-nav a.active {
    color: #0275d8;
  }

  h2 {
    margin-top: 40px;
    margin-bottom: 20px;
    font-weight: 600;
    border-bottom: 1px solid #eee;
    padding-bottom: 10px;
  }

  a {
    color: #0275d8;
    text-decoration: none;
  }

  a:hover,
  a:focus {
    color: #014c8c;
    text-decoration: underline;
  }

  .about-card {
    background: #fff;
    border: 1px solid #eee;
    border-radius: 4px;
    padding: 24px;
  }

  @media (max-width: 768px) {
    .site-title {
      font-size: 2rem;
    }
  }
</style>

<div class="container">
  <header class="site-header">
    <div class="row">
      <div class="col-md-12">
        <h1 class="site-title">About</h1>
        <p class="site-subtitle">About Me</p>
        <p class="site-institution">
          Academic profile and research interests
        </p>
      </div>
    </div>
  </header>

  <nav class="page-nav" aria-label="Page navigation">
    <a href="/">Home</a>
    <a href="/about/" class="active">About</a>
    <a href="/research/">Research</a>
    <a href="/gallery/">Gallery</a>
  </nav>

  <main>
    <div class="row">
      <div class="col-md-8">
        <h2>About Me</h2>
        <div class="about-card">
          <p>
            I am a PhD student working at the intersection of human-computer interaction,
            wearable technologies, multimodal systems, and mobile computing.
          </p>
          <p>
            My research focuses on building interactive systems that connect people,
            sensing, and intelligent interfaces. I am interested in how novel sensing
            techniques and interface design can support natural, responsive, and
            context-aware user experiences.
          </p>
        </div>
      </div>
    </div>
  </main>
</div>
