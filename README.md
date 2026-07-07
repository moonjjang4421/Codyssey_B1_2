# Codyssey_B1_2
# NightBuild AI Brand Advertisement Project

## 1. 프로젝트 개요

본 프로젝트는 생성형 AI를 활용하여 가상의 브랜드 광고를 기획하고,  
기획 의도에서 프롬프트 설계, AI 생성 결과물 제작, 통합 편집까지 이어지는  
멀티모달 광고 제작 파이프라인을 설계하는 것을 목표로 한다.

광고 대상 브랜드는 **밤샘 개발자를 위한 에너지 드링크 브랜드 `NightBuild`**이다.  
10초 이내의 짧은 광고 안에서 개발자가 밤샘 작업 중 겪는 피로와 집중력 저하를 보여주고,  
NightBuild가 이를 선명한 몰입감으로 전환하는 제품이라는 인상을 전달한다.

> 핵심 메시지: **“당신의 밤샘을, 조금 더 선명하게.”**

본 README에서는 과제 기획, 스토리보드, 사용 도구, 프롬프트 전략, 제작 파이프라인을 정리한다.  
영상 파일과 이미지 결과물 자체는 본 문서에서 생략한다.

---

## 2. 과제 목표

본 과제의 목표는 단순히 AI 이미지나 영상을 생성하는 것이 아니라,  
브랜드 광고 제작에 필요한 전체 과정을 스스로 설계하고 설명하는 것이다.

구체적인 목표는 다음과 같다.

1. 가상의 브랜드를 선정하고 브랜드 아이덴티티를 정의한다.
2. 광고의 목적과 핵심 메시지를 한 문장으로 명확히 설정한다.
3. 씬 단위의 스토리보드를 작성한다.
4. 이미지, 비디오, 오디오 생성 AI의 역할을 구분하여 사용한다.
5. 프롬프트가 결과물에 미치는 영향을 분석하고 수정 과정을 기록한다.
6. 생성 결과물을 하나의 광고 영상으로 통합하는 제작 흐름을 설명한다.
7. 멀티모달 제작 과정에서 발생할 수 있는 문제를 고려하고 대응 전략을 제시한다.

---

## 3. 브랜드 아이덴티티

| 항목 | 내용 |
|---|---|
| 브랜드명 | NightBuild |
| 브랜드 유형 | 밤샘 개발자를 위한 에너지 드링크 |
| 타겟 | 대학생 개발자, 해커톤 참가자, 프로젝트 마감 전 밤샘 작업을 하는 개발자 |
| 톤앤매너 | 어두운 밤, 모니터 빛, 코드, 도시 야경, 네온 라임과 블루 톤 |
| 핵심 감정 | 피로감 → 집중력 회복 → 선명한 몰입감 |
| USP | 밤샘 개발 중 흐려지는 집중력을 다시 선명하게 만드는 개발자 전용 에너지 드링크 |
| 캠페인 목표 | 브랜드 인지도 형성 및 짧은 CTA를 통한 전환 유도 |
| 핵심 메시지 | 당신의 밤샘을, 조금 더 선명하게. |

---

## 4. 캠페인 목표

본 광고의 주목표는 **인지도**이다.

10초 이내의 짧은 광고에서는 제품의 기능이나 성분을 자세히 설명하기 어렵다.  
따라서 이 광고는 “NightBuild = 밤샘 개발자를 위한 에너지 드링크”라는 이미지를 빠르게 각인시키는 것을 목표로 한다.

보조 목표로는 **전환**을 일부 포함한다.  
마지막 장면에 짧은 CTA를 삽입하여 사용자가 제품을 기억하고 구매 행동으로 이어질 수 있도록 설계한다.

### 목표 정리

| 목표 | 의미 | 적용 방식 |
|---|---|---|
| 인지도 | 브랜드를 기억하게 만들기 | 브랜드명, 슬로건, 제품 컷을 마지막 장면에 배치 |
| 전환 | 구매 또는 행동 유도 | CTA 문구 삽입 |
| 리텐션 | 기존 사용자의 재사용 유도 | 본 광고의 주요 목표에서는 제외 |

---

## 5. 광고 콘셉트

### 광고 제목

**NightBuild: Clear the Night**

### 광고 구조

광고는 총 4개의 씬으로 구성된다.

