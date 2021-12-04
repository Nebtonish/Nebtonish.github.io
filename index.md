---
title: Home Page
---

<p align="center"><img src="/assets/img/logo.png" alt="Logo" style="width:220px;height:220px;"></p>
<script src="/assets/js/EveryPage.js"></script>

# WEBTONISH

## WELCOME

Welcome to my website.

Here I will be posting projects that I am working on.

## POSTS
<ul>
	{% for post in site.posts %}
		<li>
			<a href="{{ post.url }}">{{ post.title }}</a>
		</li>
	{% endfor %}
</ul>

## CONTACT ME

<form
  action="https://formspree.io/f/xleabwzw"
  method="POST"
>
  <label>
    Your email (optional):
    <br>
    <input type="email" name="_replyto">
  </label>
  <label>
    <br>
    Your message:
    <br>
    <textarea name="message"></textarea>
  </label>
  <button type="submit">Send</button>
</form>
