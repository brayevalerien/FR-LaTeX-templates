<span style="font-size:8pt">
    <b>BEWARE: FRENCH REPOSITORY!</b> <br>
    This repository gathers useful LaTeX templates, but all of them are in French. If you are interested in an English version of the repository and the templates, feel free to open an issue or contact me.
</span>

---

# FR-LaTeX-templates
Ce répertoire rassemble des modèles de documents, figures et codes LaTeX qui me sont souvent utiles.

## Notes de cours

![Capture d'écran du modèle "notes de cours"](./images/notes_de_cours.png)

Modèle de document le plus complet, fournissant notamment:
- une page de garde et une introduction au cours clairs
- la mise en page automatique des chapitres
- une table des matières personnalisée
- de nombreux environnements pour questions, solutions, théorèmes, preuves, définitions, remarques, notes...
- des commandes personnalisée pour ajouter des chapitres, des images, des figures, des multi-colonnes...
- une bibliographie utilisant `bibtex`

Ce modèle est utile pour la prise de notes d'un cours pendant une session entière. Les chapitres sont séparés dans différents fichiers `.tex` pour réduire le temps de compilation et organiser les notes. Les chapitres sont ensuite inclus dans le fichier principal et la commande `\lesson` met automatiquement en page les débuts de chapitres.
Ce modèle reste lourd et le long préambule rend le temps de compilation non négligeable (autour de 15 secondes pour un petit chapitre), il ne convient donc pas à tous les usages.

Ce modèle est adapté du modèle [Charlie's Math Template](https://github.com/SeniorMars/dotfiles/tree/5b39b3ef545fa41361dfe64a2cbc03d8411a808f/latex_template) par [@SeniorMars](https://github.com/SeniorMars/).
**Note:** la capture d'écran ci-dessus ne montre pas les vraies couleurs du pdf généré (le viewer pdf applique un filtre).