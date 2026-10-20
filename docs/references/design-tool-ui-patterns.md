# 레퍼런스: 디자인 툴 공통 UI (어포던스 조사 v0.1)

> 피그마, 일러스트레이터(데스크톱·iPad), 캔바, 프로크리에이트, 어피니티(iPad)에서 **공통으로 쓰는 UI**를 정리했다. 2026년 10월 조사.
> 목적: 사용자가 이미 익힌 UI는 **그대로 따르고**, 캐로킷만의 아이덴티티는 [디자인 원칙](../design-principles.md)의 시그니처에만 둔다.
> 정확도: ✅ 공식 도움말에서 확인 / 🟡 여러 2차 자료가 일치하거나 일반적으로 알려진 내용 / ⚠️ 자료끼리 다르거나 확인 못함. 앱은 수시로 바뀌므로 화면을 그리기 전에 직접 열어서 확인한다.

---

## 0. 결론

1. **"도구는 왼쪽, 속성은 오른쪽"** 은 거의 모든 디자인 툴이 같다. 캐로킷 기본안(명세서 18장)도 이미 이 배치다.
2. 아이콘의 **뜻(은유)** 은 툴마다 거의 같다: 화살표 = 선택, T = 텍스트, 펜촉 = 펜, 눈 = 숨기기, 자물쇠 = 잠금. 이 뜻은 바꾸지 않는다. 바꿀 수 있는 건 **그리는 스타일**(선 두께, 모서리)뿐이다.
3. 단축키는 툴마다 조금 다르다. 캐로킷 명세서(13장)는 **피그마 기준**으로 맞춰져 있고, 그대로 유지한다.
4. iPad 툴은 키보드 대신 **화면 위 보조 키(Shift, Alt 역할)** 와 **손가락 탭 제스처**를 쓴다. 캐로킷도 같은 방식이 필요하다 (6장).

---

## 1. 화면 배치

| 툴 | 도구 | 속성 | 레이어 | 페이지·장 | 정확도 |
|---|---|---|---|---|---|
| **피그마** (UI3, 2024~) | **아래 가운데** 떠 있는 도구 바 | 오른쪽 | 왼쪽 (페이지와 함께) | 왼쪽 패널 위쪽 | ✅ |
| **일러스트레이터** (데스크톱) | 왼쪽 세로 | 오른쪽 패널 | 오른쪽 패널 | 아트보드 패널 | 🟡 |
| **일러스트레이터 iPad** | 왼쪽 세로 (길게 누르거나 두 번 탭하면 숨은 도구) | 오른쪽 작업 표시줄 | 오른쪽 작업 표시줄 | | ✅ |
| **캔바** | 왼쪽 사이드 패널 (템플릿, 요소, 텍스트, 업로드) | **위쪽 상황별 툴바** + 선택한 요소 옆 떠 있는 툴바 | 위치 메뉴 안 | **아래** (추가, 복제, 순서, 그리드 보기) | ✅ (아래 그리드 보기는 🟡) |
| **프로크리에이트** | **위 오른쪽** (브러쉬, 문지르기, 지우개, 레이어, 색) | 왼쪽 사이드바 (크기·불투명도 슬라이더) | 위 오른쪽 아이콘 → 펼침 | | ✅ |
| **어피니티 iPad** | 왼쪽 | 오른쪽 스튜디오 패널 | 오른쪽 스튜디오 패널 | | 🟡 |

**공통점**
- 도구는 **왼쪽**(또는 아래), 선택한 것의 속성은 **오른쪽**
- 레이어는 툴마다 왼쪽·오른쪽이 갈린다. 디자인 툴(피그마)은 왼쪽, 그림 툴(프로크리에이트, 어피니티)은 오른쪽
- 여러 장을 다루는 툴(캔바)은 장 목록을 **아래**에 둔다
- 패널을 숨기고 캔버스만 보는 기능이 있다: 피그마 ⌘\ ✅, 프로크리에이트 네 손가락 탭 🟡

**iPadOS 규칙 (애플 가이드)**
- iPad 툴바는 **화면 위쪽**에 둔다. 맨 앞(왼쪽)에는 뒤로 가기와 사이드바 열기·닫기, 그다음에 문서 제목 ✅
- 누르는 영역은 최소 **44×44pt** 🟡 (2차 자료 일치, 애플 원문은 직접 확인 필요)

**캐로킷 기본안과 비교**

