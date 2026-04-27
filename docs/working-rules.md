# Working Rules

Regles minimales pour garder le repo lisible dans le temps, meme si une autre IA reprend plus tard.

## 1) Branche et commits

- Ne pas travailler directement sur `main`.
- Utiliser une branche explicite par lot (`docs/*`, `feature/*`, `chore/*`).
- Commits courts, clairs, orientes intention.

## 2) Documentation

- Priorite a la clarte sur la quantite.
- Eviter les formulations definitives quand le sujet est encore en evolution.
- Une mise a jour importante doit etre refletee dans le journal mensuel.

## 3) Presentations

- 1 projet mature = 1 presentation Gamma.
- Les presentations non finalisees restent marquees `Draft`.

## 4) Certifications

- Mettre a jour `certifications/progression.md` a chaque changement reel.
- Ne pas inventer de validation si elle n'est pas confirmee.

## 5) ADR

- Toute decision structurante doit avoir un ADR court dans `docs/adr/`.
- Un ADR explique: contexte, decision, consequences.
