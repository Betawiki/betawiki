# Découpeuse laser

> ### Caractéristiques de la machine

>* modèle : Trotec Speedy 100

<img style="width: 80%; margin-left: 10%;" src="http://www.europages.com/filestore/opt/product/35/82/Speedy100-machine-laser-support-roulant_77aa5f95.jpg"/>

## Préparer votre fichier

Réalisez votre dessin avec un logiciel de dessin vectoriel, par exemple [Inkscape](https://inkscape.org/fr/), un logiciel libre et gratuit).

> ### Pour récupérer une image depuis Google Images (de préférence une image avec seulement des contours : Outils > Type > Dessin au trait)

>* clic droit sur l'image > Copier l'image
>* dans un nouveau document Inkscape : clic droit sur le document > Coller
>* sélectionnez l'image que vous venez d'insérer : Chemin > Vectoriser le bitmap > Valider
>* déplacez la nouvelle image que vous venez de générer et supprimez la première

<aside class="warning">

<h3 style="display: inline-block";>Vérifiez que votre fichier respecte les conditions suivantes :</h3>
<ul>
<li>les traits que vous souhaitez <strong>découper</strong> sont coloriés en <strong>ROUGE</strong> (Objet > Remplissage et contour : RGBA 255, 0, 0, 255)</li>
<li>les traits que vous souhaitez <strong>graver</strong> sont coloriés en <strong>ROUGE</strong> (Objet > Remplissage et contour : RGBA 0, 0, 0, 255)</li>
<ul><li>vous pouvez aussi utiliser des niveaux de gris pour moduler la profondeur de gravure</li></ul>
<li>l'épaisseur des traits est de <strong>0,01 mm</strong> (Objet > Remplissage et contour)</li>
<li>la page est <strong>redimensionnée à la taille du dessin</strong> (Fichier > Propriétés du document > Redimensionner la page au contenu > Ajuster la page au dessin ou à la sélection)</li>
<li>tous vos objets ont été transformés en <strong>chemins</strong> (sélectionnez vos objets > Chemin > Objets en chemins)</li>
<li>votre fichier est enregistré en <strong>.SVG</strong> (Fichier > Enregistrer sous)</li>
</ul>

</aside>

## Préparer la découpeuse laser

* placer la planche
* allumer la découpeuse laser
* placer le faisceau sur la surface de découpe avec les boutons à droite
* placer le curseur en équilibre
* monter le plateau doucement jusqu'à ce que le curseur tombe

## Paramétrer le travail

* ouvrir le fichier .SVG dans Inkscape
* Fichier > Imprimer : sélectionner Trotec, puis Préférences
	* surface de découpe : 600mm x 300mm
    * matière : sélectionner le type et l'épaisseur
* lancer l'impression : le logiciel JC s'ouvre et demande un nom pour le nouveau "job"
* le fichier devrait apparaître dans le menu de droite : le placer sur la surface de découpe par cliquer-glisser
* sélectionner tous les "jobs" puis cliquer sur Mise à jour pour avoir une estimation du temps de coupe et de gravure
* connecter la découpeuse avec le bouton en bas à droite
* lancer le travail avec le bouton en bas à droite

## Les matériaux

### Les matériaux pour la découpe et la gravure

* **bois :**
	* bois brut (faible épaisseur, éviter les bois résineux qui sont plus inflammables)
	* MDF / Medium < 6mm (sauf MDF tinté dans la masse)
	* contreplaqués
* **platiques :**
	* Polyamide / PA / Nylon
	* Polyoxyméthylène / POM / Delrin
	* Polyester / PES / Thermolite / Polarguard
	* Polyéthylène téréphtalate / PET / Mylar
	* Polyimide / PI / Kapton
	* Polystyrène / PS
	* Acrylique / Polyméthylmétacrylate / PMMA / Plexiglas
	* Polypropylène / PP
	* Acrylonitrile-butadiène-styrène / ABS
	* Polytétrafluoroéthylène) / PTFE
	* Rhodoïd / Transparent pour rétroprojecteur
* **mousses :**
	* Polyester / PES
	* Polyéthylène / PE
	* Polyuréthane / PUR
* **autres :**
	* papier
	* carton
	* liège
	* tissus : feutre, chanvre, coton, acrylique, nylon, laine
	* cuir, daim

### Les matériaux pour la gravure

* pierre, marbre, ardoise
* céramique
* verre (sauf formes cylindriques)
* métaux (sauf métaux polis/réfléchissants) : aluminium, acier, laiton

<aside class="warning">

<h3 style="display: inline-block";>Les matériaux à ne JAMAIS utiliser pour la découpe/gravure laser :</h3>
<p>Pour découper les matériaux, les machines émettent un rayon laser permettant d'élever la température d'une zone réduite de matière, jusqu'à vaporisation de celle-ci. Certains matériaux ne peuvent pas être coupés par ce procédé, il peuvent fondre, émettre des gaz dangereux, ou encore nécessiter une puissance supérieure à ce que permettent les machines du fablab.</p>
<p>Il est interdit d'utiliser dans la découpeuses des matériaux dont vous ne connaissez pas la composition et qui pourraient émettre du chlore du fluor ou autres gaz/vapeurs toxiques.</p>
<ul>
<li>les matériaux réfléchissant : miroirs, objets chromés, métaux polis, etc. -> risque d'endommager la machine</li>
<li>les métaux</li>
<li>la fibre de carbone</li>
<li>la fibre de verre</li>
<li>les matériaux contenant de la résine epoxy</li>
<li>les cartes de circuits imprimés (fibre de verre + epoxy)</li>
<li>les matériaux contenant du chlore : PVC, vinyle, simili cuir, etc. -> risque d'émission de gaz chloré mortel</li>
<li>les matériaux contenant du fluor : Téflon, etc. -> risque d’émission de fluor sous forme de gaz</li>
<li>le verre</li>
<li>le medium valcromat teinté dans la masse -> prend feu</li>
<li>le polycarbonate / PC / Lexan / Makrolon -> fond et brûle</li>
<li>le polystyrène/polypropylène expansé/extrudé (mousse) -> fond et est très inflammable</li>
<li>le neopren -> très inflammable</li>
<li>l'ABS -> émet des gaz toxiques, a tendance à fondre et est très inflammable</li>
<li>le polycarbonate (PC)</li>
<li>le polystyrol (PS)</li>
<li>le PTFE</li>
<li>le POM/Nylon</li>
<li>FOREX, Kappa, Foamcore</li>
<li>FR4 or similar</li>
<li>PUR/Polyurethan</li>
<li>PBTP</li>
<li>HDPE/bouteilles en plastique -> fond et brûle</li>
</ul>
</aside>