| 영역 | 캐로킷 기본안 (명세서 18장) | 관례와 비교 |
|---|---|---|
| 상단 바 | 뒤로, 프로젝트 이름, 실행 취소, 보기 모드, 미리보기, 내보내기 | ✅ iPadOS 규칙과 같음 |
| 도구 | 왼쪽 도구 바 | ✅ 관례와 같음 |
| 속성 | 오른쪽 패널 | ✅ 관례와 같음 |
| 레이어 | 오른쪽 패널의 탭 | ✅ 일러스트레이터·어피니티 방식 |
| 슬라이드 | 아래 슬라이드 바 | ✅ 캔바 방식 |
| 원고 | 왼쪽 패널 (도구 바 옆) | 캐로킷만의 패널. 도구 바와 붙어 있어 **왼쪽이 붐비지 않게** 디자인할 때 확인 필요 |

---

## 2. 도구 아이콘과 단축키

| 도구 | 아이콘 은유 (공통) | 피그마 | 일러스트레이터 | 캐로킷 (명세서 13장) |
|---|---|---|---|---|
| 선택 | 검은 화살표 | V ✅ | V ✅ | V |
| 점 선택 (직접 선택) | 흰 화살표 | 두 번 클릭 | A ✅ | 두 번 탭 (SH-07) |
| 텍스트 | T | T ✅ | T ✅ | T |
| 사각형 | 사각형 | R ✅ | M 🟡 | R |
| 원 | 원 | O ✅ | L 🟡 | O |
| 선 | 대각선 | L 🟡 | \ 🟡 | L |
| 펜 | 펜촉 | P ✅ | P ✅ | P |
| 크기 조절 도구 | 모서리 화살표 | K ✅ | S 🟡 | (없음, 핸들로 처리) |
| 화면 이동 | 손 | H, 스페이스 🟡 | H, 스페이스 🟡 | 스페이스 + 드래그 |
| 스포이드 | 스포이드 | I 🟡 | I 🟡 | I |
| 브러쉬 | 붓 | | B 🟡 | B |
| 지우개 | 지우개 | | ⇧E 🟡 | E |

- **겹치는 부분(V, T, P)은 모든 툴이 같다.** 갈리는 부분(사각형, 원)은 피그마를 따른다. 캔바·인스타 세대 디자이너는 피그마에 더 익숙하기 때문 (추정)
- 아이콘은 위의 **은유를 바꾸지 않는다.** 예: 선택을 손가락 모양으로 바꾸면 안 됨
- 애플 기본 아이콘 세트 **SF Symbols**에 연필, 지우개, 올가미, 눈, 자물쇠, 텍스트 같은 기본 아이콘이 있다. iPad 앱에서 쓰는 것이 허용되고 시스템과 통일감이 있다. → **기본 아이콘은 SF Symbols 기반, 캐러셀 전용 아이콘(슬라이드 나누기, 이어 보기, 원고 등)만 직접 그리기**를 추천 🟡 (아이콘별 이름과 라이선스 조건은 개발 때 확인)

---

## 3. 캔버스 위 조작

| 동작 | 관례 | 정확도 |
|---|---|---|
| 선택 표시 | 파란 테두리 + 모서리·변 가운데 **흰 네모 핸들 8개** | 🟡 |
| 회전 | 모서리 핸들 **조금 바깥**에서 끌기 | 🟡 |
| 크기 표시 | 선택 박스 아래 **가로×세로 숫자 라벨** | 🟡 |
| 비율 고정 | Shift 누르고 크기 조절 | 🟡 |
| 가운데 기준 | Alt(Option) 누르고 크기 조절 | 🟡 |
| 복제하며 이동 | Alt(Option) 누르고 끌기 | 🟡 |
| 간격 측정 | 피그마: 선택 후 Option 누르고 다른 오브젝트 위에 올리면 **빨간 선**과 거리 숫자 | ✅ |
| 스마트 가이드 | 끄는 동안 다른 오브젝트·가운데에 맞으면 선이 나타나고 붙음 | 🟡 |
| 안으로 들어가기 | 두 번 클릭(탭) = 그룹 안 선택, 텍스트 편집, 점 편집 | 🟡 |
| 빈 곳 탭 | 선택 해제 | 🟡 |

- 캐로킷의 OB, AL 기능이 이미 이 관례를 따른다.
- **색**: 선택 = 파랑, 측정·가이드 = 빨강/분홍 계열이 흔하다. 캐로킷 강조색을 정할 때 **선택 색과 겹치지 않는지** 확인한다.

---

