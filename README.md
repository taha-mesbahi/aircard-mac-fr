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
- `sitemap.xml` : URL canonique à soumettre dans Google Search Console.

## Faire découvrir le site à Google

1. Dans [Google Search Console](https://search.google.com/search-console/welcome), ajouter une propriété **Préfixe d’URL** avec `https://taha-mesbahi.github.io/aircard-mac-fr/` (barre finale comprise).
2. Vérifier la propriété avec le fichier HTML proposé par Google, en le plaçant à la racine de ce dépôt, puis en le publiant. Vérifier que son URL publique exacte répond avant de cliquer sur **Valider**. La balise HTML dans `<head>` est une autre méthode possible.
3. Dans **Sitemaps**, soumettre `https://taha-mesbahi.github.io/aircard-mac-fr/sitemap.xml`.
4. Dans **Inspection de l’URL**, inspecter la page d’accueil et, si nécessaire, demander son indexation. Suivre ensuite les impressions, clics, requêtes et problèmes d’indexation dans Search Console.

Le fichier `robots.txt` ne peut agir qu’à la racine de l’hôte (`https://taha-mesbahi.github.io/robots.txt`). Un fichier placé dans `/aircard-mac-fr/` n’aurait aucun effet sur Google. Le site n’empêche pas l’exploration, et le sitemap reste accessible à son URL publique. L’indexation et les positions ne sont pas garanties.

La meilleure amélioration à long terme est un contenu utile, exact et tenu à jour : expliquer les cas réellement rencontrés, vérifier les liens de téléchargement, puis obtenir des liens éditoriaux pertinents vers le guide, par exemple depuis la documentation du projet avec l’accord de ses mainteneurs. Éviter les pages répétitives et l’achat de liens.

Le site n'héberge **aucun DMG**, aucune œuvre AirCards et aucun code de l'application AirCard. Le bouton principal pointe vers `https://github.com/Mak5er/AirCard/releases/latest/download/AirCard.dmg` afin de télécharger le fichier depuis la release officielle courante. Le lien secondaire ouvre la page des releases si le nom de l'asset change.

## Crédits et portée

AirCard est développé par [Mak5er et ses contributeurs](https://github.com/Mak5er/AirCard). Les designs sont proposés séparément sur [AirCards](https://aircards.org/). Ce site est un guide indépendant et n'est affilié ni à Apple ni aux émetteurs de cartes. La personnalisation de l'image ne crée pas de carte et ne change pas ses permissions.

La licence MIT du présent dépôt couvre uniquement le code original de ce site. Elle ne s'applique pas à AirCard, aux logos tiers ni aux designs téléchargés ailleurs.
