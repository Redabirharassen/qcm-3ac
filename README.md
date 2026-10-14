# QCM 3AC

QCM de physique-chimie pour la 3ème année du collège (programme marocain) : 17 leçons, entraînement avec correction, quiz notés sur 10 et espace professeur.

Adresse du site une fois publié : **https://redabirharassen.github.io/qcm-3ac/**

## Contenu du dépôt

| Fichier | Rôle |
|---|---|
| `index.html` | L'application complète (questions, quiz, espace professeur) |
| `confidentialite.html` | Politique de confidentialité |
| `.nojekyll` | Indique à GitHub de publier les fichiers tels quels |
| `README.md` | Ce guide |

## Mise en ligne sur GitHub Pages

1. Connecte-toi sur github.com avec le compte **Redabirharassen**.
2. Clique sur **+** en haut à droite, puis **New repository**.
3. Nom du dépôt : `qcm-3ac` (exactement, en minuscules). Choisis **Public**, puis **Create repository**.
4. Clique sur **uploading an existing file**, glisse les 4 fichiers (dont `.nojekyll`), puis **Commit changes**.
   - Si `.nojekyll` n'apparaît pas sur ton ordinateur (fichier caché), clique **Add file → Create new file**, nomme-le `.nojekyll`, laisse-le vide et valide.
5. Va dans **Settings → Pages**. Sous *Source*, choisis **Deploy from a branch**, branche **main**, dossier **/ (root)**, puis **Save**.
6. Attends 1 à 2 minutes et ouvre https://redabirharassen.github.io/qcm-3ac/

## Utilisation en classe

- Le professeur ouvre l'**Espace professeur**, crée son compte avec le code d'établissement, choisit les leçons et obtient un code de quiz (ex. `3AC-ABD`) et un lien à donner aux élèves.
- Les notes arrivent dans la même feuille Google Sheets « Labo QCM - Notes » que Labo QCM. Les quiz de ce site se reconnaissent à leur code qui commence par `3AC`.

## Mettre à jour

Pour modifier les questions, remplace `index.html` dans le dépôt (**Add file → Upload files**) et valide. Le site se met à jour en une minute environ.
