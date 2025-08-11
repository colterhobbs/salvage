---
title: "Contact"
description: "Questions, commissions, or collaborations — we’d love to hear from you."
draft: false
---

Have a project in mind? Send us a note.

<!-- Netlify Forms -->
<form name="contact" method="POST" data-netlify="true" netlify-honeypot="bot-field" action="/contact/thanks" class="space-y-4">
  <!-- Honeypot -->
  <input type="hidden" name="form-name" value="contact" />
  <p class="hidden">
    <label>Don’t fill this out if you’re human: <input name="bot-field" /></label>
  </p>

  <div>
    <label for="name">Name</label><br/>
    <input id="name" name="name" type="text" required class="w-full p-2 border rounded"/>
  </div>

  <div>
    <label for="email">Email</label><br/>
    <input id="email" name="email" type="email" required class="w-full p-2 border rounded"/>
  </div>

  <div>
    <label for="message">How can we help?</label><br/>
    <textarea id="message" name="message" rows="6" required class="w-full p-2 border rounded"></textarea>
  </div>

  <button type="submit" class="px-6 py-3 bg-blue-600 text-white rounded hover:bg-blue-700 transition">
    Send Message
  </button>
</form>
