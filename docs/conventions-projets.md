# Conventions projets

Gabarit minimal applique a chaque nouveau repo public Peter-Ufens.

## Structure recommandee

- `README.md` : vitrine du repo (sections obligatoires ci-dessous).
- `LICENSE` : MIT par defaut sauf raison contraire documentee.
- `.gitignore` : Node, Python, .env, secrets, build.
- `.env.example` : variables d'environnement attendues, sans secret reel.
- `docs/` : documentation technique. `docs/adr/` si decisions structurantes.
- `src/` : code source (ou repertoire equivalent selon stack).

## README minimum

Sections obligatoires dans le README de chaque repo :

1. Titre + 1 ligne de description.
2. Statut : `proof-of-concept`, `alpha`, `beta`, `stable`.
3. Public vise : tech, metier, ou mixte.
4. Pre-requis : runtimes, services, comptes API.
5. Installation : 3 a 5 lignes maximum.
6. Usage : 1 exemple concret.
7. Architecture : 1 schema ou paragraphe court.
8. Securite et limites assumees : ce que le projet ne fait PAS.
9. Licence.

## Branches et commits

- `main` : protegee, pas de commit direct.
- Prefixes de branches : `feat/`, `fix/`, `docs/`, `chore/`, `refactor/`, `test/`.
- Conventional Commits : `type(scope): description`.
- Une PR = un sujet.

## Securite avant publication

Avant de basculer un repo prive en public, verifier :

- Aucun secret dans le code (.env, cles API, tokens).
- Aucun secret dans l'historique git (audit `trufflehog` ou `gitleaks`).
- Config git locale en noreply (`269768127+Peter-Ufens@users.noreply.github.com`).
- Relecture manuelle de chaque fichier source pour contenu sensible : system prompts, donnees personnelles, references a des projets prives qui ne doivent pas fuir.

## Statut publication dans le hub

Toute creation d'un nouveau repo doit etre listee dans `AI-Lab-Journal/README.md` section "Statut publication des projets" avec sa visibilite (Public ou Prive).

## Nommage des repos

- Pas de `-v1`, `-v2`, `-old` dans le nom : versionnage via tags git (`v1.0.0`).
- Kebab-case lowercase.
- Nom court, descriptif, sans acronyme obscur.
