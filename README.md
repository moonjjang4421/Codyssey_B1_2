from pathlib import Path
from shutil import copy2, make_archive
import textwrap

base = Path("/mnt/data/GENTLY_WOLF_DOCILE_RABBIT_AD")
assets = base / "assets"
assets.mkdir(parents=True, exist_ok=True)

source_map = {
    "/mnt/data/겨울밤_소중한_선물과_함께.png": assets / "scene01_keyvisual.png",
    "/mnt/data/겨울밤_공원의_따뜻한_선물.png": assets / "scene02_keyvisual.png",
    "/mnt/data/a_romantic_winter_night_scene_in_a_snowy_park_wid.png": assets / "scene03_keyvisual.png",
    "/mnt/data/a_cozy_romantic_winter_night_scene_overall_a_cine.png": assets / "scene04_keyvisual.png",
    "/mnt/data/heroine_reference.png": assets / "character_female_reference.png",
    "/mnt/data/hero_reference.png": assets / "character_male_reference.png",
    "/mnt/data/gently_wolf_product_reference.png": assets / "product_gently_wolf_reference.png",
    "/mnt/data/docile_rabbit_product_reference.png": assets / "product_docile_rabbit_reference.png",
}

missing = []
for src, dst in source_map.items():
    src_path = Path(src)
    if src_path.exists():
        copy2(src_path, dst)
    else:
        missing.append(src)

