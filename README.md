# 🚀 NEON OVERDRIVE 2099 - 3D Cyberpunk Runner

[![Three.js](https://img.shields.io/badge/Three.js-r128-00f0ff?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![HTML5](https://img.shields.io/badge/HTML5-Single--File-ff0077?style=for-the-badge&logo=html5)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Web Audio API](https://img.shields.io/badge/Web%20Audio-Procedural%20Synth-ffe600?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

> **네온 불빛이 번쩍이는 미래 사이버펑크 메트로폴리스 고속 하이웨이를 초광속으로 질주하는 3D 인터랙티브 미니 러너 게임!**  
> 외부 3D 에셋 파일이나 오디오 파일 없이, 순수 Three.js 기본 지오메트리 절차적 생성과 Web Audio API 실시간 합성 사운드로 완성된 **단 하나의 독립 실행형 HTML 파일(Single-File HTML)** 프로젝트입니다.

---

## 🎮 라이브 데모 (Live Demo)
👉 **[지금 브라우저에서 바로 플레이하기](https://jeiel85.github.io/cyberpunk-neon-runner-3d/)**

---

## ✨ 핵심 기능 및 기술적 특징 (Key Features)

1. **단 하나의 완전한 독립 실행형 파일 (Single-File Architecture)**
   - HTML5, 세련된 사이버펑크 글래스모피즘 CSS, JavaScript 로직, Three.js 씬 구성이 오직 `index.html` 파일 하나에 모두 담겨 있습니다.
   - 더블클릭만으로 모든 브라우저에서 즉시 실행됩니다.

2. **절차적 로우폴리 3D 렌더링 (Procedural 3D Generation)**
   - **Three.js WebGLRenderer & PCFSoftShadowMap**: 입체적인 그림자와 톤 매핑(ACESFilmicToneMapping) 적용.
   - **안개(FogExp2) 및 네온 대기감**: 짙은 사이버펑크 분위기를 자아내는 안개와 림라이트 연출.
   - **절차적 텍스처 & 스카이라인**: HTML Canvas로 실시간 렌더링된 네온 격자 도로 텍스처 및 무작위 높이와 발광 창문을 가진 70여 개의 마천루 빌딩.
   - **커스텀 사이버 호버카**: 쐐기형 차체, 리펄서 패드, 발광 사이언 핀, 배기 제트 엔진 및 다이내믹 틸팅(Banking) 물리 구현.

3. **풍부한 게임플레이 & 인터랙션 루프**
   - **반응형 3레인 조작**: 키보드(`A`/`D`, `←`/`→`) 차선 이동 및 부드러운 Lerp 보간.
   - **점프 부스트**: `W`, `Space`, `↑` 키를 활용한 레이저 장벽 회피.
   - **모바일 완벽 지원**: 화면 스와이프 제스처 및 전용 가상 방향키(◀, ▶, ▲) HUD 지원.
   - **점진적 난이도 곡선**: 주행 거리가 늘어남에 따라 하이웨이 속도가 점진적으로 가속.

4. **100% 무외부 Web Audio API 신디사이저 (Pure Procedural Audio)**
   - MP3나 WAV 파일 없이 브라우저 내장 오실레이터(OscillatorNode)와 필터(BiquadFilterNode)로 합성.
   - 80년대 레트로 신스웨이브 베이스라인 루프 BGM.
   - 아이템 획득 화음 챠임, 파워업 신스, 점프 사운드, 충돌 왜곡 노이즈 및 게임오버 FX 탑재 (음소거 토글 지원).

5. **다이내믹 파티클 & 비주얼 이펙트**
   - 초고속 질주감을 부여하는 워프 스피드라인 스트림(Speedlines).
   - 충돌 및 에너지 코어 수집 시 흩날리는 3D 네온 큐브 파티클 폭발.
   - 호버카 제트 엔진 후방 스파크 입자 시스템.
   - 피격 시 카메라 셰이크(Camera Shake) 및 무적 깜빡임 연출.

---

## 🕹️ 조작 방법 (Controls)

| 동작 (Action) | 데스크톱 키보드 (Desktop) | 모바일 (Mobile) |
| :--- | :--- | :--- |
| **좌 / 우 차선 이동** | `A` / `D` 또는 `←` / `→` | 화면 좌측 터치 버튼 (◀, ▶) 또는 좌우 스와이프 |
| **점프 회피** | `W` / `↑` / `Space` | 화면 우측 점프 버튼 (▲) 또는 위로 스와이프 |
| **오디오 토글** | 상단 우측 `AUDIO` 버튼 클릭 | 상단 우측 `AUDIO` 버튼 터치 |

---

## 🛠️ 기술 스택 (Tech Stack)

- **3D Graphics**: [Three.js (r128)](https://threejs.org/)
- **Audio Synthesis**: Native Web Audio API
- **Typography**: Google Fonts (Orbitron, Rajdhani)
- **Deployment**: GitHub Pages

---

## 📄 라이선스 (License)

이 프로젝트는 [MIT License](LICENSE)를 따릅니다. 누구나 자유롭게 수정 및 배포할 수 있습니다.
