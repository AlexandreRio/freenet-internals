# Freenet

Ce livre a pour but de vulgariser le fonctionnement de Freenet. Freenet est un réseau de publication et récupération de documents anonyme.

Les thèmes abordés dans ce livre seront les suivants :
* Structure globale du réseau
* Comportement d'un nœud et communication entre les nœuds
* La `location` d'un nœud et son importance
* Explication du stockage des données sur un nœud (`storage` et `cache`)
* Fonctionnement du WebOfTrust et son API
* Que va changer le build purge-db4o
* État des lieux des différents plugins de communication type Freetalk, FMS, Frost, Sone etc
* Résumé et explication de l'article "Measuring Freenet in the Wild"
* Détail des URL sur Freenet et des systèmes de clés
* Explication des différents `core settings`

Et dans un second temps :
* Aborder la limite de l'anonymat, du point de vue technique avec par exemple les IPs en opennet et le DPI, des types d'attaques envisageables et du point de vue utilisateur, en gros un laïus sur du recoupement d'information postée
* Les limites des implémentations actuelles, principalement pour les plugins. Typiquement pourquoi WoT peut être si lent
* Tutoriel de développement de plugins simples

Ça devrait donner un bon aperçu du contenu que je pense mettre, si vous trouvez qu'il manque un point important dites-le moi et j'aviserais.

## À propos de ce livre

Je veux que ce livre explique le plus clairement possible le fonctionnement et le comportement de Freenet. De manière plus précise que la documentation officielle, en citant quand cela est possible le code source directement. 

Ce livre est disponible en [Français](http://alexandrerio.gitbooks.io/freenet-internals/content/fr/index.html), ma langue maternelle, mais également en [Anglais](http://alexandrerio.gitbooks.io/freenet-internals/content/en/index.html).

## À propos de l'auteur

Je m'appelle Alexandre Rio, je ne suis pas développeur de Freenet, juste utilisateur depuis plusieurs années.

Ne trouvant pas la documentation à mon gout et en ayant marre de chercher des informations sur différents médias (site, wiki, mailing list, IRC), j'ai décidé d'écrire ce livre.

Je n'ai pour le moment pas toutes les réponses à ces questions. Il s'agit principalement des questions auxquelles j'aimerais des réponses et des points indispensables à la compréhension de Freenet.

Toute remarque ou proposition est la bienvenue,

sur le clearnet
* par email sur `contact@alexrio.fr`,
* sur Twitter [@Rio_Alexandre](https://twitter.com/Rio_Alexandre)

ou mêne directement sur Freenet :
* par Freemail (bientôt)

## Licence

Je pense citer au maximum la documentation déjà existente, en particulier pour les schémas. Pour éviter tout contentieux je préfère attendre avant de choisir une licence. Elle sera tout de même le plus libre possible, surement une GPL.