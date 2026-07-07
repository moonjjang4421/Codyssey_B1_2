# NightBuild AI Brand Advertisement Project

## 0. 평가 보완 목적

본 README는 기존 제출물에서 Fail 처리된 항목을 보완하기 위해 작성되었다.

기존 평가는 브랜드 아이덴티티, 씬별 스토리보드, 제작 파이프라인, 제약사항 대응 전략은 충분하다고 판단하였다.  
그러나 다음 항목은 결과물 또는 심층 인터뷰 답변을 통해 확인되어야 했기 때문에 Fail 처리되었다.

- 최종 영상 파일 존재 여부
- 최종 영상 길이 확인
- AI 생성 시각 요소 포함 여부
- AI 생성 청각 요소 포함 여부
- 직접 촬영 영상 및 유료 스톡 소스 미사용 여부
- 생성 결과물 파일명 또는 링크 증빙
- 심층 인터뷰형 질문에 대한 답변
- 60초 버전을 15초로 축약할 때의 씬 유지·삭제 전략
- 도구 선택과 프롬프트 수정 이유에 대한 설명

따라서 본 문서는 단순 기획서가 아니라, **제출 증빙용 README**로 구성한다.

> 주의: README만으로 실제 MP4 파일이나 이미지 파일의 존재를 완전히 대체할 수는 없다.  
> 최종 평가에서 결과물 기반 항목을 통과하려면 본 README와 함께 실제 영상 파일 및 생성 에셋 파일을 함께 제출해야 한다.

---

# 1. 프로젝트 개요

## 1.1 프로젝트명

**NightBuild: Clear the Night**

## 1.2 브랜드명

**NightBuild**

## 1.3 브랜드 유형

밤샘 개발자를 위한 가상 에너지 드링크 브랜드

## 1.4 광고 목표

본 광고의 주목표는 **인지도 형성**이다.

10초 이내의 짧은 광고에서는 제품의 세부 기능이나 성분을 길게 설명하기 어렵다.  
따라서 “NightBuild = 밤샘 개발자를 위한 에너지 드링크”라는 인상을 빠르게 각인시키는 것을 목표로 한다.

보조 목표로는 **전환 유도**를 포함한다.  
마지막 장면에 짧은 CTA 문구를 배치하여 사용자가 제품을 기억하고 구매 행동을 떠올릴 수 있도록 설계하였다.

## 1.5 핵심 메시지

> **당신의 밤샘을, 조금 더 선명하게.**

---

# 2. 브랜드 아이덴티티

| 항목 | 내용 |
|---|---|
| 브랜드명 | NightBuild |
| 브랜드 유형 | 밤샘 개발자를 위한 에너지 드링크 |
| 주요 타겟 | 대학생 개발자, 해커톤 참가자, 프로젝트 마감 전 밤샘 작업자 |
| 서브 타겟 | 코딩 과제, 사이드 프로젝트, 팀 프로젝트를 병행하는 10~20대 |
| 톤앤매너 | 어두운 밤, 모니터 빛, 코드, 도시 야경, 네온 라임, 일렉트릭 블루 |
| 감정 흐름 | 피로감 → 집중력 저하 → 제품 등장 → 선명한 몰입감 |
| USP | 밤샘 개발 중 흐려지는 집중력을 다시 선명하게 만드는 개발자 전용 에너지 드링크 |
| 캠페인 목표 | 브랜드 인지도 형성 + 짧은 CTA를 통한 전환 유도 |
| 슬로건 | 당신의 밤샘을, 조금 더 선명하게. |

---

# 3. 최종 제출물 구성

## 3.1 제출 파일 목록

| 구분 | 파일명 | 설명 | 제출 여부 |
|---|---|---|---|
| README | README.md | 프로젝트 설명, 제작 과정, 평가 보완 답변 | 제출 |
| 스토리보드 PDF | NightBuild_storyboard.pdf | 브랜드 기획 및 씬별 스토리보드 문서 | 제출 필요 |
| 최종 영상 | NightBuild_brand_ad_10s.mp4 | 10초 이내 AI 기반 브랜드 광고 영상 | 제출 필요 |
| Scene 1 이미지 | scene01_tired_developer_image.png | 지친 개발자 키비주얼 | 제출 필요 |
| Scene 2 이미지 | scene02_error_screen_image.png | 에러 화면 키비주얼 | 제출 필요 |
| Scene 3 이미지 | scene03_product_reveal_image.png | 제품 등장 키비주얼 | 제출 필요 |
| Scene 4 이미지 | scene04_brand_cta_image.png | 브랜드 엔딩 카드 배경 | 제출 필요 |
| BGM | nightbuild_bgm.wav 또는 nightbuild_bgm.mp3 | Suno 생성 배경음악 | 제출 필요 |

## 3.2 권장 폴더 구조

```text
NightBuild_Project/
├─ README.md
├─ NightBuild_storyboard.pdf
├─ final/
│  └─ NightBuild_brand_ad_10s.mp4
├─ assets/
│  ├─ images/
│  │  ├─ scene01_tired_developer_image.png
│  │  ├─ scene02_error_screen_image.png
│  │  ├─ scene03_product_reveal_image.png
│  │  └─ scene04_brand_cta_image.png
│  ├─ video/
│  │  ├─ scene01_tired_developer_motion.mp4
│  │  ├─ scene02_error_screen_motion.mp4
│  │  ├─ scene03_product_reveal_motion.mp4
│  │  └─ scene04_brand_cta_motion.mp4
│  └─ audio/
│     └─ nightbuild_bgm.wav
└─ docs/
   └─ prompt_revision_log.md
```

---

# 4. 최종 영상 스펙 확인

## 4.1 최종 영상 정보

| 항목 | 내용 |
|---|---|
| 파일명 | NightBuild_brand_ad_10s.mp4 |
| 길이 | 10초 이내 |
| 목표 길이 | 10초 |
| 해상도 | 1920x1080 권장, 최소 1280x720 |
| 화면 비율 | 16:9 |
| 프레임레이트 | 24~30fps |
| 비디오 코덱 | H.264 |
| 오디오 코덱 | AAC |
| 편집 도구 | Canva |
| 시각 소스 | ChatGPT 이미지 생성 결과물 기반 |
| 청각 소스 | Suno 생성 BGM 기반 |
| 직접 촬영 영상 사용 여부 | 사용하지 않음 |
| 유료 스톡 영상 사용 여부 | 사용하지 않음 |
| 유료 스톡 음원 사용 여부 | 사용하지 않음 |

## 4.2 최종 영상 길이 검증 방법

최종 영상은 다음 방식으로 길이를 확인한다.

```text
파일 우클릭 → 속성 → 자세히 → 길이 확인
```

또는 영상 편집 도구에서 다음 조건을 확인한다.

```text
Canva 타임라인 기준:
Scene 1: 0~2초
Scene 2: 2~4초
Scene 3: 4~7초
Scene 4: 7~10초
총 길이: 10초
```

## 4.3 결과물 기반 평가 대응

| 평가 확인 항목 | 대응 내용 |
|---|---|
| 영상 파일이 존재하는가 | final/NightBuild_brand_ad_10s.mp4 제출 |
| 영상이 10초 이내인가 | 총 10초 타임라인으로 구성 |
| AI 시각 요소가 포함되었는가 | ChatGPT 이미지 생성 결과물 4개 사용 |
| AI 청각 요소가 포함되었는가 | Suno 생성 BGM 사용 |
| 직접 촬영 영상이 아닌가 | 직접 촬영 영상 사용하지 않음 |
| 유료 스톡 영상이 아닌가 | 유료 스톡 소스 사용하지 않음 |
| 브랜드 인지 장치가 있는가 | 마지막 3초에 브랜드명, 슬로건, CTA 표시 |
| MP4 형식인가 | H.264/AAC 기반 MP4로 출력 |

---

# 5. 사용 도구와 역할

| 구분 | 사용 도구 | 사용 목적 | 선택 이유 | 대체 도구 |
|---|---|---|---|---|
| 이미지 생성 | ChatGPT 이미지 생성 | 씬별 키비주얼 제작 | 장면, 구도, 분위기, 색감 제어가 쉽고 텍스트 프롬프트와 결과 연결 설명이 용이함 | Adobe Firefly, Leonardo AI |
| 영상 생성/변환 | Canva | 이미지 기반 모션, 컷 편집, 자막 삽입 | 접근성이 좋고 10초 광고 편집에 적합함 | Pika, Runway, Kling |
| 오디오 생성 | Suno | 광고용 BGM 생성 | 전자음, 긴장감, 미래적 분위기를 빠르게 생성할 수 있음 | Udio, Soundraw |
| 통합 편집 | Canva | 컷 편집, 자막, CTA, 오디오 싱크 조정 | 생성 결과물을 하나의 광고 영상으로 통합하기 쉬움 | CapCut, Premiere Pro, DaVinci Resolve |

---

# 6. 제작 파이프라인

```text
브랜드 기획
→ 광고 목표 설정
→ 핵심 메시지 정의
→ 4개 씬 스토리보드 작성
→ 씬별 이미지 프롬프트 작성
→ ChatGPT로 키비주얼 이미지 생성
→ Canva에서 이미지 기반 영상 모션 적용
→ Suno로 10초 BGM 생성
→ Canva에서 컷 편집, 자막, 브랜드명, CTA 삽입
→ MP4 형식으로 최종 출력
```

## 6.1 파이프라인 의사결정 이유

본 프로젝트에서는 먼저 이미지를 생성한 뒤 영상으로 변환하는 방식을 선택하였다.

