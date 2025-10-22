<p align="center">
  <img src="../docs/images/reddit_banniere.png" alt="VS Code Pack - Palks Studio">
</p>

> 🇫🇷 Français | [🇬🇧 English](../README.md)

![Licence MIT](https://img.shields.io/badge/Licence-MIT-green.svg)
![Compatible VS Code](https://img.shields.io/badge/Éditeur-VS%20Code-blue.svg)
![Python](https://img.shields.io/badge/Python-3.x-yellow.svg)
![Plateformes](https://img.shields.io/badge/OS-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey.svg)

<p align="center">
  <a href="https://palks.gumroad.com/" target="_blank">
    <img src="https://img.shields.io/badge/🔽 Télécharger%20sur-Gumroad-orange?style=for-the-badge" alt="Télécharger sur Gumroad">
  </a>
</p>

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
├── README_FR.md                    ← Documentation principale (publique)
├── LICENSE.txt                  ← Licence (version anglaise)
├── .gitignore                   ← Exclut les fichiers privés/commerciaux
│
├── version_publique/
│   ├── .vscode/
│   │   ├── settings.json        ← Exemple minimal (UTF-8, LF, espaces visibles)
│   │   ├── tasks.json           ← Structure uniquement (sans scripts internes)
│   │   ├── keybindings.json     ← Raccourcis Alt+R et Alt+M
│   │   └── launch.json          ← Optionnel : exécuter le fichier Python actif
│   └── exemple_structure.txt    ← Arborescence complète du pack commercial
│
└── docs/
    └── exemples/
        ├── avant.py             ← Exemple non formaté
        └── apres.py             ← Exemple formaté
```


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
- Fichiers de démonstration : `demo.py`, `demo.js`, `demo.html`, `demo.css`, `demo.json`  
- Archives de distribution (`*.zip`, `*.tar.*`)

---

## Utilisation rapide (Version d’aperçu)

1. Clonez ou téléchargez ce dépôt  

2. Copiez le dossier `.vscode/` depuis `version_publique/` dans n’importe quel projet  

3. Ouvrez le projet dans VS Code → les réglages de base sont actifs immédiatement

---

## Ce que vous obtenez dans la version complète (Gumroad)

Scripts entièrement configurés :  
- formatage + nettoyage automatique (`clean.py`)  
- conversion CRLF → LF (`convert.py`)  
- détection des espaces en trop / lignes vides (`space.py`)  

Environnement VS Code prêt à l’emploi :  
- réglages (`settings.json`)  
- tâches (`tasks.json`)  
- raccourcis clavier (`keybindings.json`)  
- configuration de lancement (`launch.json`)

Documentation incluse :  
- exemples avant/après (Python, HTML, CSS, JS, JSON)  
- guide d’installation + documentation technique

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
