<p align="center">
  <img src="./assets/previews/idle.gif" width="168" alt="Joi idle animation">
</p>

<h1 align="center">Joi</h1>

<p align="center">
  <strong>An unofficial, non-commercial Codex pixel desktop pet based on Joi, a VirtuaReal virtual streamer.</strong>
</p>

<p align="center">
  <strong>English</strong> ·
  <a href="./README.md">简体中文</a> ·
  <a href="./README.ja.md">日本語</a> ·
  <a href="./README.ko.md">한국어</a> ·
  <a href="./README.fr.md">Français</a>
</p>

<p align="center">
  <img alt="ChatGPT Codex" src="https://img.shields.io/badge/ChatGPT-Codex-10A37F?style=flat-square&logo=openai&logoColor=white">
  <img alt="GPT5.6 Sol Ultra" src="https://img.shields.io/badge/GPT5.6-Sol%20Ultra-6D4AFF?style=flat-square&logo=openai&logoColor=white">
  <a href="https://space.bilibili.com/61639371"><img alt="Joi on Bilibili" src="https://img.shields.io/badge/Bilibili-Joi-00A1D6?style=flat-square&logo=bilibili&logoColor=white"></a>
</p>

<p align="center">
  <img alt="Codex Pet v2" src="https://img.shields.io/badge/Codex%20Pet-v2-8B5CF6?style=flat-square">
  <img alt="Atlas 1536 by 2288" src="https://img.shields.io/badge/atlas-1536%C3%972288-475569?style=flat-square">
  <a href="./LICENSE.md"><img alt="Non-commercial license" src="https://img.shields.io/badge/license-non--commercial-E11D48?style=flat-square"></a>
  <img alt="GitHub private review" src="https://img.shields.io/badge/GitHub-private%20review-F59E0B?style=flat-square&logo=github">
</p>

<p align="center">
  <a href="#overview">Overview</a> ·
  <a href="#actions">Actions</a> ·
  <a href="#specification">Specification</a> ·
  <a href="#installation">Installation</a> ·
  <a href="#license">License</a> ·
  <a href="#review">Review status</a>
</p>

---

<a id="overview"></a>

## Overview

Joi is a virtual streamer active on the Chinese video platform Bilibili and affiliated with the virtual-talent group VirtuaReal.