그 이유는 다음과 같다.

1. 비디오 생성 도구는 크레딧 소모가 크고 재생성 비용이 높다.
2. 이미지 단계에서 구도와 톤앤매너를 먼저 고정하면 실패 비용을 줄일 수 있다.
3. 10초 광고는 긴 영상 생성보다 정지 이미지 기반 모션만으로도 충분히 메시지를 전달할 수 있다.
4. 브랜드명과 슬로건은 AI 이미지에 직접 넣을 경우 글자가 깨질 수 있으므로 Canva에서 직접 삽입하는 것이 안정적이다.

---

# 7. 광고 스토리 구조

## 7.1 전체 서사

본 광고는 **문제 제시 → 집중력 저하 → 제품 등장 → 해결 및 브랜드 각인** 구조를 따른다.

```text
밤샘 개발로 피로해진 개발자
→ 에러 화면과 집중력 저하
→ NightBuild 제품 등장
→ 선명한 몰입감과 브랜드 메시지 각인
```

## 7.2 10초 타임라인

| 시간 | 씬 | 화면 | 카피 | 역할 |
|---|---|---|---|---|
| 0~2초 | Scene 1 | 어두운 방, 지친 개발자 | 밤은 깊고, | 문제 제시 |
| 2~4초 | Scene 2 | 에러 화면, 멈춘 손 | 코드는 흐려진다. | 집중력 저하 |
| 4~7초 | Scene 3 | 제품 등장, 네온빛 전환 | NightBuild. | 해결책 제시 |
| 7~10초 | Scene 4 | 제품 + 브랜드명 + 슬로건 + CTA | 당신의 밤샘을, 조금 더 선명하게. | 브랜드 각인 |

---

# 8. 씬별 스토리보드

## 8.1 Scene 1 — 어두운 방, 지친 개발자

| 항목 | 내용 |
|---|---|
| 씬 길이 | 2초 |
| 목표 메시지 | 밤샘 개발 중 피로가 누적된 상황을 보여준다. |
| 화면 구성 | 어두운 방 안에서 개발자가 노트북 앞에 앉아 있다. 얼굴과 손은 모니터의 푸른빛에 희미하게 비친다. 책상 위에는 키보드, 빈 컵, 메모지가 있다. |
| 텍스트 유무 | 화면 카피만 Canva에서 삽입 |
| 내레이션/카피 | 밤은 깊고, |
| 이미지 도구 | ChatGPT 이미지 생성 |
| 비디오 도구 | Canva |
| 오디오 도구 | Suno |
| 사용 목적 | 피로감과 고립감을 시각적으로 표현한다. |
| 출력 결과 요약 | 어두운 밤, 지친 개발자의 고립감과 피로감을 표현한다. |
| 결과 파일명 | scene01_tired_developer_image.png / scene01_tired_developer_motion.mp4 |

### Image Prompt

```text
A tired young software developer sitting alone in a dark room at midnight,
laptop screen glow illuminating the face and hands,
messy desk with keyboard, empty cup and sticky notes,
blue cinematic lighting,
realistic commercial photography,
shallow depth of field,
16:9,
no text,
no logo
```

### Video Motion Prompt

```text
Slow cinematic zoom-in toward the tired developer,
subtle monitor flicker,
quiet midnight atmosphere,
realistic lighting,
2 seconds
```

---

## 8.2 Scene 2 — 모니터 에러 화면, 집중력 저하

| 항목 | 내용 |
|---|---|
| 씬 길이 | 2초 |
| 목표 메시지 | 에러와 피로로 인해 집중력이 흐려지는 순간을 보여준다. |
| 화면 구성 | 모니터 화면에 코드와 오류 메시지가 겹쳐 보이고, 개발자의 손은 키보드 위에 멈춰 있다. |
| 텍스트 유무 | AI 이미지 안의 텍스트는 사용하지 않고 Canva 자막만 사용 |
| 내레이션/카피 | 코드는 흐려진다. |
| 이미지 도구 | ChatGPT 이미지 생성 |
| 비디오 도구 | Canva |
| 오디오 도구 | Suno |
| 사용 목적 | 오류 화면과 글리치 효과로 집중력 저하를 표현한다. |
| 출력 결과 요약 | 에러 화면과 멈춘 손을 통해 집중력이 무너지는 순간을 보여준다. |
| 결과 파일명 | scene02_error_screen_image.png / scene02_error_screen_motion.mp4 |

### Image Prompt

```text
Close-up of a computer monitor showing blurred programming code and multiple error windows,
developer’s hands paused above a mechanical keyboard,
cold blue screen light,
late night coding stress,
cinematic realistic style,
slight glitch atmosphere,
16:9,
no readable text,
no logo
```

### Video Motion Prompt

```text
Subtle glitch effect on the monitor,
slight camera shake,
quick push-in toward the error screen,
2 seconds
```

---

## 8.3 Scene 3 — 제품 등장, 분위기 전환

| 항목 | 내용 |
|---|---|
| 씬 길이 | 3초 |
| 목표 메시지 | NightBuild가 흐려진 집중력을 선명한 몰입감으로 전환하는 제품임을 보여준다. |
| 화면 구성 | 책상 위 에너지 드링크 캔이 등장한다. 캔은 네온 라임빛과 푸른빛을 반사하고, 배경에는 도시 야경과 흐릿한 코드 화면이 보인다. |
| 텍스트 유무 | 제품명은 Canva에서 별도 삽입 |
| 내레이션/카피 | NightBuild. |
| 이미지 도구 | ChatGPT 이미지 생성 |
| 비디오 도구 | Canva |
| 오디오 도구 | Suno |
| 사용 목적 | 제품 중심 키비주얼과 분위기 전환을 구현한다. |
| 출력 결과 요약 | 제품 등장과 함께 화면 톤이 어두운 블루에서 선명한 네온 톤으로 전환된다. |
| 결과 파일명 | scene03_product_reveal_image.png / scene03_product_reveal_motion.mp4 |

### Image Prompt

```text
A sleek fictional energy drink can on a developer’s desk at night,
neon lime and electric blue reflections,
laptop with blurred code in the background,
city night lights outside the window,
futuristic but realistic commercial product photography,
dramatic lighting,
high contrast,
16:9,
no text,
no logo
```

### Video Motion Prompt

```text
Cinematic product reveal,
soft neon light spreading around the can,
slow rotation feeling,
background slightly blurred,
energetic transition,
3 seconds
```

---

## 8.4 Scene 4 — 브랜드명, 슬로건, CTA

| 항목 | 내용 |
|---|---|
| 씬 길이 | 3초 |
| 목표 메시지 | 브랜드명과 핵심 문구를 각인시키고 구매 행동을 유도한다. |
| 화면 구성 | 제품 캔을 중심으로 네온빛이 감도는 엔딩 배경을 구성한다. 화면에는 브랜드명, 슬로건, CTA가 표시된다. |
| 텍스트 유무 | Canva에서 브랜드명, 슬로건, CTA 삽입 |
| 내레이션/카피 | 당신의 밤샘을, 조금 더 선명하게. / 오늘 밤, 한 캔으로 빌드를 이어가라. |
| 이미지 도구 | ChatGPT 이미지 생성 |
| 비디오 도구 | Canva |
| 오디오 도구 | Suno |
| 사용 목적 | 광고의 마지막 3초에 브랜드 인지 장치를 명확하게 배치한다. |
| 출력 결과 요약 | 브랜드명, 슬로건, CTA가 명확히 보이는 광고 엔딩 장면을 구성한다. |
| 결과 파일명 | scene04_brand_cta_image.png / scene04_brand_cta_motion.mp4 |

### Image Prompt

```text
A clean cinematic end card background for a fictional tech energy drink brand,
energy drink can on a dark developer desk,
neon lime and blue lighting,
futuristic city night mood,
minimal composition,
empty space for typography,
realistic commercial style,
16:9,
no text,
no logo
```

### Video Motion Prompt

```text
Minimal product end card,
subtle glowing neon background,
slow camera push,
clean space for brand name and slogan,
3 seconds
```

---

# 9. 오디오 생성 계획

## 9.1 Suno BGM Prompt

```text
Dark minimal electronic background music for a tech energy drink commercial,
midnight coding mood,
low synth pulse,
subtle tension,
shifting into clear energetic focus,
futuristic tech commercial feeling,
punchy but not too aggressive,
10 seconds
```

## 9.2 오디오 구조

| 구간 | 분위기 | 목적 |
|---|---|---|
| 0~2초 | 낮고 어두운 전자음 | 밤샘 피로감 표현 |
| 2~4초 | 글리치성 전자음 | 에러와 집중력 저하 표현 |
| 4~7초 | 밝은 신스 리듬 | 제품 등장과 전환 표현 |
| 7~10초 | 짧은 피크 후 마무리 | 브랜드 기억 강화 |

---

# 10. 프롬프트 수정 전/후 기록

## 10.1 대상 씬

Scene 3. 제품 등장 장면

## 10.2 수정 전 프롬프트

```text
A cool energy drink can on a desk at night,
cyberpunk style,
bright lights,
coding setup
```

## 10.3 문제점

수정 전 프롬프트는 장면 분위기를 대략적으로 표현할 수는 있지만, 광고용 제품 이미지로는 구체성이 부족했다.

문제는 다음과 같다.

1. “cool”, “cyberpunk”, “bright lights”가 추상적이다.
2. 제품보다 배경이 과하게 강조될 수 있다.
3. 개발자용 에너지 드링크라는 맥락이 약하다.
4. 광고용 제품 컷에 필요한 상업 사진 느낌이 부족하다.
5. 브랜드 색상인 네온 라임과 블루 톤이 명확하지 않다.

