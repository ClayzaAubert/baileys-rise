---
layout: default
title: WhatsApp Bot Documentation
description: Comprehensive guide for building WhatsApp bots with modern web interface
toc: false
---

<div class="hero">
  <div class="container">
    <h1>🚀 WhatsApp Bot Documentation</h1>
    <p>Comprehensive guide for building powerful WhatsApp bots with ease</p>
    <div class="cta-buttons">
      <a href="#getting-started" class="btn btn-primary">
        <i class="fas fa-rocket"></i>
        Get Started
      </a>
      <a href="https://github.com/username/repo-name" class="btn btn-secondary" target="_blank">
        <i class="fab fa-github"></i>
        View on GitHub
      </a>
    </div>
  </div>
</div>

<section class="features">
  <div class="container">
    <div class="features-grid">
      <div class="feature-card">
        <div class="feature-icon">
          <i class="fas fa-bolt"></i>
        </div>
        <h3>Easy Setup</h3>
        <p>Get started in minutes with our comprehensive installation guide and examples.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">
          <i class="fas fa-cogs"></i>
        </div>
        <h3>Full Featured</h3>
        <p>Support for all WhatsApp features including media, groups, polls, and more.</p>
      </div>
      <div class="feature-card">
        <div class="feature-icon">
          <i class="fas fa-shield-alt"></i>
        </div>
        <h3>Secure & Reliable</h3>
        <p>Built with security in mind and battle-tested for production use.</p>
      </div>
    </div>
  </div>
</section>

<div class="container">
  <div class="content-wrapper">
    <article class="article full-width">
      <div class="article-content">
        <!-- Konten dari README.md akan ditampilkan di sini -->
        {% capture readme %}{% include_relative ../README.md %}{% endcapture %}
        {{ readme | markdownify }}
      </div>
    </article>
  </div>
</div>