She likes pixel art, [cyberpunk](https://zh.moegirl.org.cn/%E8%B5%9B%E5%8D%9A%E6%9C%8B%E5%85%8B), and the film *Blade Runner*. She dislikes exercise. Her special talent is eating an entire orange in one bite, and she considers oranges the most perfect fruit. The orange `🍊` has also become her de facto, unofficial emoji. Follow Joi on her [Bilibili profile](https://space.bilibili.com/61639371).

This repository is an independent, unofficial Codex Pet v2 fan project for personal, non-commercial use only.

| Codex Pet | Standard actions | Gaze directions | Cell |
| :---: | :---: | :---: | :---: |
| `v2` | `9` | `16` | `192×208` |

> [!IMPORTANT]
> **Unofficial fan work.** This project is not affiliated with, authorized by, produced in cooperation with, sponsored by, or endorsed by Joi, VirtuaReal, Bilibili, or any related rights holder. Rights in the character name, likeness, settings, and related brands remain with their respective lawful owners.

<a id="actions"></a>

## Action previews

<table>
  <tr>
    <td align="center" width="33%">
      <img src="./assets/previews/idle.gif" width="120" alt="idle animation"><br>
      <strong>Idle</strong><br><code>idle</code>
    </td>
    <td align="center" width="33%">
      <img src="./assets/previews/running-right.gif" width="120" alt="running-right animation"><br>
      <strong>Move right</strong><br><code>running-right</code>
    </td>
    <td align="center" width="33%">
      <img src="./assets/previews/running-left.gif" width="120" alt="running-left animation"><br>
      <strong>Move left</strong><br><code>running-left</code>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="./assets/previews/waving.gif" width="120" alt="waving animation"><br>
      <strong>Wave</strong><br><code>waving</code>
    </td>
    <td align="center">
      <img src="./assets/previews/jumping.gif" width="120" alt="jumping animation"><br>
      <strong>Jump</strong><br><code>jumping</code>
    </td>
    <td align="center">
      <img src="./assets/previews/failed.gif" width="120" alt="failed feedback animation"><br>
      <strong>Failure feedback</strong><br><code>failed</code>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="./assets/previews/waiting.gif" width="120" alt="waiting for input animation"><br>
      <strong>Wait for input</strong><br><code>waiting</code>
    </td>
    <td align="center">
      <img src="./assets/previews/running.gif" width="120" alt="active task animation"><br>
      <strong>Run task</strong><br><code>running</code>
    </td>
    <td align="center">
      <img src="./assets/previews/review.gif" width="120" alt="review result animation"><br>
      <strong>Review result</strong><br><code>review</code>
    </td>
  </tr>
</table>

<details>
<summary><strong>View the complete 8×11 action overview</strong></summary>

<p align="center">
  <img src="./assets/contact-sheet.png" width="720" alt="Complete Joi action overview">
</p>

</details>

<details>
<summary><strong>View frame counts, timing, and protocol-row details</strong></summary>

| Row | State | Frames and timing | Behavior |
| ---: | --- | --- | --- |
| 0 | `idle` | 6 frames; `280 / 110 / 110 / 140 / 140 / 320 ms` | A quiet loop of breathing, blinking, and subtle weight shifts used as the default state. |
| 1 | `running-right` | 8 frames; about `120 ms` for each of the first seven, then `220 ms` | A rightward movement cycle with an alternating gait and secondary motion in the hair and clothing. |
| 2 | `running-left` | 8 frames; about `120 ms` for each of the first seven, then `220 ms` | A leftward movement cycle with an alternating gait and secondary motion in the hair and clothing. |
| 3 | `waving` | 4 frames; about `140 ms` for each of the first three, then `280 ms` | A short greeting in which Joi raises one hand and returns to her standing pose. |
| 4 | `jumping` | 5 frames; about `140 ms` for each of the first four, then `280 ms` | A jump sequence covering preparation, takeoff, apex, descent, and landing. |
| 5 | `failed` | 8 frames; about `140 ms` for each of the first seven, then `240 ms` | A disappointed reaction used for failure, cancellation, or blocked-task feedback. |
| 6 | `waiting` | 6 frames; about `150 ms` for each of the first five, then `260 ms` | An expectant gesture used when approval, help, or user input is needed. |
| 7 | `running` | 6 frames; about `120 ms` for each of the first five, then `220 ms` | The active-task state, showing Joi interacting with the terminal at her waist. |
| 8 | `review` | 6 frames; about `150 ms` for each of the first five, then `280 ms` | A focused inspection pose used when reviewing a completed result. |
| 9 | `look A` up to lower-right | 8 directions | Direction states `000 → 022.5 → 045 → 067.5 → 090 → 112.5 → 135 → 157.5`. |
| 10 | `look B` down to upper-left | 8 directions | Direction states `180 → 202.5 → 225 → 247.5 → 270 → 292.5 → 315 → 337.5`. |

</details>

<a id="specification"></a>

## Asset specification

| Item | Value |
| --- | --- |
| Pet ID | `joi` |
| Display name | `Joi` |
| English and other translated-language name | `Joi` |
| Sprite version | `spriteVersionNumber: 2` |
| Atlas | `1536×2288` WebP with a transparent background |
| Grid | 8 columns × 11 rows |
| Cell | `192×208` |
| Standard animations | 9 rows |
| Gaze directions | 16 |
| Project type | Unofficial fan work |
| License | Non-commercial use only |
| Local installation directory | `~/.codex/pets/joi/` |

**Asset files:** [`pet.json`](./pet/pet.json) · [`spritesheet.webp`](./pet/spritesheet.webp) · [`joi-pet.zip`](./release/joi-pet.zip) · [License](./LICENSE.md)

<details>
<summary><strong>View repository structure and naming conventions</strong></summary>

```text
joi-channel-codex-hatch-pet/
├── README.md
├── README.en.md
├── README.ja.md
├── README.ko.md
├── README.fr.md
├── LICENSE.md
├── THIRD_PARTY_NOTICES.md
├── pet/
│   ├── pet.json
│   └── spritesheet.webp
├── assets/
│   ├── contact-sheet.png
│   └── previews/
└── release/
    ├── joi-pet.zip
    └── joi-pet.json
```

- This English document uses `Joi`.
- The Japanese, Korean, and French translations also use `Joi`.
- The program and directory identifier is `joi`.
- The repository name is `joi-channel-codex-hatch-pet`.

</details>

<a id="installation"></a>

## Local installation

Run from the repository root:

```bash
PET_DIR="${CODEX_HOME:-$HOME/.codex}/pets/joi"
mkdir -p "$PET_DIR"
cp pet/pet.json pet/spritesheet.webp "$PET_DIR/"
```

> [!TIP]
> You can also use [`release/joi-pet.zip`](./release/joi-pet.zip) directly. `pet.json` must be in the same directory as `spritesheet.webp`, and `spriteVersionNumber: 2` must be retained.

<a id="license"></a>

## License and rights notice

> [!WARNING]
> This is an unofficial fan project for personal, non-commercial use only. Sales, paid distribution, advertising or sponsorship monetization, commercial bundling, NFT or blockchain use, and any implication of official authorization or endorsement are prohibited.

<details>
<summary><strong>View a summary of prohibited uses</strong></summary>

- Sales, paid downloads, paid distribution, subscriptions, or members-only access;
- advertising, sponsorship, commercial promotion, product placement, or other revenue-driven traffic;
- commercial software, client projects, paid services, or bundling with commercial products;
- NFTs, digital collectibles, tokens, or other blockchain assets;
- impersonating an official work or implying authorization, approval, or endorsement by Joi, VirtuaReal, Bilibili, or any other rights holder.

</details>

The license covers only original contributions that the project maintainers or contributors are legally entitled to license. See [`LICENSE.md`](./LICENSE.md) for the complete terms and [`THIRD_PARTY_NOTICES.md`](./THIRD_PARTY_NOTICES.md) for boundaries concerning the character, brands, and source material.

<a id="review"></a>

## Review status

> [!NOTE]
> This repository is hosted as a private GitHub repository for owner review only. No GitHub Release, Package, or public deployment has been created. It will not be made public until the owner explicitly approves publication.

- [x] Desktop-pet assets and installable package prepared
- [x] README and translated documentation completed
- [x] Pushed to a private GitHub repository
- [ ] Owner completes the public-release review
- [ ] Repository visibility changes to Public

---

<p align="center">
  <sub>Unofficial fan project · Non-commercial only · Private review</sub>
</p>
