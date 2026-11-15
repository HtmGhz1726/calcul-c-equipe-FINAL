# TP Git et GitHub — HAITAM ELGHAZI

## Informations sur l'étudiant

- **Nom :** HAITAM ELGHAZI
- **Établissement :** École Nationale des Sciences Appliquées (ENSA) de Khouribga
- **Formation :** 1re année cycle ingénieur
- **Module :** Introduction à l'ingénierie digitale (IID)
- **Compte GitHub principal :** [HtmGhz1726](https://github.com/HtmGhz1726)
- **Adresse e-mail associée à l'identité Git principale :** htmmirror@gmail.com

## Dépôts réalisés

| Exercice | Dépôt | Rôle |
|---|---|---|
| 1 | [calcul-c](https://github.com/HtmGhz1726/calcul-c) | Propriétaire du dépôt (compte `HtmGhz1726`) |
| 2 | [calcul-c-equipe-FINAL](https://github.com/HtmGhz1726/calcul-c-equipe-FINAL) | Propriétaire : étudiant A (`HtmGhz1726`) ; collaborateur : étudiant B (`HtmGhz`) |

## Organisation du travail collaboratif

Le dépôt `calcul-c-equipe-FINAL` est hébergé sur le compte principal `HtmGhz1726`. Pour réaliser le travail collaboratif, le propriétaire a ajouté comme collaborateur le second compte GitHub de l'étudiant : **`HtmGhz`**. Les deux comptes appartiennent au même étudiant, HAITAM ELGHAZI.

| Rôle | Compte GitHub | Adresse e-mail utilisée pour Git | Dossier local |
|---|---|---|---|
| Étudiant A — propriétaire | `HtmGhz1726` | `htmmirror@gmail.com` | `dossier-A` |
| Étudiant B — collaborateur (mon second compte) | [`HtmGhz`](https://github.com/HtmGhz) | `elghazihaitam2006@gmail.com` | `dossier-B` |

Le compte `HtmGhz` est donc un compte distinct du compte propriétaire `HtmGhz1726`. Il dispose de son propre clone dans `dossier-B` et d'une identité Git configurée localement avec le nom `projet-B` et l'adresse `elghazihaitam2006@gmail.com`.

## Pull request fusionnée

La pull request correspondant à l'ajout de la fonction de produit a été fusionnée :

[Pull request n° 1 — ajout de produit](https://github.com/HtmGhz1726/calcul-c-equipe-FINAL/pull/1)

## Bilan des commandes

### `git status`

```text
On branch main
Your branch is up to date with 'origin/main'.
nothing to commit, working tree clean
```

### `git remote -v`

```text
origin  https://github.com/HtmGhz1726/calcul-c-equipe-FINAL.git (fetch)
origin  https://github.com/HtmGhz1726/calcul-c-equipe-FINAL.git (push)
```

### `git log --oneline --graph --all`

```text
*   bc55bcd resolution finale apres correction du conflit
|\
| * 6293e45 modification finale pour apporter un conflit
|/
* acd14fb modif conflit
* 1a4c21e modifl
*   785aaa2 Merge branch 'feature/moyenne'
|\
| * d11e948 ajout de la moyenne
*   39aeb28 Merge pull request #1 from HtmGhz1726/feature/produit
|\
| * 2adc6d8 ajout de produit
|/
* 8d517ae initialisation du projet
* a12c111 Initial commit
```
