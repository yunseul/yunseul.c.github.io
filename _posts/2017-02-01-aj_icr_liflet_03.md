---
layout: post
title: "2단 리플렛"
date: 2017-02-01
categories:
  - GraphicDesign
image: https://yunseul.github.io/images/pages/20170201_aj_icr_liflet_03.jpg
image-sm: https://yunseul.github.io/images/thumbs/20170201_aj_icr_liflet_03.jpg
---

<ul class="inform">
	<li class="preview__date" itemprop="datePublished" datetime="{{ page.date | date_to_xmlschema }}">- 작업기간 : {{ page.date | date: "%Y년 %-m월부터 약 %-d개월 이내" }}</li>
	<li class="preview__catetory" itemprop="catetory">- 작업 내용 :
		{% for categories in page.categories %}
           <a href="/category/{{ categories }}/">#{{ categories }}</a>     
      	{% endfor %}</li>
</ul>

![_config.yml]({{ page.image }})

