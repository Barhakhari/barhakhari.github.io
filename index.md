---
layout: minimal
title: "Barhakhari - Guide for Nepali Alphabets"
#permalink: /marketing/
---
<head>
  <link rel="icon" href="{{ site.favicon | https://barhakhari.github.io.favicon.png }}" type="image/png">
</head>

<style>

  /* Hide default Jekyll page title and header */
  h1.page-title {
    display: none;
  }

  header {
    display: none;
  }
  
  /* Full-page background */
  .background-image {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url('/bg.png');
    background-size: cover;
    background-position: center;
    z-index: -2;
  }

  /* Blur overlay */
  .blur-overlay {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    backdrop-filter: blur(8px);
    z-index: -1;
  }

  /* Main container for content */
  .content-container {
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    padding: 20px;
  }

  /* Left and right halves */
  .left-half {
    flex: 1;
    display: flex;
    justify-content: center;
    padding: 20px;
  }

  .right-half {
    flex: 1;
    color: white;
    text-align: left;
    padding: 20px;
  }

  /* Styling for text and button */
  .title {
    font-size: 3.5em;
    font-weight: bold;
    margin-bottom: 20px;
  }

  .description {
    font-size: 1.5em;
    margin-bottom: 30px;
  }

  /* Responsive adjustments */
  @media (max-width: 768px) {
    .content-container {
      flex-direction: column;
    }

    .left-half, .right-half {
      flex: none;
      width: 100%;
      text-align: center;
    }
  }
  .app-store-button {
  display: inline-block;
  width: 230px; /* Adjust as needed */
  height: 70px; /* Adjust as needed */
  background-image: url('/appstore.png');
  background-size: cover;
  background-position: center;
  border-radius: 10px;
  text-indent: -9999px; /* Hides the text visually */
}

.app-store-button:hover {
  opacity: 0.7; /* Optional: add a slight hover effect */
}
</style>
<div class="background-image"></div>
<div class="blur-overlay"></div>

<div class="content-container">
  <!-- Left half with mobile screenshot -->
  <div class="left-half">
    <img src="/barhakhari.png" alt="Mobile Screenshot" style="width: 90%; border-radius: 20px;">
  </div>

  <!-- Right half with text and button -->
  <div class="right-half">
    <div class="title">BARHAKHARI</div>
    <div class="description">
      "Empowering young minds to trace the roots of our language, one Nepali letter at a time."
    </div>
    <!--<a href="https://your-app-store-link.com" class="app-store-button" target="_blank">Download on the App Store</a> -->
    <a href="https://your-app-store-link.com" class="app-store-button" target="_blank" aria-label="Download on the App Store"></a>
  </div>
</div>


