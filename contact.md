---
layout: page
title: Contact Me
---

<form action="[https://formspree.io/f/xeokrdqb" method="POST">
  <label>Name:</label>
  <input type="text" name="name" required>
  
  <label>Email:</label>
  <input type="email" name="_replyto" required>
  
  <label>Message:</label>
  <textarea name="message" rows="5" required></textarea>
  
  <button type="submit">Send Message</button>
</form>

<style>
  form {
    max-width: 600px;
    margin: 2rem auto;
    font-family: sans-serif;
  }
  label {
    display: block;
    margin: 1rem 0 0.3rem;
  }
  input, textarea {
    width: 100%;
    padding: 8px;
    border: 1px solid #ddd;
    border-radius: 4px;
  }
  button {
    background: #6a994e;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 4px;
    margin-top: 1rem;
    cursor: pointer;
  }
</style>
