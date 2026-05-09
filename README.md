# My Portfolio Website

Content Creator & Digital Strategist — built with plain HTML, CSS & JS.

## Files

```
portfolio/
├── index.html   ← Όλη η δομή της σελίδας
├── style.css    ← Αισθητική, χρώματα, responsive
├── script.js    ← Animations, mobile nav
├── images/      ← Βάλε εδώ τις φωτογραφίες σου (δημιούργησε τον φάκελο)
└── README.md
```

## Πώς να προσθέσεις τις φωτογραφίες σου

### Φωτογραφία hero (εσύ)
Στο `index.html` βρες:
```html
<div class="hero-photo-placeholder">...</div>
```
Αντικατέστησέ το με:
```html
<img src="images/me.jpg" alt="Το όνομά σου" class="hero-photo" />
```

### Φωτογραφίες gallery (projects)
Βρες τα `<div class="gallery-img-placeholder">` και αντικατέστησέ τα με:
```html
<img src="images/project1.jpg" alt="Περιγραφή project" class="gallery-img" />
```

## Τι να αλλάξεις στο index.html

- `Your Name` → το πραγματικό σου όνομα (Nav + Footer)
- `@yourusername` → τα πραγματικά σου social handles
- `hello@yourname.com` → το email σου
- Κείμενα φιλοσοφίας / gallery captions → τα δικά σου λόγια

## Δες το τοπικά

Άνοιξε το `index.html` στον browser σου — δεν χρειάζεσαι server.
