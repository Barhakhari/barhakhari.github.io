---
layout: minimal
title: "Contact Us"
---

<head>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
</head>

<style>
  body {
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
    background-color: #f4f4f4;
    color: #333;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }

  .contact-container {
    width: 100%;
    max-width: 600px;
    background: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    padding: 20px 30px;
  }

  .contact-container h1 {
    font-size: 2em;
    margin-bottom: 20px;
    color: #333;
  }

  .contact-form label {
    font-size: 1em;
    color: #555;
    margin-bottom: 8px;
    display: block;
  }

  .contact-form input,
  .contact-form textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ddd;
    border-radius: 5px;
    font-size: 1em;
  }

  .contact-form button {
    background-color: #0078d7;
    color: #fff;
    border: none;
    padding: 10px 20px;
    font-size: 1em;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
  }

  .contact-form button:hover {
    background-color: #005bb5;
  }

  .contact-form .success-message {
    color: green;
    font-size: 0.9em;
    margin-top: 15px;
  }

  .contact-form .error-message {
    color: red;
    font-size: 0.9em;
    margin-top: 15px;
  }
</style>

<div class="contact-container">
  <h1>Contact Us</h1>
  <form 
    class="contact-form" 
    action="https://formspree.io/f/xyzzrekp" 
    method="POST">
    <label for="name">Name</label>
    <input type="text" id="name" name="name" placeholder="Your Name" required>

    <label for="email">Email</label>
    <input type="email" id="email" name="_replyto" placeholder="Your Email" required>

    <label for="message">Message</label>
    <textarea id="message" name="message" rows="6" placeholder="Write your message here" required></textarea>

    <button type="submit">Send Message</button>
  </form>
</div>