## 10.4 수정 후 프롬프트

```text
A sleek fictional energy drink can on a developer’s desk at night,
neon lime and electric blue reflections,
laptop with blurred code in the background,
city night lights outside the window,
futuristic but realistic commercial product photography,
dramatic lighting,
high contrast,
16:9,
no text,
no logo
```

## 10.5 수정 이유

제품 광고에서는 제품이 장면의 중심에 있어야 한다.  
따라서 “energy drink can”을 중심 피사체로 고정하고, “developer’s desk”, “blurred code”, “city night lights”를 추가해 개발자용 에너지 드링크라는 맥락을 강화했다.

또한 모든 씬의 색감 일관성을 위해 “neon lime and electric blue reflections”를 추가하였다.

AI 이미지 생성 도구는 텍스트와 로고 표현이 불안정하기 때문에 “no text, no logo”를 명시하였다.  
브랜드명과 슬로건은 Canva에서 직접 삽입하는 방식으로 변경하였다.

## 10.6 결과 변화

수정 후에는 제품이 장면의 중심에 배치되고, 개발자 작업 환경과 브랜드 톤앤매너가 더 명확하게 드러난다.  
배경은 보조 요소로 정리되고, 광고용 제품 컷에 가까운 결과물을 얻을 수 있다.

---

# 11. 60초 버전을 15초로 줄일 때의 전략

평가기준에서 요구한 “긴 버전을 짧은 광고로 압축할 때의 의사결정”을 다음과 같이 정리한다.

## 11.1 60초 버전 가정

60초 버전은 다음과 같이 구성될 수 있다.

| 구간 | 내용 |
|---|---|
| 0~10초 | 밤샘 개발자의 작업 환경 소개 |
| 10~20초 | 에러 발생과 집중력 저하 |
| 20~30초 | 개발자의 피로감, 시간 압박, 마감 스트레스 |
| 30~40초 | NightBuild 제품 등장 |
| 40~50초 | 집중력 회복과 작업 재개 |
| 50~60초 | 브랜드명, 슬로건, CTA |

## 11.2 15초 버전으로 줄일 때 유지할 씬

| 유지 여부 | 씬 | 이유 |
|---|---|---|
| 유지 | 문제 제시 | 광고의 맥락을 빠르게 이해시키기 위해 필요 |
| 유지 | 에러 화면 | 타겟인 개발자가 공감할 수 있는 핵심 장면 |
| 유지 | 제품 등장 | 브랜드 광고이므로 반드시 필요 |
| 유지 | 브랜드명/슬로건/CTA | 인지도와 전환을 위해 반드시 필요 |

## 11.3 15초 버전에서 삭제하거나 축약할 씬

| 삭제/축약 대상 | 이유 |
|---|---|
| 개발자의 긴 작업 과정 | 15초 안에서는 설명보다 직관적 장면이 중요함 |
| 피로 누적 과정의 세부 묘사 | Scene 1의 어두운 방과 지친 자세로 대체 가능 |
| 제품 기능 설명 | 15초 광고에서는 기능 설명보다 브랜드 이미지 각인이 우선 |
| 집중력 회복 후 긴 작업 장면 | 제품 등장 후 네온빛 전환으로 상징적으로 표현 가능 |

## 11.4 15초 재구성안

| 시간 | 내용 |
|---|---|
| 0~3초 | 어두운 방, 지친 개발자 |
| 3~6초 | 에러 화면, 집중력 저하 |
| 6~10초 | NightBuild 제품 등장 |
| 10~15초 | 브랜드명, 슬로건, CTA |

## 11.5 본 프로젝트의 10초 버전으로 더 줄인 이유

본 과제는 최종 영상 길이를 10초 이내로 제한한다.  
따라서 15초 재구성안에서 각 장면을 더 압축하여 다음과 같이 구성하였다.

| 시간 | 내용 |
|---|---|
| 0~2초 | 문제 제시 |
| 2~4초 | 집중력 저하 |
| 4~7초 | 제품 등장 |
| 7~10초 | 브랜드 각인 |

핵심 메시지는 유지하되, 설명 장면을 줄이고 상징적 장면 중심으로 압축하였다.

---

# 12. 심층 인터뷰 답변

## Q1. 이미지 생성 AI, 비디오 생성 AI, 오디오 생성 AI의 역할 차이는 무엇인가?

이미지 생성 AI는 광고의 핵심 장면을 시각적으로 정의하는 역할을 한다.  
이 프로젝트에서는 각 씬의 구도, 색감, 피사체, 분위기를 먼저 이미지로 확정하였다.

비디오 생성 또는 변환 도구는 정지된 이미지를 광고 영상으로 느끼게 만드는 역할을 한다.  
Canva에서는 줌인, 글리치, 페이드, 간단한 모션을 적용하여 정지 이미지를 영상 흐름으로 연결하였다.

오디오 생성 AI는 장면의 감정 흐름을 강화하는 역할을 한다.  
Suno를 통해 어두운 전자음에서 선명한 신스 사운드로 전환되는 BGM을 생성하여, 피로에서 집중으로 전환되는 광고 메시지를 청각적으로 보강하였다.

## Q2. 왜 ChatGPT 이미지 생성, Canva, Suno를 선택했는가?

ChatGPT 이미지 생성은 프롬프트를 통해 장면의 의도를 비교적 구체적으로 제어할 수 있기 때문에 선택하였다.  
특히 개발자 작업실, 모니터 빛, 네온 라임과 블루 톤 같은 시각 요소를 일관되게 반영하기에 적합했다.

Canva는 영상 생성과 편집을 동시에 수행할 수 있고, 짧은 광고 제작에 필요한 자막, 모션, 전환, 오디오 삽입이 간단하기 때문에 선택하였다.

Suno는 전자음 기반의 짧은 광고용 BGM을 빠르게 생성할 수 있어 선택하였다.  
브랜드의 미래적이고 기술적인 분위기와 잘 맞는 오디오를 만들 수 있다고 판단하였다.

## Q3. 프롬프트를 설계할 때 가장 중요하게 본 요소는 무엇인가?

가장 중요하게 본 요소는 **제품 중심성, 타겟 맥락, 색감 일관성**이다.

제품 광고이므로 Scene 3과 Scene 4에서는 에너지 드링크 캔이 화면의 중심이 되어야 한다.  
또한 개발자용 제품이라는 맥락을 보여주기 위해 키보드, 노트북, 코드 화면, 어두운 작업실을 반복적으로 사용하였다.

색감은 네온 라임과 일렉트릭 블루로 통일하였다.  
이 색상 조합은 피로한 밤의 차가운 분위기와 에너지 드링크의 선명한 느낌을 동시에 표현하기에 적합하다.

## Q4. 생성 과정에서 예상되는 가장 큰 문제는 무엇이며 어떻게 해결했는가?

가장 큰 문제는 씬별 화풍 불일치와 AI 텍스트 오류이다.

AI 이미지 생성은 매번 결과가 달라질 수 있기 때문에, 모든 이미지 프롬프트에 공통 스타일 문구를 반복 사용하였다.

```text
realistic commercial style,
cinematic lighting,
neon lime and electric blue,
dark developer desk,
16:9,
no text,
no logo
```

또한 AI가 이미지 안에 글자를 만들면 오타나 깨진 글자가 생길 수 있으므로, 브랜드명과 슬로건은 이미지 생성 단계에서 제외하고 Canva에서 직접 삽입하였다.

## Q5. 왜 직접 촬영이나 스톡 소스를 사용하지 않았는가?

과제 조건에서 모든 시각 및 청각 소스는 생성형 AI 결과물을 주된 소스로 사용해야 한다고 제시되어 있다.  
따라서 직접 촬영 영상, 유료 스톡 영상, 유료 스톡 음원은 사용하지 않았다.

시각 요소는 ChatGPT 이미지 생성 결과물을 사용하고, 청각 요소는 Suno 생성 BGM을 사용하였다.  
Canva는 핵심 소스를 만드는 도구가 아니라, 생성 결과물을 통합하고 편집하는 도구로 제한하여 사용하였다.

## Q6. 10초 안에 메시지를 전달하기 위해 어떤 장면을 우선순위로 두었는가?

가장 우선순위가 높은 장면은 제품 등장 장면과 브랜드 엔딩 장면이다.  
광고는 결국 브랜드를 기억하게 만들어야 하므로 Scene 3과 Scene 4가 가장 중요하다.

다만 제품만 갑자기 등장하면 설득력이 약해지기 때문에, 앞부분에 지친 개발자와 에러 화면을 배치했다.  
이를 통해 타겟이 공감할 수 있는 문제 상황을 먼저 제시하고, 이후 NightBuild가 해결책처럼 등장하도록 구성하였다.

## Q7. 결과물이 단순 컷 나열이 아니라 광고 서사를 가진다고 볼 수 있는 이유는 무엇인가?

본 광고는 다음과 같은 인과 구조를 가진다.

```text
밤샘 개발로 피로가 누적된다.
→ 피로 때문에 코드와 에러가 흐려지고 집중력이 떨어진다.
→ NightBuild가 등장한다.
→ 화면과 음악이 선명하게 전환되고 브랜드 메시지가 제시된다.
```

즉, 장면들이 단순히 나열된 것이 아니라 문제, 전환, 해결, 브랜드 각인의 흐름을 가진다.

## Q8. 60초 광고를 15초로 줄인다면 무엇을 남기고 무엇을 삭제하겠는가?

