# Deux gestes, un projet de jeu — Tennis CA4

Site d'accompagnement EPS (cycle 4, classe de 4ᵉ) sur deux gestes du tennis : le service et le smash.

Projet de Corentin Bernier & Tom Agnan.

- Site en ligne : https://corent1-974.github.io/site-tennis-ca4/
- Tout le site tient dans un seul fichier : `index.html` (HTML + CSS + un peu de JavaScript).
- Hébergement : GitHub Pages, sur le compte GitHub de l'auteur. Le code appartient à ses auteurs
  et peut être déplacé chez n'importe quel autre hébergeur (Netlify, serveur de l'établissement…).

## Ajouter vos photos dans les mini-jeux (onglet Exercices)

1. Déposez la photo dans le dépôt (« Add file » → « Upload files »), par exemple `service-1.jpg`.
2. Dans `index.html`, cherchez `ETAPES_SERVICE` (service) ou `SITUATIONS_SMASH` (smash)
   et remplacez `photo: ''` par `photo: 'service-1.jpg'` sur la bonne ligne.

## Vidéos et photos (dossier `media/`)

- Toutes les vidéos et images viennent de nos propres vidéos. Les vidéos des pages sont en paysage (1280×720) :
  vidéo verticale au centre, fond flouté sur les côtés.
- `service-explication.mp4` (page Service) : vidéo commentée par Corentin (2 min 23, 6,6 Mo), avec arrêts sur
  image et ralentis calés sur la voix. Sous-titres dans `service-explication.vtt` (désactivés par défaut,
  activables dans le lecteur).
- `gestes.mp4` (accueil : un service puis un smash) et `smash.mp4` (page Smash) :
  montées à partir de nos vidéos, coupées, ralenti ×2,5 sur la frappe, sans son, H.264 (environ 0,5 à 0,7 Mo
  chacune). Une image d'affiche `*-poster.jpg` s'affiche avant la lecture.
- `service-1-position.jpg` … `service-4-accompagnement.jpg` et `smash-1-placement.jpg` … `smash-4-transfert.jpg` :
  images fixes des étapes. Celles du service servent aussi au mini-jeu « remets les étapes dans l'ordre ».
  `service-carte.jpg` et `smash-carte.jpg` : cartes de l'accueil.
- Les vidéos ne se lancent pas toutes seules (lecture avec les contrôles, en boucle, sans son).

## Avant d'ajouter des photos ou des vidéos

- **Texte alternatif** : chaque image doit avoir une description (attribut `alt`). Dans les mini-jeux, elle est
  ajoutée automatiquement à partir du texte de la carte. Pour les autres images, écrire par exemple
  `<img src="service-1.jpg" alt="Joueur de profil au service, bras de lancer tendu">`.
- **Droit à l'image** : pour filmer ou photographier une personne, il faut son accord écrit, et pour un mineur
  celui de ses parents.
- **Droits d'auteur** : n'utiliser que vos propres photos ou des images dont la licence autorise la réutilisation.

## Conformité (vérifiée le 14 octobre 2026)

- Aucune donnée personnelle collectée, aucun cookie, aucun service tiers (polices hébergées dans `fonts/`).
- Seul enregistrement sur l'appareil : les cases cochées (`criteres-service`, `criteres-smash`), après une action
  de l'utilisateur, effaçables depuis la page Cookies : exempté de consentement (fonctionnalité demandée par l'utilisateur).
- Pages : mentions légales, confidentialité, cookies, conditions d'utilisation (liens en bas de page).
- Contrastes vérifiés (WCAG 2.1 AA) et test automatique axe-core sans erreur sur toutes les pages.