readme = r"""# GENTLY WOLF & DOCILE RABBIT  
## AI 기반 브랜드 초콜릿 광고 제작 프로젝트

> **핵심 메시지:** 사랑은, 서로 다른 달콤함으로 완성된다.  
> **영문 슬로건:** Love, Gently Given.

---

## 1. 미션 소개

본 프로젝트는 생성형 AI를 활용하여 기획 의도부터 이미지·영상·오디오 생성, 최종 편집까지 이어지는 브랜드 광고 제작 파이프라인을 설계하는 과제이다.

광고의 주제는 **사랑을 전하는 초콜릿 선물**이며, 서로 다른 성격과 디자인을 가진 두 제품을 통해 연인이 서로의 마음을 교환하는 장면을 표현한다.

- **GENTLY WOLF**: 절제된 열정과 세련됨을 상징하는 다크초콜릿
- **DOCILE RABBIT**: 순수함과 부드러움을 상징하는 화이트초콜릿

최종 영상은 단순한 컷 나열이 아니라 다음 구조를 가진다.

1. 남자가 약속 장소로 향함
2. 여자가 공원 벤치에서 기다림
3. 두 사람이 만나 초콜릿을 교환함
4. 서로 초콜릿을 건네며 브랜드 메시지를 전달함

---

## 2. 최종 결과물

### 2.1 제출 산출물

| 산출물 | 형식 | 상태 |
|---|---|---|
| 스토리보드 및 제작 문서 | README.md 또는 PDF | 작성 완료 |
| 핵심 키 이미지 | PNG 4개 | 생성 완료 |
| 인물·제품 레퍼런스 | PNG 4개 | 생성 완료 |
| 최종 광고 영상 | MP4, 10초 이내 | 제작 예정 |
| 배경음악·효과음 | AI 생성 오디오 | 제작 예정 |
| 로고·슬로건 오버레이 | PNG 또는 편집 텍스트 | 별도 제작 예정 |

### 2.2 권장 최종 영상 스펙

- 길이: **10초 이내**
- 화면 비율: **16:9**
- 해상도: **1920×1080**, 최소 1280×720
- 프레임레이트: **24~30fps**
- 비디오 코덱: **H.264**
- 오디오 코덱: **AAC**

---

## 3. 과제 목표

본 프로젝트를 통해 다음 내용을 설명할 수 있도록 한다.

1. 이미지·비디오·오디오 생성 AI의 역할과 차이
2. 브랜드 아이덴티티를 시각적 프롬프트로 변환하는 과정
3. 프롬프트 수정 전·후의 결과 차이와 수정 이유
4. 인물·제품·색감·화면 비율의 일관성을 유지하는 방법
5. AI 생성 결과물을 하나의 짧은 광고 영상으로 통합하는 과정
6. 영상 AI의 문자 왜곡, 손가락 오류, 제품 변형 문제에 대한 대응 방법

---

## 4. 기능 요구 사항

# 4.1 브랜드 아이덴티티

| 항목 | 내용 |
|---|---|
| 브랜드명 | GENTLY WOLF & DOCILE RABBIT |
| 제품군 | 프리미엄 선물용 초콜릿 |
| 광고 주제 | 사랑을 전하는 초콜릿 |
| 주요 타겟 | 연인에게 특별한 선물을 전하려는 20~30대 소비자 |
| 캠페인 목적 | 브랜드 인지도 향상 및 크리스마스·밸런타인데이 선물 수요 전환 |
| 톤앤매너 | 로맨틱, 겨울 감성, 시네마틱, 고급스러움, 따뜻함 |
| 차별점(USP) | 서로 다른 성격을 상징하는 두 초콜릿을 한 쌍의 사랑 이야기로 연결 |
| 핵심 메시지 | 사랑은, 서로 다른 달콤함으로 완성된다. |
| 영문 슬로건 | Love, Gently Given. |

## 4.2 제품 정의

### GENTLY WOLF — Dark Chocolate

- 검은색 직육면체 상자
- 댄디하고 절제된 디자인
- 자석 방식으로 부드럽게 열리는 구조
- 내부는 빨간색 플라스틱 트레이
- 하트 모양 다크초콜릿 10개
- 핵심 색상: 블랙, 다크 레드, 골드
- 상징 이미지: 절제된 열정, 신뢰, 성숙함

### DOCILE RABBIT — White Chocolate

- 아이보리·흰색 원형 상자
- 샴페인 색상의 리본으로 묶인 디자인
- 리본을 풀고 뚜껑을 여는 구조
- 내부는 검은색 플라스틱 트레이
- 하트 모양 화이트초콜릿 10개
- 핵심 색상: 아이보리, 블랙, 샴페인 골드
- 상징 이미지: 순수함, 부드러움, 따뜻함

---

# 4.3 제작 도구 목록

> 아래 내용은 현재 제작 계획을 기준으로 작성했다. 실제 최종 영상 제작에 사용한 도구가 달라질 경우 결과 제출 전 수정한다.

| 구분 | 주 도구 | 사용 목적 | 대체 도구 |
|---|---|---|---|
| 기획·프롬프트 | ChatGPT | 브랜드 정의, 스토리보드, 프롬프트 작성 | Notion AI |
| 이미지 생성 | ChatGPT 이미지 생성 | 키 이미지, 인물·제품 레퍼런스 제작 | Midjourney, Adobe Firefly |
| 비디오 생성 | Kling AI 또는 Runway | 이미지 투 비디오, 인물·제품 모션 생성 | Pika |
| 배경음악 | Suno | 겨울 로맨틱 피아노·오르골 BGM 생성 | Udio |
| 음성 합성 | ElevenLabs | 영문 또는 한국어 슬로건 내레이션 | CLOVA Dubbing |
| 통합 편집 | CapCut 또는 Premiere Pro | 컷 편집, 자막, 로고, 색보정, 오디오 레벨 조정 | DaVinci Resolve |

---

# 4.4 공통 스타일 프롬프트

```text
A premium cinematic chocolate commercial set during a snowy Christmas evening.
Soft falling snow, romantic winter atmosphere, elegant emotional storytelling,
realistic human expressions, luxurious product presentation,
warm golden streetlights contrasting with cool blue winter shadows,
shallow depth of field, subtle slow motion, high-end holiday commercial style,
visually refined, intimate, polished, consistent color grading, 4K quality.
