# Schemelec

Éditeur de schémas électrotechniques installable comme application web progressive (PWA).

## Contacts de boutons-poussoirs et d'arrêts d'urgence

Ajoutez un contact NO ou NC depuis la palette, puis sélectionnez dans ses
propriétés le bouton-poussoir ou l'arrêt d'urgence associé dans la liste
« Appareil commandé ». Le type de contact est déduit de l'appareil choisi.
Le contact suit l'actionnement de cet organe en simulation : le bouton-poussoir
revient au repos lorsqu'il est relâché, tandis que l'arrêt d'urgence reste
enfoncé jusqu'à son déverrouillage.

La liste propose aussi les autres appareils compatibles. Un relais temporisé
sélectionné commande un contact temporisé. Les anciens contacts instantanés
associés à un relais temporisé conservent leur fonctionnement tant que leur
association n'est pas modifiée. Les repères en double doivent être rendus
uniques avant de pouvoir les sélectionner.
