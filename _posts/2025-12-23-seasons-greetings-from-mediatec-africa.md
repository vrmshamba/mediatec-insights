---
layout: post
title: "Season's Greetings from Mediatec Africa"
date: 2025-12-23 09:00:00 +0300
categories: updates
image: thumb.jpg
description: "A special holiday message and video greeting for our partners and clients as we wrap up 2025."
---

<style>
  /* 1. COMPLETELY HIDES THE THEME'S EMPTY HEADER VOID */
  .post-header, .hero, .featured-image-container, .post-title-container, .post-meta { 
    display: none !important; 
    height: 0 !important;
    margin: 0 !important;
    padding: 0 !important;
  }
  
  /* 2. PULLS EVERYTHING TO THE VERY TOP OF THE SCREEN */
  .post-content, .entry-content, .page-content, .wrapper { 
    padding-top: 0 !important; 
    margin-top: 0 !important; 
  }

  /* 3. VIMEO ZOOM FIX: Hides black bars by slightly enlarging the video */
  .vimeo-wrapper {
    width: 100%;
    margin: 0 auto 30px;
    max-width: 950px;
    box-shadow: 0 12px 45px rgba(0,0,0,0.12);
    border-radius: 12px;
    overflow: hidden;
    background: #ffffff; /* Sets background to white so gaps are invisible */
    line-height: 0;
  }
  
  .vimeo-container {
    padding: 56.25% 0 0 0;
    position: relative;
    /* Zooming in slightly (3%) to push black bars off the edges */
    transform: scale(1.03); 
    transform-origin: center;
  }
</style>

<div style="text-align: center; padding: 0; margin-top: -60px; position: relative; z-index: 10;">
  <!-- Festive Header -->
  <div style="font-size: 3.5rem; margin-bottom: 5px;">🎄</div>
  <h1 style="font-size: 2.2rem; color: #111; margin-bottom: 10px; font-weight: 800; letter-spacing: -1px;">Season's Greetings</h1>

  <p style="font-size: 1.15rem; line-height: 1.6; color: #444; max-width: 700px; margin: 0 auto 25px; padding: 0 15px;">
    As we wrap up 2025, the team at <strong>Mediatec Africa</strong> wants to share a special message of gratitude with our partners and clients across the continent.
  </p>

  <!-- THE VIDEO PLAYER WITH ZOOM FIX -->
  <div class="vimeo-wrapper">
    <div class="vimeo-container">
      <iframe 
        src="https://player.vimeo.com/video/1149000955?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479&amp;title=0&amp;byline=0&amp;portrait=0" 
        frameborder="0" 
        allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media; web-share" 
        referrerpolicy="strict-origin-when-cross-origin" 
        style="position:absolute;top:0;left:0;width:100%;height:100%;" 
        title="Season's Greetings from Mediatec Africa"
        allowfullscreen>
      </iframe>
    </div>
  </div>

  <!-- Message Box -->
  <div style="background: #fdf2f2; padding: 35px; border-radius: 12px; border-left: 6px solid #d15d2a; text-align: left; margin: 0 15px 40px; max-width: 700px; margin-left: auto; margin-right: auto;">
    <p style="margin-bottom: 10px; font-weight: bold; color: #111; font-size: 1.3rem;">
      Wishing you a restful holiday and a prosperous 2026.
    </p>
    <p style="color: #444; line-height: 1.6; margin: 0;">
      Thank you for your trust this year. We look forward to navigating new milestones and African market growth with you in the coming year.
    </p>
    <p style="color: #666; font-style: italic; margin-top: 20px;">— The Mediatec Africa Team</p>
  </div>

  <!-- Footer Link -->
  <p style="font-size: 1.05rem; color: #888; padding-bottom: 60px;">
    <a href="https://mediatec.africa" target="_blank" style="color: #d15d2a; font-weight: bold; text-decoration: none;">Visit mediatec.africa &rarr;</a>
  </p>
</div>


<!-- Vimeo API Script -->
<script src="https://player.vimeo.com/api/player.js"></script>
