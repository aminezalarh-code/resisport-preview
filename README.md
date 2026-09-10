# Aperçu du nouveau site RESISPORT

Copie statique du nouveau site, publiée pour relecture et validation avant la
mise en ligne. **Ce n'est pas le site en production.**

➡️ **https://aminezalarh-code.github.io/resisport-preview/**

## Ce qui ne fonctionne pas ici

- **Le formulaire de demande d'étude.** Il est désactivé : cette copie n'a pas
  de serveur. Une demande envoyée depuis cet aperçu serait perdue. Sur le site
  en ligne, elle est enregistrée et transmise à contact@resisport.com.
- L'administration WordPress et toute modification de contenu.
- Les coordonnées et les données structurées sont figées à la date de capture.

## Indexation

Chaque page porte `<meta name="robots" content="noindex, nofollow">`. C'est
délibéré : une copie indexable ferait concurrence à resisport.com sur ses
propres mots-clés.

> Le fichier `robots.txt` de ce dépôt est **inopérant** : GitHub Pages sert ce
> site dans un sous-répertoire, et les robots ne lisent le `robots.txt` qu'à la
> racine du domaine. La balise `noindex` est donc la seule protection réelle —
> elle suffit, mais elle ne doit pas être retirée.

---

*Généré par `tools/build-static-preview.js --base-path /resisport-preview`.
Le site réel est une installation WordPress destinée à l'hébergement
LiteSpeed/cPanel existant.*
