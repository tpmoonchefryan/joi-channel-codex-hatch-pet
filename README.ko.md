<p align="center">
  <img src="./assets/previews/idle.gif" width="168" alt="Joi 대기 애니메이션">
</p>

<h1 align="center">Joi</h1>

<p align="center">
  <strong>VirtuaReal 소속 버추얼 스트리머 Joi를 바탕으로 만든 비공식·비상업 Codex 픽셀 데스크톱 펫입니다.</strong>
</p>

<p align="center">
  <a href="./README.en.md">English</a> ·
  <a href="./README.md">简体中文</a> ·
  <a href="./README.ja.md">日本語</a> ·
  <strong>한국어</strong> ·
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
  <a href="./LICENSE.md"><img alt="비상업 라이선스" src="https://img.shields.io/badge/license-non--commercial-E11D48?style=flat-square"></a>
  <img alt="GitHub 비공개 검토" src="https://img.shields.io/badge/GitHub-private%20review-F59E0B?style=flat-square&logo=github">
</p>

<p align="center">
  <a href="#overview">개요</a> ·
  <a href="#actions">동작</a> ·
  <a href="#specification">규격</a> ·
  <a href="#installation">설치</a> ·
  <a href="#license">라이선스</a> ·
  <a href="#review">검토</a>
</p>

---

<a id="overview"></a>

## 개요

Joi는 중국 동영상 플랫폼 Bilibili에서 활동하며 버추얼 아티스트 그룹 VirtuaReal에 소속된 버추얼 스트리머입니다.

