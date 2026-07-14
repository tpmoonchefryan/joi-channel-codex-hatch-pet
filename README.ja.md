<p align="center">
  <img src="./assets/previews/idle.gif" width="168" alt="Joiの待機アニメーション">
</p>

<h1 align="center">Joi</h1>

<p align="center">
  <strong>VirtuaReal 所属のバーチャルライバー Joi をモチーフにした、非公式・非商用の Codex ピクセルデスクトップペットです。</strong>
</p>

<p align="center">
  <a href="./README.en.md">English</a> ·
  <a href="./README.md">简体中文</a> ·
  <strong>日本語</strong> ·
  <a href="./README.ko.md">한국어</a> ·
  <a href="./README.fr.md">Français</a>
</p>

<p align="center">
  <img alt="ChatGPT Codex" src="https://img.shields.io/badge/ChatGPT-Codex-10A37F?style=flat-square&logo=openai&logoColor=white">
  <img alt="GPT5.6 Sol Ultra" src="https://img.shields.io/badge/GPT5.6-Sol%20Ultra-6D4AFF?style=flat-square&logo=openai&logoColor=white">
  <a href="https://space.bilibili.com/61639371"><img alt="Bilibili · Joi" src="https://img.shields.io/badge/Bilibili-Joi-00A1D6?style=flat-square&logo=bilibili&logoColor=white"></a>
</p>

<p align="center">
  <img alt="Codex Pet v2" src="https://img.shields.io/badge/Codex%20Pet-v2-8B5CF6?style=flat-square">
  <img alt="Atlas 1536 by 2288" src="https://img.shields.io/badge/atlas-1536%C3%972288-475569?style=flat-square">
  <a href="./LICENSE"><img alt="MIT License" src="https://img.shields.io/badge/code-MIT-3DA639?style=flat-square"></a>
  <a href="./LICENSE-ASSETS.md"><img alt="CC BY-NC-SA 4.0" src="https://img.shields.io/badge/assets-CC%20BY--NC--SA%204.0-EF9421?style=flat-square"></a>
  <a href="https://github.com/tpmoonchefryan/joi-channel-codex-hatch-pet/releases/latest"><img alt="GitHub Release v1.0.1" src="https://img.shields.io/badge/release-v1.0.1-2DA44E?style=flat-square&logo=github"></a>
</p>

<p align="center">
  <a href="#overview">概要</a> ·
  <a href="#actions">アクション</a> ·
  <a href="#specification">仕様</a> ·
  <a href="#installation">インストール</a> ·
  <a href="#license">ライセンス</a>
</p>

---

<a id="overview"></a>

## 概要

Joi は、中国の動画プラットフォーム Bilibili で活動し、バーチャルアーティストグループ VirtuaReal に所属するバーチャルライバーです。