| 씬 | 역할 | 내용 |
|---|---|---|
| Scene 1 | 문제 제시 | 어두운 방에서 지친 개발자가 밤샘 작업을 하고 있다. |
| Scene 2 | 집중력 저하 | 모니터에 에러 화면이 나타나고 개발자의 손이 멈춘다. |
| Scene 3 | 전환 | NightBuild 제품이 등장하며 분위기가 선명하게 바뀐다. |
| Scene 4 | 브랜드 각인 | 브랜드명, 슬로건, CTA가 제시된다. |

### 전체 메시지 흐름

```text
밤샘 개발로 인한 피로
→ 코드와 에러로 인한 집중력 저하
→ NightBuild 등장
→ 선명한 몰입감과 브랜드 각인
```

---

## 6. 최종 영상 기획 정보

| 항목 | 내용 |
|---|---|
| 최종 영상 파일명 | NightBuild_brand_ad_10s.mp4 |
| 영상 길이 | 10초 이내 |
| 권장 해상도 | 1920x1080 |
| 최소 해상도 | 1280x720 |
| 화면 비율 | 16:9 |
| 프레임레이트 | 24~30fps |
| 비디오 코덱 | H.264 |
| 오디오 코덱 | AAC |
| 편집 도구 | Canva |

---

## 7. 사용 도구

| 구분 | 사용 도구 | 사용 목적 | 선택 이유 | 대체 도구 |
|---|---|---|---|---|
| 이미지 생성 | ChatGPT 이미지 생성 | 씬별 키비주얼 제작 | 장면, 구도, 분위기, 색감 제어가 용이함 | Adobe Firefly, Leonardo AI |
| 영상 생성/변환 | Canva | 이미지 기반 모션, 컷 편집, 자막 삽입 | 접근성이 좋고 짧은 광고 편집에 적합함 | Pika, Runway, Kling |
| 오디오 생성 | Suno | 배경음악 생성 | 전자음, 긴장감, 미래적 분위기 구현에 적합함 | Udio, Soundraw |
| 통합 편집 | Canva | 자막, 컷 편집, 오디오 조정 | 생성 결과물을 하나의 영상으로 통합하기 쉬움 | CapCut, Premiere Pro, DaVinci Resolve |

---

## 8. 제작 파이프라인

본 프로젝트의 제작 과정은 다음 순서로 진행된다.

```text
브랜드 기획
→ 광고 메시지 정의
→ 씬별 스토리보드 작성
→ 이미지 생성 프롬프트 설계
→ 키비주얼 이미지 생성
→ 이미지 기반 영상 변환
→ AI 배경음악 생성
→ Canva에서 컷 편집 및 자막 삽입
→ 최종 MP4 출력
```

### 단계별 설명

| 단계 | 설명 |
|---|---|
| 1. 브랜드 기획 | NightBuild의 타겟, 톤앤매너, USP를 정의한다. |
| 2. 메시지 정의 | “당신의 밤샘을, 조금 더 선명하게.”라는 핵심 메시지를 설정한다. |
| 3. 스토리보드 작성 | 10초 안에 들어갈 4개의 씬을 구성한다. |
| 4. 이미지 생성 | 각 씬의 키비주얼을 ChatGPT 이미지 생성으로 제작한다. |
| 5. 영상 변환 | Canva에서 이미지에 줌인, 글리치, 페이드 효과를 적용한다. |
| 6. 오디오 생성 | Suno에서 전자음 기반 BGM을 생성한다. |
| 7. 통합 편집 | Canva에서 자막, 브랜드명, 슬로건, CTA를 삽입한다. |
| 8. 최종 출력 | MP4 형식으로 10초 이내 광고 영상을 출력한다. |

---

## 9. 씬별 스토리보드

## Scene 1. 어두운 방, 지친 개발자

| 항목 | 내용 |
|---|---|
| 씬 길이 | 2초 |
| 목표 메시지 | 밤샘 개발 중 피로가 누적된 상황을 보여준다. |
| 화면 구성 | 어두운 방 안에서 개발자가 노트북 앞에 앉아 있다. 얼굴과 손은 모니터의 푸른빛에 희미하게 비친다. 책상 위에는 키보드, 빈 컵, 메모지가 있다. |
| 내레이션/카피 | 밤은 깊고, |
| 이미지 도구 | ChatGPT 이미지 생성 |
| 비디오 도구 | Canva |
| 오디오 도구 | Suno |
| 사용 목적 | 피로감과 고립감을 시각적으로 표현하고, 느린 줌인 효과로 밤샘 분위기를 강조한다. |
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

