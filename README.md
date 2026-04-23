# CHROMA · 패드 컬러 랩

> 색의 조화를 관찰하는 방법 — 500 × 500 mm 마우스패드 색상 팔레트 스튜디오

**Live:** https://n-ightmar-e.github.io/chroma-pad/

편집 매거진 스타일의 컬러 팔레트 실험실. 기준 색을 정하고, 조화 방식(유사/보색/분할보색/삼색/사색/단색)을 고르면 5가지 색이 자동으로 추천되고, 실제 마우스패드에 적용된 모습을 2D/3D 목업으로 미리 볼 수 있습니다. 로고를 올리면 흰색 배경이 자동으로 투명화됩니다.

## 주요 기능

- **HSL 기반 팔레트 엔진** — 6가지 색 조화 알고리즘
- **8종 무드 프리셋** — 노을 · 바다 · 세이지 · 점토 · 벚꽃 · 먹 · 네온 · 숲
- **4종 패턴** — 단일 · 줄무늬 · 그라데이션 · 블록
- **리얼한 2D 목업** — 직물 질감, 광원, 비네팅, 스티치 엣지
- **3D 스튜디오 뷰** — Three.js `MeshPhysicalMaterial` + 3등 조명 + `OrbitControls`
- **로고 업로드** — 드래그앤드롭 / 흰색 자동 투명화 / 9-위치 배치
- **한국어 UI** — Gowun Batang · IBM Plex Sans KR · Instrument Serif

## 기술

단일 HTML 파일 (CSS + JS 인라인). Three.js는 CDN import map 사용. 의존성 없이 정적 호스팅에서 동작.

## 로컬 실행

```bash
python3 -m http.server 4800
# → http://localhost:4800
```

---

Issue №023 · 2026 · 04 · 26
