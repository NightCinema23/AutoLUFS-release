# AutoLUFS (배포용)

![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

**AutoLUFS**는 MP3/MP4 파일의 음량을 방송 표준(ITU-R BS.1770-4)에 맞춰 자동으로 조절해주는 프로그램입니다.
이 저장소는 **실행 파일(.exe / binary)** 배포를 위해 운영됩니다.

> **소스 코드 및 개발 기여**: [NightCinema](https://youtube.com/@nightcinema23?si=yZXi-72jm5n42xin)

---

## 📥 다운로드

우측의 **[Releases](https://github.com/NightCinema23/AutoLUFS-release/releases)** 페이지에서 최신 버전을 다운로드하세요.

- **Windows**: `AutoLUFS_vX.X.exe`

---

## ✨ 주요 기능

- **자동 음량 조절**: 목표 LUFS(예: -14, -16)에 맞춰 오디오 크기 자동 보정
- **간편한 사용**: 파일을 드래그 앤 드롭하여 로드
- **파형 시각화**: 보정 전후의 파형을 그래프로 비교
- **미리 듣기**: 변환 전 앱 내에서 결과물 미리 재생 가능
- **동영상 지원**: MP4 파일의 경우 영상은 그대로 두고 오디오만 교체하여 저장
- **FFmpeg 내장**: 별도의 코덱 설치 없이 바로 실행 가능

---

## 🚀 실행 방법

### Windows
1. 다운로드한 `.exe` 파일을 실행합니다.
2. **"Windows의 PC 보호"** 경고창이 뜰 경우:
   - `추가 정보` 클릭 -> `실행` 버튼 클릭
   - (개인 개발자가 서명하지 않은 앱이라 발생하는 현상입니다.)

---

## ⚠️ 바이러스 탐지 오진 (False Positive)

이 프로그램은 Python 소스 코드를 `PyInstaller`로 패키징한 것입니다.
서명되지 않은 실행 파일 특성상 일부 백신 프로그램에서 바이러스로 오진할 수 있습니다.