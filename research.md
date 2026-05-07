---
layout: default
title: Research
permalink: /research/
---

# Research

<style>
.research-list {
  display: grid;
  gap: 52px;
  margin: 0;
  padding: 0;
}
.research-item {
  display: grid;
  grid-template-columns: minmax(260px, 360px) 1fr;
  gap: 32px;
  align-items: start;
}
.research-media {
  display: flex;
  align-items: center;
  justify-content: center;
}
.research-media img {
  width: 100%;
  height: auto;
  display: block;
  border-radius: 0;
  box-shadow: 0 24px 60px rgba(17, 17, 17, 0.12);
  image-orientation: from-image;
  transform: none;
}
.research-media iframe {
  width: 100%;
  aspect-ratio: 1.6;
  height: auto;
  display: block;
  border: 0;
  box-shadow: 0 24px 60px rgba(17, 17, 17, 0.12);
}
.research-content h3 {
  margin: 0 0 18px;
  font-size: 1.6rem;
  font-weight: 700;
}
.research-content p {
  margin: 0 0 16px;
  color: #333;
  line-height: 1.75;
}
.research-content a {
  color: #2c7dff;
  text-decoration: none;
}
.research-content a:hover,
.research-content a:focus {
  text-decoration: underline;
}
@media (max-width: 900px) {
  .research-item {
    grid-template-columns: 1fr;
  }
}
</style>

## Projects
For further details on these projects, please see my <a href="https://scholar.google.com.hk/citations?user=oDyHLIwAAAAJ&hl=zh-CN" target="_blank" rel="noopener">google scholar</a>.

<section class="research-list">
  <article class="research-item">
    <div class="research-media">
      <iframe
        src="/assets/images/FigureLock.pdf"
        title="Camera-based bimodal CMRI gating system PDF"
      ></iframe>
    </div>
    <div class="research-content">
      <h3>Camera-based bimodal CMRI gating system</h3>
      <p>We developed a non-contact CMR gating approach in collaboration with Shanghai Neusoft Medical Systems, using a dual-camera system to capture facial PPG and thoracoabdominal SCG signals for robust trigger generation, aiming to alleviate waveform distortion and delays in conventional ECG/PPG gating and improve CMR image quality and user experience.</p>
    </div>
  </article>

  <article class="research-item">
    <div class="research-media">
      <img src="/assets/images/SleepMonitoring.png" alt="Sleep Monitoring">
    </div>
    <div class="research-content">
      <h3>Sleep Monitoring</h3>
      <p>Camera-based contactless physiological monitoring is promising for sleep tracking yet limited by privacy concerns. We therefore propose a privacy-preserving framework using defocused cameras to measure heart rate, respiration rate, sleep posture and body movement via a dual-branch network.</p>
    </div>
  </article>

  <article class="research-item">
    <div class="research-media">
      <img src="/assets/images/phoneAssistant.png" alt="Smartphone Health Assistant">
    </div>
    <div class="research-content">
      <h3>Smartphone Health Assistant</h3>
      <p>We propose a smartphone-based framework that uses built-in front and rear cameras to estimate multidimensional physiological parameters including HR, HRV, RR, SpO2, and BP, and further improve camera PPG frame rate via a defocused design and rolling shutter mechanism for high-frame-rate measurements such as multi-wavelength pulse transit time.</p>
    </div>
  </article>
</section>
