# Openclassrooms - Projet 10 : Learn@Home

-   [Maquette](https://www.figma.com/file/HSalmufThELKErfAZrw35N/Learn%40Home?type=design&node-id=0%3A1&t=M8t2obJkDaZ1dWxx-1)
-   [Diagrammes de cas d'usage](https://github.com/floriansimunek/OC-P10/blob/master/Diagrammes%20de%20cas%20d%E2%80%99usage.pdf)
-   [Kanban](https://github.com/users/floriansimunek/projects/4)

## User Stories

### Connexion / Inscription

1. Je suis étudiant ou tuteur et je souhaite me connecter ou m’inscrire sur Learn@home

-   J’arrive sur un formulaire de connexion, je peux rentrer mes identifiants pour me connecter, ou cliquer sur « Inscription » pour accéder au formulaire d’inscription
-   J’arrive sur un formulaire d’inscription et je peux m’inscrire en tant qu’étudiant ou tuteur en renseignant une adresse mail, mot de passe et nom d’utilisateur

2. Je suis étudiant ou tuteur et je souhaite m’inscrire sur Learn@Home

-   Je renseigne mes informations (nom d’utilisateur, adresse mail, mot de passe)
-   Je clique sur « Je m’inscris » et le formulaire est vérifié, on vérifie que l’adresse mail n’existe pas en BDD, qu’elle est valide, la même chose pour le nom d’utilisateur, pour les mots de passes on vérifie qu’ils sont tous les 2 correspond et qu’ils sont au format valide (1maj, 1min, 8 caractères min, 1 caractère spécial)
-   Si le formulaire est bien rempli alors je suis inscrit et redirigé vers le tableau de bord
-   Si le formulaire est mal rempli alors je reste sur la page et on m’indique les erreurs que je dois corriger

3. Je suis étudiant ou tuteur et je souhaite me connecter sur Learn@Home

-   Je renseigne mes informations (adresse mail, mot de passe)
-   Si le formulaire est bien rempli, alors je suis redirigé vers le tableau de bord
-   Si le formulaire est mal rempli, je reste sur la page et on m’indique les erreurs que je dois corriger (mauvais mail ou mot de passe)

4. Je suis étudiant ou tuteur et j’ai oublié mon mot de passe

-   Je clique sur « mot de passe oublié » sur le formulaire de connexion ou d’inscription
-   Je renseigne mon adresse mail, si l’adresse mail existe en BDD alors je reçois un email pour réinitialiser mon mot de passe
-   Je reçois un email pour réinitialiser mon mot de passe
-   Je renseigne mon nouveau mot de passe et je suis redirigé vers le formulaire de connexion

### Tableau de bord

1. Je suis connecté en tant qu’étudiant ou tuteur

-   Je peux retrouver toutes les informations de ma semaine
-   Je peux voir le nombre de messages non-lus que j’ai
-   Je peux voir les rendez-vous de ma semaine (calendrier)
-   Je peux voir mes tâches à faire dans la semaine (todo list)
-   Je peux naviguer sur les autres pages grâce aux boutons dans les sections calendrier, todolist, messages non-lus ou par le menu

### Todo list

1. Je suis connecté en tant qu’étudiant ou tuteur et je suis sur la page de Todo List

-   Je peux voir ma liste de tâches (trier par date)
-   Je peux ajouter des tâches (Nom, date, participants, description)

### Tchat

1. Je suis connecté en tant qu’étudiant ou tuteur et je suis sur la page de Messages

-   Je peux voir la liste de mes contacts récents sur la gauche
-   Je peux voir si j’ai des messages non-lus (pastilles etc...)
-   Si je clique sur mon contact, le tchat s’ouvre et je peux voir et/ou envoyer des messages
-   Je peux aussi créer de nouvelles conversations avec de nouveaux contacts

### Calendrier

1. Je suis connecté en tant qu’étudiant ou tuteur et je suis sur la page Calendrier

-   Je peux voir mes tâches à faire et mes futurs rendez-vous (avec tuteur ou élève)
-   Je peux ajouter une nouvelle tâche directement sur le Calendrier (RDV ou ToDo)

### TEST

<table>
  <tr>
    <th>id</th>
    <th>As a [type of user]</th>
    <th>I want to [perform some task]</th>
    <th>so that i can [achieve some goal]</th>
  </tr>

  <tr>
    <td><code>12</code></td>
    <td>toto</td>
    <td>Ceci est un <br> exemple de retour à la ligne</td>
  </tr>
  <tr>
    <td><code>13</code></td>
    <td>tata</td>
    <td>
      On peut aussi mettre des listes :
      <ul>
        <li>C'est</li>
        <li>Vraiment</li>
        <li><strong>Cool</strong></li>
      </ul>
    </td>
  </tr>
  <tr>
    
  </tr>
</table>
