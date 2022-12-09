  ********** lien vers la page github : ***********
=============================================================
=============================================================

https://senga200.github.io/GameOn-website-AGNES/starterOnly/

=============================================================

GAME ON : Le contexte du projet

GameOn est une entreprise spécialisée dans les conférences et les concours de jeux.
Le contexte : Le site a simplifié sa page d'accueil et l'inscription aux concours après avoir reçu des commentaires négatifs de la part de certains utilisateurs.
	La maquette est fournie, et le HTML et CSS également. Les premières lignes Javascript sont également présentes qui permettent de lancer le formulaire. Un repository est disponible sur Github. 
  Il faut donc :
travailler sur un repo GitHub forké ;
utiliser des fichiers séparés pour le HTML, le CSS et le JavaScript ;
toujours commenter le code ;
tester manuellement les fonctionnalités, les entrées de formulaire et l'affichage responsive.

Les issues sont les suuivantes : 
- fermer la modale #1 
=> Ajouter la fonctionnalité au bouton (x)

- Implémenter entrées du formulaire #2 
=> (1) Lier les labels aux entrées dans le HTML en utilisant les attributs "for" et "id" dans le code existant. Corriger le code HTML quand nécessaire.
(2) Utiliser du JavaScript pur (pas de jQuery) pour terminer le formulaire :
Le formulaire doit être valide quand l'utilisateur clique sur "Submit"
Les données doivent être saisies correctement :
(1) Le champ Prénom a un minimum de 2 caractères / n'est pas vide.
(2) Le champ du nom de famille a un minimum de 2 caractères / n'est pas vide.
(3) L'adresse électronique est valide.
(4) Pour le nombre de concours, une valeur numérique est saisie.
(5) Un bouton radio est sélectionné.
(6) La case des conditions générales est cochée, l'autre case est facultative / peut être laissée décochée.
Conserver les données du formulaire (ne pas effacer le formulaire) lorsqu'il ne passe pas la validation.

- Ajouter validation ou messages d'erreur #3
=> Des messages d'erreur spécifiques doivent apparaître sous l'entrée qui n'est pas correcte. Les messages d'erreur doivent s'afficher sous le champ de saisie associé. Exemples :
"Veuillez entrer 2 caractères ou plus pour le champ du nom."
"Vous devez choisir une option."
"Vous devez vérifier que vous acceptez les termes et conditions."
"Vous devez entrer votre date de naissance."

- Ajouter confirmation quand envoi réussi #4
=> Après une validation réussie, inclure un message de confirmation de la soumission réussie pour l'utilisateur (ex. "Merci ! Votre réservation a été reçue.")

- Tests manuels #5
=> Visualiser et tester l'interface utilisateur dans les dernières versions de Chrome et de Firefox, ainsi que dans les versions mobile et desktop. Corriger les erreurs d'affichage existantes.
Tester toutes les fonctionnalités des boutons et des entrées de formulaire (tester les valeurs correctes et incorrectes)
