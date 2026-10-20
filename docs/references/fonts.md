# 레퍼런스: 한글 무료 폰트와 라이선스 (v0.1)

> 캐로킷에 기본으로 넣을 한글 폰트 후보와 라이선스 정리. 2026년 10월 조사.
> 경쟁 앱 SWVY는 한글 폰트가 거의 없고 폰트 대부분이 유료 구독이라, **한글 무료 폰트를 많이 기본 제공하는 것이 캐로킷의 차별점**이다.
> 정확도 표시는 [캐러셀 배경 지식](carousel-background.md)과 같다 (✅ 확실 / 🟡 대체로 맞음 / ⚠️ 불확실). 법률 자문은 아니다.

---

## 0. 가장 중요한 것: "무료 폰트" ≠ "앱에 넣어도 되는 폰트"

폰트를 쓰는 방법은 세 가지이고, 필요한 허락이 다르다.

| 방법 | 뜻 | 필요한 허락 |
|---|---|---|
| **A. 앱에 기본 내장** | 폰트 파일을 캐로킷 앱에 넣어서 배포 | 라이선스가 **소프트웨어에 넣어 재배포(번들)** 하는 것을 허용해야 함. 가장 까다로움 |
| **B. 사용자가 직접 가져오기** | 사용자가 눈누 등에서 받은 파일을 캐로킷으로 가져옴 (FT-02) | 캐로킷은 파일을 배포하지 않음. 결과물 사용 범위는 사용자가 각 라이선스 확인 |
| **C. 무료 폰트 사이트 안내** | 앱 안에서 눈누 같은 사이트로 연결 | 링크만 제공 |

- "상업적 사용 무료"는 보통 **폰트로 만든 결과물**(이미지, 영상, 인쇄물)을 팔아도 된다는 뜻이다. **폰트 파일 자체를 앱에 넣어 나눠 주는 것**은 별도 조항이다.
- 눈누는 무료 폰트를 모아 보여주는 사이트다. 필터(OFL, 임베딩 등)는 찾을 때 참고만 하고, **최종 판단은 제작사의 라이선스 원문**으로 한다 ✅

### OFL (SIL 오픈 폰트 라이선스)

- 폰트를 **소프트웨어에 넣어 배포하고, 그 소프트웨어를 유료로 팔아도 된다.** 금지는 **폰트 파일만 따로 파는 것** ✅
- 조건 1: 앱 안에 **저작권 표시와 라이선스 전문**을 넣는다 (설정 > 정보 > 폰트 라이선스 화면, FT-09)
- 조건 2: **"예약된 이름(Reserved Font Name)"** 이 있는 폰트는 수정하면 그 이름을 쓸 수 없다. 용량을 줄이려고 글자를 빼거나 형식을 바꾸는 것도 수정이다. → **원본 파일을 그대로 넣는다** (Pretendard, Spoqa Han Sans Neo는 예약 이름 있음 ✅)
- 그래서 **기본 내장은 OFL 폰트 위주로** 고른다.

---

## 1군: 기본 내장 가능 (OFL 확인)

### 1-1. 구글 폰트 한글 47종: 전부 OFL ✅

