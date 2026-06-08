# Coupain.com

Il s'agit d'une page statique d'un ancien domaine (coupain.com) qui n'est plus utilisé. Ce dépôt contient le code pour une redirection automatique, garantissant que les visiteurs qui utilisent encore cet ancien lien sont orientés vers le site web principal de l'auteur.

---

## Fonctionnalités Clés

*   **Redirection Automatique** : La page utilise une balise meta HTML (`meta-refresh`) pour rediriger automatiquement les utilisateurs vers `charlymedina.fr` après un délai d'une seconde.
*   **Simplissime** : Le site se compose d'un unique fichier HTML (`index.html`), sans dépendances, styles ou scripts complexes.

## Documentation Technique

La redirection est mise en œuvre à l'aide de la balise suivante, située dans la section `<head>` :

```html
<meta http-equiv="refresh" content="1; URL=[http://www.charlymedina.fr](http://www.charlymedina.fr)">
