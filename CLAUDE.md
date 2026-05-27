# Yelinne — Carousel Style Guide

Ce fichier est la référence absolue pour tout carousel ou contenu visuel généré dans ce projet.
**Respecte ces règles à chaque génération, sans exception.**

---

## Branding

- **Nom de marque** : Yelinne
- **Handle Instagram** : @yelinne

---

## Couleurs

| Rôle | Hex | Usage |
|------|-----|-------|
| Bleu foncé | `#0f1923` | Fond des slides sombres, texte principal sur fond clair, embed cards |
| Bleu moyen | `#2872A1` | Accent (bookmark, labels, règle, mots-clés, boutons CTA) |
| Bleu clair | `#CBDDE9` | Texte secondaire sur fond sombre |
| Crème / Off-white | `#f5f0eb` | Fond principal des slides claires |
| Rouge FOMO | `#e74c3c` | Uniquement pour les slides d'alerte/FOMO (bookmark, label, accent) |
| Rouge FOMO foncé | `#c0392b` | Bookmark sur slide FOMO |

---

## Typographies

| Élément | Police | Poids | Taille |
|---------|--------|-------|--------|
| Headlines | Playfair Display | 900 (Black) | 56–80px selon le slide |
| Labels (catégorie) | Inter | 700 | 16px, uppercase, letter-spacing 3px |
| Body text | Inter | 600 | 27px |
| Body light | Inter | 400 | 25px, couleur #3a4a5a |
| Bullets | Inter | 500 | 25px |
| Embed card texte | Inter | 400 | 23px |
| Analogies | Inter | 400 italic | 22px |
| Handle | Inter | 400 | 18px |
| Stat (gros chiffre) | Playfair Display | 900 | 100px |
| Stat inline (dans card) | Playfair Display | 900 | 42px |

---

## Format des slides

- **Dimensions** : 1080 x 1350 px (format Instagram portrait 4:5)
- **Padding** : 100px top, 80px sides, 80px bottom
- **Alignement** : texte aligné à gauche (sauf slides cover et CTA = centré)

---

## Éléments de mise en page (respecter sur CHAQUE slide)

### 1. Bookmark (onglet)
- Position : top-left, x=60px
- Taille : 50x70px
- Forme : clip-path polygon (fanion/bookmark)
- Couleur : `#2872A1` (ou `#c0392b` sur slide FOMO)

### 2. Watermark (numéro de slide)
- Position : top-right
- Font : Playfair Display, 320px, weight 900
- Couleur : rgba très faible (0.04 sur clair, 0.03 sur sombre)
- Ne pas afficher sur slide 1 (cover)

### 3. Label (catégorie)
- Texte en UPPERCASE, letter-spacing 3px
- Couleur `#2872A1`
- Placé en haut, après le bookmark

### 4. Headline
- Playfair Display Black
- Couleur `#0f1923` sur fond clair, `#fff` sur fond sombre
- Mots-clés importants en `.accent` (`#2872A1`)

### 5. Rule (ligne horizontale)
- 60px de large, 5px de haut
- Couleur `#2872A1`
- Placée sous le headline

### 6. Body text
- Inter Semi-Bold 27px
- Mots-clés en `.accent` (`#2872A1`)

### 7. Embed card (encart sombre)
- Fond `#0f1923`, border-radius 16px
- Padding 35px 40px
- Label interne en uppercase bleu `#2872A1`
- Texte en `#CBDDE9`, mots-clés en `#fff` bold

### 8. Analogy (encart citation)
- Fond : rgba(40, 114, 161, 0.08)
- Bordure gauche : 4px solid `#2872A1`
- Texte en italique, 22px
- Mots-clés en bold, accents en `#2872A1`

### 9. Handle
- Position : absolute, bottom 40px, left 80px
- Texte : `@yelinne`
- Couleur : rgba faible (0.3 sur clair, 0.25 sur sombre)

---

## Types de slides

### Slide claire (défaut)
- Fond : `#f5f0eb`
- Texte : `#0f1923`

### Slide sombre (avertissement, closing)
- Fond : `#0f1923`
- Texte : `#fff` / `#CBDDE9`
- Embed card : `rgba(255,255,255,0.06)`

### Slide FOMO
- Fond : `#0f1923`
- Accents : `#e74c3c` (rouge) au lieu de bleu
- Bookmark : `#c0392b`

### Slide CTA
- Fond : `#0f1923`
- Centré
- Bouton : fond `#2872A1`, texte blanc, border-radius 12px, padding 26px 55px
- Sub-text sous le bouton en `rgba(203,221,233,0.7)`

### Slide Cover
- Fond : `#f5f0eb`
- Centré
- Headline plus grand (80px)
- Pas de watermark

---

## Ton éditorial

- **Langue** : Français naturel et conversationnel
- **Ton** : Direct, punchy, légèrement provocateur mais bienveillant
- **FOMO** : Montrer ce que le lecteur PERD en n'agissant pas (temps, clients, argent)
- **Chiffres** : Utiliser des stats concrètes, arrondies, reformulées simplement
- **Analogies** : Utiliser des comparaisons relationnelles / vie quotidienne, avec humour subtil
- **CTA** : Toujours inviter à commenter un mot-clé (pas DM), le coach envoie ensuite en DM
- **Cible** : Coachs business et infopreneurs francophones

---

## Référence visuelle

Le fichier `references/slide-style.png` est la référence visuelle de base.
Toujours s'en inspirer pour la mise en page.

---

## Export

- Utiliser html2canvas pour exporter en PNG 1080x1350
- Nommage : `yelinne_slide_01.png`, `yelinne_slide_02.png`, etc.
- Bouton de téléchargement intégré dans la page HTML
