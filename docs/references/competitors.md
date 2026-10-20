# 레퍼런스: 비슷한 툴과 사람들의 작업 방식 (경쟁 분석 v0.2)

> 2026년 10월 웹 검색 기준. 앱스토어 페이지는 이 작업 환경에서 직접 열 수 없어서 **검색 결과에 나온 앱 소개 문구**로 정리했다. 소개 문구는 광고라서, 직접 설치해서 써 보고 이 문서를 고쳐야 한다.
> 정확도 표시는 [캐러셀 배경 지식](carousel-background.md)과 같다 (✅ 확실 / 🟡 대체로 맞음 / ⚠️ 불확실·추정).

---

## 1. 결론

- **캐로킷과 똑같은 툴은 아직 찾지 못했다.** 사람들은 툴 2~4개를 이어 붙여서 캐러셀을 만든다.
- 각 툴은 한 가지씩만 잘한다: 그리기(프로크리에이트, 클립스튜디오), 배치·템플릿(캔바, 미리캔버스, 피그마), 자르기(SWVY, FlowGrid 같은 분할 앱).
- 캐로킷의 기회: **"펜슬로 그리기 + 피그마식 배치 + 이어지는 캔버스 + 자르기 + 인스타 미리보기"를 한 앱에서.**
- 가장 가까운 경쟁자는 **SWVY**. 직접 써 보니 기획이 거의 같다 (3-1). 다만 해외 앱이고 아직 사용자가 많지 않아 보여서, 정면 경쟁보다는 **SWVY에 부족한 점을 채운 툴**로 간다.
- 캐로킷의 방향: **캐러셀 만드는 사람들의 완벽한 어시스트 툴.**

---

## 2. 사람들이 실제로 만드는 방식

### 이어지는 캐러셀 (파노라마처럼 이어지는 것)

모든 툴에서 원리는 같다 ✅ (여러 가이드가 일치)

1. 슬라이드 장수만큼 **넓은 캔버스 하나**를 만든다. 예: 4:5 세로 1080×1350 슬라이드 5장 → 5400×1350
2. 1080px마다 **안내선**을 그어 잘릴 위치를 표시한다
3. 전체를 하나의 그림처럼 디자인한다. 글자와 얼굴은 잘리는 선 위에 두지 않는다
4. 통째로 내보낸 뒤 **분할 툴로 자른다** (웹 분할기, 분할 앱, 포토샵 슬라이스)

툴별 방식

| 툴 | 방식 | 정확도 |
|---|---|---|
| 캔바 | 넓은 디자인 + 눈금자·안내선 → PNG 내보내기 → 웹 분할기, 또는 캔바 안의 "Image Splitter" 앱 | 🟡 |
| 피그마 | ① 넓은 프레임 + 슬라이스 도구 ② 프레임을 간격 없이 붙여 놓으면 걸친 도형이 자동으로 나뉘어 내보내짐 ③ 긴 이미지를 복제해 장마다 마스크 | 🟡 |
| 어도비 익스프레스 | 여러 페이지 기능이 있지만, 이어지는 디자인은 넓은 페이지를 만들어 분할 툴로 자르라고 안내 (커뮤니티 답변) | 🟡 |
| 프로크리에이트 | 넓은 캔버스 + 그리드 → 내보내기 → 다른 앱으로 자르기 | ⚠️ (검색으로 확인 못함, 일반적인 방법) |

### 카드뉴스 · 정보형 캐러셀

| 툴 | 특징 | 정확도 |
|---|---|---|
| **미리캔버스** | 국산, 웹. 한글 카드뉴스 템플릿이 가장 자연스럽고 무료 범위가 넓다는 평. 움직이는 템플릿은 부족 | 🟡 |
| **망고보드** | 국산, 웹. 템플릿 많음. 무료는 제작 수 제한과 워터마크 | 🟡 |
| **캔바** | 템플릿 가장 많음, iPad 앱 있음. 프로 요금 부담, 한글 폰트·템플릿은 영어권보다 적다는 평 | 🟡 |
| **피그마** | 디자이너들이 많이 씀. 컴포넌트로 반복 요소(제목, 페이지 번호)를 관리하고 한 번에 내보내기 | 🟡 |
| AI 생성기 (PostNitro 등) | 글을 넣으면 캐러셀을 자동 생성. 주로 링크드인·마케팅용, 웹 | 🟡 |

