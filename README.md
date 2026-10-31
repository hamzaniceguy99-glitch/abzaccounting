# ABZ accounting — expertise comptable & fiscale

Site vitrine statique (HTML / CSS / JS, sans build) hébergé sur GitHub Pages,
domaine `abzaccounting.shop`.

> Généré depuis `C:\Users\souha\coaching-sites-factory` (fichier `sites/abzaccounting.mjs`).
> Pour une modification de contenu, éditez ce fichier puis relancez `node build.mjs abzaccounting` :
> une modification faite directement ici serait écrasée à la prochaine génération.

## À compléter avant de communiquer sur le site

| Priorité | Quoi | Où |
|---|---|---|
| 🔴 Bloquant | Mentions légales : identité de l’éditeur, SIREN, adresse, médiateur. Obligatoire en France. | `mentions-legales.html` |
| 🟠 Important | Adresse `contact@abzaccounting.shop` : créer une redirection e-mail chez Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Formulaire : remplacer `VOTRE_ID_FORMSPREE` (sinon repli automatique en `mailto:`). | `contact.html` |
| 🟠 Important | Présentation de la personne qui coache (nom, parcours réel, photo). | `a-propos.html` |
| 🟡 Plus tard | Tarifs (Sur devis / Sur devis / Renvoyé €) et contenu des formules à ajuster à votre offre réelle. | `index.html` `#tarifs` |
| 🟡 Plus tard | Témoignages : n’en ajoutez que des vrais, avec l’accord des personnes. | — |

## Description de l’activité (Stripe, annuaires…)

```
We are ABZ accounting, a certified accountancy and tax practice based in Braine-le-Château, in Walloon Brabant, working since 2020 and registered with the ITAA. We keep books and prepare annual accounts, handle VAT and the reporting that goes with it, advise on tax before decisions are taken rather than after, and look after company obligations such as the beneficial owners register. The change every Belgian business needs to have dealt with is structured electronic invoicing: since 1 January 2026 it is mandatory between Belgian taxable persons, sent over the Peppol network, and a PDF emailed to a customer no longer satisfies the obligation. Many businesses have not finished adapting. Every engagement also starts with a written engagement letter, which our professional rules require and which is still frequently missing elsewhere. Site: abzaccounting.shop
```

## Structure

```
index.html            Accueil : hero, programmes, méthode, tarifs, approche, FAQ
programmes.html       Détail des 4 programmes
a-propos.html         Notre approche et principes
contact.html          Formulaire de prise de contact
mentions-legales.html Mentions légales, confidentialité, CGV
404.html              Page d’erreur (chemins absolus)
assets/css/style.css  Couleurs de la marque en tête de fichier, puis styles communs
assets/js/main.js     Menu, thème, animations, formulaire
```

## DNS (Namecheap → Advanced DNS)

Supprimer les enregistrements de parking, puis :

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
