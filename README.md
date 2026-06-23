# La Voile · Balco del Mar — Collioure

Site vitrine du restaurant **La Voile** et de son bar de plage **Balco del Mar**, à Collioure (Côte Vermeille).

Site statique multipage (HTML/CSS/JS, sans framework ni build).

## Structure

```
site/                      ← site déployable
├── index.html             Accueil (La Voile)
├── restaurant.html        Le Restaurant + la carte
├── balco-del-mar.html     Le bar Balco del Mar (identité festive)
├── evenements.html        Événements & concerts
├── galerie.html           Galerie photos
├── contact.html           Contact & réservation
├── sitemap.xml / robots.txt
└── assets/
    ├── css/styles.css      Système de design (2 univers via [data-univers])
    ├── js/main.js          Navbar, menu mobile, reveal, compteurs
    ├── img/                Photos optimisées (JPG)
    ├── logo/               Logos détourés/recolorés
    └── favicon.svg
```

## Design

- **La Voile** : bleu marine + crème + or, titres manuscrits *Dancing Script*.
- **Balco del Mar** : terracotta / coucher de soleil / vermillon, titres manuscrits *Kaushan Script*.
- Corps de texte : *Jost* ; accents : *Cormorant Garamond* ; libellés/carte : *Bricolage Grotesque*.

## Développement local

```bash
python -m http.server 8123 --directory site
# http://localhost:8123
```

## À compléter (placeholders)

Téléphone, e-mail, domaine canonique, horaires exacts et la carte/prix sont indicatifs. Le formulaire de réservation est une démo (sans backend).