구글 폰트 원본 저장소([github.com/google/fonts](https://github.com/google/fonts))의 각 폰트 정보 파일(METADATA.pb)에서 `korean` 지원 폰트를 모두 뽑아 직접 확인했다 (2026년 10월 16일 기준). **47종 모두 라이선스가 OFL**이다.

> 영문 이름, 라이선스, 제작, 분류는 원본 저장소 기준 ✅. **한글 이름과 "쓰임"은 참고용**이다 (한글 이름은 일부 읽기 그대로 적었고, 정식 한글 이름은 제작사 표기로 다시 확인).

**고딕 (본문, 제목)**

| 폰트 | 한글 이름 | 제작 | 굵기 수 | 쓰임 |
|---|---|---|---|---|
| Noto Sans KR | 본고딕 계열 | Google | 가변 | 본문 기본 |
| Gothic A1 | 고딕 A1 | 한양정보통신 | 9 | 본문 |
| IBM Plex Sans KR | IBM 플렉스 산스 | IBM (Bold Monday) | 7 | 본문, 정보형 |
| Nanum Gothic | 나눔고딕 | 산돌 (네이버) | 3 | 본문 |
| Gowun Dodum | 고운돋움 | 류양희 | 1 | 부드러운 본문 |
| 42dot Sans | 42dot 산스 | 42dot | 가변 | 본문 |
| Asta Sans | 아스타 산스 | 42dot | 가변 | 본문 |
| Sunflower | 해바라기 | 직지소프트 | 3 | 본문, 제목 |
| Black Han Sans | 검은고딕 | Zess Type | 1 | **굵은 제목** |
| Do Hyeon | 배민 도현체 | 우아한형제들 | 1 | **제목** |
| Jua | 배민 주아체 | 우아한형제들 | 1 | **귀여운 제목** |
| Dongle | 동글 | 류양희 | 3 | 동글동글 제목 |
| Orbit | 오르빗 | 조수운 (JAMO) | 1 | 개성 있는 제목 |
| Stylish | 스타일리시 | 아시아소프트 | 1 | 제목 |
| Gasoek One | 가석 | Jiashuo Zhang (JAMO) | 1 | 아주 굵은 제목 |
| Dotum, DotumChe | 돋움, 돋움체 | 한양정보통신 | 1 | 레트로, 시스템 글꼴 느낌 |
| Gulim, GulimChe | 굴림, 굴림체 | 한양정보통신 | 1 | 레트로, 밈 |

**명조 (감성, 에세이)**

| 폰트 | 한글 이름 | 제작 | 굵기 수 | 쓰임 |
|---|---|---|---|---|
| Noto Serif KR | 본명조 계열 | Google | 가변 | 본문 명조 |
| Nanum Myeongjo | 나눔명조 | 산돌 (네이버) | 3 | 본문 명조 |
| Gowun Batang | 고운바탕 | 류양희 | 2 | 감성 본문 |
| Hahmlet | 함렛 | Hypertype | 가변 | 세련된 명조 |
| Song Myung | 송명 | 직지 | 1 | 제목 명조 |
| Diphylleia | 산하엽 | 형민하 (JAMO) | 1 | 장식 명조 |
| Grandiflora One | 그랜디플로라 | 조해성 (JAMO) | 1 | 장식 명조 |
| Batang, BatangChe | 바탕, 바탕체 | 한양정보통신 | 1 | 레트로 |
| Gungsuh, GungsuhChe | 궁서, 궁서체 | 한양정보통신 | 1 | 레트로, 밈 ("궁서체입니다") |

**손글씨 (인스타툰 대사, 메모)**

| 폰트 | 한글 이름 | 제작 | 쓰임 |
|---|---|---|---|
| Nanum Pen Script | 나눔손글씨 펜 | 산돌 (네이버) | 손글씨 대사 |
| Nanum Brush Script | 나눔손글씨 붓 | 산돌 (네이버) | 붓글씨 |
| Gaegu | 개구 | 직지소프트 | 귀여운 손글씨 (굵기 3) |
| Hi Melody | 하이멜로디 | 윤디자인 | 손글씨 |
| Gamja Flower | 감자꽃 | 윤디자인 | 손글씨 |
| East Sea Dokdo | 동해독도 | 윤디자인 | 거친 손글씨 |
| Nanum Gothic Coding | 나눔고딕코딩 | 산돌 (네이버) | 코드, 고정폭 (구글 분류상 손글씨 칸) |

**디스플레이 (장식, 포인트)**

| 폰트 | 한글 이름 | 제작 | 쓰임 |
|---|---|---|---|
| Bagel Fat One | 베이글 | 김경원 (JAMO) | 통통한 포인트 제목 |
| Moirai One | 모이라이 | 박지연 (JAMO) | 장식 제목 |
| Yeon Sung | 배민 연성체 | 우아한형제들 | 손글씨풍 제목 |
| Kirang Haerang | 배민 기랑해랑체 | 우아한형제들 | 레트로 제목 |
| Poor Story | 푸어스토리 | 윤디자인 | 장난스러운 제목 |
| Cute Font | 큐트폰트 | 타이포디자인랩 | 귀여운 포인트 |
| Single Day | 싱글데이 | DXKorea | 장식 |
| Dokdo | 독도 | 폰트릭스 | 거친 붓 느낌 |
| Gugi | 구기 | 태시스템 | 장식 |
| Black And White Picture | 흑백사진 | 아시아소프트 | 레트로 |

### 1-2. 구글 폰트 밖의 OFL 폰트

| 폰트 | 라이선스 | 근거 | 정확도 |
|---|---|---|---|
| **Pretendard** (프리텐다드) | OFL, 예약 이름 "Pretendard" | 원본 저장소 LICENSE 파일 직접 확인 | ✅ |
| **Spoqa Han Sans Neo** (스포카 한 산스 네오) | OFL, 예약 이름 "Spoqa Han Sans Neo" | 원본 저장소 LICENSE 파일 직접 확인 | ✅ |
| **나눔스퀘어, 나눔스퀘어 네오, 나눔바른고딕 등** 네이버 나눔글꼴 | OFL. 라이선스 전문과 저작권 안내를 넣으면 소프트웨어 번들·재배포 가능 | 산돌구름 안내 페이지 (네이버 원문 미확인) | 🟡 |
| **마루부리** (네이버) | OFL, 나눔글꼴과 같은 규정 | 산돌구름 안내 페이지 | 🟡 |

---

## 2군: 넣을 수 있어 보이지만 원문 확인이나 문의가 필요

| 폰트 | 알려진 조건 | 확인할 것 | 정확도 |
|---|---|---|---|
| **배민 글꼴** (한나체, 한나는 열한살, 을지로체 등) | 상업·비상업 자유, 수정 가능, **폰트 파일 판매만 금지**. 허용 목록에 "앱 UI" 포함 | 앱에 넣어 **사용자에게 나눠 주는 것**까지 허용인지 공식 원문 확인. (주아, 도현, 연성, 기랑해랑은 이미 구글 폰트 OFL로 해결) | 🟡 |
| **카페24 폰트** (써라운드, 슈퍼매직, 아네모네 등) | 무료, 파일 판매만 금지. 사용 범위에 "소프트웨어 번들, 특정 프로그램 임베드" 포함 | 카페24 공식 원문 확인 | 🟡 |
| **에스코어 드림** | 소프트웨어 번들·재배포 가능. **수정 금지** (받은 파일 그대로 사용) | 원문 확인. 용량 줄이기(글자 빼기) 불가 | 🟡 |
| **넥슨 Lv.1 고딕** | 임베딩, 로고 허용 | 넥슨 공식 원문 확인 | 🟡 |

---

## 3군: 내장하지 않음 (사용자가 직접 가져오기로)

| 폰트 | 이유 | 정확도 |
|---|---|---|
| **여기어때 잘난체** (잘난체, 잘난체 2, 잘난체 고딕) | 임베딩이 "조건부". 수정·재배포 금지 | 🟡 |
| **G마켓 산스** | 소프트웨어 번들 조항을 찾지 못함 | ⚠️ |
| **산돌구름 무료 폰트** (산돌 자체 폰트) | 클라우드 서비스라 폰트 파일을 직접 주지 않음. 스타터팩은 비상업용 | 🟡 |
| 기타 눈누 폰트 | 폰트마다 조건이 다름. 하나씩 원문 확인 전까지는 내장하지 않음 | ✅ |

인기 폰트라도 3군은 **사용자가 눈누에서 받아 직접 가져오기(FT-02)** 로 쓰게 하고, 앱에서는 "무료 폰트 찾기" 안내(FT-11)로 연결한다.

---

## 4. 캐로킷에 넣는 방법

### 앱 용량

- 한글 폰트는 글자 수가 많아(완성형 11,172자) 파일 하나가 수 MB이고, 굵기가 많으면 더 크다 🟡
- 50종 이상을 앱에 전부 넣으면 앱이 너무 커진다. → **기본 몇 종만 앱에 넣고, 나머지는 처음 쓸 때 내려받기** (FT-10)

### 처음 쓸 때 내려받기 (서버 없이)

| 방법 | 내용 | 정확도 |
|---|---|---|
| **애플이 파일을 보관해 주는 방식** (Background Assets, Apple 호스팅) | 폰트 묶음을 App Store Connect에 올리면 애플이 저장·배포. 별도 서버 필요 없음. **iPadOS 26 이상** 필요 | 🟡 (애플 문서 직접 확인 필요) |
| 예전 방식 (On-Demand Resources) | 아직 동작하지만 애플이 사용 중단 예정으로 발표했다는 글이 있음 | ⚠️ |

→ 최소 iPadOS 버전을 정할 때(M0) 함께 결정한다.

### 기본 내장 추천 (앱에 바로 들어 있는 것, 예시)

| 용도 | 폰트 |
|---|---|
| 본문 | Pretendard, Noto Sans KR |
| 제목 | Black Han Sans, Do Hyeon, Jua |
| 명조 | Gowun Batang, Nanum Myeongjo |
| 손글씨 | Nanum Pen Script, Gaegu, Gamja Flower |

나머지 1군은 폰트 목록에 보이고, 처음 고를 때 내려받는다.

### 라이선스 관리 규칙

1. 폰트마다 **원본 출처 주소, 라이선스 파일, 받은 날짜**를 저장소의 `fonts/LICENSES/`에 함께 보관한다
2. 앱의 **설정 > 정보 > 폰트 라이선스**에 저작권 표시와 라이선스 전문을 보여준다 (FT-09)
3. 폰트 파일은 **원본 그대로** 넣는다 (예약 이름, 수정 금지 조항 대비)
4. 2군은 제작사에 이메일로 "iPad 앱에 기본 폰트로 포함해 배포해도 되는지" 문의하고 **답변을 보관**한 뒤 넣는다
5. 출시 직전에 라이선스를 한 번 더 확인한다 (조건이 바뀔 수 있음)

---

## 출처

- [Google Fonts 원본 저장소 (각 폰트 METADATA.pb)](https://github.com/google/fonts)
- [Pretendard 저장소 LICENSE](https://github.com/orioncactus/pretendard)
- [Spoqa Han Sans 저장소 LICENSE](https://github.com/spoqa/spoqa-han-sans)
- [Wikipedia: SIL Open Font License](https://www.wikipedia.org/wiki/SIL_OFL)
- [Cocoanetics: Licensing fonts for use in apps](https://cocoanetics.com/2012/03/licensing-fonts-for-use-in-apps)
- [Solar2D 포럼: OFL 폰트 번들](https://forums.solar2d.com/t/use-of-font-under-sil-open-font-license/356472)
- [Fontsource: Jua](https://fontsource.org/fonts/jua/about), [Gowun Dodum](https://fontsource.org/fonts/gowun-dodum/about)
- [산돌구름: Pretendard](https://www.sandollcloud.com/font/16951/Pretendard)
- [산돌구름: Spoqa Han Sans](https://www.sandollcloud.com/font/261/SpoqaHanSans)
- [산돌구름: 나눔스퀘어](https://www.sandollcloud.com/free-font/229/NanumSquareOTF), [나눔스퀘어 네오](https://www.sandollcloud.com/free-font/17678/NanumSquareNeo), [마루부리](https://www.sandollcloud.com/free-font/16193/Maru-Buri)
- [산돌구름: 배민 주아](https://www.sandollcloud.com/free-font/210/BM-JUA), [배민 을지로](https://www.sandollcloud.com/free-font/855/BM-EULJIRO), [배민 도현](https://www.sandollcloud.com/free-font/219/BM-DoHyeon)
- [산돌구름: 카페24 슈퍼매직](https://www.sandollcloud.com/free-font/18335/Cafe24-Supermagic)
- [산돌구름: 에스코어 드림](https://www.sandollcloud.com/free-font/778/S-CoreDream)
- [산돌구름: 넥슨 Lv1 고딕](https://www.sandollcloud.com/free-font/16183/NEXON-Lv1-Gothic-OTF)
- [산돌구름: 여기어때 잘난체](https://www.sandollcloud.com/free-font/772/Jalnan), [잘난체 고딕](https://www.sandollcloud.com/free-font/19493/Jalnan-Gothic)
- [산돌구름 앱 (App Store)](https://apps.apple.com/kr/app/%EC%82%B0%EB%8F%8C%EA%B5%AC%EB%A6%84-%EC%95%84%EC%9D%B4%ED%8F%B0%EC%9A%A9-%EB%AC%B4%EB%A3%8C-%EC%9C%A0%EB%A3%8C-%EA%B8%80%EC%94%A8%EC%B2%B4-%EB%A7%88%EC%BC%93/id1499925527?uo=2)
- [눈누레터: 어디든 써도 괜찮아](https://maily.so/noonnu/posts/61gz25dz3ql)
- [브런치: 상업용 무료 폰트 사이트 추천](https://brunch.co.kr/@ssoxxl/477)
- [KLDP: 나눔글꼴 수정해서 상용 S/W에 사용](https://kldp.org/node/104433)
- [Blake Crosley: On Demand Resources Is Deprecated](https://blakecrosley.com/ko/blog/on-demand-resources-deprecated-background-assets)