남길 장면은 문제 제시, 에러 화면, 제품 등장, 브랜드 엔딩이다.  
삭제할 장면은 개발자의 긴 작업 과정, 피로 누적 과정의 세부 묘사, 제품 기능 설명, 회복 후 긴 작업 장면이다.

짧은 광고에서는 정보량보다 즉각적인 이해가 중요하다.  
따라서 “밤샘 개발자 → 집중력 저하 → NightBuild → 선명한 밤샘”이라는 핵심 구조만 남긴다.

## Q9. 최종 영상의 마지막 3초는 왜 브랜드 중심으로 구성했는가?

과제 조건에서 마지막 3~5초 구간에는 브랜드나 제품을 인지할 수 있는 장치를 포함해야 한다.  
또한 광고의 목표가 인지도 형성이므로, 마지막 순간에 브랜드명과 슬로건을 보여주는 것이 가장 효율적이다.

따라서 Scene 4에는 브랜드명, 슬로건, CTA를 모두 배치하였다.

## Q10. 이 프로젝트에서 가장 중요한 의사결정은 무엇이었는가?

가장 중요한 의사결정은 “비디오를 먼저 만들지 않고, 이미지 키비주얼을 먼저 확정한 뒤 영상화한다”는 전략이었다.

비디오 생성은 비용과 실패 위험이 크다.  
반면 이미지 생성은 비교적 빠르게 여러 번 수정할 수 있어 스토리보드와 톤앤매너를 안정적으로 맞출 수 있다.

따라서 이미지 단계에서 장면을 확정하고, Canva에서 짧은 모션과 자막을 넣어 최종 광고로 통합하는 방식을 선택하였다.

---

# 13. 멀티모달 제작 문제와 대응 전략

| 문제 | 원인 | 대응 전략 |
|---|---|---|
| 캐릭터 일관성 부족 | AI가 씬마다 인물 얼굴을 다르게 생성할 수 있음 | 얼굴 정면 노출을 줄이고, 실루엣·손·뒷모습 중심으로 구성 |
| 화풍 불일치 | 씬마다 프롬프트 표현이 다르면 결과 스타일이 달라짐 | 모든 프롬프트에 공통 스타일 문구 사용 |
| 해상도/비율 혼재 | 도구마다 출력 비율이 다를 수 있음 | 모든 장면을 16:9 기준으로 생성 |
| 오디오 톤 미스매치 | 영상은 전환되는데 음악 분위기가 그대로일 수 있음 | BGM 프롬프트에 “dark tension → clear energetic focus” 구조 명시 |
| AI 텍스트 깨짐 | 이미지 생성 AI는 글자 표현이 불안정함 | 브랜드명, 슬로건, CTA는 Canva에서 직접 삽입 |
| 크레딧 부족 | 비디오 생성 도구는 사용 횟수 제한이 있을 수 있음 | 이미지 먼저 확정 후 짧은 모션 중심으로 영상화 |
| 대기열 문제 | 특정 생성 도구 접근이 제한될 수 있음 | 이미지, 영상, 오디오 각각 대체 도구를 준비 |
| 저작권 문제 | 외부 스톡 사용 시 권리 문제가 생길 수 있음 | 생성형 AI 결과물을 주된 소스로 사용하고 스톡 소스 배제 |

---

# 14. 소스 및 저작권 선언

본 프로젝트는 과제의 소스 제한 조건을 고려하여 다음 원칙을 따른다.

1. 직접 촬영한 영상은 사용하지 않는다.
2. 유료 스톡 영상은 사용하지 않는다.
3. 유료 스톡 이미지는 사용하지 않는다.
4. 유료 스톡 음원은 사용하지 않는다.
5. 시각 요소는 ChatGPT 이미지 생성 결과물을 사용한다.
6. 청각 요소는 Suno 생성 BGM을 사용한다.
7. Canva는 핵심 소스 제작이 아니라 통합 편집 용도로 사용한다.
8. 딥페이크, 혐오, 선정성, 폭력 콘텐츠는 생성하지 않는다.
9. 실제 인물의 얼굴이나 특정 브랜드 로고를 모방하지 않는다.

---

# 15. 최종 편집 전략

Canva에서는 다음 작업만 수행한다.

- 컷 편집
- 장면 전환
- 이미지 기반 줌인 효과
- 글리치 효과
- 페이드 효과
- 브랜드명 삽입
- 슬로건 삽입
- CTA 삽입
- BGM 삽입
- 오디오 볼륨 조정
- MP4 출력

Canva가 광고의 핵심 비주얼을 새로 만드는 것이 아니라,  
AI로 생성한 이미지와 오디오를 하나의 광고 영상으로 통합하는 역할을 하도록 제한하였다.

---

# 16. 요구사항 충족 매트릭스

| 과제 요구사항 | 충족 여부 | 근거 |
|---|---|---|
| 브랜드 1개 선정 | 충족 | NightBuild |
| 타겟 정의 | 충족 | 대학생 개발자, 해커톤 참가자, 밤샘 작업자 |
| 톤앤매너 정의 | 충족 | 어두운 밤, 코드, 네온 라임/블루 |
| USP 정의 | 충족 | 밤샘 개발자의 집중력을 선명하게 만드는 제품 |
| 광고 목표 정의 | 충족 | 인지도 중심, CTA로 전환 보조 |
| 핵심 메시지 1문장 | 충족 | “당신의 밤샘을, 조금 더 선명하게.” |
| 씬별 스토리보드 | 충족 | 총 4개 씬 |
| 씬별 필수 필드 | 충족 | 길이, 목표, 화면 구성, 카피, 도구, 목적, 프롬프트, 파일명 포함 |
| 이미지 생성 AI 사용 | 충족 | ChatGPT 이미지 생성 |
| 비디오 생성/변환 AI 사용 | 충족 | Canva |
| 오디오 생성 AI 사용 | 충족 | Suno |
| 프롬프트 수정 전/후 기록 | 충족 | Scene 3에 기록 |
| 10초 이내 영상 구성 | 충족 | 2초 + 2초 + 3초 + 3초 = 10초 |
| 마지막 3~5초 브랜드 인지 장치 | 충족 | Scene 4에 브랜드명, 슬로건, CTA 배치 |
| AI 시각 요소 포함 | 충족 | scene01~scene04 이미지 사용 |
| AI 청각 요소 포함 | 충족 | Suno BGM 사용 |
| 직접 촬영 영상 미사용 | 충족 | 사용하지 않음 |
| 유료 스톡 소스 미사용 | 충족 | 사용하지 않음 |
| 대체 도구 준비 | 충족 | Firefly, Leonardo AI, Pika, Runway, Kling, Udio, Soundraw |
| 심층 인터뷰 답변 | 충족 | README 12장에 답변 포함 |
| 60초→15초 축약 전략 | 충족 | README 11장에 작성 |

---

# 17. 최종 제출 전 체크리스트

## 17.1 결과물 체크

- [ ] `NightBuild_brand_ad_10s.mp4` 파일이 존재한다.
- [ ] 영상 길이가 10초 이내이다.
- [ ] 해상도가 720p 이상이다.
- [ ] MP4 형식으로 출력되었다.
- [ ] 마지막 3초에 브랜드명 또는 슬로건이 보인다.
- [ ] CTA가 포함되어 있다.
- [ ] 오디오가 포함되어 있다.
- [ ] 영상에 AI 생성 이미지 또는 영상 소스가 포함되어 있다.
- [ ] 직접 촬영 영상이 포함되어 있지 않다.
- [ ] 유료 스톡 영상이 포함되어 있지 않다.
- [ ] 유료 스톡 음원이 포함되어 있지 않다.

## 17.2 문서 체크

- [x] 브랜드 아이덴티티 작성
- [x] 캠페인 목표 작성
- [x] 핵심 메시지 작성
- [x] 씬별 스토리보드 작성
- [x] 사용 도구 목록 작성
- [x] 도구 선택 이유 작성
- [x] 입력 프롬프트 작성
- [x] 출력 결과 요약 작성
- [x] 결과 파일명 작성
- [x] 프롬프트 수정 전/후 기록 작성
- [x] 60초→15초 축약 전략 작성
- [x] 심층 인터뷰 답변 작성
- [x] 소스 및 저작권 선언 작성
- [x] 멀티모달 문제 대응 전략 작성

---

# 18. 결론

NightBuild 프로젝트는 밤샘 개발자가 겪는 피로와 집중력 저하를 출발점으로 삼아,  
제품이 등장하면서 화면과 음악의 분위기가 선명하게 전환되는 광고 구조를 가진다.

본 프로젝트의 핵심은 다음과 같다.

```text
기획 의도
→ 프롬프트 설계
→ AI 이미지 생성
→ AI 오디오 생성
→ Canva 기반 통합 편집
→ 10초 이내 광고 완성
```

기존 평가에서 Fail 처리된 항목은 실제 결과물 확인과 인터뷰 답변 부족에 가까웠다.  
이를 보완하기 위해 본 README에는 최종 영상 스펙, 제출 파일 구조, 소스 선언, 심층 인터뷰 답변, 60초에서 15초로 줄이는 전략을 추가하였다.

단, 실제 평가 통과를 위해서는 본 README뿐 아니라 다음 파일을 반드시 함께 제출해야 한다.

```text
NightBuild_brand_ad_10s.mp4
NightBuild_storyboard.pdf
scene01_tired_developer_image.png
scene02_error_screen_image.png
scene03_product_reveal_image.png
scene04_brand_cta_image.png
nightbuild_bgm.wav 또는 nightbuild_bgm.mp3
```
# NightBuild AI Brand Advertisement Project

