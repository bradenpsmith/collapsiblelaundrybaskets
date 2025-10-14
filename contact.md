---
layout: default
title: "Contact"
nav_title: "Contact"
permalink: /contact/
---

<div class="hero">
  <h1>Get in Touch</h1>
  <p class="sub">
    Have feedback, a basket recommendation, or a tragic laundry story?  
    I’d love to hear it.
  </p>
</div>

<section class="trust">
  <h2>Email</h2>
  <p>
    Send a note to <a href="mailto:collapsiblelaundrybaskets@gmail.com">collapsiblelaundrybaskets@gmail.com</a>.
  </p>
</section>

<section class="trust">
  <h2>Or use the form</h2>
  <form name="contact" method="POST" data-netlify="true">
    <input type="hidden" name="form-name" value="contact">
    <p><label>Name<br><input type="text" name="name" required></label></p>
    <p><label>Email<br><input type="email" name="email" required></label></p>
    <p><label>Message<br><textarea name="message" rows="6" required></textarea></label></p>
    <p><button type="submit">Send</button></p>
  </form>
</section>
