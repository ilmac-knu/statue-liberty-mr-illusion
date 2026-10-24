# 자유의 여신상 MR 착시 극장

기존 `statue-liberty-touch-mr`의 WebXR 카메라 배치·손가락 조작을 바탕으로,
빛나는 원형 무대, 상승 애니메이션, 반투명 등장, 광선·입자 효과를 추가한 교육용 MR 시각 연출 실험입니다.

> **주의:** 스마트폰 화면 밖으로 실제 빛을 투영하는 홀로그램 장치가 아닙니다.
> WebXR 기반 AR 공간 배치에 시각적 연출을 더한 체험입니다.

## 파일 구성

- `index.html`: 실행 화면 및 WebXR 코드
- `statue_of_liberty_1.glb`: 자유의 여신상 3D 모델 (별도로 업로드 필요)
- `README.md`: 프로젝트 설명

## 설치

1. 이 저장소에 `index.html`, `README.md`를 업로드합니다.
2. 기존 저장소 `statue-liberty-touch-mr`에서 `statue_of_liberty_1.glb`를 다운로드하여 **동일한 파일명으로 저장소 최상위**에 업로드합니다.
3. GitHub 저장소 **Settings → Pages → Build and deployment**에서 **Deploy from a branch**, **main / (root)**를 선택하여 저장합니다.
4. 배포 후 아래 주소에 접속합니다.

https://ilmac-knu.github.io/statue-liberty-mr-illusion/

## 체험

- **노트북**: 카메라 없이 3D 미리보기, 드래그 회전, 휠 확대·축소, 등장 효과 다시 보기
- **WebXR AR 지원 안드로이드 스마트폰**: Chrome에서 **MR 시작** → 책상 비추기 → 초록 원이 나타나면 화면 터치 → 무대 및 여신상 등장 → 손가락 조작
- **재배치**: AR 상태에서 `재배치` 버튼
- **다시 보기**: 배치 후 `등장 효과 다시 보기` 버튼

일부 스마트폰·브라우저에서는 WebXR `immersive-ar` 및 `dom-overlay`가 지원되지 않아 카메라 AR 또는 손가락 조작이 제한됩니다. iPhone Safari에서는 일반적으로 이 WebXR AR 흐름이 작동하지 않습니다.

## 출처 및 라이선스

자유의 여신상 3D 모델: **tech.service.allwe**,
[Sketchfab 원본](https://sketchfab.com/3d-models/statue-of-liberty-1-b3105217169b4ebbabeefb1d97e3696c),
[Creative Commons Attribution 4.0 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

Three.js 및 WebXR 사용. 원본 3D 모델의 저작자 표시를 유지하세요.
