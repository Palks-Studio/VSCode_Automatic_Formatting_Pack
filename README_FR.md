> 🇫🇷 Français | [🇬🇧 English](./README.md)

# VS Code – Pack de Formatage Automatique (Version Lite)

Un environnement **propre**, prêt à l’emploi pour Visual Studio Code, qui garde vos fichiers **alignés, bien indentés et cohérents**, sans dépendre de Prettier, d’extensions externes ou de scripts spécifiques à chaque projet.

Ce dépôt contient la **version publique / d’aperçu** du pack.
La version complète (avec scripts prêts à l’emploi : `clean.py`, `convert.py`, `space.py`, guide d’installation, tâches automatisées, démos…) est disponible sur Gumroad :

https://palks.gumroad.com/

---

## Ce que fait ce pack

✔ Maintient automatiquement un code propre, **aligné et uniforme**  
✔ Compatible avec **Python, HTML, CSS, JavaScript, JSON**  
✔ Normalise automatiquement :  
- Indentation  
- Espaces / fin de ligne (CRLF → LF)  
- Encodage UTF-8

✔ Ajoute des raccourcis et tâches utiles dans VS Code :  
- Alt + R → réindentation complète du fichier actif  
- Alt + M → afficher / masquer la minimap  
- Formatage automatique optionnel (Python : Autopep8 + nettoyage)

---

## Structure du dépôt (version publique) 
```
VSCode_Pack_Formatage_Automatique_FR/ (Version Lite)
├── README_FR.md                 ← Documentation principale (publique)
├── .gitignore                   ← Exclut les fichiers privés/commerciaux
│
├── LICENSE                      ← Licence MIT (publique)
├── version_publique/
│   ├── .vscode/
│   │   ├── settings.json        ← Exemple minimal (UTF-8, LF, espaces visibles)
│   │   ├── tasks.json           ← Structure uniquement (sans scripts internes)
│   │   ├── keybindings.json     ← Raccourcis Alt+R et Alt+M
│   │   └── launch.json          ← Optionnel : exécuter le fichier Python actif
│   └── exemple_structure.txt    ← Arborescence complète du pack commercial
│
└── docs/
    └── exemples/                 ← (Optionnel) Avant / Après détaillés de formatage
        ├── avant.py              ← Versions sales / déstructurées
        ├── apres.py              ← Versions propres générées par le pack
        ├── convert_lf.mp4        ← Fichiers CRLF reconvertis en LF automatiquement
        ├── indent_clean.mp4      ← Fichiers avec indentation/marges cassées + auto-correction instantanée
        ├── indent_python.mp4     ← Fichier Python mal indenté + correction automatique
        └── space_clean.mp4       ← Fichiers cassé volontairement + analyse marges + auto-correction instantanée
```


Les fichiers `.mp4` présents dans ce dossier (convert_lf.mp4, indent_clean.mp4, etc.) sont volontairement inclus dans la version Lite : ce sont des démonstrations réelles du pack complet, pour montrer ce qu’il est capable de faire.

---

## Non inclus dans ce dépôt (réservé à la version complète)

- `.vscode/extensions.json` — désactivation locale d’extensions (Prettier / RunOnSave)  
- `settings.json` — version complète avec toutes les règles d’édition  
- `keybindings.json` — ensemble complet des raccourcis  
- `tasks.json` — tâches reliées aux scripts du pack  
- `launch.json` — profils complets de débogage  
- `clean.py` — nettoyage global du projet  
- `convert.py` — conversion CRLF → LF dans tout l’espace de travail  
- `space.py` — détection d’espaces ou lignes superflues  
- `INSTALL.md` — guide d’installation et d’utilisation  
- `README_COMMERCIAL.md` — présentation du produit (version Gumroad)  
- `docs/README_TECHNIQUE.md` — notes techniques / maintenance  
- Archives de distribution (`*.zip`, `*.tar.*`)

---

## Utilisation rapide (Version d’aperçu)

1. Clonez ou téléchargez ce dépôt  

2. Copiez le dossier `.vscode/` depuis `version_publique/` dans n’importe quel projet  

3. Ouvrez le projet dans VS Code → les réglages de base sont actifs immédiatement

---

## Ce que vous obtenez dans la version complète (Gumroad)

- Scripts entièrement opérationnels :  
   - `clean.py` → nettoie tous les fichiers (supprime les marges inutiles + supprime les lignes vides uniquement à partir de 3)  
   - `convert.py` → convertit tous les CRLF en LF dans le projet  
   - `space.py` → analyse en lecture seule (détecte espaces inutiles, tabulations, lignes vides — sans modifier les fichiers)

- Tâches VS Code configurées (prêtes à l’emploi)  
- Installation en moins de 30 secondes  
- Documentation complète : INSTALL, README technique, README commercial  
- Exemples avant/après, vidéos de démonstration, support Discord  

Disponible ici (à saisir manuellement) :  
https://palks.gumroad.com/

---

## Compatibilité technique

| Outil / Plateforme       | Supporté                |
| ------------------------ | ----------------------- |
| Visual Studio Code       | 1.90+                   |
| Systèmes d’exploitation  | Windows / macOS / Linux |
| Python installé          | Oui (requis)            |
| Fonctionne sans Prettier | Oui                     |
| Fonctionne hors ligne    | Oui                     |

---

## Retour et Communauté

Tu veux tester, proposer des améliorations ou poser des questions ?

- **Gumroad :** https://palks.gumroad.com/
  
- **Serveur Discord :** https://discord.gg/kzrSyThyZ7
  
- **Reddit :** https://www.reddit.com/user/Puzzled_Gap_2951/

---

**Palks Studio — Créateur d’outils utiles et autonomes.**
