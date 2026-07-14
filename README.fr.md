<p align="center">
  <img src="./assets/previews/idle.gif" width="168" alt="Animation de veille de Joi">
</p>

<h1 align="center">Joi</h1>

<p align="center">
  <strong>Un compagnon de bureau Codex en pixel art, non officiel et non commercial, inspiré de Joi, streameuse virtuelle de VirtuaReal.</strong>
</p>

<p align="center">
  <a href="./README.en.md">English</a> ·
  <a href="./README.md">简体中文</a> ·
  <a href="./README.ja.md">日本語</a> ·
  <a href="./README.ko.md">한국어</a> ·
  <strong>Français</strong>
</p>

<p align="center">
  <img alt="ChatGPT Codex" src="https://img.shields.io/badge/ChatGPT-Codex-10A37F?style=flat-square&logo=openai&logoColor=white">
  <img alt="GPT5.6 Sol Ultra" src="https://img.shields.io/badge/GPT5.6-Sol%20Ultra-6D4AFF?style=flat-square&logo=openai&logoColor=white">
  <a href="https://space.bilibili.com/61639371"><img alt="Joi sur Bilibili" src="https://img.shields.io/badge/Bilibili-Joi-00A1D6?style=flat-square&logo=bilibili&logoColor=white"></a>
</p>

<p align="center">
  <img alt="Codex Pet v2" src="https://img.shields.io/badge/Codex%20Pet-v2-8B5CF6?style=flat-square">
  <img alt="Atlas 1536 par 2288" src="https://img.shields.io/badge/atlas-1536%C3%972288-475569?style=flat-square">
  <a href="./LICENSE"><img alt="Licence MIT" src="https://img.shields.io/badge/code-MIT-3DA639?style=flat-square"></a>
  <a href="./LICENSE-ASSETS.md"><img alt="CC BY-NC-SA 4.0" src="https://img.shields.io/badge/assets-CC%20BY--NC--SA%204.0-EF9421?style=flat-square"></a>
  <a href="https://github.com/tpmoonchefryan/joi-channel-codex-hatch-pet/releases/latest"><img alt="GitHub Release v1.0.1" src="https://img.shields.io/badge/release-v1.0.1-2DA44E?style=flat-square&logo=github"></a>
</p>

<p align="center">
  <a href="#overview">Présentation</a> ·
  <a href="#actions">Actions</a> ·
  <a href="#specification">Spécifications</a> ·
  <a href="#installation">Installation</a> ·
  <a href="#license">Licence</a>
</p>

---

<a id="overview"></a>

## Présentation

Joi est une streameuse virtuelle active sur la plateforme vidéo chinoise Bilibili et affiliée au groupe d’artistes virtuels VirtuaReal.

