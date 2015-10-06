---
layout: page
title: Contact
permalink: /contact/
comments: false
---

<div id="form-error" class="form-error">
  <h2>Something went wrong. Please try again Later.</h2>
</div>
<div id="form-success" class="form-success">
  <h2>Thanks. I'll be in touch soon.</h2>
</div>
<form id="contact-form" class="contact-form" action="//formspree.io/{{ site.email }}" method="POST">
  <label>
    Name:
    <input type="text" name="name">
  </label>
  <label>
    Email:
    <input type="email" name="_replyto" required>
  </label>
  <label style="display:none">
    Phone:
    <input type="text" name="_gotcha" />
  </label>
  <label>
    Message:
    <textarea id="message" name="message" required></textarea>
  </label>
  <input class="smallbutton blue" type="submit" value="Send">
</form>
