# Conventional Commits
👋 Bienvenue sur la convention pour les commits github/gitlab.
Le commit est souvent négligé auprès des jeunes développeur. 
Voici donc une convention pour que vous puissiez envoyer vos commits .

## Commençons

Le "commit" doit être structuré comme suit :
```bash
<type>[champs des options] : <Description>

[option body]

[option footer]
```
#### Voici donc les structures à apprendre et à appliquer :<br><br>
`build:` Changements qui affectent le système de compilation. (exemple: npm, broccoli, gulp ...)<br>
`ci:` Modifications de fichier et/ou scripts de configuration CI. (exemple: Travis, Circle, BrowserStack ...)<br>
`docs:` Modifications de la documentation uniquement.<br>
`feat:` Une nouvelle fonctionnalité.<br>
`fix:` Correction d'un bug.<br>
`perf:` Un changement de code qui améliore les performances. <br>
`refactor:` Un changement de code qui corrige pas un bug et n'ajoute pas de fonctionnalité. <br>
`style:` Changements qui n'affectent pas la signification du code (exemple: espace blanc, formatage ...) <br>
`test:` Ajout de tests manquant ou correction de tests existants. <br>
