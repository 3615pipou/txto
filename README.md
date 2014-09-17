== txto
== Langage de balisage léger pour les rédacteurs découragés par LaTex

=== Objectifs

L’objectif est de disposer d’un langage de balisage léger pour que les rédacteurs ne s’occupent que du sens, du fond, et de la structure du document sans se soucier ni de la mise en forme du document ni du format de publication (html, pdf, papier, dot, etc.). La notion de texte source pour un document est ainsi popularisée et vulgarisée.

Pour cela on va définir une syntaxe simple à écrire, lisible et intuitive. Ses symboles doivent donc exprimer l’intention qu’ils indiquent. Cette syntaxe ne doit pas entrer en conflit avec le contenu, c’est pourquoi les symboles sont souvent doublés. Cette syntaxe doit recouvrir 90% des besoins des rédacteurs, permettre d’exprimer les intentions communes et laisser les 10 autres pourcentages à LaTex.

D’une part nous nous inspirons du ***Markdown*** (ou CommonMark) pour sa lisibilité et sa simplicité. Mais ce langage est trop pensé à partir du html, donc trop restreint, et il ne prend pas suffisamment en compte les documents annexes. D’autre part nous nous inspirons du ***LaTex*** qui satisfait très bien les besoins d’expression des intention des rédacteurs et qui gère les documents annexes. Mais il est trop compliqué et peu lisible.

La syntaxe souhaitée doit permettre ¨¨d’invoquer dans le document d’autres documents complexes¨¨ (images, sons, films, tableaux, infographies) qui sont stockés à coté du document texte. Tous ces documents sont accessibles via le ¨¨gestionnaire de fichier¨¨. La syntaxe décrira donc aussi un système de fichiers, de dossiers et de paquet pour regrouper tous ces éléments.

La rédaction se fait donc par un éditeur de texte, pas par un traitement de texte. La co-rédaction peut aussi se faire facilement avec un logiciel de gestion de versions décentralisé (git, git-annex, Bup, Darcs), ce qui permet d’historiser et d’archiver l’évolution du document et les discussions qui portent sur la transformation du document (à ne pas confondre avec les commentaires qui eux s’ajoutent au document).


=== Public

Cette syntaxe s’adresse surtout aux rédacteurs ayant besoin de se concentrer sur le contenu (étudiants, blogueurs, encyclopédiste, universitaires, journalistes, etc.), que LaTex rebute, qui doivent publier leurs documents dans de multiples contextes ou les transmettre à une personne qui mettra en forme le document et/ou le publiera dans un contexte possédant déjà sa mise en forme.