픽셀 아트와 사이버펑크, 영화 《블레이드 러너》를 좋아하고 운동은 싫어합니다. 특기는 귤 한 개를 한입에 먹는 것이며, 귤을 가장 완벽한 과일이라고 생각합니다. 귤을 뜻하는 `🍊`는 비공식적으로 Joi를 대표하는 사실상의 이모지가 되었습니다. [Joi_Channel의 Bilibili 프로필](https://space.bilibili.com/61639371)도 방문해 보세요.

| Codex Pet | 표준 애니메이션 | 시선 방향 | 셀 |
| :---: | :---: | :---: | :---: |
| `v2` | `9` | `16` | `192×208` |

> [!IMPORTANT]
> 이 저장소는 팬이 Joi를 모티브로 독립 제작한 비공식·비상업 Codex 데스크톱 펫이며, Joi, VirtuaReal, Bilibili 또는 그 밖의 관련 권리자가 제작·제휴·허가·후원한 공식 작품이 아닙니다.

<a id="actions"></a>

## 동작 미리보기

<table>
  <tr>
    <td align="center" width="33%">
      <img src="./assets/previews/idle.gif" width="120" alt="idle 대기 애니메이션"><br>
      <strong>대기</strong><br><code>idle</code>
    </td>
    <td align="center" width="33%">
      <img src="./assets/previews/running-right.gif" width="120" alt="running-right 오른쪽 이동 애니메이션"><br>
      <strong>오른쪽 이동</strong><br><code>running-right</code>
    </td>
    <td align="center" width="33%">
      <img src="./assets/previews/running-left.gif" width="120" alt="running-left 왼쪽 이동 애니메이션"><br>
      <strong>왼쪽 이동</strong><br><code>running-left</code>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="./assets/previews/waving.gif" width="120" alt="waving 손 흔들기 애니메이션"><br>
      <strong>손 흔들기</strong><br><code>waving</code>
    </td>
    <td align="center">
      <img src="./assets/previews/jumping.gif" width="120" alt="jumping 점프 애니메이션"><br>
      <strong>점프</strong><br><code>jumping</code>
    </td>
    <td align="center">
      <img src="./assets/previews/failed.gif" width="120" alt="failed 실패 피드백 애니메이션"><br>
      <strong>실패 피드백</strong><br><code>failed</code>
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="./assets/previews/waiting.gif" width="120" alt="waiting 입력 대기 애니메이션"><br>
      <strong>입력 대기</strong><br><code>waiting</code>
    </td>
    <td align="center">
      <img src="./assets/previews/running.gif" width="120" alt="running 작업 실행 애니메이션"><br>
      <strong>작업 실행</strong><br><code>running</code>
    </td>
    <td align="center">
      <img src="./assets/previews/review.gif" width="120" alt="review 결과 검토 애니메이션"><br>
      <strong>결과 검토</strong><br><code>review</code>
    </td>
  </tr>
</table>

<details>
<summary><strong>전체 8×11 동작 개요 보기</strong></summary>

<p align="center">
  <img src="./assets/contact-sheet.png" width="720" alt="Joi 전체 동작 개요">
</p>

</details>

<details>
<summary><strong>프레임 수, 타이밍 및 프로토콜 행 세부 정보 보기</strong></summary>

| 행 | 상태 | 프레임 수와 타이밍 | 동작 설명 |
| ---: | --- | --- | --- |
| 0 | `idle` 대기 | 6프레임; `280 / 110 / 110 / 140 / 140 / 320 ms` | 잔잔한 호흡, 눈 깜박임, 자연스러운 무게중심 변화를 표현합니다. 조용하지만 정지 화면은 아니며, 기본 상태와 모션 감소 설정의 첫 프레임에 적합합니다. |
| 1 | `running-right` 오른쪽 이동 | 8프레임; 앞 7프레임은 약 `120 ms`, 마지막 프레임은 `220 ms` | 화면 오른쪽을 바라보며 나아갑니다. 번갈아 내딛는 발에 맞춰 치맛자락과 땋은 머리가 리듬감 있게 흔들립니다. |
| 2 | `running-left` 왼쪽 이동 | 8프레임; 앞 7프레임은 약 `120 ms`, 마지막 프레임은 `220 ms` | 화면 왼쪽을 바라보며 나아갑니다. 발걸음에 맞춰 머리카락과 의상이 흔들리고, 오른쪽 이동과 다른 옆모습을 보여 줍니다. |
| 3 | `waving` 손 흔들기 | 4프레임; 앞 3프레임은 약 `140 ms`, 마지막 프레임은 `280 ms` | 자연스러운 선 자세에서 손을 들어 인사한 뒤 부드럽게 처음 자세로 돌아옵니다. |
| 4 | `jumping` 점프 | 5프레임; 앞 4프레임은 약 `140 ms`, 마지막 프레임은 `280 ms` | 도약 준비, 이륙, 정점, 하강, 착지를 차례로 보여 주며 몸의 높이와 자세 변화로 경쾌한 움직임을 표현합니다. |
| 5 | `failed` 실패 피드백 | 8프레임; 앞 7프레임은 약 `140 ms`, 마지막 프레임은 `240 ms` | 풀이 죽은 표정에서 뚜렷한 낙담과 움츠린 자세로 이어진 뒤 다시 작업을 계속할 수 있는 상태로 돌아옵니다. 실패, 취소, 차단 피드백에 사용합니다. |
| 6 | `waiting` 입력 대기 | 6프레임; 앞 5프레임은 약 `150 ms`, 마지막 프레임은 `260 ms` | 기대하거나 묻는 듯한 시선과 손동작으로 “승인, 도움 또는 사용자 입력이 필요함”을 표현하며, 일반 대기 및 결과 검토 상태와 명확히 구분됩니다. |
| 7 | `running` 작업 실행 | 6프레임; 앞 5프레임은 약 `120 ms`, 마지막 프레임은 `220 ms` | 여기서 `running`은 달리는 동작이 아니라 작업이 처리 중임을 뜻합니다. Joi는 허리 단말기를 중심으로 집중해서 조작하고, 생각하고, 피드백합니다. |
| 8 | `review` 결과 검토 | 6프레임; 앞 5프레임은 약 `150 ms`, 마지막 프레임은 `280 ms` | 시선, 머리 기울기, 상체의 전방 움직임, 손동작 변화로 완료된 결과를 살펴보는 모습을 표현합니다. |
| 9 | `look A` 위쪽에서 오른쪽 아래까지 | 8개 방향 | `000 → 022.5 → 045 → 067.5 → 090 → 112.5 → 135 → 157.5`; 위쪽에서 화면 오른쪽을 거쳐 오른쪽 아래로 시선이 이어집니다. |
| 10 | `look B` 아래쪽에서 왼쪽 위까지 | 8개 방향 | `180 → 202.5 → 225 → 247.5 → 270 → 292.5 → 315 → 337.5`; 아래쪽에서 화면 왼쪽을 거쳐 왼쪽 위로 시선이 이어집니다. |

</details>

<a id="specification"></a>

## 에셋 규격

| 항목 | 값 |
| --- | --- |
| Pet ID | `joi` |
| 표시 이름 | `Joi` |
| 스프라이트 버전 | `spriteVersionNumber: 2` |
| 아틀라스 | 투명 배경의 `1536×2288` WebP |
| 그리드 | 8열 × 11행 |
| 셀 | `192×208` |
| 표준 애니메이션 | 9행 |
| 시선 방향 | 16개 |
| 작품 성격 | 비공식 팬 작품 |
| 라이선스 | 비상업적 이용만 허용 |
| 로컬 설치 경로 | `~/.codex/pets/joi/` |

**파일:** [`pet.json`](./pet/pet.json) · [`spritesheet.webp`](./pet/spritesheet.webp) · [`joi-pet.zip`](./release/joi-pet.zip) · [라이선스](./LICENSE.md)

<details>
<summary><strong>저장소 구조 및 이름 규칙 보기</strong></summary>

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

- English / 日本語 / 한국어 / Français에서 사용하는 이름: `Joi`
- 프로그램 및 디렉터리 식별자: `joi`
- 저장소 이름: `joi-channel-codex-hatch-pet`

</details>

<a id="installation"></a>

## 로컬 설치

저장소 루트에서 다음 명령을 실행합니다.

```bash
PET_DIR="${CODEX_HOME:-$HOME/.codex}/pets/joi"
mkdir -p "$PET_DIR"
cp pet/pet.json pet/spritesheet.webp "$PET_DIR/"
```

> [!TIP]
> [`release/joi-pet.zip`](./release/joi-pet.zip)을 직접 사용할 수도 있습니다. `pet.json`은 `spritesheet.webp`와 같은 디렉터리에 있어야 하며, `spriteVersionNumber: 2`를 삭제하면 안 됩니다.

<a id="license"></a>

## 라이선스 및 권리

> [!WARNING]
> 이 작품은 비공식·비상업 팬 작품이며 개인의 비상업적 이용만 허용됩니다. 판매, 유료 배포, 수익화, 상업 서비스에 포함하거나 묶어 제공하는 행위, 블록체인 용도, 공식 허가나 보증을 받은 것처럼 오인하게 하는 행위는 금지됩니다.

<details>
<summary><strong>금지되는 이용 범위 요약 보기</strong></summary>

- 판매, 유료 다운로드, 유료 배포, 구독자 또는 회원 전용 제공;
- 광고, 후원, 상업 홍보 또는 그 밖의 수익화;
- 상업용 소프트웨어, 고객 프로젝트, 유료 서비스 또는 상업 제품에 포함하거나 묶어 제공하는 행위;
- NFT, 디지털 수집품, 토큰 또는 그 밖의 블록체인 용도;
- 공식 작품을 사칭하거나 Joi, VirtuaReal, Bilibili 및 그 밖의 권리자가 허가·승인·보증한 것처럼 암시하는 행위.

</details>

Joi의 이름, 캐릭터 형상과 설정, 그리고 VirtuaReal, Bilibili 및 그 밖의 제3자에 속한 이름, 상표, 자료 등의 권리는 각 적법한 권리자에게 유보됩니다. 이 저장소의 라이선스는 그러한 제3자 권리를 부여하지 않습니다. 자세한 내용은 [`LICENSE.md`](./LICENSE.md)와 [`THIRD_PARTY_NOTICES.md`](./THIRD_PARTY_NOTICES.md)를 확인하세요.

<a id="review"></a>

## 검토 상태

> [!NOTE]
> 이 저장소는 소유자 검토를 위해 GitHub 비공개 저장소에 호스팅되어 있습니다. GitHub Release, Package 또는 공개 배포는 생성하지 않았으며, 소유자가 명시적으로 승인하기 전에는 Public으로 전환하지 않습니다.

- [x] 데스크톱 펫 에셋 및 설치 패키지 정리 완료
- [x] README 및 다국어 문서 작성 완료
- [x] GitHub 비공개 저장소에 푸시 완료
- [ ] 소유자의 공개 검토 완료
- [ ] Public 전환

---

<p align="center">
  <sub>Unofficial fan project · Non-commercial only · Private review</sub>
</p>