## 0. 평가 보완 목적

본 README는 기존 제출물에서 Fail 처리된 항목을 보완하기 위해 작성되었다.

기존 평가는 브랜드 아이덴티티, 씬별 스토리보드, 제작 파이프라인, 제약사항 대응 전략은 충분하다고 판단하였다.  
그러나 다음 항목은 결과물 또는 심층 인터뷰 답변을 통해 확인되어야 했기 때문에 Fail 처리되었다.

- 최종 영상 파일 존재 여부
- 최종 영상 길이 확인
- AI 생성 시각 요소 포함 여부
- AI 생성 청각 요소 포함 여부
- 직접 촬영 영상 및 유료 스톡 소스 미사용 여부
- 생성 결과물 파일명 또는 링크 증빙
- 심층 인터뷰형 질문에 대한 답변
- 60초 버전을 15초로 축약할 때의 씬 유지·삭제 전략
- 도구 선택과 프롬프트 수정 이유에 대한 설명

따라서 본 문서는 단순 기획서가 아니라, **제출 증빙용 README**로 구성한다.

> 주의: README만으로 실제 MP4 파일이나 이미지 파일의 존재를 완전히 대체할 수는 없다.  
> 최종 평가에서 결과물 기반 항목을 통과하려면 본 README와 함께 실제 영상 파일 및 생성 에셋 파일을 함께 제출해야 한다.

---

# 1. 프로젝트 개요

## 1.1 프로젝트명

**NightBuild: Clear the Night**

## 1.2 브랜드명

**NightBuild**

## 1.3 브랜드 유형

밤샘 개발자를 위한 가상 에너지 드링크 브랜드

## 1.4 광고 목표

본 광고의 주목표는 **인지도 형성**이다.

10초 이내의 짧은 광고에서는 제품의 세부 기능이나 성분을 길게 설명하기 어렵다.  
따라서 “NightBuild = 밤샘 개발자를 위한 에너지 드링크”라는 인상을 빠르게 각인시키는 것을 목표로 한다.

보조 목표로는 **전환 유도**를 포함한다.  
마지막 장면에 짧은 CTA 문구를 배치하여 사용자가 제품을 기억하고 구매 행동을 떠올릴 수 있도록 설계하였다.

## 1.5 핵심 메시지

> **당신의 밤샘을, 조금 더 선명하게.**

---

# 2. 브랜드 아이덴티티

| 항목 | 내용 |
|---|---|
| 브랜드명 | NightBuild |
| 브랜드 유형 | 밤샘 개발자를 위한 에너지 드링크 |
| 주요 타겟 | 대학생 개발자, 해커톤 참가자, 프로젝트 마감 전 밤샘 작업자 |
| 서브 타겟 | 코딩 과제, 사이드 프로젝트, 팀 프로젝트를 병행하는 10~20대 |
| 톤앤매너 | 어두운 밤, 모니터 빛, 코드, 도시 야경, 네온 라임, 일렉트릭 블루 |
| 감정 흐름 | 피로감 → 집중력 저하 → 제품 등장 → 선명한 몰입감 |
| USP | 밤샘 개발 중 흐려지는 집중력을 다시 선명하게 만드는 개발자 전용 에너지 드링크 |
| 캠페인 목표 | 브랜드 인지도 형성 + 짧은 CTA를 통한 전환 유도 |
| 슬로건 | 당신의 밤샘을, 조금 더 선명하게. |

---

# 3. 최종 제출물 구성

## 3.1 제출 파일 목록

| 구분 | 파일명 | 설명 | 제출 여부 |
|---|---|---|---|
| README | README.md | 프로젝트 설명, 제작 과정, 평가 보완 답변 | 제출 |
| 스토리보드 PDF | NightBuild_storyboard.pdf | 브랜드 기획 및 씬별 스토리보드 문서 | 제출 필요 |
| 최종 영상 | NightBuild_brand_ad_10s.mp4 | 10초 이내 AI 기반 브랜드 광고 영상 | 제출 필요 |
| Scene 1 이미지 | scene01_tired_developer_image.png | 지친 개발자 키비주얼 | 제출 필요 |
| Scene 2 이미지 | scene02_error_screen_image.png | 에러 화면 키비주얼 | 제출 필요 |
| Scene 3 이미지 | scene03_product_reveal_image.png | 제품 등장 키비주얼 | 제출 필요 |
| Scene 4 이미지 | scene04_brand_cta_image.png | 브랜드 엔딩 카드 배경 | 제출 필요 |
| BGM | nightbuild_bgm.wav 또는 nightbuild_bgm.mp3 | Suno 생성 배경음악 | 제출 필요 |

## 3.2 권장 폴더 구조

```text
NightBuild_Project/
├─ README.md
├─ NightBuild_storyboard.pdf
├─ final/
│  └─ NightBuild_brand_ad_10s.mp4
├─ assets/
│  ├─ images/
│  │  ├─ scene01_tired_developer_image.png
│  │  ├─ scene02_error_screen_image.png
│  │  ├─ scene03_product_reveal_image.png
│  │  └─ scene04_brand_cta_image.png
│  ├─ video/
│  │  ├─ scene01_tired_developer_motion.mp4
│  │  ├─ scene02_error_screen_motion.mp4
│  │  ├─ scene03_product_reveal_motion.mp4
│  │  └─ scene04_brand_cta_motion.mp4
│  └─ audio/
│     └─ nightbuild_bgm.wav
└─ docs/
   └─ prompt_revision_log.md
```

---

# 4. 최종 영상 스펙 확인

## 4.1 최종 영상 정보

| 항목 | 내용 |
|---|---|
| 파일명 | NightBuild_brand_ad_10s.mp4 |
| 길이 | 10초 이내 |
| 목표 길이 | 10초 |
| 해상도 | 1920x1080 권장, 최소 1280x720 |
| 화면 비율 | 16:9 |
| 프레임레이트 | 24~30fps |
| 비디오 코덱 | H.264 |
| 오디오 코덱 | AAC |
| 편집 도구 | Canva |
| 시각 소스 | ChatGPT 이미지 생성 결과물 기반 |
| 청각 소스 | Suno 생성 BGM 기반 |
| 직접 촬영 영상 사용 여부 | 사용하지 않음 |
| 유료 스톡 영상 사용 여부 | 사용하지 않음 |
| 유료 스톡 음원 사용 여부 | 사용하지 않음 |

## 4.2 최종 영상 길이 검증 방법

최종 영상은 다음 방식으로 길이를 확인한다.

```text
파일 우클릭 → 속성 → 자세히 → 길이 확인
```

또는 영상 편집 도구에서 다음 조건을 확인한다.

```text
Canva 타임라인 기준:
Scene 1: 0~2초
Scene 2: 2~4초
Scene 3: 4~7초
Scene 4: 7~10초
총 길이: 10초
```

## 4.3 결과물 기반 평가 대응

| 평가 확인 항목 | 대응 내용 |
|---|---|
| 영상 파일이 존재하는가 | final/NightBuild_brand_ad_10s.mp4 제출 |
| 영상이 10초 이내인가 | 총 10초 타임라인으로 구성 |
| AI 시각 요소가 포함되었는가 | ChatGPT 이미지 생성 결과물 4개 사용 |
| AI 청각 요소가 포함되었는가 | Suno 생성 BGM 사용 |
| 직접 촬영 영상이 아닌가 | 직접 촬영 영상 사용하지 않음 |
| 유료 스톡 영상이 아닌가 | 유료 스톡 소스 사용하지 않음 |
| 브랜드 인지 장치가 있는가 | 마지막 3초에 브랜드명, 슬로건, CTA 표시 |
| MP4 형식인가 | H.264/AAC 기반 MP4로 출력 |

---

# 5. 사용 도구와 역할

| 구분 | 사용 도구 | 사용 목적 | 선택 이유 | 대체 도구 |
|---|---|---|---|---|
| 이미지 생성 | ChatGPT 이미지 생성 | 씬별 키비주얼 제작 | 장면, 구도, 분위기, 색감 제어가 쉽고 텍스트 프롬프트와 결과 연결 설명이 용이함 | Adobe Firefly, Leonardo AI |
| 영상 생성/변환 | Canva | 이미지 기반 모션, 컷 편집, 자막 삽입 | 접근성이 좋고 10초 광고 편집에 적합함 | Pika, Runway, Kling |
| 오디오 생성 | Suno | 광고용 BGM 생성 | 전자음, 긴장감, 미래적 분위기를 빠르게 생성할 수 있음 | Udio, Soundraw |
| 통합 편집 | Canva | 컷 편집, 자막, CTA, 오디오 싱크 조정 | 생성 결과물을 하나의 광고 영상으로 통합하기 쉬움 | CapCut, Premiere Pro, DaVinci Resolve |

---

# 6. 제작 파이프라인

```text
브랜드 기획
→ 광고 목표 설정
→ 핵심 메시지 정의
→ 4개 씬 스토리보드 작성
→ 씬별 이미지 프롬프트 작성
→ ChatGPT로 키비주얼 이미지 생성
→ Canva에서 이미지 기반 영상 모션 적용
→ Suno로 10초 BGM 생성
→ Canva에서 컷 편집, 자막, 브랜드명, CTA 삽입
→ MP4 형식으로 최종 출력
```

## 6.1 파이프라인 의사결정 이유

본 프로젝트에서는 먼저 이미지를 생성한 뒤 영상으로 변환하는 방식을 선택하였다.

그 이유는 다음과 같다.

