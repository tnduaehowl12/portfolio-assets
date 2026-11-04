# portfolio-assets

김도윤 로보틱스 포트폴리오에 넣는 **이미지·영상 자료**입니다.
노션 등 외부 문서에서 `raw.githubusercontent.com` 주소로 바로 불러 쓰려고 만들었습니다.

프로젝트 코드는 각 저장소에 있습니다 — [프로필](https://github.com/tnduaehowl12) 참고.

## 규칙

- 파일 하나당 **5 MB 이하**
- 영상은 **H.264 / 720p / MP4**
- 폴더는 프로젝트 단위: `scv` `coop-hub` `rc-car` `book-shelving` `rocycle` `roskin` `gesture`

## 들어 있는 것

| 경로 | 내용 | 비고 |
|---|---|---|
| `book-shelving/arm_demo_home.mp4` | 로봇팔 홈 자세 복귀 | 720p · 38초 |
| `book-shelving/arm_demo_shelfA.mp4` | 서가 A 배가 동작 | 720p · 96초 |
| `book-shelving/arm_demo_shelfB.mp4` | 서가 B 배가 동작 | 720p · 98초 |
| `book-shelving/full_cycle_20260923.mp4` | AMR 이동 → 파지 → 삽입 → 복귀 전체 사이클 | 1080p · 165초 |
| `book-shelving/return_kiosk_3d.png` | 무인반납기 3D 모델 (내부 컨베이어·투입구) | |
| `book-shelving/return_kiosk_3d_side.png` | 같은 모델 측면 | 작업 중 뷰 |
| `rocycle/cell_demo_20260911.mp4` | 컨베이어 추적·파지·분류 작업 셀 시연 | 720p · 50초 |
| `rocycle/roboflow_labeling.png` | 데이터 라벨링 (Roboflow) | |
| `scv/control_dashboard.png` | 관제 화면 — 설비 판정과 블랙박스 | |

영상은 모두 **원본 녹화본**이고, `rocycle/cell_demo_20260911.mp4` 만 1080p 46.8 MB 원본을
720p 640 kbps 로 다시 인코딩했습니다 (3.9 MB).

## 사용법

```
https://raw.githubusercontent.com/tnduaehowl12/portfolio-assets/main/<경로>
```

예: `https://raw.githubusercontent.com/tnduaehowl12/portfolio-assets/main/scv/control_dashboard.png`