## Scene 2. 모니터 에러 화면, 집중력 저하

| 항목 | 내용 |
|---|---|
| 씬 길이 | 2초 |
| 목표 메시지 | 개발자가 에러와 피로로 인해 집중력을 잃는 순간을 보여준다. |
| 화면 구성 | 모니터 화면에 코드와 오류 메시지가 겹쳐 보이고, 개발자의 손은 키보드 위에 멈춰 있다. |
| 내레이션/카피 | 코드는 흐려진다. |
| 이미지 도구 | ChatGPT 이미지 생성 |
| 비디오 도구 | Canva |
| 오디오 도구 | Suno |
| 사용 목적 | 오류 화면, 멈춘 손, 글리치 효과를 통해 집중력 저하를 표현한다. |
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

## Scene 3. 제품 등장, 도시적인 빛과 함께 분위기 전환

| 항목 | 내용 |
|---|---|
| 씬 길이 | 3초 |
| 목표 메시지 | NightBuild가 피로한 밤샘 상황을 선명한 몰입감으로 전환하는 제품임을 보여준다. |
| 화면 구성 | 책상 위에 에너지 드링크 캔이 등장한다. 캔은 네온 라임빛과 푸른빛을 반사하고, 배경에는 도시 야경과 흐릿한 코드 화면이 보인다. |
| 내레이션/카피 | NightBuild. |
| 이미지 도구 | ChatGPT 이미지 생성 |
| 비디오 도구 | Canva |
| 오디오 도구 | Suno |
| 사용 목적 | 제품 중심 키비주얼을 만들고, 빛의 전환 효과로 분위기 변화를 표현한다. |
| 출력 결과 요약 | 제품 등장과 함께 색감이 피로한 블루 톤에서 선명한 네온 톤으로 전환된다. |
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

## Scene 4. 브랜드명, 슬로건, CTA

| 항목 | 내용 |
|---|---|
| 씬 길이 | 3초 |
| 목표 메시지 | 브랜드명과 핵심 문구를 각인시키고 구매 행동을 유도한다. |
| 화면 구성 | 제품 캔을 중심으로 네온빛이 감도는 엔딩 배경을 구성한다. 화면에는 브랜드명, 슬로건, CTA가 표시된다. |
| 내레이션/카피 | 당신의 밤샘을, 조금 더 선명하게. / 오늘 밤, 한 캔으로 빌드를 이어가라. |
| 이미지 도구 | ChatGPT 이미지 생성 |
| 비디오 도구 | Canva |
| 오디오 도구 | Suno |
| 사용 목적 | 브랜드명, 슬로건, CTA를 명확히 전달하는 엔딩 카드를 구성한다. |
| 출력 결과 요약 | 브랜드명과 슬로건이 명확히 보이는 광고 엔딩 장면을 구성한다. |
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

## 10. 오디오 기획

### Suno BGM Prompt

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

### 오디오 방향

| 구간 | 오디오 분위기 |
|---|---|
| 0~2초 | 낮고 어두운 전자음 |
| 2~4초 | 글리치 효과와 긴장감 |
| 4~7초 | 리듬 전환, 밝은 신스 |
| 7~10초 | 선명한 피크 후 짧은 마무리 |

---

## 11. 최종 영상 타임라인

| 시간 | 씬 | 화면 | 자막/카피 | 오디오 |
|---|---|---|---|---|
| 0~2초 | Scene 1 | 어두운 방, 지친 개발자 | 밤은 깊고, | 낮은 전자음 시작 |
| 2~4초 | Scene 2 | 모니터 에러 화면, 멈춘 손 | 코드는 흐려진다. | 글리치 효과음 |
| 4~7초 | Scene 3 | NightBuild 제품 등장 | NightBuild | 리듬 전환, 밝은 신스 |
| 7~10초 | Scene 4 | 제품 + 브랜드명 + 슬로건 + CTA | 당신의 밤샘을, 조금 더 선명하게. / 오늘 밤, 한 캔으로 빌드를 이어가라. | 음악 피크 후 마무리 |

---

## 12. 프롬프트 수정 전/후 기록

### 대상 씬

Scene 3. 제품 등장 장면

### 수정 전 프롬프트

```text
A cool energy drink can on a desk at night,
cyberpunk style,
bright lights,
coding setup
```

### 수정 전 문제점

