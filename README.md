# Site web — Prospray

Site vitrine + outil de soumission pour un service de **réémaillage de baignoires** dans le **KRTB** (Rivière-du-Loup, Montmagny, La Pocatière, Saint-Alexandre, Kamouraska) et le corridor de l'autoroute 20.

Tout tient dans **un seul fichier** (`index.html`) — aucune installation, aucun logiciel à apprendre.

## Fichiers

```
index.html   ← tout le site (services, tarifs, formulaire, etc.)
merci.html   ← page affichée après l'envoi du formulaire
README.md    ← ce guide
```

---

## 👀 1. Voir le site

Double-clique sur **`index.html`** : il s'ouvre dans ton navigateur.
> Note : le formulaire n'envoie rien tant que le site n'est pas hébergé sur Netlify (voir §4).

---

## ✏️ 2. Personnaliser (Rechercher/Remplacer dans `index.html` et `merci.html`)

| Cherche… | Remplace par… |
|---|---|
| `Prospray` | Le nom de ton entreprise (si différent) |
| `(418) 000-0000` | Ton vrai numéro |
| `+14180000000` | Ton numéro sans espaces, avec le `1` devant (ex. `+15815551234`) — fait fonctionner le bouton « Appeler » |
| `info@prospray.ca` | Ton courriel |
| `prospray.ca` | Ton nom de domaine (si tu en prends un) |

---

## 📸 3. Ajouter tes vraies photos avant/après

Ce sont elles qui vendent. Dépose tes images dans ce dossier, puis dans le curseur du haut et la galerie « Réalisations », remplace les blocs de couleur par tes photos (cherche `ba-after` / `ba-before` ; instructions en commentaire dans le code).

---

## 📬 4. Le formulaire avec téléversement de photos → héberge sur **Netlify** (gratuit)

Le formulaire de soumission **exige des photos** (essentiel pour détecter un ancien émaillage et donner le bon prix). Un site statique seul ne peut pas recevoir de fichiers — mais **Netlify Forms** le fait **gratuitement** (jusqu'à 100 soumissions/mois), photos incluses. Le code est déjà configuré pour ça.

**Mettre en ligne :**
1. Va sur **[app.netlify.com/drop](https://app.netlify.com/drop)** (crée un compte gratuit).
2. **Glisse ce dossier complet** dans la fenêtre.
3. Ton site est en ligne en ~30 secondes, à une adresse gratuite `xxxxx.netlify.app`.

**Recevoir les demandes par courriel :**
- Dans Netlify : **Forms → Notifications → Add notification → Email**, et mets ton courriel.
- Chaque soumission (avec les photos) apparaît aussi dans **Forms** sur ton tableau de bord Netlify.

> ⚠️ GitHub Pages n'accepte PAS les envois de fichiers. Pour la photo obligatoire, **utilise Netlify** (ou un service équivalent). Plus tard tu pourras brancher un vrai domaine (ex. `prospray.ca`, ~15-20 $/an).

---

## 📍 5. Être trouvé sur Google dans le KRTB (SEO local)

Le site est déjà optimisé côté contenu : titres, textes et données structurées ciblent Rivière-du-Loup, Montmagny, etc. Pour apparaître dans **la carte Google** (le « pack local »), il te faut en plus une **fiche Google Business Profile** :

- Crée-la sur **[business.google.com](https://business.google.com)**.
- Choisis le type **« entreprise de service à domicile »** : tu peux **cacher ton adresse** et lister tes **zones desservies** (RDL, Montmagny, La Pocatière…).
- ⚠️ **N'invente jamais une fausse adresse** dans une ville où tu n'es pas : c'est contre les règles de Google et ta fiche peut être bannie.

---

## 🔧 6. Ajuster le contenu

- **Prix** : cherche `625 $` / `795 $`. Pour cacher les prix, remplace la section `id="tarifs"` par « Sur soumission ».
- **Multi-surface** : c'est un service secondaire (3e carte des Services). Retire la carte si tu ne l'offres pas encore.
- **Villes** : ajoute/enlève des municipalités dans le bandeau `id="zones"` et dans le menu déroulant du formulaire.
