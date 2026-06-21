# L'infini en mathématiques — cours en vidéo

Un cours en **trois semaines** sur la notion d'infini, de la classe de Seconde jusqu'aux frontières de la recherche. Chaque semaine est une **vidéo commentée** (diapositives + narration en voix off) accompagnée de **deux quiz**.

## Contenu

| Fichier | Semaine | Jours | Diapos | Quiz |
|---|---|---|---|---|
| `index.html` | **Menu d'accueil** | — | — | — |
| `partie-1.html` | I · L'infini apprivoisé | Jours 1 – 5 | 20 | `quiz-s1a` (J1–3), `quiz-s1b` (J4–5) |
| `partie-2.html` | II · La rigueur | Jours 6 – 10 | 19 | `quiz-s2a` (J6–8), `quiz-s2b` (J9–10) |
| `partie-3.html` | III · Les tailles de l'infini | Jours 11 – 15 | 20 | `quiz-s3a` (J11–13), `quiz-s3b` (J14–15) |

**56 scènes** et **6 quiz** (60 questions). Une partie = une semaine. Les semaines 4 et 5 seront ajoutées plus tard.

Les passages historiques sont illustrés par les portraits de mathématiciens (Zénon, Aristote, Pythagore, Apollonius, Fibonacci, d'Alembert, Cauchy, Dedekind, Dirichlet, Riemann, Galilée, Euclide, Hilbert, Cantor, Kronecker) ; le reste par des équations et des schémas tracés fidèlement (asymptotes, série de Zénon, couloir ε, trou de ℚ, série harmonique alternée, Hôtel de Hilbert, serpent de Cantor, argument diagonal, ensemble des parties).

## Utilisation

Chaque fichier est **autonome** : les visuels et les portraits sont intégrés directement dans le HTML (base64, aucun fichier image séparé). Aucune dépendance à installer.

- Ouvrir `index.html`, choisir une semaine, ou lancer directement un quiz.
- **Lecture** lance la narration en voix off ; l'enchaînement se fait automatiquement après une courte pause entre les diapositives.
- Boutons **Précédent / Pause / Suivant**, ou au clavier : `←` `→` pour naviguer, `Espace` pour lecture/pause.
- Bouton **✎ Quiz** et bouton **⌂ Menu** en haut à droite de chaque vidéo.
- La dernière diapositive vue est mémorisée ; barre de progression et pastilles permettent de se repérer.

### La voix off

La narration est **entièrement rédigée et verbalisée** : les symboles (∞, fractions, S(n), ℵ₀, √2…) sont énoncés en toutes lettres, pour que la synthèse vocale ne les lise pas de travers. Le lecteur **classe automatiquement les voix françaises disponibles** et écarte les voix « compact / eSpeak » de mauvaise qualité ; un **sélecteur de voix** (en haut à droite) permet de changer manuellement, choix mémorisé. Pour le meilleur rendu : Chrome (voix « Google français ») ou Safari/macOS (voix « Thomas »). La lecture audio démarre après un clic sur **Lecture** (politique des navigateurs).

## Quiz

Chaque semaine propose **deux quiz** (≈ un tous les 2–3 jours), accessibles depuis le menu ou le bouton **✎ Quiz** du lecteur.

- 10 questions à choix multiple, avec **correction et explication immédiates**.
- Les bonnes réponses sont **réparties aléatoirement** (positions imprévisibles, distribution équilibrée).
- Score final, message personnalisé et récapitulatif question par question.
- L'élève saisit son nom ; le bouton **✉ Envoyer mes résultats** ouvre un e-mail pré-rempli (score + détail) vers le professeur (`renaudfabbri@gmail.com`).

## Mise en ligne (GitHub Pages)

1. Déposer tous les fichiers (`index.html`, les `partie-*.html` et les `quiz-*.html`) à la racine du dépôt, en conservant les noms — les liens sont relatifs.
2. Dépôt → **Settings → Pages** → *Deploy from a branch* → branche `main`, dossier `/ (root)`.
3. La page sera disponible à `https://<utilisateur>.github.io/<dépôt>/`.

## Crédits

Conçu à partir du programme « L'infini en mathématiques » (5 semaines) et du matériel détaillé de la Semaine 3 (Cantor : du réarrangement de Riemann aux cardinaux transfinis).
