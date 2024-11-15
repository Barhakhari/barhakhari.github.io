---
layout: minimal
title: "Barhakhari - Guide for Nepali Alphabets"
#permalink: /marketing/
---
<head>
  <link rel="icon" href="/favicon.png" type="image/png">
</head>

<style>
  /* Adjusting left-half styles */
  .left-half {
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: center; /* Ensures the image stays centered vertically within its container */
    padding: 0; /* Removes padding around the container */
    margin: 0; /* Ensures no additional spacing */
  }

  .left-half img {
    width: 100%;
    height: 100%; /* Ensures the image covers the full height */
    object-fit: cover; /* Ensures the image maintains aspect ratio while filling the container */
    border-radius: 0; /* Removes rounded corners */
  }

  /* Full-page container adjustments for padding */
  .content-container {
    align-items: stretch; /* Allows the left-half to stretch to the full height */
    min-height: 100vh; /* Keeps the container height as 100% of the viewport */
    padding: 0; /* Removes padding from the entire content container */
  }

  /* Responsive adjustments */
  @media (max-width: 768px) {
    .content-container {
      flex-direction: column;
    }

    .left-half,
    .right-half {
      flex: none;
      width: 100%;
    }

    .left-half img {
      height: auto; /* Resets height for responsive design */
    }
  }
</style>

<div class="content-container">
  <!-- Left half with mobile screenshot -->
  <div class="left-half">
    <img src="/barhakhari.jpg" alt="Mobile Screenshot">
  </div>

  <!-- Right half with text and button -->
  <div class="right-half">
    <div class="title">BARHAKHARI</div>
    <div class="description">
      "Empowering young minds to trace the roots of our language, one Nepali letter at a time."
    </div>
    <div class="additional-info">
      This app will guide children to write Nepali vowels, consonants, numbers, and Barhakhari.
    </div>

    <a href="https://your-app-store-link.com" class="app-store-button" target="_blank" aria-label="Download on the App Store"></a>
  </div>
</div>



