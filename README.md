# 💚 대용량 틱톡 비디오 다운로더 5.0 🎥
대용량 TikTok 비디오 다운로더, 트위터 비디오 다운로더(HD), tiktok 비디오 다운로더, 워터마크 없는 tiktok 비디오 다운로더, tiktok 비디오 다운로더 no watermark, tiktok 비디오 다운로더 4k.

<div align="center">
  <a href="../../releases/latest">
    <img width="1000" alt="TikTok Video Downloader No Watermark Banner" src="assets/release.png" />
  </a>
</div>

### 고급 기능을 갖춘 현대적인 다운로더
  
[![Python](https://img.shields.io/badge/Python-3.13%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![PySide6](https://img.shields.io/badge/UI-PySide6-41CD52?style=for-the-badge&logo=qt&logoColor=white)](https://pypi.org/project/PySide6/)
[![requests](https://img.shields.io/badge/HTTP-requests-2496ED?style=for-the-badge&logo=python&logoColor=white)](https://pypi.org/project/requests/)
[![FFmpeg](https://img.shields.io/badge/External-FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)](https://ffmpeg.org/)
</div>

## 📋 목차
- [기능](#-key-features)
- [설치](../../releases)
- [사용법](#-usage)
- [스크린샷](showcase/showcase.md)
- [기여](CONTRIBUTING.md)
- [라이선스](LICENSE)

### 📜 라이선스
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge&logo=gnu&logoColor=white)](LICENSE)

## 🌟 주요 기능

### 🛠️ 핵심 기능
- **다운로드 지원**  
  YouTube, Vimeo 등 HTTP 스트림을 지원하는 플랫폼에서 비디오와 오디오 다운로드 가능.

- **스마트 플레이리스트 정리**  
  플레이리스트 이름으로 폴더를 자동 생성하여 정리 저장.

- **플레이리스트 다운로드**  
  몇 번의 클릭으로 전체 플레이리스트를 순차적으로 다운로드.

- **다양한 포맷 지원**  
  **MP4**(비디오), **MP3**, **M4A**, **WAV**, **AAC**, **FLAC**, **OPUS**, **VORBIS** 등 다양한 오디오 포맷으로 다운로드 가능하며, **고급 품질 제어** 지원.

- **고급 오디오 품질 제어** 🎵  
  무손실 추출 기능을 갖춘 혁신적인 오디오 처리 시스템:
  - **Smart Copy 모드**: M4A/AAC/OPUS 포맷에서 품질 손실 없음
  - **사용자 지정 비트레이트**: 128k, 192k, 256k, 320k, 또는 “best”
  - **원본 품질 유지**: 불필요한 재인코딩 방지
  - **고충실도 대체 모드**: 320k 비트레이트 + 48kHz 샘플링 (이전 192k + 44.1kHz 대비 개선)
  - **포맷별 자동 최적화**

- **고해상도 지원**  
  **8K, 4K, 2K, 1080p, 720p, 360p**까지 다운로드 가능. 설정에서 원하는 해상도 선택 가능.

- **모듈형 코드 구조**  
  코드가 `core/`, `ui/`, `tests/` 디렉토리로 완전히 리팩토링되어 유지보수 및 기여가 쉬움.

### 🛠️ 고급 기능
- **배치 처리**  
  여러 다운로드를 한 번에 큐에 추가하고 동시에 관리. 일시정지, 재개, 취소 모두 간단히 가능.

- **오디오 품질 혁신** 🎵  
  **67% 비트레이트 향상** 및 **무손실 추출**:
  - 오디오 비트레이트(128k~320k) 및 품질 유지 설정 가능  
  - Smart Copy 모드로 불필요한 재인코딩 방지  
  - 이전 버전에서 보고된 스펙트로그램 손실 문제 해결  
  - 모든 오디오 옵션에 친절한 툴팁 제공

- **프로필 관리**  
  사용자 이름, 프로필 사진, 다운로드 경로, 비디오 해상도, 오디오 포맷 등 선호 설정 저장 가능.

- **프로필 내보내기 / 가져오기**  
  프로필, 설정, 다운로드 기록, 프로필 사진을 하나의 ZIP 파일로 내보내고 다른 장치에서 복원 가능. 백업 및 마이그레이션에 적합.

- **드래그 앤 드롭 인터페이스**  
  앱 창으로 URL을 드래그하여 바로 추가 가능.

- **시스템 트레이 통합**  
  최소화 시 트레이에 상주하며 빠른 복원 및 종료 메뉴 제공.

- **향상된 다운로드 시스템**  
  대용량 파일 안정성 강화, 다중 다운로드 효율 개선.

- **큐 시스템 최적화**  
  전체 일시정지/재개, 프록시 기반 대역폭 제한 기능 포함.

- **자동 업데이트**  
  업데이트를 자동으로 확인하고 설치.

### 🎨 사용자 경험
- **다크 & 라이트 모드**  
  다크모드와 라이트모드 간 손쉽게 전환 가능.

- **에러 처리**  
  상세 로그 제공으로 디버깅 용이.

- **스케줄러**  
  특정 날짜와 시간에 자동 다운로드 예약 가능.

- **다운로드 기록**  
  과거 다운로드 내역을 앱 내에서 조회, 검색, 관리 가능.

- **향상된 알림 시스템**  
  다운로드 완료, 실패, 취소 시 알림 제공.

- **강화된 UI**  
  향상된 애니메이션, 반응성 개선, 컬러 구분 로그 및 검색/필터 기능 제공.

### 🔧 기술적 기능
- **FFmpeg 자동 감지**  
  FFmpeg 설치 여부를 자동으로 감지하고 없을 경우 설정 요청.
  
## 스크린샷

### 홈화면
![Image](assets/homepage.png)

### 비디오 페이지
![Image](assets/videopage.png)

### 오디오 페이지
![Image](assets/audiopages.png)

### 기록 페이지
![Image](assets/history.png)

## ⚙️ 설치

### Windows
- [Releases](../../releases)에서 최신 `.exe` 인스톨러 또는 `.zip` 아카이브 다운로드  
- FFmpeg 포함 모든 의존성 내장  
- 설치 또는 압축 해제 후 `Tok Downloader.exe` 실행  

## 🔧 사용법

### 기본 사용
```bash
# 앱 실행
python main.py
````

### 주요 기능 사용

* **설정(Settings)** 또는 **프로필(Profile)** 페이지에서 프로필 구성
* MP4 또는 MP3 탭에서 비디오 다운로드 또는 오디오 추출
* 큐 페이지에서 여러 다운로드를 동시에 관리
* 스케줄러를 이용해 예약 다운로드 설정

### 팁 & 트릭

* 드래그 앤 드롭으로 빠르게 URL 추가
* 시스템 트레이 활성화로 백그라운드에서 실행
* 스케줄러로 야간 시간대 다운로드 예약
* **오디오 품질**: “원본 유지: 예” + 320k 비트레이트 설정 시 최고 품질
* **무손실 오디오**: M4A/FLAC 포맷 + copy 모드 사용
* 프로필을 내보내어 손쉽게 마이그레이션

## ⚠️ 참고사항

### 요구사항

```bash
# FFmpeg 필수
# 오디오 추출, 비디오 병합 등 일부 기능은 FFmpeg에 의존합니다.
# FFmpeg이 설치되어 있고 PATH에 등록되어 있는지 확인하세요.

# 서드파티 라이브러리
# yt_dlp를 사용하여 다운로드 및 메타데이터 추출을 수행합니다.
# 자세한 내용은 yt_dlp GitHub 페이지를 참고하세요.
```

## 🙏 기여

### 기여 방법

```bash
# Tok Downloader 5.0 개선을 위한 기여를 환영합니다.
# GitHub를 통해 issue 또는 pull request를 제출해주세요.

# Tok Downloader 5.0 즐겁게 사용하세요!
🚀
```

### 개발 환경 설정

1. 저장소 Fork
2. 새 기능 브랜치 생성
3. 수정사항 적용
4. Pull Request 제출

## ⚠️ 법적 고지

Downloader는 독립적인 오픈소스 프로젝트입니다.
YouTube 및 Google과는 독립적으로 동작하며, 그들의 API를 사용하지 않습니다.
이 프로젝트는 YouTube 서비스 약관이나 정책에 구속되지 않습니다.

---

