# RE2020 Bullet Graphs v4.0

## Lancement local
```bash
pip install -r requirements.txt
voila RE2020_BulletGraphs_v4.0.ipynb --strip_sources=True
```

## Déploiement gratuit avec Binder + Voilà
1. Déposer à la racine du dépôt GitHub :
   - `RE2020_BulletGraphs_v4.0.ipynb`
   - `requirements.txt`
   - `runtime.txt`
   - `voila.json`
2. Utiliser l'URL :

```text
https://mybinder.org/v2/gh/UTILISATEUR/DEPOT/BRANCHE?urlpath=voila/render/RE2020_BulletGraphs_v4.0.ipynb
```

Exemple si la branche est `main` :
```text
https://mybinder.org/v2/gh/UTILISATEUR/DEPOT/main?urlpath=voila/render/RE2020_BulletGraphs_v4.0.ipynb
```

## Remarques
- Le notebook ne contient plus de `pip install` : Binder construit l'environnement depuis `requirements.txt`.
- Le premier démarrage Binder peut prendre plusieurs minutes si l'image doit être reconstruite. Les démarrages suivants sont généralement plus rapides tant que l'image reste en cache.
- Le stockage Binder est temporaire. Les utilisateurs doivent télécharger leurs exports et leur JSON avant de fermer la session.
