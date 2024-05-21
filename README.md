# <span style="font-size: 2em; color: #4CAF50;">Crossmaster</span>

**_L'application mobile de la gestion du cross_**

## <span style="color: #2196F3;">Propriété de l'app</span>

<em>L'app utilise un system de communication avec des requetes vers le serveur central de commande</em>

Voici les lien utiles des ressources utiliser par le programme 
- [Flutter: framework pour dart](https://docs.flutter.dev/)
- [Dart: language de devlopement de l'application](https://dart.dev)
- [Flask: framework de devlopement du serveur](https://flask.palletsprojects.com/en/3.0.x/)
- [Python: language de devloppement de tout nos outil du cross (serveur-client)](https://www.python.org/)

Si besoin d'aide veuillez nous contactez a ce mail: [test@exemple.com](mailto:john@example.com)
## <span style="color: #2196F3;">Structure de l'app mobile</span>

```plaintext
crossmaster/
├── lib/
│   ├── main.dart
├── android/
│   └── /android file
├── ios/
│   └── ...
├── web/
│   └── ...
├── pubspec.yaml
└── README.md
```
**Voici un aperçus du scrypt de requete de l'app vers le serveur**
```js
    $('#stop-btn').click(function(){
    $.ajax({
        type: 'POST',
        url: '/stop',
        success: function(response) {
            console.log(response);
            location.reload();
        },
        error: function(xhr, status, error) {
            console.error("error post");
        }
    });
});
```

### <span style="color: #2196F3;">le scrypt utilse ajax pour efectuer des requete post a une adresse de façons rapide</span>

### Explications du fonctionnement de l'app

<!--### <span style="color: red;">Project Structure</span>-->

- **Titre principal** : Utilisation de `<span>` pour changer la taille et la couleur du texte.
- **Description** : Utilisation de `**` pour mettre en gras et `_` pour mettre en italique.
- **Sous-titres** : Utilisation de `<span>` pour changer la couleur du texte.
- **Texte en italique** : Utilisation de `<em>` pour mettre en italique.
- **Blocs de code** : Reste inchangé pour conserver la structure de code lisible.

Ce fichier README utilise des éléments HTML pour appliquer des styles supplémentaires qui ne sont pas pris en charge nativement par Markdown. GitHub et d'autres plateformes de gestion de code prennent en charge ce mélange de Markdown et HTML, permettant d'enrichir le style visuel de vos fichiers README.md.


### Explication des sections

- **Titre et description** : Présentez le projet.
- **Getting Started** : Fournit des ressources pour débuter avec Flutter.
- **Project Structure** : Décrit la structure du projet (vous pouvez personnaliser selon votre projet réel).
- **Installation** : Instructions pour cloner le projet et installer les dépendances.
- **Running the App** : Commandes pour exécuter l'application.
- **Building the App** : Commandes pour construire l'application pour différentes plateformes.
- **Contributing** : Invite à la contribution et explique comment contribuer.
- **License** : Indique sous quelle licence le projet est distribué.

Vous pouvez adapter ce modèle en fonction des spécificités de votre projet.

