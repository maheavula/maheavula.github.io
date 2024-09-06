---
layout: default
title: Welcome
---

# Welcome to My Professional Portfolio

## About Me

I am a cybersecurity enthusiast with hands-on experience in security analysis, reverse engineering, and vulnerability management. My portfolio includes various projects in malware detection and network security.

### Professional Website

<div style="text-align: center; padding: 20px; position: relative;">
  <a href="https://maheavula.netlify.app/" 
     class="btn" 
     style="color: white; 
            padding: 15px 30px; 
            text-decoration: none; 
            border-radius: 50px; 
            font-size: 18px; 
            font-weight: bold; 
            background: linear-gradient(90deg, #24292e, #0366d6);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3); 
            position: relative; 
            overflow: hidden; 
            transition: all 0.5s ease;">
    Visit My Professional Website
  </a>

  <!-- Background glow effect -->
  <div style="position: absolute; 
              top: -100px; 
              left: -100px; 
              width: 300px; 
              height: 300px; 
              background: rgba(3, 102, 214, 0.5); 
              filter: blur(100px); 
              z-index: -1;
              transition: all 0.7s ease;"></div>
</div>

<style>
  .btn:hover {
    background: linear-gradient(90deg, #0366d6, #24292e);
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4);
  }

  /* Hover animation effect on the glow */
  .btn:hover + div {
    top: -120px;
    left: -120px;
    filter: blur(120px);
  }
</style>
