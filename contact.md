---
layout: page
title: Contact
permalink: /contact/
---
<div class="fr" dir="rtl">תודה על ביקורכם באתר,  אם אהבתם את מה שראיתם, אנא צרו קשר.
אני זמינה למשרה מלאה, חלקית וכפרילנסר.
<br /> </div>
<div class="fl">Thanks for stopping by my site. If you liked what you saw, get in touch! I'm available for hire as a fulltime or part time freelance or salaried position. <br /></div>
<div class="full">
	
		<div class="card">
	    <figure class="photo">
	      <img class="cont-pic" src="../images/contact.jpg" alt="pic">

	      <figcaption class="pic-desc"><a href="tel:01234567890">(054) 693-3675</a>
	      	<span>&#103;&#105;&#110;&#097;&#108;&#101;&#055;&#064;&#103;&#109;&#120;&#046;&#099;&#111;&#109;</span></figcaption>
	    </figure>
	  </div>

	  <div class="social-links">
	  	<ul>
	  		{% if site.behance_username %}
          <li>
            {% include icon-behance.html username=site.behance_username %}
          </li>
          {% endif %}
	  		{% if site.github_username %}
	  		<li>
            {% include icon-github.html username=site.github_username %}
          </li>
          {% endif %}

          {% if site.twitter_username %}
          <li>
            {% include icon-twitter.html username=site.twitter_username %}
          </li>
          {% endif %}
	  	</ul>
	  </div>
</div>
