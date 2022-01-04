## Spring Boot Maven
Dans ce readme nous allons voir un petit guide de Maven.

### Qu'est-ce que Maven ?
---
**(Apache Maven)**[https://maven.apache.org/] est un outil d'automatisation de build pour les projets Java.
Si vous avez déjà eu à créer un projet Java avec des dépendances ou des exigences de construction spéciales, 
vous avez probablement traversé les frustrations que Maven vise à éliminer.

### Pourquoi Maven est-il utile ?
---
Maven est un projet open source sous Apache depuis 2003. Compte tenu de son soutien solide et de son immense popularité, 
Maven est très stable et riche en fonctionnalités, fournissant de nombreux plugins qui peuvent tout faire.
Maven est un outil permettant d'automatiser la gestion de projets Java. Il offre les fonctionalités suivantes :
* Gérer les dépendances
* Lancer la compilation des sources
* Lancer les Test Unitaires
* Générer les packages (jar, war, ear)
* Installer les packages dans le repository
* Déployer l’application dans le serveur
* Générer la documentation du projet

Maven se connecte à des référentiels distants (ou vous pouvez configurer vos propres référentiels locaux) 
et télécharge automatiquement toutes les dépendances nécessaires à la création de votre projet.

### Comment utilisez-vous Maven ?
---
L'utilisation de Maven est extrêmement simple, une fois que vous avez appris quelques-uns des principaux concepts. 
Chaque projet contient un fichier appelé POM ( Project Object Model )[https://en.wikipedia.org/wiki/Apache_Maven#Project_Object_Model], 
qui n'est qu'un fichier XML contenant les détails du projet. Certains de ces détails peuvent inclure le nom du projet, 
la version, le type de package, les dépendances, les plugins Maven, etc.
<br/>
Pour exécuter réellement Maven, il vous suffit de naviguer jusqu'au dossier du projet et d'exécuter :
```
$ mvn [command]
```
La commande peut être un certain nombre de choses, mais pour n'en nommer que quelques-unes :
* `test` : Exécute tous les tests du projet
* `clean`: Supprime tous les anciens fichiers de construction
* `package` : Emballez le projet dans un fichier jar (ou dans un autre format selon ce qui a été spécifié)
* `install` : Place le projet dans le référentiel Maven local
* `deploy` : Place le projet dans le référentiel Maven distant

Maven est un sujet énorme, et cette brève introduction était uniquement destinée à vous donner une idée de ce que fait Maven, 
alors assurez-vous de consulter les ressources officiel pour plus d'informations sur la façon de l'utiliser réellement.
<br/>
**Ressources** : 
* http://maven.apache.org/
* http://en.wikipedia.org/wiki/Apache_Maven
* http://docs.codehaus.org/display/MAVENUSER/The+Maven+2+tutorial