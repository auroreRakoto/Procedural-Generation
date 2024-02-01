# Proc# Guide d'utilisation - Unity avec EndlessTerrain

## Prérequis
- Unity version 2022.3.15f1
- Les scripts Unity: `EndlessTerrain.cs`, `MapDisplay.cs`, `MapGenerator.cs`

## Instructions

1. **Téléchargement du projet**
   - Clonez le dépôt Git sur votre machine locale :
     ```bash
     git clone https://github.com/votre-utilisateur/votre-projet.git
     ```

2. **Ouverture du projet Unity**
   - Lancez Unity Hub.
   - Sélectionnez "Add" et choisissez le répertoire du projet cloné.

3. **Association des scripts à un Empty GameObject**
   - Dans la fenêtre Unity, ouvrez la scène où vous souhaitez utiliser les scripts.
   - Assurez-vous que les scripts `EndlessTerrain`, `MapDisplay`, et `MapGenerator` sont présents dans le dossier "Assets/Scripts" ou un autre emplacement de votre choix.
   - Créez un GameObject vide (`GameObject -> Create Empty`).
   - Faites glisser et déposez les scripts sur l'objet vide dans l'Inspecteur pour les attacher.

4. **Script `MapGeneratorEditor` dans le dossier "Editor"**
   - Assurez-vous que le script `MapGeneratorEditor` est placé dans un dossier nommé "Editor" à l'intérieur de "Assets". Si ce dossier n'existe pas, créez-le.

5. **Ajout de plans pour tester la génération de chunk**
   - Ajoutez deux plans (`GameObject -> 3D Object -> Plane`).
   - Utilisez ces plans pour tester la génération de chunk sans lancer le bouton "Play". En les ajoutant sur le EmptyGameObject.

6. **Ajout d'un joueur (cube) pour tester le suivi du monde infini**
   - Ajoutez un joueur (par exemple, un cube) pour tester le suivi du monde infini en mode "Play". (`GameObject -> 3D Object -> Cube`)
   - Placez le joueur dans la scène selon vos besoins.

7. **Lancement de la scène**
   - Appuyez sur le bouton "Play" dans Unity pour lancer la scène.
   - Vérifiez la console Unity pour les éventuels messages d'erreur ou de débogage.
## Notes supplémentaires
- Assurez-vous d'avoir les bonnes versions des scripts pour éviter les incompatibilités.
- Consultez la documentation des scripts pour plus d'informations sur la configuration.

---

**Auteur : Aurore Rakotoarivony**
