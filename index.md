---
layout: minimal
title: "Barhakhari - Guide for Nepali Alphabets"
#permalink: /marketing/
---

<head>
  <link rel="icon" href="/favicon.png" type="image/png">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
</head>

<style>

  /* General reset */
  body {
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
    color: #fff;
    overflow-x: hidden;
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
    background-color: rgba(0, 0, 0, 0.6);
    backdrop-filter: blur(8px);
    z-index: -1;
  }

  /* Main container */
  .content-container {
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    padding: 20px;
  }

  /* Left half with mobile screenshot */
  .left-half {
    flex: 1;
    display: flex;
    align-items: center;
    justify-content: center;
    animation: fadeIn 1s ease-in-out;
  }

  .left-half img {
    width: 90%;
    max-width: 400px;
    border-radius: 15px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.5);
    transition: transform 0.3s;
  }

  .left-half img:hover {
    transform: scale(1.05);
  }

  /* Right half with text and button */
  .right-half {
    flex: 1;
    padding: 20px;
    text-align: left;
    animation: slideIn 1s ease-in-out;
  }

  .title {
    font-size: 3em;
    font-weight: 700;
    margin-bottom: 20px;
    color: #ffcc33;
    text-transform: uppercase;
  }

  .description {
    font-size: 1.5em;
    font-weight: 400;
    margin-bottom: 20px;
    line-height: 1.6;
  }

  .additional-info {
    font-size: 1.2em;
    font-weight: 400;
    margin-bottom: 30px;
  }

  /* App Store button */
  .app-store-button {
  display: inline-block;
  width: 250px; /* Adjust width */
  height: 70px; /* Adjust height */
  background-image: url('/appstore.png'); /* Ensure this is a black button image */
  background-size: contain; /* Fit the image within the button */
  background-repeat: no-repeat;
  background-position: center;
  border-radius: 12px; /* Rounded corners */
  text-indent: -9999px; /* Hides text visually */
  transition: transform 0.3s, opacity 0.3s; /* Hover effect */
}

.app-store-button:hover {
  transform: scale(1.1); /* Slight zoom-in effect */
  opacity: 0.9; /* Fade effect */
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

    .left-half img {
      max-width: 300px;
    }

    .right-half {
      padding: 0;
    }
  }

  /* Animations */
  @keyframes fadeIn {
    from {
      opacity: 0;
    }
    to {
      opacity: 1;
    }
  }

  @keyframes slideIn {
    from {
      transform: translateY(30px);
      opacity: 0;
    }
    to {
      transform: translateY(0);
      opacity: 1;
    }
  }

</style>

<div class="background-image"></div>
<div class="blur-overlay"></div>

<div class="content-container">
  <!-- Left half with mobile screenshot -->
  <div class="left-half">
    <img src="/barhakhari.jpg" alt="Mobile Screenshot">
  </div>

  <!-- Right half with text and button -->
  <div class="right-half">
    <div class="title">Barhakhari</div>
    <div class="description">
      "Empowering young minds to trace the roots of our language, one Nepali letter at a time."
    </div>
    <div class="additional-info">
      This app will guide children to write Nepali Vowels, Consonants, Numbers, and Barhakhari.
    </div>
    <a href="https://your-app-store-link.com" class="app-store-button" target="_blank" aria-label="Download on the App Store"></a>
  </div>
</div>
