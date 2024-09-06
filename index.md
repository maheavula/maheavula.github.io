---
layout: default
title: Welcome
---

# Welcome to My Professional Portfolio

## About Me

I am a cybersecurity enthusiast with hands-on experience in security analysis, reverse engineering, and vulnerability management. My portfolio includes various projects in malware detection and network security.

### Professional Website

<div style="text-align: center; padding: 20px;">
  <a href="https://maheavula.netlify.app/" 
     class="btn" 
     style="display: inline-block; 
            color: white; 
            padding: 15px 30px; 
            text-decoration: none; 
            border-radius: 50px; 
            font-size: 18px; 
            font-weight: bold; 
            background: linear-gradient(90deg, #24292e, #0366d6);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3); 
            position: relative; 
            overflow: hidden; 
            transition: all 0.4s ease;">
    Visit My Professional Website
  </a>
</div>

<style>
  .btn {
    display: inline-block;
    color: white;
    padding: 15px 30px;
    text-decoration: none;
    border-radius: 50px;
    font-size: 18px;
    font-weight: bold;
    background: linear-gradient(90deg, #24292e, #0366d6);
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
    position: relative;
    overflow: hidden;
    transition: all 0.4s ease;
  }

  .btn::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 300%;
    height: 300%;
    background: rgba(3, 102, 214, 0.3);
    transition: all 0.5s ease;
    z-index: 0;
    border-radius: 50%;
    transform: scale(0);
  }

  .btn:hover::before {
    transform: scale(1);
  }

  .btn:hover {
    background: linear-gradient(90deg, #0366d6, #24292e);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4);
    transform: translateY(-5px);
  }

  .btn {
    position: relative;
    overflow: hidden;
  }

  .btn span {
    position: relative;
    z-index: 1;
  }
</style>
