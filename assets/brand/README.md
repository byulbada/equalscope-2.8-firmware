# 별바다 다이브 / Equalscope 브랜드 키트

회사명 **별바다 다이브** (BYULBADA DIVE) · 제품 브랜드 **Equalscope**.
로고 컨셉 = **별(★) + 파도(🌊)**. 별 = 주황, 파도 = 파랑.

## 대표 색상
| 용도 | HEX |
|------|-----|
| 주황 (별, primary) | `#FF6600` |
| 파랑 (파도, secondary) | `#0099FF` |
| 어두운 배경 (navy) | `#0D2137` |

## 파일

### 브랜드 키트 (이 폴더 = 원본)
| 파일 | 설명 |
|------|------|
| `byulbada-dive_symbol.svg` | 심볼 단독 (별+파도) |
| `byulbada-dive_logo_horizontal.svg` | 가로형 (심볼 + 워드마크) |
| `byulbada-dive_logo_horizontal_dark.svg` | 가로형 — 어두운 배경용 |
| `byulbada-dive_logo_stacked.svg` | 세로 적층형 |
| `byulbada-star_pattern.svg` | 배경 패턴 |
| `app-icon-1024.png` | 앱 아이콘 원본 (라이트) |
| `app-icon_navy-1024.png` | 앱 아이콘 원본 (네이비) |

### 웹 배포 아이콘 (repo 루트 — 자동 인식)
| 파일 | 용도 |
|------|------|
| `/favicon.svg` | 모던 브라우저 (= 심볼) |
| `/favicon.ico` | 레거시 브라우저 |
| `/apple-touch-icon.png` | iOS 홈 화면 (180) |
| `/icon-192.png`, `/icon-512.png` | PWA / Android (app-icon-1024 리사이즈) |
| `/site.webmanifest` | PWA 매니페스트 |

## 사용 메모
- 밝은 배경엔 일반 로고, 어두운 배경엔 `*_dark` 버전 사용.
- 앱 아이콘 192/512 는 `app-icon-1024.png` 에서 Pillow 리사이즈로 재생성 가능.
- 색상은 [[brand-colors]] 메모리와 동일. 변경 시 양쪽 동기화.
