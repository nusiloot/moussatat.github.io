---
layout: page
title: SNT 2ndes A
---
# Derniers billets
<div>
<ul class="posts">
  {% for post in site.categories['SNT'] %}
    <li><a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a> » <span class="f1">{% include dateShort.html date=post.date %}</span></li>
  {% endfor %}
</ul></div>
  
# Liens divers
- **Programme** de Sciences numériques et technologie [<i class="far fa-file-pdf"></i>](http://cache.media.education.gouv.fr/file/CSP/41/0/2de_Sciences_numeriques_et_technologie_Ens-commun_1025410.pdf)
- Environnement de développement 
	- [**Module Python de vittascience**](href="https://fr.vittascience.com/python/)
	- [**Basthon**](https://basthon.infobrisson.fr/) 
- [**Emulateur Numworks**](https://www.numworks.com/fr/simulateur/)
- [Ressources eduscol](https://eduscol.education.fr/cid143713/snt-bac-2021.html)