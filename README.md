# L'infini en mathématiques — cours en vidéo

Un cours en quatre parties sur la notion d'infini, de la classe de Seconde jusqu'aux frontières de la recherche. Chaque partie est une **vidéo commentée** qui se lit dans le navigateur : diapositives, narration en voix off automatique et schémas mathématiques tracés fidèlement.

## Contenu

| Fichier | Partie | Jours | Diapos | Quiz |
|---|---|---|---|---|
| `index.html` | **Menu d'accueil** — vidéos + quiz | — | — | — |
| `partie-1.html` · `quiz-1.html` | I · L'infini apprivoisé | Jours 1 – 3 | 12 | 10 questions |
| `partie-2.html` · `quiz-2.html` | II · Frôler sans atteindre | Jours 4 – 5 | 9 | 10 questions |
| `partie-3.html` · `quiz-3.html` | III · La rigueur | Jours 6 – 8 | 12 | 10 questions |
| `partie-4.html` · `quiz-4.html` | IV · Construire le continu, compter l'infini | Jour 9 & Cantor | 7 | 10 questions |

Soit **36 scènes** et **40 questions** réparties en 4 parties. Les passages historiques sont illustrés par les portraits de mathématiciens (Zénon, Aristote, Pythagore, Apollonius, Fibonacci, d'Alembert, Cauchy, Dedekind, Cantor) ; le reste par des équations et des schémas correspondant strictement au cours. La **narration est entièrement rédigée et détaillée**, et lue par une voix soigneusement sélectionnée (les symboles comme ∞, 1/2 ou S(n) sont énoncés en toutes lettres).

## Utilisation

Chaque fichier est **autonome** : les visuels et les portraits sont intégrés directement dans le HTML (aucun fichier image séparé). Il n'y a aucune dépendance à installer.

- Ouvrir `index.html`, puis choisir une partie.
- **Lecture** lance la narration en voix off ; la lecture s'enchaîne automatiquement après une courte pause entre chaque diapositive.
- Boutons **Précédent / Pause / Suivant**, ou au clavier : `←` `→` pour naviguer, `Espace` pour lecture/pause.
- Bouton **⌂ Menu** (en haut à droite) pour revenir à l'accueil à tout moment.
- La dernière diapositive vue est mémorisée ; la barre de progression et les pastilles permettent de se repérer et de sauter directement à une diapositive.

- Un **sélecteur de voix** (en haut à droite) permet de choisir la voix française préférée ; le choix est mémorisé.

> La voix off utilise la synthèse vocale du navigateur (voix française). Le lecteur classe automatiquement les voix disponibles et écarte les voix « compact / eSpeak » de mauvaise qualité. La disponibilité dépend du système : pour le meilleur rendu, Chrome (voix « Google français ») ou Safari/macOS (voix « Thomas ») sont recommandés. La lecture audio démarre après un clic sur **Lecture** (politique des navigateurs).

## Quiz

Chaque partie a son quiz (`quiz-N.html`), accessible depuis le menu ou depuis le bouton **✎ Quiz** dans le lecteur vidéo.

- 10 questions à choix multiple, avec **correction et explication immédiates**.
- Score final, message personnalisé et récapitulatif question par question.
- L'élève saisit son nom ; le bouton **✉ Envoyer mes résultats** ouvre un e-mail pré-rempli (score + détail) à destination du professeur (`renaudfabbri@gmail.com`).

## Mise en ligne (GitHub Pages)

1. Déposer tous les fichiers (`index.html`, les `partie-*.html` et les `quiz-*.html`) à la racine du dépôt — en conservant les noms, car les liens entre le menu, les parties et les quiz sont relatifs.
2. Dépôt → **Settings → Pages** → *Build and deployment* → *Source : Deploy from a branch* → branche `main`, dossier `/ (root)`.
3. La page sera disponible à l'adresse `https://<utilisateur>.github.io/<dépôt>/`.

## Crédits

Conçu à partir du cours « L'infini en mathématiques » (synthèses Jours 1 à 8, zoom sur la résolution du paradoxe de Zénon, coupures de Dedekind et tailles d'infini de Cantor).
