<canvas id="custom" class="canvas" data-fragment-url="examples/moon.frag" data-textures="examples/images/moon-texture.jpg" width="350px" height="350px"></canvas>

# The Book of Shaders
*par [Patricio Gonzalez Vivo](http://patriciogonzalezvivo.com/)*

Ceci est un guide étape-par-étape à travers le monde abstrait et complexe des Fragment Shaders.

<div class="header">
<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=B5FSVSHGEATCG" style="float: right;"><img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif" alt=""></a>
</div>

## Contenu

* [A propos de ce livre](00/?lan=fr)

* Pour commencer
    * [Qu'est ce qu'un shader?](01/?lan=fr)
    * [“Hello world!”](02/?lan=fr)
    * [Les uniforms](03/?lan=fr)
    * [Exécuter votre shader](04/?lan=fr)

* Le dessin algorithmique
    * [Les fonctions](05/?lan=fr)
    * [Les couleurs](06/?lan=fr)
    * [Les formes](07/?lan=fr)
    * [Les matrices](08/?lan=fr)
    * [Les motifs](09/?lan=fr)

* La conception générative
    * [Le hasard](10/?lan=fr)
    * [Le bruit](11/?lan=fr)
    * Fractional Brownian Motion
    * Fractals

* Image processing:
    * Textures
    * Image operations
    * Kernel convolutions
    * Filters
    * Others effects

* Simulation
    * Pingpong
    * Conway
    * Ripples
    * Water color
    * Reaction diffusion

* 3D graphics
    * Lights
    * Normal-maps
    * Bump-maps
    * Ray marching
    * Environmental-maps (spherical and cube)
    * Reflect and refract

* [Appendice:](appendix/) Autres manières d'utiliser ce livre
	* [Comment puis-je consulter ce livre hors-ligne?](appendix/)
	* [Comment exécuter les exemples sur un RaspberryPi?](appendix/)
	* [Comment imprimer ce livre?](appendix/)

* [Galerie d'exemples](examples/)

* [Glossaire](glossary/)

## A propos de l'auteur

[Patricio Gonzalez Vivo](http://patriciogonzalezvivo.com/) (1982, Buenos Aires, Argentine) est un artiste et développeur installé à New York. Il explore les espaces interstitiels entre l'organique et le synthétique, l'analogique et le numérique, l'individuel et le collectif. Dans son travail, il utilise le code comme un langage expressif avec l'intention de développer un mieux-vivre ensemble.

Patricio a étudié et a pratiqué la psychothérapie et l'art-thérapie. Il détient un MFA en Design & Technologie de Parsons The New School, où il enseigne maintenant. Actuellement il travaille comme ingénieur graphique pour Mapzen, travaillant sur des outils cartographiques openSource.

<div class="header"><a href="https://twitter.com/patriciogv" target="_blank">Twitter</a> - <a href="https://github.com/patriciogonzalezvivo" target="_blank">GitHub</a> - <a href="https://vimeo.com/patriciogv" target="_blank">Vimeo</a> - <a href="https://www.flickr.com/photos/106950246@N06/" target="_blank"> Flickr</a></div>

## Remerciements

Merci à ma femme [Jen Lowe](http://www.datatelling.com/), pour son support sans faille, son aide et son temps passé à la révision de ce livre.

Merci à [Scott Murray](http://alignedleft.com/) pour l'inspiration et les conseils.

Merci à [Kenichi Yoneda (Kynd)](https://twitter.com/kyndinfo) et [Sawako](https://twitter.com/sawakohome) pour la [traduction (日本語訳)](?lan=jp) japonaise

Merci à [Tong Li](https://www.facebook.com/tong.lee.9484) et [Yi Zhang](https://www.facebook.com/archer.zetta?pnref=story) pour la [traduction (中文版)](?lan=ch) chinoise

Merci à [Jae Hyun Yoo](https://www.facebook.com/fkkcloud) pour la [traduction (한국어)](?lan=kr) coréenne

Merci à [Karim Naaji](http://karim.naaji.fr/) qui a contribué par son support, ses bonnes idées et son code.

Merci à tous ceux qui ont cru en ce projet et à ceux qui ont [contributé aux corrections](https://github.com/patriciogonzalezvivo/thebookofshaders/graphs/contributors) ou qui ont fait des dons.

## De nouveaux chapitres

Abonnez-vous à la newsletter ou [suivez-nous sur Twitter](https://twitter.com/bookofshaders)

 <form style="border:1px solid #ccc;padding:3px;text-align:center;" action="https://tinyletter.com/thebookofshaders" method="post" target="popupwindow" onsubmit="window.open('https://tinyletter.com/thebookofshaders', 'popupwindow', 'scrollbars=yes,width=800,height=600');return true"><a href="https://tinyletter.com/thebookofshaders"><p><label for="tlemail">Entrez votre adresse mail</label></p></a><p><input type="text" style="width:140px" name="email" id="tlemail" /></p><input type="hidden" value="1" name="embed"/><input type="submit" value="Souscrire" /><p><a href="https://tinyletter.com" target="_blank"></a></p></form>
