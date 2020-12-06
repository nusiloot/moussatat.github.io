---
layout: post 
categories: ['classes',' ']
title: "Séquence 2 : Les réseaux sociaux"
subtitle: "le cours"
date: 2021-01-08
tags: [ ] 
comments: false
social-share: false
---
## <span style="color: #f1c40f;"><i class="fas fa-bolt icon-yellow" aria-hidden="true"></i></span> Les Réseaux Sociaux
{: .box-warning}
 
### Définition et exemples
**Réseau social** Selon [Wikipédia](https://fr.wikipedia.org/wiki/R%C3%A9seau_social), l'expression réseau social désigne en science humaines un ensemble de liens entre des individus et/ou des organisations (des **entités sociales**), constituant un groupement qui a un sens : la famille, les collègues, un groupe d'amis, une communauté.

**Exemples de réseaux sociaux** :
- Une famille et les liens de parenté
- Une classe et les liens entre les élèves : &laquo; être amis de &raquo; 
- Une population et les liens orientés &laquo; être fan de &raquo; (un artiste, équipe de foot)

{: .box-note}  
Avec l'apparition d'internet, l'expression **Réseaux sociaux** désigne couramment les **services de réseautage social en ligne** : c'est l'ensemble des moyens virtuels mis en oeuvre pour relier des entités sociales.
 
**Exemples** :
- <i class="fab fa-facebook-f"></i> Facebook : littéralement trombinoscope, au départ un réseau social universitaire devenu en l'espace de 7 ans un outil important dans le printemps arabe. Dispose d'un outil nommé **Social graph** qui représente tout types de liens entre entités.
	![Social Graph](https://upload.wikimedia.org/wikipedia/commons/d/de/Social_graph.gif)
- <i class="fab fa-linkedin-in"></i> LinkedIn : réseau social d'employés entre entreprises.

### Caractéristiques

Un internaute est amené à fournir des données personnelles lors de son inscription et la création d'un identifiant.  
Les fonctionnalités sont :
- sites accessibles depuis différentes plateformes (<i class="fas fa-laptop"></i> ordinateurs, <i class="fas fa-mobile-alt"></i> mobile, <i class="fab fa-xbox"></i> consoles)
- partage de différents types de contenu :
	- texte : <i class="fab fa-wordpress"></i> Wordpress, <i class="fab fa-tumblr"></i> tumblr, <i class="fab fa-blogger"></i> blogger
	- forums : <i class="fab fa-reddit"></i> reddit, <i class="fab fa-steam-symbol"></i> steam 
	- microblogging : <i class="fab fa-twitter"></i> Twitter, <i class="fab fa-weibo"></i> sina Weibo
	- Images : <i class="fab fa-instagram"></i> Instagram, <i class="fab fa-snapchat"></i> Snapchat,
	- Son : <i class="fab fa-soundcloud"></i> Soundcloud, 
	- Vidéos : <i class="fab fa-youtube"></i> Youtube, <i class="fab fa-periscope"></i> Périscope, <i class="fab fa-twitch"></i> twitch
	- Avis : <i class="fab fa-tripadvisor"></i> Tripadvisor
- contenu public, ou restreint. Éphémère ou persistant.
- Possibilité d'interactions avec des <i class="far fa-comments"></i> commentaires, <i class="fas fa-share-alt-square"></i> partages, <i class="far fa-heart"></i> likes...

L'utilisation des réseaux sociaux laisse des traces qui constituent notre **identité numérique**. Elles façonnent l'image que les autres se font de nous : &laquo; notre **e-réputation** &raquo;. Le paramétrage de ses comptes et la sécurité de son identification et authentification visent à protéger sa e-réputation.
 
### Le modèle économique 
- **ciblage publicitaire** : elle peut être *ciblée* en fonction du profil de l’utilisateur et *sponsorisée* pour être mise en avant. 
- **revente des données des utilisateurs** : ce sont les entreprises des réseaux sociaux qui fournissent des informations nécessaires pour le ciblage 
- le modèle **fremium** qui combine un accès de base gratuit et un abonnement **premium** proposant des fonctionnalités supplémentaires.


## <span style="color: #f1c40f;"><i class="fas fa-bolt icon-yellow" aria-hidden="true"></i></span> Modélisation d'un réseau social
{: .box-warning}

Pour représenter un réseau social on utilise un graphe défini par :
- **sommets** : modélisent les entités sociales (utilisateurs)
- **arêtes** : modélisent les relations non orientées entre les entités
- **arcs** : modélisent une relation orientée d'une personne ou entité vers une autre.

**Exemple de graphe non orienté** : Sur le réseau Facebook, pour être en relation, deux personnes
inscrites doivent sʼaccepter mutuellement comme amis. Une arête entre 2 sommets représente la relation &laquo; sont amis &raquo;.

**Exemple de graphe orienté** : Sur Twitter, il est possible de suivre une personne inscrite sans que cela soit réciproque. Un arc entre 2 sommets représente la relation &laquo; est un abonnés de &raquo;.
 
<div class="mxgraph" style="max-width:100%;border:1px solid transparent;" data-mxgraph="{&quot;highlight&quot;:&quot;#0000ff&quot;,&quot;nav&quot;:true,&quot;resize&quot;:true,&quot;toolbar&quot;:&quot;zoom layers lightbox&quot;,&quot;edit&quot;:&quot;_blank&quot;,&quot;xml&quot;:&quot;&lt;mxfile host=\&quot;www.draw.io\&quot; modified=\&quot;2019-12-25T21:41:33.778Z\&quot; agent=\&quot;Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/79.0.3945.88 Safari/537.36\&quot; etag=\&quot;_zN3B5GI3lYq-B3Jj8ji\&quot; version=\&quot;12.4.3\&quot; type=\&quot;device\&quot; pages=\&quot;1\&quot;&gt;&lt;diagram name=\&quot;Page-1\&quot; id=\&quot;42789a77-a242-8287-6e28-9cd8cfd52e62\&quot;&gt;7VvbcqM4EP0aP2aLO/ZjLpPZSu1OTVVSsztPUwootjYYeYQc2/P1KxlxE8IGm8skJi9BLSFEn9PdUjeemLfL7WcCVou/sQ+DiaH524l5NzEMQzNc9o9LdrFE11w9lswJ8oUsEzyiXzAZKKRr5MOoMJBiHFC0Kgo9HIbQowUZIARvisNecFB86grMYUnw6IGgLP0H+XQhpLqmZR1/QjRfiEdPbdHxDLzXOcHrUDxvYpgv+7+4ewmSucT4aAF8vMmJzE8T85ZgTOOr5fYWBly5idri++4retN1ExjSWjdAYOquO9N8wwOzqXllxDO8gWANk1dwAjbXTbQCIbue8+snHO4SOZs83yXei+4SXbIHMthY42azQBQ+roDHezaMOky2oMuAtXR2uVcb5AvT+OMSzfAuDy+RJzoC8AyDm1TPtzjAhHWFOOTPiCjBrylo/N4XHNJ7sEQBJ+M3SHwQAiEWxNOZ2m9AgOYha3hMc5CkL5JXpdDuGyQUbnMiodrPEC8hJUwxWtKb0ELYgeGI9iYjlWvHokWOTsltQNB4ns6cQckuBJo1kTVrIfuwDhAMR2yPYstsvoBtivUQ2Lq1sP2CmHaE/JlkoI5YN8R6UDuelbB+AD4c4cq5Xavodgc1zWRLc8Q27wmDYLTEphHV7BHaJ+2vq8iNHhxto/348p+7WNwFV5YCXRmu0L/me9JMpTmIitq1mIQph+z+Fd37xneO0x920rzbCtzi1k604udCv7SzLak7wmviwQq+ilBCAZlDWjHGUGOUwyDRtwoDAgNA0VtxmSpgxBO+YsReIKOAVqSAJWMbv564K7/3lSeSuGRp0kSxDkoT7XmSvvbp1LG7o06OLd/zTOqWOomrG7nTOXecj8adOm7HHKnTAnVUZ4W2qNMsYsEtommgY9e5u1gru4k3WqbbbKRbT3SbHqebtyZv+11q7Gt65Z7WgHtsafeIv33vQXN20VRkfAC73LAVHxAdWLApHRJc7fC6dGm8fmS8URyvTwvj2UW84lbtqHzs78ZtH4v3Sqfdh8s2fnuXLdHIck+1E0eayOjXZeuGgmtxaoKf8Qukc36ucdJxFe1P/9dsgD5dbbPONMkBPPiM8Wsu0RFPWJHooHBLVSyWMhQvzClLolLugacYkAeCa9GxRL4fVKVQinkToQw5R6FgcHXaQqZGgmiOmWlNKE9NGfnW8hZ6vXLA5RR6zsLXlkJknwliNbyqvNRlV3vOAtgxh6v2qAFWZY/Gkk9ngA9v0eWUzwes+5yFmTUbru6jxqxeXfZyaj+tBtnBaz96jdxG7kzmBSCKuOK7qf9k2Qn95EPXwVCTP3kd2FMOdfyy5OzCqWkKmWd9Z8z0Zkf9prRqmN/vjlaKlP9Iq+5olRwlPzqtansra6RVG7RKvuHoiFYNg+AJJaXuqOiMVOyViqq8pUTF91lripjmaNmE9uKho7Nz0dxtWpuyps1qU5ZUCzhWm0qLDn3WpgxVMrk6BvxOxanB7cx8HzFCLkmdWtuyqyohfcWI6sT4ebWtpw2iPNVxaaWtEjMGL20ZZ3xycl6O5gTvpB/0Tm06Gquuo7GHdDSuro5fjR2NK/Ey/Sik5YDuSh+DGNrhAF0ab/URoGuklM7aGZ8Qd5V76dpZg4Gi9fs40dnHuF/XiBzJGmVjbMmG7Kl6vZXLkj/AMs+yIdbMfnEbD89+12x++h8=&lt;/diagram&gt;&lt;/mxfile&gt;&quot;}"></div>
<script type="text/javascript" src="https://www.draw.io/js/viewer.min.js"></script>


## Vocabulaire dans un graphe non orienté 
- **chaîne** : suite de sommets reliés par des arêtes**
- **distance entre deux sommet**  est égale à la longueur de la plus petite chaîne qui les relie.
- **écartement/éxcentricité d'un sommet** est la distance maximale entre ce sommet  et les autres nœuds du graphe
- **le centre** est **l'ensemble** des sommets d'écartement minimal.
- **diamètre du graphe** est la distance maximale entre deux sommet de ce graphe.
- **tableau d'adjacence** est un tableau à double entrée ou chaque case contient 1 si les sommets sont liés par une arête, 0 sinon.  
<div class="row">
<div class="col-md-4">
<div class="mxgraph" style="max-width:100%;border:1px solid transparent;" data-mxgraph="{&quot;highlight&quot;:&quot;#0000ff&quot;,&quot;nav&quot;:true,&quot;resize&quot;:true,&quot;toolbar&quot;:&quot;zoom layers lightbox&quot;,&quot;edit&quot;:&quot;_blank&quot;,&quot;xml&quot;:&quot;&lt;mxfile host=\&quot;www.draw.io\&quot; modified=\&quot;2019-12-25T22:55:52.411Z\&quot; agent=\&quot;Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/79.0.3945.88 Safari/537.36\&quot; etag=\&quot;GoTfJwD4itEA6nbIcx3E\&quot; version=\&quot;12.4.3\&quot; type=\&quot;device\&quot; pages=\&quot;1\&quot;&gt;&lt;diagram id=\&quot;871sRjvbQmCMhLPe-pNo\&quot; name=\&quot;Page-1\&quot;&gt;5VnbjtowEP2aPG6VOBDgkQ1sq0orVaJSdx/TxCRWTcwaA2G/vhNi557lspBQmgfkObbHmTnHYwOaaS+ir9xZBs/Mw1RDuhdp5kRDaGgY8BkDuwTo6aME8DnxEsjIgBl5xxLUJbomHl4VBgrGqCDLIuiyMMSuKGAO52xbHDZntLjq0vFxBZi5Dq2iv4gnAhkWGmT4N0z8QK1sWDK+haMGy0hWgeOxbQ4yp5ppc8ZE0lpENqZx7lReknlPDb3pi3EcimMmMHekz7+/ich/Jmv8vvHEz+2D9LJx6FoGrCGLgr/HALosP24pZM5gIYhD7GRyrLc1Ux0Pqz11YxhgDJdR1qm8jJUbeMPEU9E7wPklUWElBKEA42A8bgMi8GzpuHHPFjQXv6tYULAMaDqrZSKDOYmwFwOU+CHYLqQJcwA2mAsCBI9lx28mBFuki8bdOGrMsZEyB4rHbIEF38EQNUGRvSvZ20w7PQkFOdkozJFq9VPPGaHQkJyewC9qjd/Hjvi9Jp1IL9I57JhN83Q2XUYZL7CpIXO+f/LQuaxPOmJ9Tii109BM29bhubYaSps75bkrOfRa29zTO9zc5Vqdbvau6Oy3Rqd9Y7s2focc/rR/rr2bh6Wj2uqYfquG/nLmQ28c32nBClmIi9luSiLkg+9eANSV8RobX/rKnET5zslOWRERL9J33H7NtbMpsaFmrARnf9Jrci/lCXuVO3aJJYiSrbmLDxc74XAfi0NnZJX1HKv9GlYVxjF1BNkUX7eOarnCD0b2G7GhpphWSS1JmHJW/rJedjQoOTJKjpI8VBztlZeGfb4YB58UY1UKjfKskZn+ocwyQWcaTsX5gaAvKEbzSDH270KM5VKZnpQtiXHYnhjra+XFK+UFpYj+Kyl2XRdHHUjxWlXuoGQaLlAtSaZ3oOj8K5JRy3V1libyOeI0Pe16eMESdqwe76OEocGg4MgYtqzHut98b6uGKR1n2j18K7ygHo+93aG70GPn9RF1oMdz1HhKVb2gGo/94nsf1bFy7LddHet+Y7+yGo2zauMtV8Zub463XxnBzP74TYZn/56b078=&lt;/diagram&gt;&lt;/mxfile&gt;&quot;}"></div>
<script type="text/javascript" src="https://www.draw.io/js/viewer.min.js"></script>
</div>
<div class="col-md-8" markdown="1">
**Exemple**  Dans le graphe ci-contre :
- la distance du sommet A au sommet B est de 2
- la distance du sommet C au sommet B est de 1
- la distance du sommet C aux sommets A, B, D et E est de 1. Le sommet a un écartement de 1.
- l'écartement du sommet D est de 1.
- l'ensemble des sommets \\( \{ C; D\} \\) est le centre du graphe.  
- Le tableau d'adjacence et celui des distances entre sommets de ce graphe sont :   

</div>
</div>
<div class="row">
<div class="col-md-4" markdown="1">

| Adjacence | A | B | C | D | E |  
| :---: | :---: | :---: | :---: | :---: | :---:- |  
| A | 0 | 0 | 1 | 1 | 1 |  
| B | 0 | 0 | 1 | 1 | 0 |  
| C | 1 | 1 | 0 | 1 | 1 |  
| D | 1 | 1 | 1 | 0 | 1 |  
| E | 1 | 0 | 1 | 1 | 0 | 

</div>
<div class="col-md-2">
</div>
<div class="col-md-4" markdown="1">

| Distance | A | B | C | D | E |  
| :---: | :---: | :---: | :---: | :---: | :---:- |  
| A | 0 | 2 | 1 | 1 | 1 |  
| B | 2 | 0 | 1 | 1 | 2 |  
| C | 1 | 1 | 0 | 1 | 1 |  
| D | 1 | 1 | 1 | 0 | 1 |  
| E | 1 | 2 | 1 | 1 | 0 | 

</div>
</div>

### Le phénomène du petit monde

Les réseaux sociaux peuvent aider à la construction de nouveux liens entre personnes. Si les rencontres sociales semblent aléatoires, l'organisation de ces réseaux tend vers des regroupements reliés entre eux. 
![phénomène du petit monde](https://i.imgur.com/uqHuMpm.jpg)
Ceci illustre 2 effets :
- les regroupements se font le long de caractéristiques communes : goûts, opinions politiques, diplomes, écoles, éthiniques, linguistiques, religieuses...
	Les algorithmes utilisés par les réseaux sociaux pour recommander du contenu (ou des entités à suivre) peuvent renforcer le phénomène de **chambre d'écho** (de cloisonnement) et à l'**appauvrissement de la pensée critique**.  
- le **phénomène du petit monde** est l'hypothèse selon laquelle chacun puisse être relié à n'importe quel autre individu par une courte chaîne de relations sociales. Les réseaux sociaux diminuent ce degré de séparation entre les entités.

	


## <span style="color: #f1c40f;"><i class="fas fa-bolt icon-yellow" aria-hidden="true"></i></span>  La Cyberviolence
{: .box-warning} 
  
La **cyberviolence** regroupe toues les violences commises à l’aide d’outils de communication numérique. Dans le cas d’actes **répétés** de cyberviolence, on parle de **cyberharcèlement**.  
 
Depuis 2014, il existe un délit spécifique au harcèlement sur internet [(article 222-3-2 du Code pénal)](https://www.legifrance.gouv.fr/affichCodeArticle.do?idArticle=LEGIARTI000026268205&cidTexte=LEGITEXT000006070719). qui a été [renforcé en 2018](https://www.legifrance.gouv.fr/affichCodeArticle.do;jsessionid=A38CEE7B149F44AD3E45C5FE3BDD8171.tplgfr38s_2?idArticle=LEGIARTI000037289658&cidTexte=LEGITEXT000006070719&dateTexte=20180920&categorieLien=id&oldAction=&nbResultRech=)
Les sanctions pénales peuvent atteindre 3 ans de prison et 45 000 € d’amende.
 