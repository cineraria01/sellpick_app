# 셀픽ai 공식 다운로드

[최신 버전 다운로드](https://github.com/cineraria01/sellpick_app/releases/latest)

- **macOS (Apple Silicon)**: `sellpick-darwin-arm64.app.zip`을 풀고 `sellpick.app`을 쓰기 가능한 Applications 폴더로 옮겨 실행합니다.
- **Windows (64비트)**: `sellpick-windows-amd64.zip`을 풀고 `sellpick.exe`를 실행합니다. WebView2와 FFmpeg/ffprobe 등 미디어 도구의 준비 상태는 앱 설정에서 확인합니다.
- GitHub의 “Source code” ZIP은 앱 설치 파일이 아닙니다.

앱은 새 버전을 확인하고 Ed25519 서명과 SHA-256을 검증한 뒤 안전하게 교체합니다. 작업·저장이 끝난 홈 화면에서 자동 재시작하거나 설정에서 저장 후 재시작할 수 있습니다. 프로젝트와 설정은 앱 밖에 보관됩니다.

현재 macOS 앱은 ad-hoc 서명이며 Apple Developer ID 공증과 Windows Authenticode는 적용되지 않았습니다. 업데이트 무결성 서명과 OS 코드 서명은 별개입니다.

이 저장소는 앱 배포 전용입니다. 소스 코드는 포함하지 않습니다.
