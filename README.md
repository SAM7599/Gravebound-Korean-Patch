<div align="center">

# 🪦 Gravebound 한국어 패치

**Steam 『Gravebound』 비공식 팬 한글패치**

![version](https://img.shields.io/badge/patch-v1.5-orange)
![engine](https://img.shields.io/badge/Unreal_Engine-5.5-blue)
![platform](https://img.shields.io/badge/platform-Windows-lightgrey)
![language](https://img.shields.io/badge/language-한국어-brightgreen)

설치 한 번으로 메뉴 · 옵션 · 임무 · 무기 · 인게임 문구까지 한글로!

</div>

---

## ✨ 주요 특징

| 구분 | 내용 |
|---|---|
| 🗣️ **전체 한글화** | 메인 메뉴, 임무, 개조, 땜장이, 무기고, 옷장, 알림, 탈출 화면 등 |
| ⚙️ **옵션 메뉴 한글화** | 소리 · 자막 · 마우스/키보드 · 게임패드 · 그래픽 항목과 설명, 키 설정 이름 |
| 🔤 **한글 글꼴 내장** | 게임 기본 글꼴에 한글이 없어 글자가 비던 문제 해결 |
| 🎨 **글꼴 통일** | 여러 글꼴이 섞여 어지럽던 UI를 **Noto Sans KR** 하나로 통일 |
| 📖 **용어 정리** | 뜻을 알기 어렵던 용어를 알아보기 쉽게 다듬음 |
| 🔁 **설치 / 제거 한 파일로** | `Gravebound_KR_Patch.bat` 하나로 설치와 제거 모두 가능 |

### 📚 용어 정리

| 원문 | 번역 |
|---|---|
| Augmentation | **개조** |
| Directive | **임무** |
| Tinkerer | **땜장이** |
| Modifier | **추가 옵션** |
| Noob Town | **뉴비 타운** |

---

## 📥 설치 방법

1. 우측 **[Releases](../../releases)** 에서 최신 `Gravebound_KR_Patch_v1.5.zip` 을 받습니다.
2. 압축을 **완전히 풀어줍니다.** (압축 비밀번호: `0000`)
3. `Gravebound_KR_Patch.bat` 을 실행합니다.
4. 안내에 따라 `Y` → **1번 (설치)** 을 선택합니다.
5. 게임을 실행하면 한글로 표시됩니다.

> 💡 게임 폴더는 **자동으로 찾습니다.** (Steam 라이브러리, 여러 드라이브, C드라이브만 있는 PC 모두 지원)
> 못 찾으면 폴더 경로를 직접 붙여넣을 수 있어요.

> ⚠️ 영어로 보이면 Steam → Gravebound 우클릭 → **속성 → 시작 옵션** 에 `-culture=ko` 를 입력하세요.

## 🗑️ 제거 방법

`Gravebound_KR_Patch.bat` 을 다시 실행하고 **2번 (제거)** 을 선택하면 원래대로 돌아갑니다.
원본 게임 파일은 수정하지 않기 때문에 안전하게 되돌릴 수 있습니다.

---

## 🧩 설치되는 파일

게임 폴더의 `ShooterExtractor\Content\Paks\` 안에 아래 파일만 추가됩니다.

```text
pakchunk99-WindowsClient_P.pak      ← 번역 + 한글 글꼴
pakchunk98-WindowsClient_P.pak
pakchunk98-WindowsClient_P.utoc     ← 인게임 고정 문구 번역
pakchunk98-WindowsClient_P.ucas
```

---

## 🔄 게임 버전이 다를 때

패치가 만들어진 게임 버전과 설치된 게임 버전이 다르면, 설치 전에 **한 번만** 안내하고 계속할지 물어봅니다.
`Y` 를 누르면 그대로 설치됩니다. 문제가 생기면 언제든 제거할 수 있어요.

> 게임이 업데이트되면 일부 문구가 영어로 보이거나 오류가 날 수 있습니다.
> 스팀 업데이트 후에는 패치를 **다시 설치**해 주세요.

---

## 📝 변경 내역

| 버전 | 내용 |
|---|---|
| **v1.5** | 인게임 화면(무기 보너스, 목표 타이머, 세션 등) 고정 영문 문구 한글화 |
| **v1.4** | 키 설정 이름 / 구역 제목, 옵션 항목 추가 한글화 |
| **v1.3** | 옵션(설정) 메뉴 한글화, 모든 글꼴을 Noto Sans KR 하나로 통일 |
| **v1.2** | 용어 정리, 버튼 / 알림 / 탈출 화면 등 누락 문구 추가 번역 |
| **v1.1** | 한글 글꼴 추가 (글자가 빈칸으로 보이던 문제 수정) |
| **v1.0** | 최초 공개 |

---

## ❓ 자주 묻는 질문

<details>
<summary><b>일부 글자가 아직 영어예요</b></summary>

게임 안에 직접 박혀 있는 문구 중 일부는 아직 번역하지 못했습니다.
어느 화면인지 스크린샷과 함께 [Issues](../../issues) 에 남겨주세요.

</details>

<details>
<summary><b>글자가 겹치거나 잘려 보여요</b></summary>

글꼴을 하나로 통일하면서 원래보다 글자 폭이 넓어진 곳이 있을 수 있습니다.
화면 스크린샷을 [Issues](../../issues) 에 남겨주세요.

</details>

<details>
<summary><b>설치했는데 게임이 켜지지 않아요</b></summary>

`Gravebound_KR_Patch.bat` 을 실행해 **2번 (제거)** 을 누른 뒤 게임이 정상 실행되는지 확인하고, 이슈로 알려주세요.

</details>

<details>
<summary><b>백신이 파일을 막아요</b></summary>

패치 폴더를 백신 예외로 등록한 뒤 다시 시도해 주세요.

</details>

---

## ⚖️ 면책

- 본 패치는 **비공식 팬 제작물**이며 게임 개발사 및 배급사와 관련이 없습니다.
- 게임의 원본 파일은 수정하지 않으며, 번역 파일만 별도로 추가합니다.
- 사용에 따른 책임은 사용자에게 있습니다.
- 온라인 요소가 있는 게임이므로 사용 중 문제가 생기면 즉시 제거해 주세요.
