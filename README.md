# springBoot-chat-App-Bassouat

## But du Projet:

Dans ce projet , je construis une application de chat avec SpringBoot et Websocket
où on peut communiquer et chatter avec les autres.il suffit de juste se connecter 
avec un username et commencer le chatte.

## Sujet principal abordé: Le Websocket protocol

En fait, lorsqu'un client ou un browser communique avec un serveur , il utilise le one-way communication
ce qui veut dire la communication dans un seul sens , le serveur ne renvoie pas la réponse directement au client,
il attend la requête (request) du client d'abord avant de lui envoyer la réponse,le serveur dépend donc du client.
Pour pallier ce problème, on utilise le WebSocket protocol, ce qui permet de rendre le serveur indépendant du client
ce qui veut dire qu'il n'a pas à attendre la requête du client avant de lui envoyer sa réponse(c'est le two-ways communication).

## Comment démarrer l'application?

Pour la démarrer il faut la lancer avec le "RUN SpringBootChatAppBassouatApplication" en cliquant droit sur l'application
principale qui est SpringBootChatAppBassouatApplication.java
en ensuite on la visionne sur le http://localhost:8080

## Comment l'utiliser?

Vu que c'est un chat , il faut donc utiliser au moins 2 fenêtres, une fenêtre principale sur google chrome où on l'ouvre sur http://localhost:8080
ensuite on lui donne un username et on se connecte et commence le chat.
Ensuite une deuxième fenêtre en ouvrant le "Guest browser" c'est à dire le navigateur invité, le lien ci dessous explique comment ouvrir le navigateur
invité sur Google chrome https://support.google.com/chrome/answer/6130773?hl=fr&co=GENIE.Platform%3DDesktop.

Sur ce "Guest Browser", on l'ouvre aussi à l'adresse http://localhost:8080 et on lui donne un username différent du premier.
Ensuite, on observe l'application fonctionner.

### Commentaires et remarques:

Si vous avez des commentaires et remarques à me faire svp, n'hésitez pas à m'écrire svp à l'adresse mail:bassouat8@gmail.com





