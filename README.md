# Conventional Commits
:wave: Bienvenue sur la convention pour les commits github/gitlab. <br>
Le commit est souvent négligé auprès des jeunes développeur. <br>
Voici donc une convention pour que vous puissiez envoyer vos commits proprement.

## Commençons

Le "commit" doit être structuré comme suit :
```
<type>[champs des options] : <Description>

[option body]

[option footer]
```
## Voici donc les différents types :<br><br>
`build:` Changements qui affectent le système de compilation. (exemple: npm, broccoli, gulp ...)<br>
`ci:` Modifications de fichier et/ou scripts de configuration CI. (exemple: Travis, Circle, BrowserStack ...)<br>
`docs:` Modifications de la documentation uniquement.<br>
`new:` Une nouvelle fonctionnalité.<br>
`fix:` Correction d'un bug.<br>
`perf:` Un changement de code qui améliore les performances. <br>
`refactor:` Un changement de code qui ne corrige pas un bug et n'ajoute pas de fonctionnalité. <br>
`style:` Changements qui n'affectent pas la signification du code (exemple: espace blanc, formatage ...) <br>
`test:` Lors d'un test de commit. <br>
`security:` Lors d'une résolution de sécuritée. <br>
`performance:` Lors d'une résolution de performance (optimisation inclus). <br>
`improuvement:` Lors d'une validation d'amélioration rétro-compatible. <br>
`breaking:` Lors d'une validation d'amélioration incompatible avec les versions antérieures. <br>
`improuvement:` Lors d'une validation d'amélioration rétro-compatible. <br>
`config:` Lors d'une validation de la configuration. <br>
`release:` Pour publier le commit. <br>
`update:` Utiliser lors de la mise à jour. <br>

## A savoir
Le sujet contient une description écourté du changement:

- utiliser le présent: "changer" pas "changé" ni "changements"
- ne mettez pas la première lettre en majuscule
- pas de point (.) à la fin

## Auteur
- Augustin Ribreau - <i>Developpeur</i> - <a href="https://augustin.ribreau.co/" target="_blank">augustin.ribreau.co</a>

Voir aussi la liste des <a href="https://github.com/AugustinRibreau/Convention-Commits/blob/master/source.txt" target="_blank">sources</a> ayant été utilisé.