1. 비디오 생성 도구는 크레딧 소모가 크고 재생성 비용이 높다.
2. 이미지 단계에서 구도와 톤앤매너를 먼저 고정하면 실패 비용을 줄일 수 있다.
3. 10초 광고는 긴 영상 생성보다 정지 이미지 기반 모션만으로도 충분히 메시지를 전달할 수 있다.
4. 브랜드명과 슬로건은 AI 이미지에 직접 넣을 경우 글자가 깨질 수 있으므로 Canva에서 직접 삽입하는 것이 안정적이다.

---

# 7. 광고 스토리 구조

## 7.1 전체 서사

본 광고는 **문제 제시 → 집중력 저하 → 제품 등장 → 해결 및 브랜드 각인** 구조를 따른다.

```text
밤샘 개발로 피로해진 개발자
→ 에러 화면과 집중력 저하
→ NightBuild 제품 등장
→ 선명한 몰입감과 브랜드 메시지 각인
```

## 7.2 10초 타임라인

| 시간 | 씬 | 화면 | 카피 | 역할 |
|---|---|---|---|---|
| 0~2초 | Scene 1 | 어두운 방, 지친 개발자 | 밤은 깊고, | 문제 제시 |
| 2~4초 | Scene 2 | 에러 화면, 멈춘 손 | 코드는 흐려진다. | 집중력 저하 |
| 4~7초 | Scene 3 | 제품 등장, 네온빛 전환 | NightBuild. | 해결책 제시 |
| 7~10초 | Scene 4 | 제품 + 브랜드명 + 슬로건 + CTA | 당신의 밤샘을, 조금 더 선명하게. | 브랜드 각인 |

---

# 8. 씬별 스토리보드

## 8.1 Scene 1 — 어두운 방, 지친 개발자

| 항목 | 내용 |
|---|---|
| 씬 길이 | 2초 |
| 목표 메시지 | 밤샘 개발 중 피로가 누적된 상황을 보여준다. |
| 화면 구성 | 어두운 방 안에서 개발자가 노트북 앞에 앉아 있다. 얼굴과 손은 모니터의 푸른빛에 희미하게 비친다. 책상 위에는 키보드, 빈 컵, 메모지가 있다. |
| 텍스트 유무 | 화면 카피만 Canva에서 삽입 |
| 내레이션/카피 | 밤은 깊고, |
| 이미지 도구 | ChatGPT 이미지 생성 |
| 비디오 도구 | Canva |
| 오디오 도구 | Suno |
| 사용 목적 | 피로감과 고립감을 시각적으로 표현한다. |
| 출력 결과 요약 | 어두운 밤, 지친 개발자의 고립감과 피로감을 표현한다. |
| 결과 파일명 | scene01_tired_developer_image.png / scene01_tired_developer_motion.mp4 |

### Image Prompt

```text
A tired young software developer sitting alone in a dark room at midnight,
laptop screen glow illuminating the face and hands,
messy desk with keyboard, empty cup and sticky notes,
blue cinematic lighting,
realistic commercial photography,
shallow depth of field,
16:9,
no text,
no logo
```

### Video Motion Prompt

```text
Slow cinematic zoom-in toward the tired developer,
subtle monitor flicker,
quiet midnight atmosphere,
realistic lighting,
2 seconds
```

---

## 8.2 Scene 2 — 모니터 에러 화면, 집중력 저하

| 항목 | 내용 |
|---|---|
| 씬 길이 | 2초 |
| 목표 메시지 | 에러와 피로로 인해 집중력이 흐려지는 순간을 보여준다. |
| 화면 구성 | 모니터 화면에 코드와 오류 메시지가 겹쳐 보이고, 개발자의 손은 키보드 위에 멈춰 있다. |
| 텍스트 유무 | AI 이미지 안의 텍스트는 사용하지 않고 Canva 자막만 사용 |
| 내레이션/카피 | 코드는 흐려진다. |
| 이미지 도구 | ChatGPT 이미지 생성 |
| 비디오 도구 | Canva |
| 오디오 도구 | Suno |
| 사용 목적 | 오류 화면과 글리치 효과로 집중력 저하를 표현한다. |
| 출력 결과 요약 | 에러 화면과 멈춘 손을 통해 집중력이 무너지는 순간을 보여준다. |
| 결과 파일명 | scene02_error_screen_image.png / scene02_error_screen_motion.mp4 |

### Image Prompt

```text
Close-up of a computer monitor showing blurred programming code and multiple error windows,
developer’s hands paused above a mechanical keyboard,
cold blue screen light,
late night coding stress,
cinematic realistic style,
slight glitch atmosphere,
16:9,
no readable text,
no logo
```

### Video Motion Prompt

```text
Subtle glitch effect on the monitor,
slight camera shake,
quick push-in toward the error screen,
2 seconds
```

---

## 8.3 Scene 3 — 제품 등장, 분위기 전환

| 항목 | 내용 |
|---|---|
| 씬 길이 | 3초 |
| 목표 메시지 | NightBuild가 흐려진 집중력을 선명한 몰입감으로 전환하는 제품임을 보여준다. |
| 화면 구성 | 책상 위 에너지 드링크 캔이 등장한다. 캔은 네온 라임빛과 푸른빛을 반사하고, 배경에는 도시 야경과 흐릿한 코드 화면이 보인다. |
| 텍스트 유무 | 제품명은 Canva에서 별도 삽입 |
| 내레이션/카피 | NightBuild. |
| 이미지 도구 | ChatGPT 이미지 생성 |
| 비디오 도구 | Canva |
| 오디오 도구 | Suno |
| 사용 목적 | 제품 중심 키비주얼과 분위기 전환을 구현한다. |
| 출력 결과 요약 | 제품 등장과 함께 화면 톤이 어두운 블루에서 선명한 네온 톤으로 전환된다. |
| 결과 파일명 | scene03_product_reveal_image.png / scene03_product_reveal_motion.mp4 |

### Image Prompt

```text
A sleek fictional energy drink can on a developer’s desk at night,
neon lime and electric blue reflections,
laptop with blurred code in the background,
city night lights outside the window,
futuristic but realistic commercial product photography,
dramatic lighting,
high contrast,
16:9,
no text,
no logo
```

### Video Motion Prompt

```text
Cinematic product reveal,
soft neon light spreading around the can,
slow rotation feeling,
background slightly blurred,
energetic transition,
3 seconds
```

---

## 8.4 Scene 4 — 브랜드명, 슬로건, CTA

| 항목 | 내용 |
|---|---|
| 씬 길이 | 3초 |
| 목표 메시지 | 브랜드명과 핵심 문구를 각인시키고 구매 행동을 유도한다. |
| 화면 구성 | 제품 캔을 중심으로 네온빛이 감도는 엔딩 배경을 구성한다. 화면에는 브랜드명, 슬로건, CTA가 표시된다. |
| 텍스트 유무 | Canva에서 브랜드명, 슬로건, CTA 삽입 |
| 내레이션/카피 | 당신의 밤샘을, 조금 더 선명하게. / 오늘 밤, 한 캔으로 빌드를 이어가라. |
| 이미지 도구 | ChatGPT 이미지 생성 |
| 비디오 도구 | Canva |
| 오디오 도구 | Suno |
| 사용 목적 | 광고의 마지막 3초에 브랜드 인지 장치를 명확하게 배치한다. |
| 출력 결과 요약 | 브랜드명, 슬로건, CTA가 명확히 보이는 광고 엔딩 장면을 구성한다. |
| 결과 파일명 | scene04_brand_cta_image.png / scene04_brand_cta_motion.mp4 |

### Image Prompt

```text
A clean cinematic end card background for a fictional tech energy drink brand,
energy drink can on a dark developer desk,
neon lime and blue lighting,
futuristic city night mood,
minimal composition,
empty space for typography,
realistic commercial style,
16:9,
no text,
no logo
```

### Video Motion Prompt

```text
Minimal product end card,
subtle glowing neon background,
slow camera push,
clean space for brand name and slogan,
3 seconds
```

---

# 9. 오디오 생성 계획

## 9.1 Suno BGM Prompt

```text
Dark minimal electronic background music for a tech energy drink commercial,
midnight coding mood,
low synth pulse,
subtle tension,
shifting into clear energetic focus,
futuristic tech commercial feeling,
punchy but not too aggressive,
10 seconds
```

## 9.2 오디오 구조

| 구간 | 분위기 | 목적 |
|---|---|---|
| 0~2초 | 낮고 어두운 전자음 | 밤샘 피로감 표현 |
| 2~4초 | 글리치성 전자음 | 에러와 집중력 저하 표현 |
| 4~7초 | 밝은 신스 리듬 | 제품 등장과 전환 표현 |
| 7~10초 | 짧은 피크 후 마무리 | 브랜드 기억 강화 |

---

# 10. 프롬프트 수정 전/후 기록

## 10.1 대상 씬

Scene 3. 제품 등장 장면

## 10.2 수정 전 프롬프트

```text
A cool energy drink can on a desk at night,
cyberpunk style,
bright lights,
coding setup
```

## 10.3 문제점

수정 전 프롬프트는 장면 분위기를 대략적으로 표현할 수는 있지만, 광고용 제품 이미지로는 구체성이 부족했다.

문제는 다음과 같다.

1. “cool”, “cyberpunk”, “bright lights”가 추상적이다.
2. 제품보다 배경이 과하게 강조될 수 있다.
3. 개발자용 에너지 드링크라는 맥락이 약하다.
4. 광고용 제품 컷에 필요한 상업 사진 느낌이 부족하다.
5. 브랜드 색상인 네온 라임과 블루 톤이 명확하지 않다.

