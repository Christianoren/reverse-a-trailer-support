---
title: Support
description: Get help with Learn to Reverse a Trailer. Contact us by email or find answers to common questions about the trailer reversing app.
permalink: /support
faq:
  - q: The app crashes on startup. What should I do?
    a: Try restarting your device and launching the app again. If the problem continues, please email us with your device model and your Android or iOS version.
  - q: How do I reset my level progress?
    a: Deleting and reinstalling the app resets all progress.
  - q: Can I play in both landscape orientations?
    a: Yes, the app supports both landscape left and landscape right.
  - q: I have an idea for a new level. How do I suggest it?
    a: We'd love to hear it. Send your ideas to reverseatrailer@gmail.com.
---

<div class="wrap page">
  <h1>Support</h1>
  <p class="lead">If you have questions or feedback, or something isn't working in the app, get in touch.</p>

  <div class="contact-card">
    <p><strong>Email:</strong> <a href="mailto:reverseatrailer@gmail.com">reverseatrailer@gmail.com</a></p>
    <p>We aim to respond within 48 hours.</p>
  </div>

  <h2>Frequently asked questions</h2>
  <div class="faq">
    {% for item in page.faq %}
    <details>
      <summary>{{ item.q }}</summary>
      <p>{{ item.a }}</p>
    </details>
    {% endfor %}
  </div>
</div>
