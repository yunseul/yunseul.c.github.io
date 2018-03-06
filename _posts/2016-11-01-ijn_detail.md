---
layout: post
title: "상세페이지"
date: 2016-11-01
categories:
  - ShoppingMall
  - Design
image: https://kjuhee0712.github.io/images/pages/20161101_ijn_detail.jpg
image-sm: https://kjuhee0712.github.io/images/thumbs/20161101_ijn_detail.jpg
---

<ul class="inform">
	<li class="preview__date" itemprop="datePublished" datetime="{{ page.date | date_to_xmlschema }}">- 작업기간 : {{ page.date | date: "%Y년 %-m월부터 약 %-d개월 이내" }}</li>
	<li class="preview__catetory" itemprop="catetory">- 작업 내용 :
		{% for categories in page.categories %}
           <a href="/category/{{ categories }}/">#{{ categories }}</a>     
      	{% endfor %}</li>
</ul>

![_config.yml]({{ page.image }})