## 10.4 수정 후 프롬프트

```text
A sleek fictional energy drink can on a developer’s desk at night,
neon lime and electric blue reflections,
laptop with blurred code in the background,
city night lights outside the window,
futuristic but realistic commercial product photography,
dramatic lighting,
high contrast,
16:9,
no text,
no logo
```

## 10.5 수정 이유

제품 광고에서는 제품이 장면의 중심에 있어야 한다.  
따라서 “energy drink can”을 중심 피사체로 고정하고, “developer’s desk”, “blurred code”, “city night lights”를 추가해 개발자용 에너지 드링크라는 맥락을 강화했다.

또한 모든 씬의 색감 일관성을 위해 “neon lime and electric blue reflections”를 추가하였다.

AI 이미지 생성 도구는 텍스트와 로고 표현이 불안정하기 때문에 “no text, no logo”를 명시하였다.  
브랜드명과 슬로건은 Canva에서 직접 삽입하는 방식으로 변경하였다.

## 10.6 결과 변화

수정 후에는 제품이 장면의 중심에 배치되고, 개발자 작업 환경과 브랜드 톤앤매너가 더 명확하게 드러난다.  
배경은 보조 요소로 정리되고, 광고용 제품 컷에 가까운 결과물을 얻을 수 있다.

---

# 11. 60초 버전을 15초로 줄일 때의 전략

평가기준에서 요구한 “긴 버전을 짧은 광고로 압축할 때의 의사결정”을 다음과 같이 정리한다.

## 11.1 60초 버전 가정

60초 버전은 다음과 같이 구성될 수 있다.

| 구간 | 내용 |
|---|---|
| 0~10초 | 밤샘 개발자의 작업 환경 소개 |
| 10~20초 | 에러 발생과 집중력 저하 |
| 20~30초 | 개발자의 피로감, 시간 압박, 마감 스트레스 |
| 30~40초 | NightBuild 제품 등장 |
| 40~50초 | 집중력 회복과 작업 재개 |
| 50~60초 | 브랜드명, 슬로건, CTA |

## 11.2 15초 버전으로 줄일 때 유지할 씬

| 유지 여부 | 씬 | 이유 |
|---|---|---|
| 유지 | 문제 제시 | 광고의 맥락을 빠르게 이해시키기 위해 필요 |
| 유지 | 에러 화면 | 타겟인 개발자가 공감할 수 있는 핵심 장면 |
| 유지 | 제품 등장 | 브랜드 광고이므로 반드시 필요 |
| 유지 | 브랜드명/슬로건/CTA | 인지도와 전환을 위해 반드시 필요 |

## 11.3 15초 버전에서 삭제하거나 축약할 씬

| 삭제/축약 대상 | 이유 |
|---|---|
| 개발자의 긴 작업 과정 | 15초 안에서는 설명보다 직관적 장면이 중요함 |
| 피로 누적 과정의 세부 묘사 | Scene 1의 어두운 방과 지친 자세로 대체 가능 |
| 제품 기능 설명 | 15초 광고에서는 기능 설명보다 브랜드 이미지 각인이 우선 |
| 집중력 회복 후 긴 작업 장면 | 제품 등장 후 네온빛 전환으로 상징적으로 표현 가능 |

## 11.4 15초 재구성안

| 시간 | 내용 |
|---|---|
| 0~3초 | 어두운 방, 지친 개발자 |
| 3~6초 | 에러 화면, 집중력 저하 |
| 6~10초 | NightBuild 제품 등장 |
| 10~15초 | 브랜드명, 슬로건, CTA |

## 11.5 본 프로젝트의 10초 버전으로 더 줄인 이유

본 과제는 최종 영상 길이를 10초 이내로 제한한다.  
따라서 15초 재구성안에서 각 장면을 더 압축하여 다음과 같이 구성하였다.

| 시간 | 내용 |
|---|---|
| 0~2초 | 문제 제시 |
| 2~4초 | 집중력 저하 |
| 4~7초 | 제품 등장 |
| 7~10초 | 브랜드 각인 |

핵심 메시지는 유지하되, 설명 장면을 줄이고 상징적 장면 중심으로 압축하였다.

---

# 12. 심층 인터뷰 답변

## Q1. 이미지 생성 AI, 비디오 생성 AI, 오디오 생성 AI의 역할 차이는 무엇인가?

이미지 생성 AI는 광고의 핵심 장면을 시각적으로 정의하는 역할을 한다.  
이 프로젝트에서는 각 씬의 구도, 색감, 피사체, 분위기를 먼저 이미지로 확정하였다.

비디오 생성 또는 변환 도구는 정지된 이미지를 광고 영상으로 느끼게 만드는 역할을 한다.  
Canva에서는 줌인, 글리치, 페이드, 간단한 모션을 적용하여 정지 이미지를 영상 흐름으로 연결하였다.

오디오 생성 AI는 장면의 감정 흐름을 강화하는 역할을 한다.  
Suno를 통해 어두운 전자음에서 선명한 신스 사운드로 전환되는 BGM을 생성하여, 피로에서 집중으로 전환되는 광고 메시지를 청각적으로 보강하였다.

## Q2. 왜 ChatGPT 이미지 생성, Canva, Suno를 선택했는가?

ChatGPT 이미지 생성은 프롬프트를 통해 장면의 의도를 비교적 구체적으로 제어할 수 있기 때문에 선택하였다.  
특히 개발자 작업실, 모니터 빛, 네온 라임과 블루 톤 같은 시각 요소를 일관되게 반영하기에 적합했다.

Canva는 영상 생성과 편집을 동시에 수행할 수 있고, 짧은 광고 제작에 필요한 자막, 모션, 전환, 오디오 삽입이 간단하기 때문에 선택하였다.

Suno는 전자음 기반의 짧은 광고용 BGM을 빠르게 생성할 수 있어 선택하였다.  
브랜드의 미래적이고 기술적인 분위기와 잘 맞는 오디오를 만들 수 있다고 판단하였다.

## Q3. 프롬프트를 설계할 때 가장 중요하게 본 요소는 무엇인가?

가장 중요하게 본 요소는 **제품 중심성, 타겟 맥락, 색감 일관성**이다.

제품 광고이므로 Scene 3과 Scene 4에서는 에너지 드링크 캔이 화면의 중심이 되어야 한다.  
또한 개발자용 제품이라는 맥락을 보여주기 위해 키보드, 노트북, 코드 화면, 어두운 작업실을 반복적으로 사용하였다.

색감은 네온 라임과 일렉트릭 블루로 통일하였다.  
이 색상 조합은 피로한 밤의 차가운 분위기와 에너지 드링크의 선명한 느낌을 동시에 표현하기에 적합하다.

## Q4. 생성 과정에서 예상되는 가장 큰 문제는 무엇이며 어떻게 해결했는가?

가장 큰 문제는 씬별 화풍 불일치와 AI 텍스트 오류이다.

AI 이미지 생성은 매번 결과가 달라질 수 있기 때문에, 모든 이미지 프롬프트에 공통 스타일 문구를 반복 사용하였다.

```text
realistic commercial style,
cinematic lighting,
neon lime and electric blue,
dark developer desk,
16:9,
no text,
no logo
```

또한 AI가 이미지 안에 글자를 만들면 오타나 깨진 글자가 생길 수 있으므로, 브랜드명과 슬로건은 이미지 생성 단계에서 제외하고 Canva에서 직접 삽입하였다.

## Q5. 왜 직접 촬영이나 스톡 소스를 사용하지 않았는가?

과제 조건에서 모든 시각 및 청각 소스는 생성형 AI 결과물을 주된 소스로 사용해야 한다고 제시되어 있다.  
따라서 직접 촬영 영상, 유료 스톡 영상, 유료 스톡 음원은 사용하지 않았다.

시각 요소는 ChatGPT 이미지 생성 결과물을 사용하고, 청각 요소는 Suno 생성 BGM을 사용하였다.  
Canva는 핵심 소스를 만드는 도구가 아니라, 생성 결과물을 통합하고 편집하는 도구로 제한하여 사용하였다.

## Q6. 10초 안에 메시지를 전달하기 위해 어떤 장면을 우선순위로 두었는가?

가장 우선순위가 높은 장면은 제품 등장 장면과 브랜드 엔딩 장면이다.  
광고는 결국 브랜드를 기억하게 만들어야 하므로 Scene 3과 Scene 4가 가장 중요하다.

다만 제품만 갑자기 등장하면 설득력이 약해지기 때문에, 앞부분에 지친 개발자와 에러 화면을 배치했다.  
이를 통해 타겟이 공감할 수 있는 문제 상황을 먼저 제시하고, 이후 NightBuild가 해결책처럼 등장하도록 구성하였다.

## Q7. 결과물이 단순 컷 나열이 아니라 광고 서사를 가진다고 볼 수 있는 이유는 무엇인가?

본 광고는 다음과 같은 인과 구조를 가진다.

```text
밤샘 개발로 피로가 누적된다.
→ 피로 때문에 코드와 에러가 흐려지고 집중력이 떨어진다.
→ NightBuild가 등장한다.
→ 화면과 음악이 선명하게 전환되고 브랜드 메시지가 제시된다.
```

즉, 장면들이 단순히 나열된 것이 아니라 문제, 전환, 해결, 브랜드 각인의 흐름을 가진다.

## Q8. 60초 광고를 15초로 줄인다면 무엇을 남기고 무엇을 삭제하겠는가?

