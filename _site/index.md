<h1 align="center"><img src="/assets/img/logo.png" alt="Logo"></h1>

# Nebtonish Website

## Table of Contents

- seed
{:toc}

## Welcome to my website

This is my website

I will be using this to potentially post things that I am working on or am interested in

## Posts
<ul>
	{% for post in site.posts %}
		<li>
			<a href="{{ post.url }}">{{ post.title }}</a>
		</li>
	{% endfor %}
</ul>

## Contact me

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
