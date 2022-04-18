---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<h3>Это рыба</h3>

краткая характеристика сборного курса и выпячивание нашей уникальности.

<h3>Наши выпускники:</h3>

<ul>
{% for physicist in site.alumni %}
	<li>
	  {{ physicist.name }}, {{ physicist.from }}-{{ physicist.to }}, {{ physicist.position }}
  	<!-- <p>{{ physicist.content | markdownify }}</p> -->
	</li>
{% endfor %}
</ul>

[Фото и видео](/photo/)

[Истории, рассказанные нами](/stories/)

[Хвастаемся](/bragging/)
