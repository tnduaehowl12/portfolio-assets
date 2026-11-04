# portfolio-assets

김도윤 로보틱스 포트폴리오에 넣는 **이미지·영상 자료**입니다.
노션 등 외부 문서에서 `raw.githubusercontent.com` 주소로 바로 불러 쓰려고 만들었습니다.

프로젝트 코드는 각 저장소에 있습니다 — [프로필](https://github.com/tnduaehowl12) 참고.

## 규칙

- 파일 하나당 **5 MB 이하**
- 영상은 **H.264 / 720p / MP4**
- 폴더는 프로젝트 단위: `scv` `coop-hub` `rc-car` `book-shelving` `rocycle` `roskin` `gesture`

## 들어 있는 것

| 폴더 | 파일 |
|---|---|
| `scv/` | `scv_demo_two_robots.mp4` (2대 동시 순찰 시연 · 챕터 자막 · 55초) · `scv_overview.png` · `scv_system_layout.png` · `scv_core_flow.png` · `rssi_heatmap.png` (계획 경로+실제 궤적+RSSI 히트맵+설비 8곳) · `control_dashboard.png` · `task_list.png` |
| `rocycle/` | `cell_demo_20260911.mp4` (연속 분류 시연 · 50초) · `system_architecture.png` · `hardware.png` · `process_chart.png` · `pipeline_8steps.png` · `calibration_improvement.png` · `roboflow_labeling.png` |
| `book-shelving/` | `full_cycle_20260923.mp4` (전체 사이클 · 2분 45초) · `arm_demo_shelfA.mp4` · `arm_demo_shelfB.mp4` · `arm_demo_home.mp4` · `diagram1_cycle_9steps.png` · `diagram2_carry_4segments.png` · `return_kiosk_3d.png` · `return_kiosk_3d_side.png` |
| `roskin/` | `force_entry.png` / `.svg` (힘 감지 진입 판정) · `flow_12step.png` / `.svg` (제조 12단계) |
| `coop-hub/` | `coophub_architecture.png` · `coophub_review_flow.png` |
| `rc-car/` | `flowchart.png` (탐지 → 출동 → 탐색 → 추종) |
| `gesture/` | (비어 있음) |

영상은 모두 **원본 녹화본**입니다. 다시 인코딩한 것은
`rocycle/cell_demo_20260911.mp4` 하나뿐으로, 1080p 46.8 MB 원본을 720p 640 kbps 로
줄였습니다 (3.9 MB).

## 사용법

```
https://raw.githubusercontent.com/tnduaehowl12/portfolio-assets/main/<경로>
```

예: `https://raw.githubusercontent.com/tnduaehowl12/portfolio-assets/main/scv/control_dashboard.png`