수정 전 프롬프트는 장면의 분위기는 표현할 수 있지만 광고용 제품 이미지로는 구체성이 부족했다.  
“cool”, “cyberpunk”, “bright lights”와 같은 표현은 추상적이기 때문에 결과물이 과하게 화려해지거나,  
제품보다 배경이 더 강조될 가능성이 있었다.

또한 개발자용 에너지 드링크라는 맥락, 제품 중심 구도, 색감 일관성, 상업 사진 느낌이 부족했다.

### 수정 후 프롬프트

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

### 수정 이유

제품 광고에서는 제품이 장면의 중심에 있어야 한다.  
따라서 “energy drink can”을 중심 피사체로 고정하고,  
“developer’s desk”, “blurred code”, “city night lights”를 추가하여 개발자용 에너지 드링크라는 맥락을 강화했다.

또한 모든 씬의 색감 일관성을 위해 “neon lime and electric blue reflections”를 추가했다.  
AI 이미지 생성 과정에서 글자가 부정확하게 생성될 수 있으므로 “no text, no logo”를 넣고,  
브랜드명과 슬로건은 Canva에서 직접 삽입하도록 설계했다.

### 결과 변화

수정 후에는 제품이 장면의 중심에 배치되고,  
개발자 작업 환경과 브랜드 톤앤매너가 더 명확하게 드러난다.  
배경은 보조 요소로 정리되고, 광고용 제품 컷에 가까운 결과물을 얻을 수 있다.

---

## 13. 멀티모달 제작 문제와 대응 전략

| 문제 | 원인 | 대응 전략 |
|---|---|---|
| 캐릭터 일관성 부족 | AI가 씬마다 인물 얼굴을 다르게 생성할 수 있음 | 인물 얼굴을 반복 노출하지 않고, 실루엣·손·뒷모습 중심으로 구성 |
| 화풍 불일치 | 씬마다 프롬프트 표현이 다르면 결과 스타일이 달라짐 | 모든 프롬프트에 공통 스타일 문구 사용 |
| 해상도/비율 혼재 | 도구마다 기본 출력 비율이 다를 수 있음 | 모든 장면을 16:9 기준으로 생성 |
| 오디오 톤 미스매치 | 영상은 전환되는데 음악 분위기가 그대로일 수 있음 | BGM 프롬프트에 “dark tension → clear energetic focus” 구조 명시 |
| 텍스트 깨짐 | AI 이미지 생성은 글자 표현이 불안정함 | 브랜드명, 슬로건, CTA는 Canva에서 직접 삽입 |
| 크레딧 부족 | 비디오 생성 도구는 사용 횟수 제한이 있을 수 있음 | 이미지 먼저 확정 후 짧은 모션 중심으로 영상화 |
| 대기열 문제 | 특정 생성 도구 접근이 제한될 수 있음 | 이미지, 영상, 오디오 각각 대체 도구를 준비 |

### 공통 스타일 유지 문구

```text
realistic commercial style,
cinematic lighting,
neon lime and electric blue,
dark developer desk,
16:9,
no text,
no logo
```

---

## 14. 편집 전략

Canva는 생성형 AI 결과물을 조합하는 통합 편집 도구로 사용한다.  
영상의 핵심 비주얼과 오디오는 AI 생성 결과물을 주된 소스로 유지하고,  
Canva에서는 다음 작업만 수행한다.

- 컷 편집
- 장면 전환
- 자막 삽입
- 브랜드명 삽입
- 슬로건 삽입
- CTA 삽입
- 오디오 레벨 조정
- 간단한 줌인 및 페이드 효과 적용

이 방식은 과제의 제약 조건인 “편집 도구는 통합 편집 용도로만 제한적으로 사용”한다는 조건을 만족한다.

---

## 15. 파일명 규칙

| 파일 종류 | 파일명 |
|---|---|
| Scene 1 이미지 | scene01_tired_developer_image.png |
| Scene 1 영상 | scene01_tired_developer_motion.mp4 |
| Scene 2 이미지 | scene02_error_screen_image.png |
| Scene 2 영상 | scene02_error_screen_motion.mp4 |
| Scene 3 이미지 | scene03_product_reveal_image.png |
| Scene 3 영상 | scene03_product_reveal_motion.mp4 |
| Scene 4 이미지 | scene04_brand_cta_image.png |
| Scene 4 영상 | scene04_brand_cta_motion.mp4 |
| BGM | nightbuild_bgm.wav |
| 최종 영상 | NightBuild_brand_ad_10s.mp4 |
| 스토리보드 PDF | NightBuild_storyboard.pdf |

