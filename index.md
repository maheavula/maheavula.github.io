---
layout: default
title: Welcome
---

<style>
  body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: linear-gradient(45deg, #24292e, #0366d6);
    background-size: 400% 400%;
    animation: gradientAnimation 15s ease infinite;
    color: white;
    overflow: hidden;
  }

  @keyframes gradientAnimation {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }

  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    text-align: center;
    padding: 20px;
  }

  .glass {
    background: rgba(255, 255, 255, 0.1);
    backdrop-filter: blur(10px);
    padding: 30px;
    border-radius: 15px;
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
    color: white;
    max-width: 600px;
    width: 100%;
  }

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
    transition: all 0.3s ease;
  }

  .btn:hover {
    background: linear-gradient(90deg, #0366d6, #24292e);
    transform: translateY(-5px);
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.4);
  }
</style>

<div class="container">
  <div class="glass">
    <h1>Welcome to My Professional Portfolio</h1>
    <p>I am a cybersecurity enthusiast with hands-on experience in security analysis, reverse engineering, and vulnerability management. My portfolio includes various projects in malware detection and network security.</p>
    <p>
      <a href="https://maheavula.netlify.app/" class="btn">
        Visit My Professional Website
      </a>
    </p>
  </div>
</div>
