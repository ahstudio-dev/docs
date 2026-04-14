# AHStudio — Charte graphique

> Référence officielle de l'identité visuelle d'AHStudio. À consulter avant tout travail de design ou de développement frontend.

---

## Logo

### Concept
4 carrés géométriques représentant les 4 piliers d'AHStudio : **Dev · Design · Build · Ship**.

### Hiérarchie des carrés
| Carré | Couleur | Signification |
|-------|---------|---------------|
| Haut gauche | Émeraude `#1D9E75` | Principal — identité forte |
| Haut droite | Émeraude `#1D9E75` à 50% | Secondaire |
| Bas gauche | Émeraude `#1D9E75` à 50% | Secondaire |
| Bas droite | Blanc `#ffffff` / Noir `#111827` | Contraste — ancrage |

### Variantes
- **Logo complet** — icône + texte "AHStudio"
- **Logo avec tagline** — icône + texte + "DEV · BUILD · SHIP"
- **Icône seule** — pour favicon, photo de profil, petits formats
- **Fond sombre** — fond `#111827`, texte blanc
- **Fond vert** — fond `#0F6E56`, carrés blancs

### Règles d'utilisation
- Ne jamais déformer ou étirer le logo
- Ne jamais changer les couleurs en dehors des variantes officielles
- Espace minimum autour du logo : égal à la hauteur d'un carré
- Taille minimum : 24px de hauteur pour l'icône seule

---

## Palette de couleurs

### Couleurs principales

| Nom | Hex | Usage |
|-----|-----|-------|
| Émeraude | `#1D9E75` | Couleur principale, boutons, accents, logo |
| Émeraude foncé | `#0F6E56` | Hover, états actifs |
| Émeraude clair | `#E1F5EE` | Fonds, badges, highlights |
| Noir corporate | `#111827` | Textes principaux, fond dark, logo |
| Blanc cassé | `#F9FAFB` | Fond principal light mode |
| Gris neutre | `#6B7280` | Textes secondaires, bordures |

### Couleurs secondaires

| Nom | Hex | Usage |
|-----|-----|-------|
| Gris clair | `#F3F4F6` | Fonds secondaires, badges neutres |
| Gris bordure | `#E5E7EB` | Bordures, séparateurs |
| Texte muted | `#9CA3AF` | Labels, captions, placeholders |

### Usage dark mode

| Élément | Light | Dark |
|---------|-------|------|
| Fond principal | `#F9FAFB` | `#080f0c` |
| Fond carte | `#ffffff` | `#111827` |
| Texte principal | `#111827` | `#ffffff` |
| Texte secondaire | `#6B7280` | `#9CA3AF` |
| Accent | `#1D9E75` | `#1D9E75` |
| Accent texte dark | — | `#5DCAA5` |

---

## Typographie

### Police
**System UI** — on utilise la police système de l'appareil pour des performances maximales et un rendu natif.

```css
font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
```

### Échelle typographique

| Niveau | Taille | Poids | Usage |
|--------|--------|-------|-------|
| Hero | 48px | 700 | Titre principal de page |
| H1 | 32px | 700 | Titres de section |
| H2 | 24px | 600 | Sous-titres |
| H3 | 20px | 600 | Titres de carte |
| Body | 15px | 400 | Corps de texte |
| Small | 13px | 400 | Texte secondaire |
| Label | 12px | 500 | Badges, labels, captions |
| Micro | 11px | 500 | Metadata, timestamps |

### Règles
- Letter-spacing négatif sur les grands titres : `-0.03em` à `-0.05em`
- Line-height : `1.2` pour les titres, `1.7` pour le corps
- Letter-spacing positif sur les labels uppercase : `0.08em`

---

## Composants UI

### Boutons

```css
/* Bouton principal */
background: #1D9E75;
color: #ffffff;
border: none;
padding: 10px 20px;
border-radius: 8px;
font-size: 14px;
font-weight: 500;

/* Bouton secondaire */
background: transparent;
color: #1D9E75;
border: 1.5px solid #1D9E75;
padding: 9px 20px;
border-radius: 8px;

/* Bouton dark */
background: #111827;
color: #ffffff;
border: none;
padding: 10px 20px;
border-radius: 8px;
```

### Badges & Tags

```css
/* Badge émeraude */
background: #E1F5EE;
color: #0F6E56;
font-size: 12px;
font-weight: 500;
padding: 4px 10px;
border-radius: 6px;

/* Badge neutre */
background: #F3F4F6;
color: #374151;

/* Badge dark */
background: #111827;
color: #ffffff;
```

### Cartes

```css
background: #ffffff;
border: 0.5px solid #E5E7EB;
border-radius: 12px;
padding: 1.25rem;
```

### Bordures & Rayons

| Élément | Rayon |
|---------|-------|
| Boutons, badges | `8px` |
| Cartes | `12px` |
| Logo icône | `13px` |
| Modales | `16px` |

---

## Tagline

> **DEV · BUILD · SHIP**

Utilisée sous le logo en format complet. Toujours en majuscules, letter-spacing `3px`, couleur émeraude `#1D9E75` sur fond clair, `#5DCAA5` sur fond sombre.

---

## Tokens CSS recommandés

```css
:root {
  --color-primary: #1D9E75;
  --color-primary-dark: #0F6E56;
  --color-primary-light: #E1F5EE;
  --color-dark: #111827;
  --color-bg: #F9FAFB;
  --color-text: #111827;
  --color-text-muted: #6B7280;
  --color-border: #E5E7EB;

  --radius-sm: 6px;
  --radius-md: 8px;
  --radius-lg: 12px;
  --radius-xl: 16px;

  --font-sans: system-ui, -apple-system, sans-serif;
}
```

---

*Dernière mise à jour : avril 2025 — AHStudio*
