# Présentation

Freenet est un réseau P2P (peer to peer) construit sur Internet. Il permet principalement le partage de fichiers en se focalisant sur l'anonymat de son auteur et la robustesse de son réseau.

Pour accéder au réseau l'utilisateur doit installer un [nœud](https://freenetproject.org/download.html). Il peut ensuite accéder à son nœud de différentes manières, la plus classique restant l'accès via un navigateur internet mais il est également possible de communiquer via l'API.

## Le réseau

### Structure

Chaque nœud est demandeur et producteur de contenu, puisque le réseau ne possède pas de points centraux le contenu du réseau est intégralement réparti sur les différends nœuds.

Pour récupérer un fichier un nœud doit donc en récupérer les morceaux un à un disséminer sur le réseau.

Pour permettre au réseau de bien fonctionner les nœuds s'échangent en permanence des morceaux de fichier.

C'est grâce à la bande passante et à l'espace disque, souvent appelé datastore, que chaque nœud met à disposition que Freenet peut fonctionner.

### Smallworld

### Résistant à la censure

L'un des avantages de Freenet et qui le rend plus résistant aux pannes que les autres darknets (voir état de l'art) est qu'un fichier est découpé puis disséminé sur le réseau. Pour censurer un fichier et donc le retirer du réseau il faut localiser chaque copie de chaque morceau le composant.

Pour supprimer manuellement un fichier il faudrait pouvoir localiser les morceaux et les retirer de tous les datastores du réseau, ce qui est impossible.

### Résistant aux spam

Certains plugins de communication fonctionnant sur le réseau utilisent le plugin `WebOfTrust` pour que chaque ajout de contenu se fasse sous une `Identity`, identité, à laquelle une confiance est associée.

## Les modes de connexion

### Opennet
tl;ld: On ne cache pas qu'on fait tourner un nœud mais on cache ce qu'on en fait

### Darknet