## 4. 패널

### 속성 패널 (위에서 아래 순서)

피그마 기준으로 흔한 순서 🟡:

1. 위치와 크기: X, Y, W, H, 회전, 모서리 둥글기
2. 레이아웃 (오토 레이아웃 등)
3. 모양: 불투명도, 블렌드 모드
4. 채우기 (+ 버튼으로 여러 겹)
5. 테두리
6. 효과 (그림자, 흐림)
7. 내보내기

- 숫자 칸: **라벨을 좌우로 끌면 값이 바뀜** (피그마), 직접 입력, 위아래 화살표 키 🟡 → 캐로킷 OB-07에 반영됨
- **선택한 종류에 따라 칸이 바뀐다** (텍스트면 글꼴 칸, 이미지면 보정 칸): 피그마, 캔바, 일러스트레이터 iPad 공통 ✅

### 레이어 패널

| 관례 | 정확도 |
|---|---|
| **목록 위쪽이 화면 앞** | 🟡 |
| 끌어서 순서 바꾸기 | 🟡 |
| **눈** = 숨기기, **자물쇠** = 잠금. 피그마는 마우스를 올렸을 때 나타남 | ✅ (자물쇠) |
| 눈·자물쇠를 끌어서 여러 개 한 번에 | 🟡 |
| 그룹은 들여쓰기 + 접기 화살표 | 🟡 |
| 종류 아이콘 (텍스트 T, 이미지, 그룹 등) | 🟡 |
| 프로크리에이트: 탭하면 선택(파란색), **두 레이어를 집어 오므리면 합치기** | ✅ |

- iPad에는 "마우스 올리기"가 없다. → 눈·자물쇠는 **항상 보이게** 하거나, 왼쪽으로 밀면 나타나게 한다 (펜슬 호버 지원 기기는 호버로도)

### 색 선택기

공통 구성 🟡: **채도·밝기 사각형 + 색상 막대 + 불투명도 막대 + HEX 입력 + 스포이드 + 저장한 색**

- 아이패드 기본 색 선택 창(그리드, 스펙트럼, 슬라이더, 스포이드)이 있다. 사용자에게 익숙하지만 캐로킷 팔레트·시리즈 키트(CL)와 연결하려면 **직접 만드는 것**이 낫다 🟡

### 정렬

공통 아이콘 6개 + 간격 🟡: 왼쪽 / 가로 가운데 / 오른쪽, 위 / 세로 가운데 / 아래, 가로 간격 균등 / 세로 간격 균등. **막대와 기준선** 그림으로 표현 → 캐로킷 AL과 같음

---

## 5. 상황별 툴바

- **캔바**: 선택하면 위쪽 툴바가 그 요소용으로 바뀌고, 요소 옆에도 작은 떠 있는 툴바(복사, 삭제 등) ✅
- **일러스트레이터 iPad**: 속성은 오른쪽 작업 표시줄에서 열기 ✅
- **아이패드 기본**: 텍스트를 길게 누르면 뜨는 편집 메뉴(복사, 붙여넣기)

→ 캐로킷: 펜슬로 쓰기 좋게 **선택한 오브젝트 옆에 작은 떠 있는 메뉴**(복제, 삭제, 잠금, 순서)를 두고, 자세한 설정은 오른쪽 패널. 길게 누르기 메뉴(명세서 OB, LY)와 같은 항목으로 맞춘다.

---

## 6. iPad 전용 관례 (키보드 없이)

| 관례 | 툴 | 정확도 |
|---|---|---|
| **화면 위 보조 키**: 누르고 있는 동안 Shift·Alt처럼 동작 (비율 고정, 복제 등) | 일러스트레이터 iPad "터치 단축키", 어피니티 "명령 컨트롤러" | ✅ (일러스트레이터) / 🟡 (어피니티) |
| 두 손가락 탭 = 실행 취소, 세 손가락 탭 = 다시 실행 | 프로크리에이트, 일러스트레이터 iPad | ✅ (프로크리에이트) / 🟡 (일러스트레이터) |
| 두 손가락 오므리기·펼치기 = 확대·축소, 두 손가락 끌기 = 이동 | 거의 모든 툴 | 🟡 |
| 길게 누르기 = 스포이드 | 프로크리에이트 | 🟡 |
| 사이드바 왼쪽 ↔ 오른쪽 바꾸기 (왼손잡이) | 프로크리에이트 | ✅ |
| 펜슬 호버 = 브러쉬 크기 미리보기 | 프로크리에이트 | ✅ |

