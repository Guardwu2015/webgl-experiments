# webgl-experiments
Werkende demo op:
https://webgl-experiment.herokuapp.com/

## CODE
- WebGL with Three.js
- Socketing with socket.io
- QR code scannen

## QR Codes
Gebruikte technologie: qrcode-generator van kazuhikoarase (https://kazuhikoarase.github.io/qrcode-generator/)

QR codes zijn op UX gebied niet de beste keuze omdat niet iedere gebruiker een qrcode scanner op zijn gsm heeft staan. Omdat dit project een experiment is en niet klantgericht heb ik toch voor QR codes gekozen. Indien iemand een betere oplossing hiervoor weet mag u dit altijd laten weten.

## Project
Een 3D vorm staat op het scherm en de beweging ervan is afhankelijk van de positie van een smartphone.
De index.html draait op een vast scherm, er is een QR code aanwezig die wordt gescant door een smartphone en deze verbind dan met de controller.html en dan wordt de gyroscoop data van de smartphone gebruikt om de vorm te laten bewegen.

## Package.JSON
Er zitten nog geen linters in dit project omdat dit begonnen is vanuit een klein experiment waarvoor dit overkill zou zijn, deze zouden best nog toegevoegd worden.

## Commits
De laatste commits zijn allemaal voorzien van een emoji, de betekennisen hiervan zijn te bekijken op https://gitmoji.carloscuesta.me/.

## Leap motion
Er is support voor de Leap Motion, dit moet handmatig worden aangezet in de script.js als je beschikt over een Leap Motion.
