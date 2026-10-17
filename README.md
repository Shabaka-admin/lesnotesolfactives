# Le Guide des Notes (Jekyll / GitHub Pages)

1. Le domaine lesnotesolfactives.com est déjà renseigné dans `CNAME`, `_config.yml`, `robots.txt` et la page contact (créer la boîte mail contact@ ou changer l'adresse).
2. Créer un dépôt GitHub, y envoyer tous ces fichiers.
3. Settings > Pages : Source = "Deploy from a branch", branche `main`, dossier `/ (root)`.
4. Chez le registrar : enregistrements DNS vers GitHub Pages (voir la doc GitHub), puis cocher "Enforce HTTPS".
5. Nouvel article : ajouter un fichier `_posts/AAAA-MM-JJ-titre.md` (voir les exemples). Menu, accueil et sitemap se mettent à jour seuls.