### 인스타툰

| 툴 | 특징 | 정확도 |
|---|---|---|
| **클립스튜디오** | 만화·웹툰 작가 표준. 컷, 말풍선 도구, 휴대폰 비율 확인, 긴 원고 내보내기. 월 구독 | 🟡 (공식 사이트 자료라 홍보 성격) |
| **프로크리에이트** | iPad 대표 드로잉 앱, 한 번 구매. 만화 전용 기능은 적음. 한 문서에서 캔버스를 넘겨 보는 페이지 보조 기능 있음 | 🟡 |
| **이비스페인트** | 무료(전체 기능은 유료 멤버십). 브러시 많고 스크린톤, 클리핑, 벡터 도구 | 🟡 |
| 메디방페인트 | 무료 만화 앱 | 🟡 |
| 흔한 조합 | 그리기 앱에서 그림 → 글자·말풍선은 클립스튜디오나 캔바에서 → 장별로 내보내기 | ⚠️ (일반적인 방법, 설문 근거 없음) |

인스타툰 사이즈로는 1080×1080(정사각), 1080×1440(3:4)을 쓴다는 안내가 있다 🟡 (외주 판매 페이지 기준)

---

## 3. iPad 캐러셀 전용 앱 (가장 가까운 경쟁자)

| 앱 | 소개 문구에 나온 기능 | 캐로킷과 비교 | 정확도 |
|---|---|---|---|
| **SWVY: Seamless Carousel Maker** | iPad 지원, 이어지는 슬라이드 정렬, 템플릿, 스티커, **낙서·그리기**, iPad에서 더 큰 캔버스 | 가장 직접적인 경쟁자. 그리기 깊이(브러쉬, 필압, 레이어)와 텍스트 기능 확인 필요 | 🟡 (앱 소개 문구) |
| **FlowGrid Seamless Carousel** | iPad 전용 설계, 무한 캔버스, 파노라마를 2~10장으로 자동 분할 | 분할 최대 10장 (인스타는 20장) | 🟡 (앱 소개 문구) |
| **Grid Square Cut** | 템플릿, 인스타·링크드인·페이스북 크기, 끌어다 놓기 편집 | 템플릿·분할 중심 | 🟡 |
| **Panorama Split** | 사진 고르기 → 비율·장수 → 내보내기 | 자르기 전용 | 🟡 |
| Sparkal, Crsel 등 | 콜라주·템플릿, 일부는 iPhone 전용 | 휴대폰용 간단 편집 | 🟡 |

검색 결과에서 **애플 펜슬 지원을 강조하는 캐러셀 앱은 찾지 못했다** ⚠️

### 3-1. SWVY 직접 써 본 기록 (2026년 10월, 직접 사용 ✅)

| 구분 | 내용 | 캐로킷 반영 |
|---|---|---|
| 같은 점 | 기획이 거의 같다. 이어지는 캐러셀, 그리기, 템플릿, **미리보기**까지 지원 | 기능만으로는 차별이 약함. 아래 차이점과 완성도로 승부 |
| 없는 기능 | **원고 쓰고 붙이기** 없음 | 원고 패널(SC) 유지. 핵심 차별점 |
| 없는 기능 | **동영상 파일 넣기** 없음 | 동영상(VD) P0 유지. 핵심 차별점 |
| 문제점 | 텍스트 박스를 입력한 뒤 **크기를 키우면 해상도가 떨어진다** (그림처럼 늘어남) | **손그림 외 모든 오브젝트를 벡터 방식으로** (명세서 19장 선명도, 개발 설계 핵심 원칙 1) |
| 좋은 점 | **인스타 화면 모양 디자인 소스**가 많다 (DM 메시지 모양, 위치 태그 등) | 디자인 소스(명세서 15-1장, AS-01~06). 기본 로직 완성 후 범위 결정 |
| 좋은 점 | **도형**이 많이 준비돼 있어 쉽게 꾸밀 수 있다 | AS-02 도형 소스 |
| 시장 | 해외 앱. 사용자가 아직 많지 않은 것으로 보임 | 한국 사용자(한글 폰트, 원고, 인스타툰)에 맞춘 완성도로 차별 |

