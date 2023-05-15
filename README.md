# Openclassrooms - Projet 10 : Learn@Home

-   [Maquette](https://www.figma.com/file/HSalmufThELKErfAZrw35N/Learn%40Home?type=design&node-id=0%3A1&t=M8t2obJkDaZ1dWxx-1)
-   [Diagrammes de cas d'usage](https://github.com/floriansimunek/OC-P10/blob/master/Diagrammes%20de%20cas%20d%E2%80%99usage.pdf)
-   [Kanban](https://github.com/users/floriansimunek/projects/4)

## User Stories

<table>
  <tr>
    <th>id</th>
    <th>As a [type of user]</th>
    <th>I want to [perform some task]</th>
    <th>so that i can [achieve some goal]</th>
  </tr>

  <tr>
    <td><code>1</code></td>
    <td>Étudiant ou Tuteur</td>
    <td>Je souhaite me connecter ou m’inscrire sur Learn@home</td>
	<td>
		<ul>
			<li>J’arrive sur un formulaire de connexion, je peux rentrer mes identifiants pour me connecter, ou cliquer sur « Inscription » pour accéder au formulaire d’inscription</li>
			<li>J’arrive sur un formulaire d’inscription et je peux m’inscrire en tant qu’étudiant ou tuteur en renseignant une adresse mail, mot de passe et nom d’utilisateur</li>
		</ul>
	</td>
  </tr>
  <tr>
    <td><code>2</code></td>
    <td>Étudiant ou Tuteur</td>
    <td>Je souhaite m’inscrire sur Learn@Home</td>
	<td>
		<ul>
			<li>Je renseigne mes informations (nom d’utilisateur, adresse mail, mot de passe)</li>
			<li>Je clique sur « Je m’inscris » et le formulaire est vérifié, on vérifie que l’adresse mail n’existe pas en BDD, qu’elle est valide, la même chose pour le nom d’utilisateur, pour les mots de passes on vérifie qu’ils sont tous les 2 correspond et qu’ils sont au format valide (1maj, 1min, 8 caractères min, 1 caractère spécial)</li>
			<li>Si le formulaire est bien rempli alors je suis inscrit et redirigé vers le tableau de bord</li>
			<li>Si le formulaire est mal rempli alors je reste sur la page et on m’indique les erreurs que je dois corriger</li>
		</ul>
	</td>
  </tr>
  <tr>
    <td><code>3</code></td>
    <td>Étudiant ou Tuteur</td>
    <td>Je souhaite me connecter sur Learn@Home</td>
	<td>
		<ul>
			<li>Je renseigne mes informations (adresse mail, mot de passe)</li>
			<li>Si le formulaire est bien rempli, alors je suis redirigé vers le tableau de bord</li>
			<li>Si le formulaire est mal rempli, je reste sur la page et on m’indique les erreurs que je dois corriger (mauvais mail ou mot de passe)</li>
		</ul>
	</td>
  </tr>
  <tr>
    <td><code>4</code></td>
    <td>Étudiant ou Tuteur</td>
    <td>J’ai oublié mon mot de passe</td>
	<td>
		<ul>
			<li>Je clique sur « mot de passe oublié » sur le formulaire de connexion ou d’inscription</li>
			<li>Je renseigne mon adresse mail, si l’adresse mail existe en BDD alors je reçois un email pour réinitialiser mon mot de passe</li>
			<li>Je reçois un email pour réinitialiser mon mot de passe</li>
			<li>Je renseigne mon nouveau mot de passe et je suis redirigé vers le formulaire de connexion</li>
		</ul>
	</td>
  </tr>
  <tr>
    <td><code>5</code></td>
    <td>Étudiant ou Tuteur</td>
    <td>Je suis connecté sur la page <code>Tableau de bord</code></td>
	<td>
		<ul>
			<li>Je peux retrouver toutes les informations de ma semaine</li>
			<li>Je peux voir le nombre de messages non-lus que j’ai</li>
			<li>Je peux voir les rendez-vous de ma semaine (calendrier)</li>
			<li>Je peux voir mes tâches à faire dans la semaine (todo list)</li>
			<li>Je peux naviguer sur les autres pages grâce aux boutons dans les sections calendrier, todolist, messages non-lus ou par le menu</li>
		</ul>
	</td>
  </tr>
  <tr>
    <td><code>6</code></td>
    <td>Étudiant ou Tuteur</td>
    <td>Je suis connecté sur la page <code>Todo List</code></td>
	<td>
		<ul>
			<li>Je peux voir ma liste de tâches (trier par date)</li>
			<li>Je peux ajouter des tâches (Nom, date, participants, description)</li>
		</ul>
	</td>
  </tr>
    <tr>
    <td><code>7</code></td>
    <td>Étudiant ou Tuteur</td>
    <td>Je suis connecté sur la page <code>Messages</code></td>
	<td>
		<ul>
			<li>Je peux voir la liste de mes contacts récents sur la gauche</li>
			<li>Je peux voir si j’ai des messages non-lus (pastilles etc...)</li>
			<li>Si je clique sur mon contact, le tchat s’ouvre et je peux voir et/ou envoyer des messages</li>
			<li>Je peux aussi créer de nouvelles conversations avec de nouveaux contacts</li>
		</ul>
	</td>
  </tr>
  <tr>
    <td><code>8</code></td>
    <td>Étudiant ou Tuteur</td>
    <td>Je suis connecté sur la page <code>Calendrier</code></td>
	<td>
		<ul>
			<li>Je peux voir mes tâches à faire et mes futurs rendez-vous (avec tuteur ou élève)</li>
			<li>Je peux ajouter une nouvelle tâche directement sur le Calendrier (RDV ou ToDo)</li>
		</ul>
	</td>
  </tr>
</table>
