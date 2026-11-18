# ↪️ coupain.com

Ancien nom de domaine, **plus utilisé**. Ce dépôt sert uniquement à rediriger les visiteurs de [coupain.com](https://coupain.com) vers **[charlymedina.fr](https://charlymedina.fr)**.

---

## ⚙️ Fonctionnement

Une seule page `index.html`, publiée via GitHub Pages (domaine défini dans `CNAME`) :

- **Redirection** après 1 seconde grâce à une balise meta :
  ```html
  <meta http-equiv="refresh" content="1; URL=http://www.charlymedina.fr">
  ```
- **Statistiques** : Google Analytics (gtag.js), pour savoir si l'ancien domaine reçoit encore des visites.

## 📁 Structure

```
├── index.html   # Page de redirection
└── CNAME        # Domaine : coupain.com
```

## 💡 Pistes d'amélioration

- Rediriger vers `https://charlymedina.fr` (HTTPS) plutôt que `http://www.charlymedina.fr`.
- Si le domaine ne reçoit plus de visites, il pourra être abandonné et ce dépôt archivé.
