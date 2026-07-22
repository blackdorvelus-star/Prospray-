# Site web — NéoSpray

Site vitrine + outil de soumission pour un service de **réémaillage de baignoires**, de **Bellechasse à Rivière-du-Loup** (et tous les environs de Rivière-du-Loup), le long du corridor de l'autoroute 20. Plus loin que Rivière-du-Loup : sur demande, pour les projets de plus grande envergure.

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
> Note : le formulaire envoie les demandes par courriel une fois le site en ligne et FormSubmit activé (voir §4).

---

## ✏️ 2. Personnaliser (Rechercher/Remplacer dans `index.html` et `merci.html`)

Les coordonnées sont **déjà remplies**. Voici les valeurs en place, si tu dois les changer un jour :

| Cherche… (valeur actuelle) | C'est… |
|---|---|
| `NéoSpray` | Le nom de l'entreprise |
| `(581) 922-0377` | Le numéro affiché sur le site |
| `+15819220377` | Le numéro du bouton « Appeler » (sans espaces, avec le `1` devant) |
| `infoneospray@gmail.com` | Le courriel qui reçoit les demandes |
| `prospray-rdl.netlify.app` | L'adresse actuelle du site (lien canonique + données SEO) — à remplacer si tu prends un vrai domaine |

---

## 📸 3. Ajouter tes vraies photos avant/après

Ce sont elles qui vendent. Dépose tes images dans ce dossier, puis dans le curseur du haut et la galerie « Réalisations », remplace les blocs de couleur par tes photos (cherche `ba-after` / `ba-before` ; instructions en commentaire dans le code).

---

## 📬 4. Recevoir les demandes par courriel (gratuit, via FormSubmit)

Le formulaire envoie les demandes **directement dans ta boîte Gmail** grâce à **FormSubmit.co** — gratuit, illimité, **aucun frais mensuel**, aucun compte à créer. Les photos, elles, arrivent **par texto** au 581 922-0377 (donc aucun stockage à payer).

**Activation (à faire UNE seule fois) :**
1. Mets le site en ligne (voir l'hébergement ci-dessous).
2. Remplis toi-même le formulaire une première fois et envoie-le.
3. Tu recevras un courriel de **FormSubmit** avec un bouton **« Activate Form »** → clique-le.
4. Voilà : à partir de là, chaque demande arrive à `infoneospray@gmail.com` (l'adresse courriel du client devient l'adresse de réponse, tu peux répondre directement).

> Pour changer l'adresse de réception : cherche `formsubmit.co/infoneospray@gmail.com` dans `index.html`.
> Si du pourriel apparaît un jour : remets `_captcha` à `true` dans le formulaire.

**Hébergement (gratuit) :** le site est relié à GitHub et publié sur **Netlify** ; chaque modification poussée se met en ligne automatiquement. (Pour un simple test, tu peux aussi glisser le dossier sur [app.netlify.com/drop](https://app.netlify.com/drop).)

---

## 📍 5. Être trouvé sur Google dans le KRTB (SEO local)

Le site est déjà optimisé côté contenu : titres, textes et données structurées ciblent Rivière-du-Loup, Montmagny, etc. Pour apparaître dans **la carte Google** (le « pack local »), il te faut en plus une **fiche Google Business Profile** :

- Crée-la sur **[business.google.com](https://business.google.com)**.
- Choisis le type **« entreprise de service à domicile »** : tu peux **cacher ton adresse** et lister tes **zones desservies** (RDL, Montmagny, La Pocatière…).
- ⚠️ **N'invente jamais une fausse adresse** dans une ville où tu n'es pas : c'est contre les règles de Google et ta fiche peut être bannie.

---

## 🔧 6. Ajuster le contenu

- **Prix** : cherche `625 $` / `795 $`. Pour cacher les prix, remplace la section `id="tarifs"` par « Sur soumission ».
- **Multi-surface** : retiré pour l'instant afin de se concentrer sur le réémaillage. Quand tu voudras l'offrir, redemande-moi de réactiver la carte.
- **Villes** : ajoute/enlève des municipalités dans le bandeau `id="zones"` et dans le menu déroulant du formulaire.