**캐로킷 반영 제안**
- 명세서 OB-15(키보드 없이 쓰는 대안)에 **"화면 위 보조 키"** 를 추가하면 좋겠다. 지금은 다중 선택 버튼, 자동 각도 스냅, 복제 버튼만 있다. 보조 키 하나로 비율 고정, 가운데 기준, 복제하며 이동을 한꺼번에 해결할 수 있다.
- 탭 제스처(DR-14), 왼손잡이 배치(18장)는 이미 반영됨

---

## 7. 따를 것과 우리 것

| 따른다 (관례) | 캐로킷 것으로 (아이덴티티) |
|---|---|
| 화면 배치 (도구 왼쪽, 속성 오른쪽, 장 아래) | 슬라이드 경계 표시 모양 |
| 아이콘 은유, 단축키 (피그마 기준) | 아이콘 **그리는 스타일** (선 두께, 모서리) |
| 선택 핸들, Shift·Alt 동작, 스마트 가이드 | 강조색 하나, 회색 단계 |
| 속성 패널 순서, 숫자 칸 조작 | 숫자 표기 (장 번호 01/20 등) |
| 레이어 눈·자물쇠, 색 선택기 구성, 정렬 아이콘 | 넘김·스냅의 움직임과 진동 |
| iPad 제스처 (두 손가락 탭 등) | 조수 말투 (경고, 안내 문구) |

**판단 기준**: "이걸 바꾸면 사용자가 다시 배워야 하나?" → 그렇다면 따른다. 아니라면 캐로킷답게.

---

## 출처

**공식 도움말**
- [Figma: Navigating UI3](https://help.figma.com/hc/articles/23954856027159)
- [Figma: Lock and unlock layers](https://help.figma.com/hc/en-us/articles/360041596573)
- [Figma: Measure distances between layers](https://help.figma.com/hc/en-us/articles/360039956974)
- [Adobe: Illustrator on the iPad workspace](https://helpx.adobe.com/illustrator/ipad/get-started/overview-and-setup/workspace-on-iPad.html)
- [Adobe: Illustrator desktop vs iPad](https://www.adobe.com/learn/illustrator/web/compare-desktop-vs-ipad)
- [Adobe: Illustrator on iPad keyboard shortcuts](https://learn.adobe.com/illustrator/using/keyboard-shortcuts-ios.html)
- [Canva: Add elements](https://www.canva.com/help/article/add-elements)
- [Canva Design School: Using and customizing templates](https://www.canva.com/design-school/resources/using-and-customizing-templates)
- [Procreate Handbook: Interface](https://help.procreate.com/procreate/handbook/interface-gestures/interface)
- [Procreate Handbook: Gestures](https://help.procreate.com/procreate/handbook/interface-gestures/gestures)
- [Affinity Designer 2 iPad: Interface visual reference](https://affinity.help/designer2ipad/English.lproj/pages/Workspace/interface.html)
- [Affinity Publisher 2 iPad: Interface visual reference](https://affinity.help/publisher2ipad/en-US.lproj/pages/Workspace/interface.html)
- [Apple HIG: Toolbars](https://developer-mdn.apple.com/design/human-interface-guidelines/components/menus-and-actions/toolbars)

**2차 자료**
- [Hongkiat: 100+ Illustrator keyboard shortcuts](https://www.hongkiat.com/blog/adobe-illustrator-keyboard-shortcuts/)
- [Skillademia: Figma shortcuts](https://www.skillademia.com/shortcuts/figma-shortcuts/)
- [Envato Tuts+: Essential Figma shortcuts](https://webdesign.tutsplus.com/essential-figma-shortcuts--cms-35478t)
- [Envato Tuts+: Figma layers panel tips](https://webdesign.tutsplus.com/figma-layers-panel-tips--cms-31982t)
- [CreativeLive: Illustrator on the iPad, toolbar and shortcuts](https://site.creativelive.com/class/adobe-illustrator-on-the-ipad-jason-hoppe/lessons/toolbar-task-bar-interface-and-shortcuts)
- [Brenda Cadman: How to navigate the Canva editor](https://brendacadman.com/how-to-navigate-the-canva-design-editor/)
- [Design Monks: Figma UI changes](https://designmonks.co/figma-ui-changes-to-enhance-your-design-workflow/)
- [PC Pro (2018): Reinventing graphic design on the iPad](https://www.pressreader.com/uk/pc-pro/20181001/282583083834212)
