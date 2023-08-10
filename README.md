# management_student

Le DG de ESIS vous demande de lui faire une application de gestion des
étudiants. ESIS cherche à savoir pour chaque étudiant le nom, le post-nom, le
prénom, l’âge et le nom du tuteur. L’application doit aider à enregistrer,
modifier et afficher les noms des étudiants de la base de données(fichier).

A l’exécution du projet, un menu simple apparaît permettant à un utilisateur de
choisir l’une des opérations suivantes:

#1. Enregistrement

   Lors de l’enregistrement d’un étudiant, un matricule de 6 caractères
est généré automatiquement en fusionnant les deux premiers
caractères du nom, les 2 derniers caractères de son post-nom et son
âge. Si l’étudiant a comme nom: KAZADI,
post-nom: KONGOLO et âge:25 ; son matricule sera KALO25

   Les informations de l’étudiant (matricule y compris) et celle de son
tuteur sont ajoutées à la base des données (ici un fichier data.txt)
sous forme d’une ligne.
  
   L’application peut demander de saisir les informations de plusieurs
étudiants en même temps avant de les ajouter au fichier des données
(on n’écrase pas les anciennes données du fichier)

#3. Affichage des données
   Afficher le contenu du fichier des données data.txt en triant sur base
du nom.

#4. Rechercher et modifier un étudiant:
Le système doit permettre de rechercher un étudiant déjà enregistré sur
base de son matricule. Il doit également donner la possibilité de modifier
le prénom.

#5. Quitter l’application
