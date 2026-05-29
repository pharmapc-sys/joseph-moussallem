# Joseph Moussallem — Carte de Visite Numérique

Site vitrine / carte de visite moderne pour Joseph Moussallem — double compétence IT & Social.

## 🔧 Mode d'emploi

### Structure du site

```
site-carte-visite/
├── index.html        # Page principale
├── style.css         # Styles du site
├── README.md         # Ce fichier
├── img/
│   ├── photo.jpg              # Photo principale (portrait)
│   ├── photo-audiovisuel.jpg  # Photo secondaire
│   ├── photo-informatique.jpg # Photo alternative
│   └── hero-bg.png            # Fond décoratif du hero
```

### Modifier le contenu

- **Texte** : édite `index.html` avec n'importe quel éditeur (Bloc-notes, VS Code, etc.)
- **Couleurs** : le style est dans `style.css` — la couleur jaune est `#ffd700`
- **Photos** : remplace les fichiers dans `img/` en gardant le même nom

### Mettre en ligne les changements

```bash
cd ~/Documents/CV/site-carte-visite
git add -A
git commit -m "Description des changements"
git push
```

Le site se met à jour automatiquement en ~1 minute sur :
https://pharmapc-sys.github.io/joseph-moussallem

### Ajouter un domaine personnalisé (optionnel)

Si tu veux utiliser moussallem.fr :
1. Ajoute un fichier `CNAME` avec `moussallem.fr` dedans
2. Dans les paramètres DNS de moussallem.fr, crée un enregistrement CNAME pointant vers `pharmapc-sys.github.io`

---

📧 joseph@moussallem.fr | 📞 07 83 74 31 83 | 🌐 moussallem.fr
