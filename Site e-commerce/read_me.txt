Bonjour et bienvenue sur mon site de e-commerce !

Vous êtes sur le point de plonger dans l’univers des huiles essentielles, des encens et des bougies parfumées, pour faire de votre intérieur un lieu propice à la détente et au bien-être.

1) Concernant la structure du site
    a) Le menu
        J’ai choisi de faire un menu déroulant en haut de l’écran pour y intégrer des sous-menus. J’aurais pu ne pas le faire et choisir en catégorie simplement les différentes utilisations des huiles essentielles, mais j’étais contente d’avoir réussi le menu déroulant… donc je l’ai laissé, même s’il m’a fallu trouver les autres catégories du menu.
        Le menu est toujours placé en haut des pages sur ordinateur et disparaît lors du scroll sur les supports plus petits : cela permet de libérer de l’espace de lecture.
    b) Le sous-menu
        Le sous-menu n’est pas disponible sur les supports plus petits tels que les téléphones. On peut toujours y accéder via la catégorie parente, à savoir « huiles essentielles ». De là, la page permet de se rendre sur chaque sous-menu initialement disponible. C’est d’ailleurs le cas sur tous les supports.
    c) Les pages du site
        J’ai choisi volontairement de ne pas mettre d’image de fond en background. Le site comportant déjà des images, je me suis dit que cela chargerait les pages inutilement et rendrait la lecture plus compliquée.
        J’ai chargé 2 polices différentes : la principale et la secondaire uniquement pour les termes latins.
	d) Côté HTML/css
		J’ai créé des classes que je n’utilise pas dans mon css. J’ai souhaité les conserver, car elles pourraient sans doute être utilisées dans les prochaines étapes d’amélioration, peut-être en lien avec d’autres langages. Ma première idée était de pouvoir relier entre elles toutes les classes d’huiles essentielles identiques par exemple en les affichant et créant ainsi un lien vers des pages uniquement d’huiles essentielles utilisables avec des compresses… mais il a fallu faire un choix dans ce qu’on faisait lors du développement de ce projet et j’ai opté pour regrouper les huiles par catégorie « eau », « air », « peau » et « urgence » et n’ai donc pas utilisé les classes « compresse » par exemple.


2) Concernant le contenu
	a) Les textes
		Le contenu a été largement inspiré du livre « Mon guide des huiles essentielles » paru aux éditions « PRISMA » (ISBN:978-2-8104-2882-3). Les textes ont été retravaillés pour éviter le plagiat, puis finalement, la plupart des textes ont simplement été générés par Lorem Ipsum. 
	b) Les images
        Les images ont été récupérées via https://eol.org/ et https://commons.wikimedia.org/wiki/Accueil. Certaines sont simplement des placeholder par souci de gain de temps sur la recherche de photo. Si je n’ai fait aucune erreur, elles sont toutes libres de droits et d’utilisation.
		Au début, j’ai redimensionné certaines images, mais leurs dimensions étant trop aléatoire, j’ai opté pour mettre un cadre via le css pour n’afficher qu’une partie des images, sans les déformer.
		J’ai puisé sur internet la manière de faire un manège pour faire défiler les images. Je l’ai adapté à mon site et mon cadre, mais malgré de nombreuses tentatives, je n’ai pas réussi à l’adapter exactement comme je le voulais. J’aurais aimé que le fait de cliquer sur une image ne fasse pas scroller la page pour afficher l’image tout en haut. De même, j’ai rencontré un souci lors de l’adaptation sur mobile : j’ai donc opté pour afficher les images sans manège sur les formats de téléphone et tablette en format portrait (sur tablette, en format paysage, le manège revient.
	c) L’accessibilité
		J’ai tenté de me conformer aux normes d’accessibilité vues en cours, j’ai notamment choisi d’agrandir l’espacement entre les lettres : j’avais déjà appris par le passé que cela facilitait la lecture aux personnes dyslexique et c’est tellement simple à faire que j’ai choisi de l’appliquer de base.
		J’ai également veillé au contraste entre les couleurs, en mode clair comme en mode sombre.
		Je n’ai pas rencontré de souci avec la navigation via le clavier, donc je pense que cela ne posera pas de souci.

3) Mon apprentissage
	Leçon 1 : faire des templates ou une systématisation des tâches
		Quand on a des parties qui se répètent, comme les produits recommandés dont on veut favoriser la vente, avoir un template permet de modifier le texte éventuellement une fois sur la page du site, puis une fois satisfait du résultat, le mettre dans le template pour effectuer les modifications sur les autres pages par la suite. Bien sûr, on peut le faire immédiatement, mais garder un template à jour s’est avéré bien pratique.
	Leçon 2 : soigner son indentation
		Elle aurait pu être en leçon 1. J’ai avancé dans mes pages puis je me suis posé une question sur les indentations et il m’a fallu tout reprendre. Cela n’a pas énormément d’incidence… sauf quand on oublie de fermer une balise, et c’est là que la bonne indentation permet de résoudre rapidement le souci.
	Leçon 3 : dormir
		Ça m’a bien aidé à mettre mes idées au clair et trouver la solution à des soucis sur lesquels j’avais pu passer un bon bout de temps. Je repense notamment à un souci d’affichage de mes écritures latines. J’avais même posé la question en cours, étant à court d’idées. Un camarade m’a demandé si j’avais bien mis la police dans ma page. Machinalement, j’ai répondu que oui, mais elle n’était pas remise sur cette page précise (autrement dit, mon header dans cette page-là n’était pas à jour) : c’est ma nuit de sommeil qui m’a fait comprendre ce dont il me parlait (à savoir bien de la page et non pas du css) et il avait raison… ce qui nous renvoie à la leçon 1 : avec un template à jour, j’aurais éviter ce souci, car certains headers n’avaient pas été mis à jour.
		
Conclusion :
C’est en forgeant qu’on devient forgeron… ou learning by doing… C’est une technique qui fonctionne assez bien avec moi, ayant une mémoire kinesthésique. À force de me tromper, de chercher, d’essayer, je comprends de mieux en mieux. Je suis heureuse qu’internet existe, il facilite aussi grandement la recherche de solution (avec du tri… parfois beaucoup de tri…), surtout quand on a les bonnes ressources !
