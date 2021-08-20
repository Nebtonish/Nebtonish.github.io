<h1 align="center"><img src="/assets/img/logo.png" alt="Logo" style="width:220px;height:220px;"></h1>
<script src="/assets/js/firstScript.js"></script>

# NEBTONISH WEBSITE

## TABLE OF CONTENTS

- seed
{:toc}

## WELCOME TO MY WEBSITE

This is my website

I will be using this to potentially post things that I am working on or am interested in

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
