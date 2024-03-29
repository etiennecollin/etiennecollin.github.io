---
layout: page
title: Contact
permalink: /contact/
image:
---

You have any questions about me or my work? You want to collaborate and have a
project in mind? Do not hesitate to contact me, I will get back to you as soon
as possible!

In the meantime, check me out on [GitHub](https://github.com/etiennecollin)
and [LinkedIn](https://www.linkedin.com/in/etiennecollin/).

Here is my [online resume](https://resume.etiennecollin.com).

<!-- Version of the form to send basic email -->
<div style="text-align: center">
	<br />
	<button
		class="button button--small"
		onclick="location.href='mailto:{{site.data.settings.contact.email}}';"
		type="button"
	>
		Send me an email!
	</button>
</div>

<!-- Version of the form to send complete email but formatting of email content broken -->
<!-- <div class="form-box">
	<div class="contact-head">
		{% if site.data.settings.contact.description %}
		<p class="contact-description">
			{{site.data.settings.contact.description}}
		</p>
		{% endif %}
	</div>
	<form
		class="form"
		action="{% if site.data.settings.contact.email %}mailto:{{site.data.settings.contact.email}}{% else %}#{% endif %}"
		method="GET"
		enctype="text/plain"
	>
		<div class="form__group">
			<label class="form__label screen-reader-text" for="form-name">
				Your Name
			</label>
			<input
				class="form__input"
				id="form-name"
				type="text"
				name="name"
				placeholder="Name"
				required
			/>
		</div>
		<div class="form__group">
			<label class="form__label screen-reader-text" for="form-subject">
				Your Subject
			</label>
			<input
				class="form__input"
				id="form-subject"
				type="text"
				name="subject"
				placeholder="Subject"
				required
			/>
		</div>
		<div class="form__group">
			<label class="form__label screen-reader-text" for="form-body">
				Your Message
			</label>
			<textarea
				class="form__input"
				id="form-body"
				name="body"
				rows="10"
				placeholder="Message"
				required
			></textarea>
		</div>
		<div class="form__group">
			<button class="button button--primary" type="submit" value="Send">
				Send Message
			</button>
		</div>
	</form>
</div> -->

<!-- Version of the form to use with FormSpree -->
<!-- <div class="form-box">
	<div class="contact-head">
	  {% if site.data.settings.contact.description %}
		<p class="contact-description">{{site.data.settings.contact.description}}</p>
	  {% endif %}
	</div>
	<form class="form" action="{% if site.data.settings.contact.email %}https://formspree.io/f/{{site.data.settings.contact.email}}{% else %}#{% endif %}" method="POST">
	  <div class="form__group">
		<label class="form__label screen-reader-text" for="form-name">Your Name</label>
		<input class="form__input" id="form-name" type="text" name="name" placeholder="Name" required>
	  </div>
	  <div class="form__group">
		<label class="form__label screen-reader-text" for="form-email">Your Email</label>
		<input class="form__input" id="form-email" type="email" name="_replyto" placeholder="Email" required>
	  </div>
	  <div class="form__group">
		<label class="form__label screen-reader-text" for="form-text">Your Message</label>
		<textarea class="form__input" id="form-text" name="text" rows="10" placeholder="Message" required></textarea>
	  </div>
	  <div class="form__group">
		<button class="button button--primary" type="submit">Send Message</button>
	  </div>
	</form>
  </div> -->
