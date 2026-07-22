# Site web — Émaillage Pro

Un site web complet **en un seul fichier** (`index.html`). Aucune installation, aucun logiciel à apprendre. Tu l'ouvres, tu changes quelques textes, et tu le mets en ligne.

---

## 👀 1. Voir le site tout de suite

Double-clique sur le fichier **`index.html`**. Il s'ouvre dans ton navigateur (Chrome, Safari, Edge…). C'est déjà ça, ton site.

---

## ✏️ 2. Le personnaliser (les 5 choses importantes)

Ouvre `index.html` avec un éditeur de texte gratuit comme **[VS Code](https://code.visualstudio.com/)** (recommandé) ou même le Bloc-notes. Utilise **Rechercher/Remplacer** (Ctrl+H) pour changer :

| Cherche… | Remplace par… |
|---|---|
| `Émaillage Pro` | Le nom de ton entreprise |
| `(418) 000-0000` | Ton vrai numéro de téléphone |
| `+14180000000` | Ton numéro **sans espaces ni tirets**, avec le `1` devant (ex. `+15145551234`) — c'est ce qui fait fonctionner le bouton « Appeler » |
| `info@votredomaine.ca` | Ton adresse courriel |
| `Région de Québec` | Ta région / ta ville |

> 💡 Change une valeur à la fois, sauvegarde, et rafraîchis la page dans ton navigateur pour voir le résultat.

---

## 📸 3. Ajouter tes vraies photos avant/après

Les photos sont **le nerf de la guerre** pour ce métier. Mets tes photos dans le dossier `emaillage/`, puis dans le curseur du haut de page, remplace les blocs de couleur par tes images. Cherche `ba-after` et `ba-before` dans le fichier ; les instructions sont juste au-dessus, en commentaire.

Le plus simple : nomme tes photos `apres.jpg` et `avant.jpg`, place-les dans le dossier, et suis les commentaires `background:url('...')` déjà présents dans le code.

---

## 📬 4. Faire fonctionner le formulaire de contact

Par défaut, le formulaire n'envoie encore rien. Pour recevoir les demandes par courriel **gratuitement** :

1. Crée un compte sur **[formspree.io](https://formspree.io)** (gratuit).
2. Ils te donnent une adresse du genre `https://formspree.io/f/abcdwxyz`.
3. Dans `index.html`, cherche `VOTRE_ID` et remplace toute l'adresse `action="..."` par la tienne.

C'est tout — les demandes arriveront directement dans ta boîte courriel.

---

## 🌐 5. Mettre le site en ligne (gratuit)

La façon la plus facile, sans aucune compétence technique :

1. Va sur **[app.netlify.com/drop](https://app.netlify.com/drop)**
2. **Glisse le dossier `emaillage`** dans la fenêtre.
3. Ton site est en ligne en 30 secondes, avec une adresse gratuite.

Plus tard, tu pourras y brancher un vrai nom de domaine (ex. `emaillagepro.ca`) pour environ 15-20 $/an.

---

## 🔧 6. Le multi-surface te stresse ? Retire-le en 10 secondes

Le site met **l'émaillage de bains en vedette**. Le multi-surface est une section à part, clairement identifiée, que tu peux enlever quand tu veux :

1. Dans `index.html`, cherche `SECTION OPTIONNELLE`.
2. Supprime tout le bloc `<section id="multisurface" ...>` jusqu'à son `</section>`.
3. (Optionnel) enlève aussi la ligne `Multi-surfaces` dans le menu du bas de page.

Le reste du site continue de marcher parfaitement. Tu lances avec ce dont tu es sûr, et tu ajoutes le reste quand tu te sens prêt. 👍

---

## Structure du dossier

```
emaillage/
├── index.html   ← tout ton site est ici
└── README.md    ← ce guide
```
