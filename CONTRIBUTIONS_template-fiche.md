<!-- À placer dans le dépôt https://github.com/rudetools/contributions à la racine : template-fiche.md -->

# Modèle de fiche pour proposer un outil

Copiez ce fichier, renommez-le (ex. `mon-outil.md`), remplissez les sections et ajoutez-le à votre fork avant d’ouvrir une Pull Request. Les fiches du site RudeTools suivent cette structure.

---

## En-tête (frontmatter)

À mettre en tout début du fichier :

```yaml
---
title: Nom affiché de l'outil
sidebar_label: Nom court (pour la sidebar)
description: Une phrase pour le SEO et les aperçus (rôle principal de l'outil).
---
```

---

## Overview (résumé encadré)

Un à trois paragraphes décrivant :
- À quoi sert l’outil
- Les briques principales (concepts, composants)
- Ce qui le distingue (déploiement, intégrations, cas d’usage clés)

*Exemple : « X permet de… L’outil s’appuie sur… Il se distingue par… »*

---

## Informations essentielles

Tableau avec au minimum :

| Propriété   | Valeur |
| -----------| ------ |
| Site officiel | (URL) |
| Repository | (URL GitHub, etc.) |
| Licence    | (ex. MIT, Apache-2.0) |
| Déploiement| (ex. Docker, binaire, package) |
| Langage    | (ex. Go, Python) |
| Plateforme | (ex. Linux, multi-OS) |

---

## Cas d’usage typiques

Liste à puces (5–10 points) : dans quels contextes l’outil est pertinent.

---

## Intégrations et écosystème (optionnel)

Avec quels outils ou plateformes il s’intègre (CI/CD, cloud, monitoring, etc.).

---

## Avantages

Liste avec ✅ : points forts (simplicité, fonctionnalités, communauté, etc.).

---

## Inconvénients et limitations

Liste avec ❌ : limites, contraintes, cas non couverts.

---

## Alternatives (optionnel)

Quelques outils proches ou concurrents.

---

## Ressources

- Documentation : (URL)
- GitHub : (URL)
- Quick start / tutoriel : (URL si pertinent)
