---
title: "Contact"
permalink: /contact/
layout: single
author_profile: true
classes: wide
---

<div class="contact-form">
  <p>
    We are located at: <br/><br/>
    5835 York Rd #1159 <br/>
    Baltimore, MD 21212
  </p>
  <p>
    Interested in working with InOrder?  Please send us a message and we will be in touch shortly.
  </p>
  <form action="https://formspree.io/f/xanqqdqk" method="POST">
    <div class="form-group">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
    </div>
    
    <div class="form-group">
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
    </div>
    
    <div class="form-group">
      <label for="message">Message:</label>
      <textarea id="message" name="message" required></textarea>
    </div>
    
    <button type="submit">Send Message</button>
  </form>
</div>

<style>
.contact-form {
  margin-top: 2em;
}

.form-group {
  margin-bottom: 1em;
}

.form-group label {
  display: block;
  margin-bottom: 0.5em;
}

.form-group input,
.form-group textarea {
  width: 100%;
  padding: 0.5em;
  border: 1px solid #ddd;
  border-radius: 4px;
}

.form-group textarea {
  height: 150px;
}

button[type="submit"] {
  background-color: #007bff;
  color: white;
  padding: 0.5em 1em;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

button[type="submit"]:hover {
  background-color: #0056b3;
}
</style>