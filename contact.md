---
layout: page
title: Contact
permalink: /contact/
---
<div class="fr" dir="ltr">תודה על ביקורכם באתר. אם אהבתם את מה ראיתם נא צרו קשר! אני' מוכנה למשרות שלמות או חלקיות, פרילאנס או קבע<br /> </div>
<div class="fl">Thanks for stopping by my site. If you liked what you saw, get in touch! I'm available for hire as a fulltime or part time freelance or salaried job. <br /></div>
<div class="full">
	
		<div class="card">
	    <figure class="photo">
	      <!-- <img class="self-pic" src="http://www.fillmurray.com/251/251" alt="pic"> -->
	      <img class="self-pic" src="/images/self.gif" alt="pic">

	      <figcaption class="pic-desc"><a href="tel:01234567890">(012) 345-6789</a>
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
