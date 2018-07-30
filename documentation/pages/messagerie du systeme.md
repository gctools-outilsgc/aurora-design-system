# Messagerie du système

Les notifications du système sont de courts messages qui apparaissent pour communiquer de l’information à l’utilisateur. Des notifications apparaissent comme des bannières en premier plan qui ont besoin d’être fermées ou qui se ferment après une période de temps. Il y a quatre niveaux de gravité qui peuvent être appliqués à la notification : erreur, avertissement, information et succès.

Les notifications conçues du système en ordre décroissant de sévérité :

## Erreur
Les notifications d’erreur sont utilisées pour les pannes de système et les erreurs de l’utilisateur.

Exemple d’erreur : « Votre mot de passe doit contenir au moins huit (8) caractères. »

## Avertissement

Les notifications d’avertissement sont utilisées pour les avis d’éventuelles erreurs.

Exemple d’avertissement : « Verr. Maj. est activé ce qui pourrait faire en sorte que vous entriez votre mot de passe incorrectement. »

## Information

Les notifications d’information servent à fournir des renseignements supplémentaires et des notes à l’utilisateur qu’elles peuvent trouver utiles selon le contexte.

Exemple d’information : « Vous pouvez changer votre mot de passe dans les paramètres. »

## Succès

Les notifications de succès sont utilisées pour confirmer qu’une tâche a été achevée avec succès.

Exemple de succès : « Votre mot de passe a été mis à jour avec succès. »

## Style de notifications

### Conception

Les notifications sont conçues avec le même concept de simplicité que celui des tableaux d’humeur. Il y a suffisamment de couleur dans les bannières pour fournir un effet visuel qui capte l’attention de l’utilisateur, sans submerger son champ de vision.

Les icônes de police de caractères sont extraordinaires et ont été choisies en raison de leur conception simple et de leur universalité.

Une ombre portée est utilisée pour montrer à l’utilisateur que la notification peut être fermée en cliquant sur le bouton « X ». L’ombre portée a un axe des X de 1px, un axe des Y de 1px et une opacité de 23 %.

### Couleurs

Les couleurs utilisées pour les notifications sont de la palette de conception du système.

Couleur hexadécimale pour les notifications d’erreur : no D3080C

Couleur hexadécimale pour les notifications d’avertissement : no FF9900

Couleur hexadécimale pour les notifications d’information : no 269ABC

Couleur hexadécimale pour les notifications de succès : no 278400

### Emplacement

Les notifications devraient être situées au haut de la page ou dans un endroit pratique et visible pour l’utilisateur.

### Police

La police de caractères utilisée pour les notifications est la police normalisée de conception du système Nunito sans régulier. Le titre de la notification est de couleur noire et de taille 16px. Le message de la notification est de couleur noire et de taille 14px. Les tailles de police ont été choisies pour leur grande visibilité et lisibilité facile. Toutefois, la taille de la police peut varier en fonction de la taille de l’affichage, de l’appareil utilisé ou de combien de temps dure le message de notification.

### Taille et remplissage

Les notifications sont de 62px par 425px. Le texte a un remplissage de 15px sur le dessus et en dessous, ainsi qu’un remplissage de 30px à partir de la gauche. Les coins sont arrondis à 2px. Les tailles de remplissage peuvent varier en fonction de la longueur du message. Le remplissage est utilisé pour rendre le texte plus prononcé afin de séparer le contenu du message de l’arrière-plan du contenu.

### Messages de notification

Les messages de notification devraient être simples et aussi courts que possible et devraient aussi utiliser des mots clés. Les messages longs peuvent être imprécis et peuvent avoir une incidence sur la taille et la lisibilité du message.

Exemple d’une notification claire : Votre photo de profil a été modifiée avec succès.

*Chronométrage*

Les notifications sont automatiquement chronométrées pour améliorer la fluidité du site Web. Le chronométrage des notifications est fondé sur l’estimation prudente d’une vitesse de lecture de 200 mots par minute.

Les courtes notifications (70 caractères ou moins) devraient avoir :
•	Une animation d’affichage de 0,4 seconde.
•	Une durée d’affichage de 3,5 secondes.
•	Une animation de masquage d’une (1) seconde.

Les longues notifications (de 70 à 140 caractères) devraient avoir :
•	Une animation d’affichage de 0,4 seconde.
•	Une durée d’affichage de sept (7) secondes.
•	Une animation de masquage de deux (2) secondes.

Si votre notification fait plus de 140 caractères, envisager une différente méthode de communiquer le message.