---

## 16. 요구사항 충족 여부

| 과제 요구사항 | 충족 여부 | 설명 |
|---|---|---|
| 브랜드 1개 선정 | 충족 | 가상 브랜드 NightBuild 선정 |
| 타겟 정의 | 충족 | 대학생 개발자, 해커톤 참가자, 밤샘 개발자 |
| 톤앤매너 정의 | 충족 | 어두운 밤, 코드, 네온 블루/라임, 도시적 분위기 |
| USP 정의 | 충족 | 밤샘 개발자의 집중력을 선명하게 만드는 개발자 전용 에너지 드링크 |
| 광고 목표 정의 | 충족 | 인지도 중심, CTA로 전환 요소 일부 포함 |
| 핵심 메시지 1문장 | 충족 | “당신의 밤샘을, 조금 더 선명하게.” |
| 씬별 스토리보드 | 충족 | 총 4개 씬 구성 |
| 씬별 필수 필드 | 충족 | 길이, 목표, 화면 구성, 카피, 도구, 목적, 프롬프트, 파일명 포함 |
| 이미지 생성 AI 사용 | 충족 | ChatGPT 이미지 생성 |
| 비디오 생성/변환 AI 사용 | 충족 | Canva |
| 오디오 생성 AI 사용 | 충족 | Suno |
| 프롬프트 수정 전/후 기록 | 충족 | Scene 3 제품 등장 장면에 기록 |
| 10초 이내 영상 구성 | 충족 예정 | 2초 + 2초 + 3초 + 3초 = 총 10초 |
| 마지막 3~5초 브랜드 인지 장치 | 충족 | Scene 4에 브랜드명, 슬로건, CTA 배치 |
| 도구 대체안 준비 | 충족 | 이미지, 비디오, 오디오 대체 도구 작성 |
| 제약사항 대응 | 충족 | 저작권, 크레딧, 비율, 텍스트 깨짐, 톤 미스매치 대응 전략 작성 |

---

## 17. 제출 체크리스트

### 스토리보드 문서

- [x] 브랜드명 작성
- [x] 타겟 작성
- [x] 톤앤매너 작성
- [x] USP 작성
- [x] 캠페인 목표 작성
- [x] 핵심 메시지 작성
- [x] 씬별 길이 작성
- [x] 씬별 목표 메시지 작성
- [x] 씬별 화면 구성 작성
- [x] 씬별 내레이션 또는 화면 카피 작성
- [x] 씬별 사용 도구와 목적 작성
- [x] 씬별 입력 프롬프트 작성
- [x] 씬별 출력 결과 요약 작성
- [x] 씬별 결과 파일명 작성
- [x] 프롬프트 수정 전/후 기록 작성
- [x] 대체 도구 작성

### 광고 영상

- [ ] MP4 형식으로 출력
- [ ] 10초 이내로 제작
- [ ] 720p 이상 해상도 확보
- [ ] AI 생성 시각 요소 포함
- [ ] AI 생성 청각 요소 포함
- [ ] 마지막 3초에 브랜드명 또는 슬로건 포함
- [ ] CTA 포함
- [ ] 자막 오타 확인
- [ ] 오디오 볼륨 확인
- [ ] 파일명 규칙 유지

---

## 18. 결론

NightBuild 광고는 밤샘 개발자가 겪는 피로와 집중력 저하를 출발점으로 삼아,  
제품이 등장하면서 분위기가 선명하게 전환되는 구조를 가진다.

이 프로젝트의 핵심은 단순히 AI 도구를 사용하는 것이 아니라,  
브랜드 기획 의도를 프롬프트로 구체화하고,  
이미지·영상·오디오 생성 결과물을 하나의 광고 경험으로 통합하는 제작 파이프라인을 설계했다는 점이다.

최종 광고는 다음 흐름을 따른다.

```text
지친 밤샘 개발자
→ 흐려지는 코드와 에러
→ NightBuild 등장
→ 선명한 집중감과 브랜드 각인
```

따라서 본 프로젝트는 과제에서 요구하는  
브랜드 정의, 멀티모달 생성 도구 활용, 스토리보드 문서화, 프롬프트 개선 기록,  
제작 제약 대응 전략을 모두 포함한다.
