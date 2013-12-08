

Manuel Utilisateur : 

Tout d'abord, pour lancer le programme, il faut l'importer sur eclipse.
Un fois fait, ouvrir le dossier, aller dans le dossier src, puis Vue.
Avoir la classe VueMenuPrincipal ouvert, et lancer l'application.



La Connexion (il suffit d’entrer son ID) :
Il y a trois types de Connexion : 
Si vous êtes un membre du bureau, votre ID commence par M…..
Si vous êtes un Licencie, votre ID commence par L…..
Si vous êtes un Entraîneur, votre ID commence par E…..
     Test (pour la connexion) : 
     Nous avons créé différents types d’ID
     (E001, M001, L001)

Licencié : 
Lors de la connexion le licencié a deux choix :
Voir la liste des entraînements 
Pour s’inscrire à un entraînement il faut obligatoirement sélectionner une ligne sinon le bouton ne fait rien.
Voir ses propres entraînements inscrits
Bug : 
Dans la liste des entraînements, le licencié ne peut pas sélectionner la première ligne ni la supprimé ainsi que la dernière.
De plus le licencié peut s’inscrire deux fois dans le même entraînement.
Le nombre d’inscrit ne s’incrémente pas à chaque inscription….


Pourquoi ces bugs : 
On n’a pas réussi à manipuler une Base de données du coup tout marche avec des Vector List...
Entraîneur : 
L’entraîneur peut voir la liste des entraînements, ajouter un entraînement ou en supprimer.
L’ajout se passe bien, cependant la date est saisie manuellement du coup les erreurs de compréhensions et de frappes  peuvent être importantes.
Bugs
La vérification des saisies des entraînements n’est pas faite.
On ne peut pas supprimer la première et la dernière ligne de la liste.
Membre Bureau : 
L’ajout d’un entraîneur et d’un licencié se passe bien même si on ne peut pas avoir la liste de tous les membres du club (manque de temps).




Que manque-t-il ? : 
La liste des membres, la modification d’un membre, la suppression de membres...
Une base de données (Quand on relance l’application toutes  les données sont perdues).
Les bons points : 
Les membres ne peuvent  pas avoir le même numéro de licence.