**2차 사용 기록**

| 구분 | 내용 | 캐로킷 반영 |
|---|---|---|
| 그리기 | 브러쉬, 필압이 **아이폰·아이패드 사진 앱의 기본 그리기 도구와 똑같다.** 애플 기본 그리기 도구(PencilKit)를 불러와 쓰는 것으로 보임 | ⚠️ 추정 (화면이 같다는 사용 관찰). 캐로킷은 브러쉬 엔진을 직접 만들어서(DR) 필압·기울기 켜기/끄기, 형광펜, 직선 보정을 지원 → **차별점** |
| 장수 | 최대 **20장** | 캐로킷도 인스타 최대(20장)에 맞춤. 그 이상은 만들지 않음 |
| 가격 | **제작 자체는 무료로 충분.** 유료 구독은 그래픽 소스, 템플릿, 폰트를 더 제공 | 수익 모델 참고 (명세서 20장) |
| 폰트 | 대부분 **영문**, 한글 폰트는 거의 없음 (한국인 대상 툴이 아님). 유료 구독해야 쓸 수 있는 폰트가 많음. **사용자가 폰트 파일을 직접 가져올 수 있음** | **한글 무료 폰트를 많이 기본 제공** (FT-01, [폰트 레퍼런스](fonts.md)) + 직접 가져오기(FT-02) |

**더 확인해 볼 것**
- 내보내기 형식과 화질
- 레이어, 정렬, 수치 입력 같은 편집 기능의 깊이

---

## 4. 캐로킷이 채울 수 있는 빈자리

| 지금 사람들이 겪는 불편 | 캐로킷 기능 |
|---|---|
| 그리는 앱, 글자 넣는 앱, 자르는 앱을 오가야 함 | 한 앱에서 그리기(DR) + 배치(OB, AL) + 텍스트(TX) + 내보내기 분할(EX) |
| 넓은 캔버스를 만들 때 픽셀 계산, 안내선을 직접 그어야 함 | 이어 보기 캔버스, 장수만 고르면 끝 (CV) |
| 잘리는 선에 글자가 걸리는지 올려 봐야 앎 | 잘림 영역 표시, 휴대폰 화면 미리보기, 프로필 그리드 (IG) |
| 글(원고)을 따로 써 두고 복사·붙여넣기 반복 | 원고 패널에서 끌어다 놓기, 자동 흘려넣기 (SC) |
| 회차마다 같은 스타일을 다시 맞춤 | 시리즈와 디자인 키트 (SR) |
| 분할 앱은 10장 제한인 경우가 있음 | 인스타 최대 장수(20장)에 맞춤 |
| 글자를 키우면 흐려짐 (SWVY) | 손그림 외에는 벡터라 키워도 선명 |
| 영상은 다른 앱에서 따로 편집 | 동영상 넣기, 자르기, 배속, MP4 내보내기 (VD) |

**조심할 점**
- 캔바, 프로크리에이트, 클립스튜디오는 이미 익숙한 툴이라, 캐로킷은 "다 된다"보다 **"캐러셀 만드는 시간이 확 줄어든다"** 를 보여줘야 한다.
- 브러쉬 품질은 프로크리에이트와 비교될 수밖에 없다 (구현 가능성 검토의 최고 난이도 항목).
- 경쟁 앱이 같은 기능을 추가할 수 있으니, 출시 전에 다시 조사한다.

---

## 5. 다음에 할 것 (직접 써 보기)

무료로 설치해서 같은 캐러셀(예: 이어지는 5장 + 말풍선 + 손글씨)을 만들어 보고 기록하기.

| 앱 | 볼 것 |
|---|---|
| SWVY | 2차 사용 완료 (3-1). 남은 확인 항목은 3-1 참고 |
| FlowGrid | 무한 캔버스 사용감, 분할 방식 |
| 캔바 (iPad) | 넓은 디자인 + 분할 과정이 몇 단계인지 |
| 미리캔버스 (iPad 사파리) | 한글 템플릿, 폰트 |
| 프로크리에이트 / 클립스튜디오 | 인스타툰 한 편 만드는 과정, 말풍선, 텍스트 불편함 |