Elle aime le pixel art, le cyberpunk et le film *Blade Runner*. Elle n’aime pas le sport. Son talent particulier est de manger une orange entière en une seule bouchée, et elle considère l’orange comme le fruit le plus parfait. L’orange `🍊` est ainsi devenue son emoji de fait, sans être officielle. Suivez le [profil Bilibili de Joi_Channel](https://space.bilibili.com/61639371).

Ce dépôt est un projet de fans Codex Pet v2 indépendant et non officiel. Le code, la configuration et le texte de la documentation utilisent la licence MIT ; les contributions visuelles et animées originales utilisent CC BY-NC-SA 4.0.

| Codex Pet | Actions standard | Directions du regard | Cellule |
| :---: | :---: | :---: | :---: |
| `v2` | `9` | `16` | `192×208` |

> [!IMPORTANT]
> **Œuvre de fans non officielle.** Ce projet n’est ni affilié à, ni autorisé par, ni réalisé en coopération avec, ni sponsorisé par, ni approuvé par Joi, VirtuaReal, Bilibili ou tout autre ayant droit concerné. Les droits relatifs au nom, à l’apparence et à l’univers du personnage, ainsi qu’aux marques associées, appartiennent à leurs titulaires légitimes respectifs.

<a id="actions"></a>

## Aperçu des actions

<table>
  <tr>
    <td align="center" width="33%">
      <img src="./assets/previews/idle.gif" width="120" alt="Animation idle de veille"><br>
      <strong>Veille</strong><br><code>idle</code>
    </td>
    <td align="center" width="33%">
      <img src="./assets/previews/running-right.gif" width="120" alt="Animation running-right vers la droite"><br>
      <strong>Déplacement à droite</strong><br><code>running-right</code>
    </td>
    <td align="center" width="33%">
      <img src="./assets/previews/running-left.gif" width="120" alt="Animation running-left vers la gauche"><br>
      <strong>Déplacement à gauche</strong><br><code>running-left</code>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="./assets/previews/waving.gif" width="120" alt="Animation waving de salutation"><br>
      <strong>Salutation</strong><br><code>waving</code>
    </td>
    <td align="center">
      <img src="./assets/previews/jumping.gif" width="120" alt="Animation jumping de saut"><br>
      <strong>Saut</strong><br><code>jumping</code>
    </td>
    <td align="center">
      <img src="./assets/previews/failed.gif" width="120" alt="Animation failed de retour d’échec"><br>
      <strong>Retour d’échec</strong><br><code>failed</code>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="./assets/previews/waiting.gif" width="120" alt="Animation waiting en attente d’une saisie"><br>
      <strong>Attente d’une saisie</strong><br><code>waiting</code>
    </td>
    <td align="center">
      <img src="./assets/previews/running.gif" width="120" alt="Animation running d’exécution de tâche"><br>
      <strong>Exécution de tâche</strong><br><code>running</code>
    </td>
    <td align="center">
      <img src="./assets/previews/review.gif" width="120" alt="Animation review de vérification du résultat"><br>
      <strong>Vérification du résultat</strong><br><code>review</code>
    </td>
  </tr>
</table>

<details>
<summary><strong>Afficher la vue d’ensemble complète des actions 8×11</strong></summary>

<p align="center">
  <img src="./assets/contact-sheet.png" width="720" alt="Vue d’ensemble complète des actions de Joi">
</p>

</details>

<details>
<summary><strong>Afficher le nombre d’images, le rythme et le détail des lignes du protocole</strong></summary>

| Ligne | État | Images et rythme | Comportement |
| ---: | --- | --- | --- |
| 0 | `idle` veille | 6 images ; `280 / 110 / 110 / 140 / 140 / 320 ms` | Une boucle discrète mêlant respiration, clignement des yeux et léger déplacement du poids, utilisée comme état par défaut. |
| 1 | `running-right` déplacement à droite | 8 images ; environ `120 ms` pour chacune des sept premières, puis `220 ms` | Un cycle de déplacement vers la droite, avec une démarche alternée et des mouvements secondaires des cheveux et des vêtements. |
| 2 | `running-left` déplacement à gauche | 8 images ; environ `120 ms` pour chacune des sept premières, puis `220 ms` | Un cycle de déplacement vers la gauche, avec une démarche alternée et des mouvements secondaires des cheveux et des vêtements. |
| 3 | `waving` salutation | 4 images ; environ `140 ms` pour chacune des trois premières, puis `280 ms` | Une courte salutation durant laquelle Joi lève une main avant de reprendre sa posture debout. |
| 4 | `jumping` saut | 5 images ; environ `140 ms` pour chacune des quatre premières, puis `280 ms` | Une séquence de saut comprenant la préparation, le décollage, le sommet, la descente et la réception. |
| 5 | `failed` retour d’échec | 8 images ; environ `140 ms` pour chacune des sept premières, puis `240 ms` | Une réaction déçue utilisée pour signaler un échec, une annulation ou une tâche bloquée. |
| 6 | `waiting` attente d’une saisie | 6 images ; environ `150 ms` pour chacune des cinq premières, puis `260 ms` | Un geste d’attente utilisé lorsqu’une approbation, une aide ou une saisie utilisateur est nécessaire. |
| 7 | `running` exécution de tâche | 6 images ; environ `120 ms` pour chacune des cinq premières, puis `220 ms` | Un unique terminal de taille fixe reste suspendu indépendamment, sans attache et sans changer de silhouette ; Joi saisit dans les airs en sa direction, tandis que seules les lignes de code cyan à l’intérieur de l’écran s’actualisent, sans déploiement, repli ni clavier. |
| 8 | `review` vérification du résultat | 6 images ; environ `150 ms` pour chacune des cinq premières, puis `280 ms` | Le même terminal de taille fixe reste suspendu indépendamment, sans attache et sans changer de forme ; Joi l’examine par gestes, tandis que seule la ligne de balayage cyan se déplace à l’intérieur de l’écran. Son regard, sa tête et le haut de son corps suivent le balayage avant la reprise de la boucle. |
| 9 | `look A` du haut vers le bas à droite | 8 directions | États directionnels `000 → 022.5 → 045 → 067.5 → 090 → 112.5 → 135 → 157.5`. |
| 10 | `look B` du bas vers le haut à gauche | 8 directions | États directionnels `180 → 202.5 → 225 → 247.5 → 270 → 292.5 → 315 → 337.5`. |

</details>

<a id="specification"></a>

## Spécifications des ressources

| Élément | Valeur |
| --- | --- |
| ID du compagnon | `joi` |
| Nom affiché | `Joi` |
| Nom en anglais et dans les autres traductions | `Joi` |
| Version du sprite | `spriteVersionNumber: 2` |
| Atlas | WebP `1536×2288` sur fond transparent |
| Grille | 8 colonnes × 11 lignes |
| Cellule | `192×208` |
| Animations standard | 9 lignes |
| Directions du regard | 16 |
| Nature du projet | Œuvre de fans non officielle |
| Licence | Code/configuration/documentation : MIT ; visuels et animations originaux : CC BY-NC-SA 4.0 |
| Répertoire d’installation locale | `~/.codex/pets/joi/` |

**Fichiers des ressources :** [`pet.json`](./pet/pet.json) · [`spritesheet.webp`](./pet/spritesheet.webp) · [Paquet GitHub Release](https://github.com/tpmoonchefryan/joi-channel-codex-hatch-pet/releases/latest/download/joi-pet.zip) · [Licence MIT](./LICENSE) · [Licence des ressources](./LICENSE-ASSETS.md)

<details>
<summary><strong>Afficher la structure du dépôt et les conventions de nommage</strong></summary>

```text
joi-channel-codex-hatch-pet/
├── README.md
├── README.en.md
├── README.ja.md
├── README.ko.md
├── README.fr.md
├── LICENSE
├── LICENSE-ASSETS.md
├── THIRD_PARTY_NOTICES.md
├── pet/
│   ├── pet.json
│   └── spritesheet.webp
└── assets/
    ├── contact-sheet.png
    └── previews/
```

- Ce document français utilise `Joi`.
- Les traductions anglaise, japonaise et coréenne utilisent également `Joi`.
- L’identifiant du programme et du répertoire est `joi`.
- Le dépôt s’appelle `joi-channel-codex-hatch-pet`.

</details>

<a id="installation"></a>

## Installation locale

À exécuter depuis la racine du dépôt :

```bash
PET_DIR="${CODEX_HOME:-$HOME/.codex}/pets/joi"
mkdir -p "$PET_DIR"
cp pet/pet.json pet/spritesheet.webp "$PET_DIR/"
```

> [!TIP]
> Téléchargez la dernière version de `joi-pet.zip` depuis [GitHub Releases](https://github.com/tpmoonchefryan/joi-channel-codex-hatch-pet/releases/latest). Après extraction, placez ensemble `pet.json` et `spritesheet.webp` dans `~/.codex/pets/joi/` et conservez `spriteVersionNumber: 2`.

<a id="license"></a>

## Licence et droits

Ce dépôt utilise deux licences :

- le code, la configuration créée pour le projet et le texte de la documentation utilisent la [licence MIT](./LICENSE) ;
- les contributions visuelles et animées originales créées pour le projet dans `assets/` et `pet/spritesheet.webp` utilisent [CC BY-NC-SA 4.0](./LICENSE-ASSETS.md), qui impose l’attribution, l’usage non commercial et le partage dans les mêmes conditions.

> [!WARNING]
> Ces licences ne couvrent que les contributions originales que les responsables ou contributeurs sont légalement habilités à concéder. Elles n’accordent aucun droit sur le nom, l’apparence ou les éléments du personnage Joi, ni sur les noms, marques, ressources ou références de VirtuaReal, Bilibili ou de tout autre tiers.

Consultez [`THIRD_PARTY_NOTICES.md`](./THIRD_PARTY_NOTICES.md) pour les limites complètes relatives au personnage, aux marques et aux sources.

---

<p align="center">
  <sub>Projet de fans non officiel · Code MIT · Ressources originales CC BY-NC-SA 4.0</sub>
</p>
