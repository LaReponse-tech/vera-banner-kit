# Bannières Vera - Kit d'intégration

Intégrez facilement une bannière Vera sur votre site pour permettre à vos visiteurs d'interroger **+500 sources fiables**.

---

## Thèmes disponibles

| Thème | Fichiers |
|-------|----------|
| **Vert** (classique) | [Horizontal](./banners/banner-horizontal-green.html) · [Vertical](./banners/banner-vertical-green.html) |
| **Rouge** (exemple) | [Horizontal](./banners/banner-horizontal-red.html) · [Vertical](./banners/banner-vertical-red.html) |

> Ouvrez [`preview.html`](./preview.html) dans votre navigateur pour prévisualiser toutes les bannières.

---

## Installation rapide

1. **Choisissez** le thème et le format
2. **Copiez** le contenu du fichier HTML
3. **Collez** dans votre page

> Les assets sont hébergés sur ce repo — rien à télécharger.

---

## Personnalisation

Les couleurs sont modifiables via les variables CSS :

<details>
<summary><strong>Thème Vert (classique)</strong></summary>

```css
--vera-bg: #fdf7f0;           /* Fond beige */
--vera-bg-outer: #f1e8de;     /* Bordure */
--vera-text: #837768;         /* Texte */
--vera-highlight-bg: #d6f3b8; /* Surlignage vert */
```
</details>

<details>
<summary><strong>Thème Rouge (exemple)</strong></summary>

```css
--vera-bg: #f7f7f7;                         /* Fond gris */
--vera-text: #1e1e1e;                       /* Texte */
--vera-accent: #ce2e0a;                     /* Accent */
--vera-highlight-bg: rgba(234,104,75,0.18); /* Surlignage */
```
</details>

---

## Structure

```
├── banners/          # Fichiers HTML à copier
│   ├── banner-horizontal-green.html
│   ├── banner-horizontal-red.html
│   ├── banner-vertical-green.html
│   └── banner-vertical-red.html
├── assets/           # Ressources (hébergées)
│   ├── vera.webp
│   ├── vera.svg
│   ├── bg-vera.png
│   └── Lastik-Regular.woff2
└── preview.html      # Prévisualisation locale
```

---

## Support

Questions ? [Contactez l'équipe Vera](https://askvera.org)
