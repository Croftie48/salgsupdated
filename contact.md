---
layout: default
title: Contact Us
permalink: /contact/
description: Contact Seaford Allotment Society.
---

<section class="page-head">
  <div class="container">
    <p class="eyebrow">Get in touch</p>
    <h1>Contact Us</h1>
    <p>Have a question about the allotments or the Society? Send us a message and we'll get back to you.</p>
  </div>
</section>

<section class="prose contact-page">
  <div class="contact-card">
    <form action="https://formsubmit.co/contact@seafordallotment.com" method="POST">
      <input type="hidden" name="_subject" value="New contact message — Seaford Allotment Society">
      <input type="hidden" name="_next" value="https://croftie48.github.io/salgsupdated/contact/">
      <input type="hidden" name="_template" value="table">
      <input type="hidden" name="_captcha" value="true">

      <div class="form-field">
        <label for="contact-name">Name</label>
        <input id="contact-name" type="text" name="name" autocomplete="name" required>
      </div>

      <div class="form-field">
        <label for="contact-email">Email</label>
        <input id="contact-email" type="email" name="email" autocomplete="email" required>
      </div>

      <div class="form-field">
        <label for="contact-message">Message</label>
        <textarea id="contact-message" name="message" rows="8" required></textarea>
      </div>

      <button class="button contact-submit" type="submit">Send Message</button>
    </form>

    <p class="contact-note">Your message will be sent to the Seaford Allotment Society committee.</p>
  </div>
</section>
