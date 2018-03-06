---
layout: post
title: "어플리케이션"
date: 2016-09-03
categories:
  - MobileWeb
  - ShoppingMall
  - Design
  - Logo
image: https://kjuhee0712.github.io/images/pages/20160903_ijn_mobile.jpg
image-sm: https://kjuhee0712.github.io/images/thumbs/20160903_ijn_mobile.jpg
---

<ul class="inform">
	<li class="preview__date" itemprop="datePublished" datetime="{{ page.date | date_to_xmlschema }}">- 작업기간 : {{ page.date | date: "%Y년 %-m월부터 약 %-d개월 이내" }}</li>
	<li class="preview__catetory" itemprop="catetory">- 작업 내용 :
		{% for categories in page.categories %}
           <a href="/category/{{ categories }}/">#{{ categories }}</a>     
      	{% endfor %}</li>
</ul>

![_config.yml]({{ page.image }})


