# 화투부자

세로형 모바일 게임 앱입니다.

## 사용법

앞으로는 루트의 `index.html`만 교체하면 됩니다.

1. GitHub에서 `index.html` 교체
2. Commit changes
3. Actions → `Build Hwatu Rich APK`
4. 완료된 workflow → Artifacts → `hwatu-rich-debug-apk`
5. APK 설치

로컬 Android Studio, Java, Node.js, npm, Gradle은 필요 없습니다. GitHub Actions가 빌드를 수행합니다.

게임 HTML은 Android WebView의 로컬 asset으로 패키징되므로 게임 실행에 인터넷 권한이 필요하지 않습니다.
