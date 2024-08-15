---
layout: page
title: Message Board
permalink: /message/
nav: true
nav_order: 4
---

<link rel="stylesheet" href="{{ '/assets/css/message-board.css' | relative_url }}">

{% include message-board.liquid %}

<h1>Message Board</h1>

<form action="#" method="post" id="message-form">
  <input type="text" name="name" placeholder="Your Name" required>
  <textarea name="message" placeholder="Your Message" required></textarea>
  <button type="submit">Post Message</button>
</form>
