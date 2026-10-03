# AirCard pour Mac — site en français

Page statique expliquant comment télécharger et utiliser **AirCard pour macOS**.
Elle dirige le téléchargement vers la [dernière release du projet Mak5er/AirCard](https://github.com/Mak5er/AirCard/releases/latest) et les designs vers [aircards.org](https://aircards.org/).

## Voir le site

Site publié : [AirCard pour Mac](https://taha-mesbahi.github.io/aircard-mac-fr/).

Pour le consulter localement, ouvrir `index.html` dans un navigateur ou lancer un serveur :

```sh
python3 -m http.server 8080
```

Puis ouvrir `http://localhost:8080/`.

## Modifier le contenu

- `index.html` : texte, liens de téléchargement, balises SEO et données structurées.
- `styles.css` : mise en page, cartes illustratives, responsive et accessibilité.
- `assets/` : favicon, icône Apple et image de partage social.
- `robots.txt` et `sitemap.xml` : indexation de la page GitHub Pages.

Le site n'héberge **aucun DMG**, aucune œuvre AirCards et aucun code de l'application AirCard. Le bouton principal pointe vers `https://github.com/Mak5er/AirCard/releases/latest/download/AirCard.dmg` afin de télécharger le fichier depuis la release officielle courante. Le lien secondaire ouvre la page des releases si le nom de l'asset change.

## Crédits et portée

AirCard est développé par [Mak5er et ses contributeurs](https://github.com/Mak5er/AirCard). Les designs sont proposés séparément sur [AirCards](https://aircards.org/). Ce site est un guide indépendant et n'est affilié ni à Apple ni aux émetteurs de cartes. La personnalisation de l'image ne crée pas de carte et ne change pas ses permissions.

La licence MIT du présent dépôt couvre uniquement le code original de ce site. Elle ne s'applique pas à AirCard, aux logos tiers ni aux designs téléchargés ailleurs.