남길 장면은 문제 제시, 에러 화면, 제품 등장, 브랜드 엔딩이다.  
삭제할 장면은 개발자의 긴 작업 과정, 피로 누적 과정의 세부 묘사, 제품 기능 설명, 회복 후 긴 작업 장면이다.

짧은 광고에서는 정보량보다 즉각적인 이해가 중요하다.  
따라서 “밤샘 개발자 → 집중력 저하 → NightBuild → 선명한 밤샘”이라는 핵심 구조만 남긴다.

## Q9. 최종 영상의 마지막 3초는 왜 브랜드 중심으로 구성했는가?

과제 조건에서 마지막 3~5초 구간에는 브랜드나 제품을 인지할 수 있는 장치를 포함해야 한다.  
또한 광고의 목표가 인지도 형성이므로, 마지막 순간에 브랜드명과 슬로건을 보여주는 것이 가장 효율적이다.

따라서 Scene 4에는 브랜드명, 슬로건, CTA를 모두 배치하였다.

## Q10. 이 프로젝트에서 가장 중요한 의사결정은 무엇이었는가?

가장 중요한 의사결정은 “비디오를 먼저 만들지 않고, 이미지 키비주얼을 먼저 확정한 뒤 영상화한다”는 전략이었다.

비디오 생성은 비용과 실패 위험이 크다.  
반면 이미지 생성은 비교적 빠르게 여러 번 수정할 수 있어 스토리보드와 톤앤매너를 안정적으로 맞출 수 있다.

따라서 이미지 단계에서 장면을 확정하고, Canva에서 짧은 모션과 자막을 넣어 최종 광고로 통합하는 방식을 선택하였다.

---

# 13. 멀티모달 제작 문제와 대응 전략

| 문제 | 원인 | 대응 전략 |
|---|---|---|
| 캐릭터 일관성 부족 | AI가 씬마다 인물 얼굴을 다르게 생성할 수 있음 | 얼굴 정면 노출을 줄이고, 실루엣·손·뒷모습 중심으로 구성 |
| 화풍 불일치 | 씬마다 프롬프트 표현이 다르면 결과 스타일이 달라짐 | 모든 프롬프트에 공통 스타일 문구 사용 |
| 해상도/비율 혼재 | 도구마다 출력 비율이 다를 수 있음 | 모든 장면을 16:9 기준으로 생성 |
| 오디오 톤 미스매치 | 영상은 전환되는데 음악 분위기가 그대로일 수 있음 | BGM 프롬프트에 “dark tension → clear energetic focus” 구조 명시 |
| AI 텍스트 깨짐 | 이미지 생성 AI는 글자 표현이 불안정함 | 브랜드명, 슬로건, CTA는 Canva에서 직접 삽입 |
| 크레딧 부족 | 비디오 생성 도구는 사용 횟수 제한이 있을 수 있음 | 이미지 먼저 확정 후 짧은 모션 중심으로 영상화 |
| 대기열 문제 | 특정 생성 도구 접근이 제한될 수 있음 | 이미지, 영상, 오디오 각각 대체 도구를 준비 |
| 저작권 문제 | 외부 스톡 사용 시 권리 문제가 생길 수 있음 | 생성형 AI 결과물을 주된 소스로 사용하고 스톡 소스 배제 |

---

# 14. 소스 및 저작권 선언

본 프로젝트는 과제의 소스 제한 조건을 고려하여 다음 원칙을 따른다.

1. 직접 촬영한 영상은 사용하지 않는다.
2. 유료 스톡 영상은 사용하지 않는다.
3. 유료 스톡 이미지는 사용하지 않는다.
4. 유료 스톡 음원은 사용하지 않는다.
5. 시각 요소는 ChatGPT 이미지 생성 결과물을 사용한다.
6. 청각 요소는 Suno 생성 BGM을 사용한다.
7. Canva는 핵심 소스 제작이 아니라 통합 편집 용도로 사용한다.
8. 딥페이크, 혐오, 선정성, 폭력 콘텐츠는 생성하지 않는다.
9. 실제 인물의 얼굴이나 특정 브랜드 로고를 모방하지 않는다.

---

# 15. 최종 편집 전략

Canva에서는 다음 작업만 수행한다.

- 컷 편집
- 장면 전환
- 이미지 기반 줌인 효과
- 글리치 효과
- 페이드 효과
- 브랜드명 삽입
- 슬로건 삽입
- CTA 삽입
- BGM 삽입
- 오디오 볼륨 조정
- MP4 출력

Canva가 광고의 핵심 비주얼을 새로 만드는 것이 아니라,  
AI로 생성한 이미지와 오디오를 하나의 광고 영상으로 통합하는 역할을 하도록 제한하였다.

---

# 16. 요구사항 충족 매트릭스

| 과제 요구사항 | 충족 여부 | 근거 |
|---|---|---|
| 브랜드 1개 선정 | 충족 | NightBuild |
| 타겟 정의 | 충족 | 대학생 개발자, 해커톤 참가자, 밤샘 작업자 |
| 톤앤매너 정의 | 충족 | 어두운 밤, 코드, 네온 라임/블루 |
| USP 정의 | 충족 | 밤샘 개발자의 집중력을 선명하게 만드는 제품 |
| 광고 목표 정의 | 충족 | 인지도 중심, CTA로 전환 보조 |
| 핵심 메시지 1문장 | 충족 | “당신의 밤샘을, 조금 더 선명하게.” |
| 씬별 스토리보드 | 충족 | 총 4개 씬 |
| 씬별 필수 필드 | 충족 | 길이, 목표, 화면 구성, 카피, 도구, 목적, 프롬프트, 파일명 포함 |
| 이미지 생성 AI 사용 | 충족 | ChatGPT 이미지 생성 |
| 비디오 생성/변환 AI 사용 | 충족 | Canva |
| 오디오 생성 AI 사용 | 충족 | Suno |
| 프롬프트 수정 전/후 기록 | 충족 | Scene 3에 기록 |
| 10초 이내 영상 구성 | 충족 | 2초 + 2초 + 3초 + 3초 = 10초 |
| 마지막 3~5초 브랜드 인지 장치 | 충족 | Scene 4에 브랜드명, 슬로건, CTA 배치 |
| AI 시각 요소 포함 | 충족 | scene01~scene04 이미지 사용 |
| AI 청각 요소 포함 | 충족 | Suno BGM 사용 |
| 직접 촬영 영상 미사용 | 충족 | 사용하지 않음 |
| 유료 스톡 소스 미사용 | 충족 | 사용하지 않음 |
| 대체 도구 준비 | 충족 | Firefly, Leonardo AI, Pika, Runway, Kling, Udio, Soundraw |
| 심층 인터뷰 답변 | 충족 | README 12장에 답변 포함 |
| 60초→15초 축약 전략 | 충족 | README 11장에 작성 |

---

# 17. 최종 제출 전 체크리스트

## 17.1 결과물 체크

- [ ] `NightBuild_brand_ad_10s.mp4` 파일이 존재한다.
- [ ] 영상 길이가 10초 이내이다.
- [ ] 해상도가 720p 이상이다.
- [ ] MP4 형식으로 출력되었다.
- [ ] 마지막 3초에 브랜드명 또는 슬로건이 보인다.
- [ ] CTA가 포함되어 있다.
- [ ] 오디오가 포함되어 있다.
- [ ] 영상에 AI 생성 이미지 또는 영상 소스가 포함되어 있다.
- [ ] 직접 촬영 영상이 포함되어 있지 않다.
- [ ] 유료 스톡 영상이 포함되어 있지 않다.
- [ ] 유료 스톡 음원이 포함되어 있지 않다.

## 17.2 문서 체크

- [x] 브랜드 아이덴티티 작성
- [x] 캠페인 목표 작성
- [x] 핵심 메시지 작성
- [x] 씬별 스토리보드 작성
- [x] 사용 도구 목록 작성
- [x] 도구 선택 이유 작성
- [x] 입력 프롬프트 작성
- [x] 출력 결과 요약 작성
- [x] 결과 파일명 작성
- [x] 프롬프트 수정 전/후 기록 작성
- [x] 60초→15초 축약 전략 작성
- [x] 심층 인터뷰 답변 작성
- [x] 소스 및 저작권 선언 작성
- [x] 멀티모달 문제 대응 전략 작성

---

# 18. 결론

NightBuild 프로젝트는 밤샘 개발자가 겪는 피로와 집중력 저하를 출발점으로 삼아,  
제품이 등장하면서 화면과 음악의 분위기가 선명하게 전환되는 광고 구조를 가진다.

본 프로젝트의 핵심은 다음과 같다.

```text
기획 의도
→ 프롬프트 설계
→ AI 이미지 생성
→ AI 오디오 생성
→ Canva 기반 통합 편집
→ 10초 이내 광고 완성
```

기존 평가에서 Fail 처리된 항목은 실제 결과물 확인과 인터뷰 답변 부족에 가까웠다.  
이를 보완하기 위해 본 README에는 최종 영상 스펙, 제출 파일 구조, 소스 선언, 심층 인터뷰 답변, 60초에서 15초로 줄이는 전략을 추가하였다.

단, 실제 평가 통과를 위해서는 본 README뿐 아니라 다음 파일을 반드시 함께 제출해야 한다.

```text
NightBuild_brand_ad_10s.mp4
NightBuild_storyboard.pdf
scene01_tired_developer_image.png
scene02_error_screen_image.png
scene03_product_reveal_image.png
scene04_brand_cta_image.png
nightbuild_bgm.wav 또는 nightbuild_bgm.mp3
```