기록 항목: 걸린 시간, 앱을 몇 번 옮겼는지, 가장 짜증 났던 순간, 좋았던 기능

---

## 출처

**이어지는 캐러셀 방법**
- [Krumzi: How to Make a Seamless Instagram Carousel (2026)](https://www.krumzi.com/blog/seamless-instagram-carousel)
- [DEV: The pixel math behind seamless Instagram carousels](https://dev.to/quinn-yang/the-pixel-math-behind-seamless-instagram-carousels-533l)
- [Fstoppers: How to create a seamless carousel on Instagram](https://fstoppers.com/social-media/how-create-seamless-carousel-instagram-431677)
- [RFG Creative: seamless carousel in Canva](https://rfgcreative.com/misc/how-to-create-seamless-instagram-carousel.html)
- [Blogging Guide: seamless carousel in Canva](https://bloggingguide.com/how-to-create-a-seamless-instagram-carousel-in-canva/)
- [Canva Apps: Image Splitter](https://www.canva.com/hi_in/apps/AAGRBT0C7xk/image-splitter)
- [Iconfinder: seamless carousel in Figma](https://www.iconfinder.com/blog/make-seamless-carousel-in-figma)
- [Visuals: seamless carousels in Figma](https://usevisuals.com/blog/seamless-carousels-in-figma)
- [BrandGhost: Figma for social media creators](https://blog.brandghost.ai/posts/figma-for-social-media-creators/)
- [Adobe Express: Instagram post (multiple pages)](https://adobe.com/express/create/post/instagram)
- [Adobe Community: carousel scheduling issue](https://community.adobe.com/t5/adobe-express-discussions/i-can-t-schedule-an-instagram-carousel-post-with-adobe-express/m-p/15395299)

**카드뉴스 툴**
- [mirra: 2026 캔바 대안 10가지](https://www.mirra.my/ko/blog/best-canva-alternatives)
- [마라스튜디오: 설치 없이 무료로 디자인할 수 있는 도구 7가지](https://maily.so/marastudio/posts/5bf32277)
- [서울에일리언: 미리캔버스](https://seoulalien.substack.com/p/94)
- [TheGuideX: Best Instagram carousel generators 2026](https://theguidex.com/resources/best-instagram-carousel-generators)
- [PostNitro: best carousel maker for Instagram](https://postnitro.ai/blog/post/best-carousel-maker-for-instagram)

**인스타툰 툴**
- [클립스튜디오: 만화·웹툰 제작에 좋은 앱 5가지](https://www.clipstudio.net/kr/comics-manga/beginners-guide/)
- [클립스튜디오: 2026 iPad 그림 앱 추천](https://www.clipstudio.net/drawing/archives/172510)
- [클립스튜디오: iPad로 연재만화 그리는 법](https://www.clipstudio.net/drawing/archives/165184)
- [App Store: ibis Paint X](https://apps.apple.com/KR/app/id441179131)
- [크몽: 인스타툰 제작 (사이즈 기준)](https://kmong.com/gig/697926)

**iPad 캐러셀 앱**
- [App Store: SWVY Seamless Carousel Maker](https://apps.apple.com/us/app/-/id6737145861)
- [App Store: FlowGrid Seamless Carousel](https://apps.apple.com/th/app/flowgrid-seamless-carousel/id6758648018)
- [App Store: Grid Square Cut-Carousel Maker](https://apps.apple.com/us/app/id1632635796)
- [App Store: Panorama Split](https://apps.apple.com/us/app/-/id6475376119)
- [Sparkal: Carousel & Collage](https://mwm.ai/apps/sparkal-carousel-collage/6772778160)
- [App Store: Crsel](https://apps.apple.com/app/id6744095828)

**참고: Affinity (Canva)**
- [AppleInsider (2025.10): Affinity iPad apps free](https://appleinsider.com/articles/25/10/02/all-affinity-apps-are-now-free-for-the-ipad---for-now)
- [iGeeksBlog: Affinity goes free with unified Mac app](https://www.igeeksblog.com/affinity-free-unified-mac-app/)
