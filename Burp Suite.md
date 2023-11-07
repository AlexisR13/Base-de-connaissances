```toc

```


# Overview
Fonctionnalités :
- **Proxy** : permet d'intercepter et de modifier les requêtes avant de les envoyer au serveur.
- **Repeater** : permet de répéter une requête, très pratique pour tatonner lors de l'exploitation d'une vulnérabilité (ex : SQLi).
- **Intruder** : permet d'automatiser le lancement d'un grand nombre de requêtes paramétrées sur une liste de valeur, très utile pour le brute force (la version gratuite limite à 1 requête / seconde).
- **Decoder** : permet d'encoder ou de décoder des données avant de les envoyer ou après les avoir reçu.
- **Comparer** : permet de comparer deux groupes de données.
- **Sequencer** : permet de détecter des patterns dans les tokens qui n'ont pas été générés aléatoirement.

Shortcut pour naviguer entre les onglets :
- Ctrl + Shift + D : dashboard
- Ctrl + Shift + T : target
- Ctrl + Shift + P : proxy
- Ctrl + Shift + I : intruder
- Ctrl + Shift + R : repeater

Pour commencer à utiliser Burp, il faut mettre en place le proxy : soit en lançant chromium depuis l'onglet proxy, soit en installant FoxyProxy sur Firefox et en redirigeant les requête vers Burp par exemple.

# Target tab
Dans l'onglet target, on retrouve 3 sous-onglets :
- *Sitemap* : représente l'ensemble des URL découvertes avec les requêtes et réponses associées.
- *Issue definitions* : liste les vulnérabilités que le scanneur de Burp peut identifier avec leur description et recommandation (le scanneur est utilisable seulement en version pro...).
- *Scope setting* : permet de délimiter le périmètre de test et permet d'afficher uniquement les URL dans le périmètre dans le sitemap par exemple.

