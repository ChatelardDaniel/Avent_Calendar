# Calendrier de l'avent

1. créer le fichier index.html
2. mettre en place sass,voir la vidéo de charline 'sass pratique 1 sur 5' installer l'extension: live sass compiler de glenn Marks.
3. puis intaller l'extension Sass(.sass only) de Syler, pour la coloration.
4. allez dans L'extension 'Live Sass Compiler', puis cliquez sur la roue crantée, ensuite sur 'paramètres extension'.
5. dans le setting, ajouter "liveSassCompile.settings.formats"
6. créer un dossier 'sass'.
7. créer un fichier 'main.sass' dans le dossier 'sass.
8. lancer watch.
9. créer un reset avec meyer dans le dossier 'base'
10. créer un reset custom personnel dans le dossier 'base'
11. importer les fichiers '_reset' dans main.sass
12. créer un dossier 'page' dans le dossier 'sass', puis créer un fichier '_calendar.sass' dans le dossier 'page' pour mettre un fond sur ma page.
13. mettre une class="calendar sur la balise 'body' du fichier 'index.html'
14. utiliser un '@use"./page/_calendar"' dans 'main.sass' pour relier le fichier '_calendar.sass'
15. créer un dossier 'components' dans le dossier 'sass', puis un fichier '_advent.sass' pour créer une grille.
16. Ajout d'une boucle en sass pour les images
17. créer un bouton dans le fichier 'index.html' et le styliser
18. créer un dossier 'abstract' dans le dossier 'sass', puis créer un fichier '_mixins.sass' pour faire une mixin (genre de fonction)

## copie du setting

```json
"liveSassCompile.settings.autoprefix": [],
"liveSassCompile.settings.formats": [
  {
    "format": "expanded",
    "extensionName": ".css",
    "savePath": "~/../assets/css",
    "savePathReplacementPairs": null
  }
]
```

## reset de meyer

[lien reset de meyer](https://meyerweb.com/eric/tools/css/reset/)
