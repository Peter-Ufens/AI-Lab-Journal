# ADR 0002 - Presentations Gamma comme couche portfolio

## Contexte

Le repo doit etre lisible aussi par des profils non techniques (manager, commercial, recruteur).  
Le markdown seul ne suffit pas toujours a faire passer rapidement la valeur metier.

## Decision

Maintenir une couche visuelle Gamma:

- chaque presentation publiee est indexee dans `presentations/README.md`
- colonnes obligatoires: date, audience, use case, statut, lien
- une presentation en construction est marquee `Draft`

## Consequences

- Meilleure accessibilite pour les publics non techniques.
- Portfolio plus actionnable en contexte professionnel.
- Besoin de discipline pour garder l'index a jour.