ピクセルアート、サイバーパンク、映画『ブレードランナー』が好きで、運動は嫌いです。特技は「ミカンを一口で一個食べられる」ことで、ミカンを最も完璧な果物だと考えています。ミカンの「🍊」は、非公式ながら Joi を表す事実上の絵文字にもなっています。[Joi_Channel の Bilibili プロフィール](https://space.bilibili.com/61639371)もぜひご覧ください。

| Codex Pet | 標準アニメーション | 視線方向 | セル |
| :---: | :---: | :---: | :---: |
| `v2` | `9` | `16` | `192×208` |

> [!IMPORTANT]
> 本リポジトリは、Joi をモチーフにファンが独立して制作した非公式・非商用の Codex デスクトップペットであり、Joi、VirtuaReal、Bilibili またはその他の関係権利者による公式作品、提携、許諾、スポンサー提供を示すものではありません。

<a id="actions"></a>

## アクションプレビュー

<table>
  <tr>
    <td align="center" width="33%">
      <img src="./assets/previews/idle.gif" width="120" alt="idle 待機アニメーション"><br>
      <strong>待機</strong><br><code>idle</code>
    </td>
    <td align="center" width="33%">
      <img src="./assets/previews/running-right.gif" width="120" alt="running-right 右移動アニメーション"><br>
      <strong>右へ移動</strong><br><code>running-right</code>
    </td>
    <td align="center" width="33%">
      <img src="./assets/previews/running-left.gif" width="120" alt="running-left 左移動アニメーション"><br>
      <strong>左へ移動</strong><br><code>running-left</code>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="./assets/previews/waving.gif" width="120" alt="waving 手振りアニメーション"><br>
      <strong>手を振る</strong><br><code>waving</code>
    </td>
    <td align="center">
      <img src="./assets/previews/jumping.gif" width="120" alt="jumping ジャンプアニメーション"><br>
      <strong>ジャンプ</strong><br><code>jumping</code>
    </td>
    <td align="center">
      <img src="./assets/previews/failed.gif" width="120" alt="failed 失敗フィードバックアニメーション"><br>
      <strong>失敗フィードバック</strong><br><code>failed</code>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="./assets/previews/waiting.gif" width="120" alt="waiting 入力待ちアニメーション"><br>
      <strong>入力待ち</strong><br><code>waiting</code>
    </td>
    <td align="center">
      <img src="./assets/previews/running.gif" width="120" alt="running タスク実行アニメーション"><br>
      <strong>タスク実行</strong><br><code>running</code>
    </td>
    <td align="center">
      <img src="./assets/previews/review.gif" width="120" alt="review 結果レビューアニメーション"><br>
      <strong>結果レビュー</strong><br><code>review</code>
    </td>
  </tr>
</table>

<details>
<summary><strong>完全な 8×11 アクション一覧を表示</strong></summary>

<p align="center">
  <img src="./assets/contact-sheet.png" width="720" alt="Joiの全アクション一覧">
</p>

</details>

<details>
<summary><strong>フレーム数、タイミング、プロトコル行の詳細を表示</strong></summary>

| 行 | ステート | フレーム数とタイミング | 動作 |
| ---: | --- | --- | --- |
| 0 | `idle` 待機 | 6フレーム；`280 / 110 / 110 / 140 / 140 / 320 ms` | わずかな呼吸、まばたき、自然な重心移動。控えめながら静止画ではなく、デフォルト状態や動きを抑えた表示の先頭フレームに適しています。 |
| 1 | `running-right` 右へ移動 | 8フレーム；最初の7フレームは約 `120 ms`、最後は `220 ms` | 画面右を向いて進みます。交互に運ぶ足に合わせて、スカートと三つ編みがリズミカルに揺れます。 |
| 2 | `running-left` 左へ移動 | 8フレーム；最初の7フレームは約 `120 ms`、最後は `220 ms` | 画面左を向いて進みます。足取りに合わせて髪と衣装が揺れ、右移動とは異なる横顔を見せます。 |
| 3 | `waving` 手を振る | 4フレーム；最初の3フレームは約 `140 ms`、最後は `280 ms` | 自然な立ち姿から手を上げて挨拶し、滑らかに開始姿勢へ戻ります。 |
| 4 | `jumping` ジャンプ | 5フレーム；最初の4フレームは約 `140 ms`、最後は `280 ms` | 踏み込み、離地、頂点、下降、着地を順に描き、体の高さと姿勢の変化で弾む動きを表現します。 |
| 5 | `failed` 失敗フィードバック | 8フレーム；最初の7フレームは約 `140 ms`、最後は `240 ms` | 落ち込んだ表情から、はっきりとした沈み込みと体を縮める姿勢へ移り、再び作業を続けられる状態へ戻ります。失敗、キャンセル、ブロック時のフィードバックに使用します。 |
| 6 | `waiting` 入力待ち | 6フレーム；最初の5フレームは約 `150 ms`、最後は `260 ms` | 期待や問いかけを感じさせる視線と手の動きで、「承認、支援、またはユーザー入力が必要」であることを示します。通常の待機やレビュー状態とは明確に区別されます。 |
| 7 | `running` タスク実行 | 6フレーム；最初の5フレームは約 `120 ms`、最後は `220 ms` | 固定サイズの端末が身体に接続されない独立した浮遊状態と同じ外形を保ち、Joiは端末に向かって空中入力します。変化するのは画面内のシアンのコードだけで、展開・収納・キーボード化はありません。 |
| 8 | `review` 結果レビュー | 6フレーム；最初の5フレームは約 `150 ms`、最後は `280 ms` | 同じ固定サイズの端末が身体に接続されない独立した浮遊状態と外形を保ち、Joiはジェスチャーで内容を確認します。動くのは画面内のシアンのスキャンラインだけで、視線・頭・上半身が走査位置を追ってから滑らかにループへ戻ります。 |
| 9 | `look A` 上から右下 | 8方向 | `000 → 022.5 → 045 → 067.5 → 090 → 112.5 → 135 → 157.5`；上方から画面右を経て右下へ、視線が連続して移ります。 |
| 10 | `look B` 下から左上 | 8方向 | `180 → 202.5 → 225 → 247.5 → 270 → 292.5 → 315 → 337.5`；下方から画面左を経て左上へ、視線が連続して移ります。 |

</details>

<a id="specification"></a>

## アセット仕様

| 項目 | 値 |
| --- | --- |
| Pet ID | `joi` |
| この日本語版での名称 | `Joi` |
| ローカライズ | 簡体中国語版のみローカライズされた表示名を使用 |
| スプライトバージョン | `spriteVersionNumber: 2` |
| アトラス | `1536×2288` WebP、透明背景 |
| グリッド | 8列 × 11行 |
| セル | `192×208` |
| 標準アニメーション | 9行 |
| 視線方向 | 16方向 |
| 作品の位置づけ | 非公式ファン作品 |
| ライセンス | コード／設定／文書：MIT；オリジナルのビジュアルとアニメーション：CC BY-NC-SA 4.0 |
| ローカルインストール先 | `~/.codex/pets/joi/` |

**ファイル：** [`pet.json`](./pet/pet.json) · [`spritesheet.webp`](./pet/spritesheet.webp) · [GitHub Release パッケージ](https://github.com/tpmoonchefryan/joi-channel-codex-hatch-pet/releases/latest/download/joi-pet.zip) · [MIT License](./LICENSE) · [アセットライセンス](./LICENSE-ASSETS.md)

<details>
<summary><strong>リポジトリ構成と命名規約を表示</strong></summary>

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

- この日本語版では `Joi`
- English / 한국어 / Français でも `Joi`
- 簡体中国語版のみローカライズされた表示名を使用
- プログラムおよびディレクトリの識別子：`joi`
- リポジトリ名：`joi-channel-codex-hatch-pet`

</details>

<a id="installation"></a>

## ローカルインストール

リポジトリのルートディレクトリで次を実行します。

```bash
PET_DIR="${CODEX_HOME:-$HOME/.codex}/pets/joi"
mkdir -p "$PET_DIR"
cp pet/pet.json pet/spritesheet.webp "$PET_DIR/"
```

> [!TIP]
> 最新の `joi-pet.zip` は [GitHub Releases](https://github.com/tpmoonchefryan/joi-channel-codex-hatch-pet/releases/latest) からダウンロードしてください。展開後、`pet.json` と `spritesheet.webp` を一緒に `~/.codex/pets/joi/` へ配置し、`spriteVersionNumber: 2` を保持してください。

<a id="license"></a>

## ライセンスと権利

本リポジトリは次のデュアルライセンスを採用しています。

- コード、プロジェクト独自の設定、文書テキストには [MIT License](./LICENSE) を適用します。
- `assets/` と `pet/spritesheet.webp` に含まれる、プロジェクト作者が権利を有するオリジナルのビジュアルおよびアニメーションへの寄与には [CC BY-NC-SA 4.0](./LICENSE-ASSETS.md) を適用し、表示、非営利、継承を要件とします。

> [!WARNING]
> いずれのライセンスも、プロジェクト管理者または貢献者が法的に許諾できるオリジナル部分のみを対象とします。Joi の名称、キャラクターデザインや設定、VirtuaReal、Bilibili その他の第三者の名称、商標、素材、参考資料に関する権利は付与しません。

キャラクター、ブランド、資料の権利範囲については [`THIRD_PARTY_NOTICES.md`](./THIRD_PARTY_NOTICES.md) を参照してください。

---

<p align="center">
  <sub>Unofficial fan project · Code MIT · Original assets CC BY-NC-SA 4.0</sub>
</p>
