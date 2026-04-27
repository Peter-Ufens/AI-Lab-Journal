# ADR 0003 - AI-Lab-Journal comme hub vitrine

## Contexte

Au depart, AI-Lab-Journal etait pense comme un journal de bord du parcours IA. Avec la structuration progressive (presentations, certifications, projets WIP, ADR), le repo a depasse sa fonction initiale.

Besoin actuel : un point d'entree unique pour qui veut savoir qui est Peter, ce qu'il fait, et ou trouver les informations.

## Decision

AI-Lab-Journal devient le **hub vitrine personnel** de Peter-Ufens :

- presentation personnelle dans le README.
- index des projets (WIP, Released, Prives a basculer).
- index des presentations Gamma.
- progression certifications.
- conventions reutilisables pour les futurs projets (`docs/conventions-projets.md`).

Pas de creation d'un repo profil separe (`Peter-Ufens/Peter-Ufens`) : un seul hub clair plutot que deux endroits a maintenir.

## Consequences

- Lecture immediate du portfolio en 1 URL : `github.com/Peter-Ufens/AI-Lab-Journal`.
- Le README devient le document le plus visible, donc discipline d'edition requise.
- Les futurs repos publics (banques vectorielles, etc.) reutilisent les conventions definies dans `docs/conventions-projets.md`.
- Si demain Peter veut un repo profil minimal en plus, il pourra le faire sans casser ce hub.
