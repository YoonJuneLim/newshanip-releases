# 뉴스한입 (NewsHanip) 설치 파일

**뉴스한입**은 국내외 언론사의 최근 기사를 한 화면에 모아 보여 주는 안드로이드 앱입니다.

- 여러 언론사가 함께 다룬 가장 큰 이슈를 기기 안의 AI(Gemini Nano)가 한 문장으로 요약하고, 요약에 쓴 기사 출처를 함께 보여 줍니다
- 환율·지수·코인 시세, 방송사 유튜브 생방송 바로가기
- 기사 품질 필터, 다크 모드, 홈 화면 위젯
- 서버·계정 없음. 기사 분석은 모두 기기 안에서 합니다

이 저장소에는 소스 코드가 없고, 버전마다 서명된 설치 파일(APK)만 올라옵니다.

## 내려받기

**[최신 버전 내려받기](https://github.com/YoonJuneLim/newshanip-releases/releases/latest)** → 아래 Assets에서 `NewsHanip-vX.Y.Z.apk`를 누르세요.

- 안드로이드 8.0 이상, 64비트 폰(최근 5년 안에 나온 폰은 대부분 됩니다)
- 처음 열 때 Wi-Fi에 연결돼 있으면 기사 필터용 분석 모델(약 135MB)을 한 번 받습니다

## 설치하기 ("출처를 알 수 없는 앱" 허용)

플레이 스토어 밖에서 받은 앱이라 설치할 때 경고가 몇 번 뜹니다. 어떤 앱이든 똑같이 뜨는 경고입니다.

1. 크롬에서 APK를 내려받습니다. "이 파일은 기기에 손상을 줄 수 있습니다"가 뜨면 **다운로드**를 누릅니다.
2. 받은 파일을 엽니다. "보안을 위해 이 출처의 알 수 없는 앱을 설치할 수 없습니다"가 뜨면 **설정 → 이 출처 허용**을 켜고 뒤로 갑니다.
   - 직접 켜려면: 설정 → 애플리케이션 → (메뉴) 특별한 접근 → 출처를 알 수 없는 앱 설치 → Chrome(또는 내 파일) → 허용
3. **설치**를 누릅니다.
4. "Play 프로텍트" 창이 뜨면 **세부정보 → 그래도 설치**를 누릅니다.

설치가 끝나면 2번에서 켠 허용은 다시 꺼도 됩니다.

## 업데이트

새 버전 APK를 받아 그대로 설치하면 덮어써지고, 설정과 기사도 그대로 남습니다. 지우고 다시 설치할 필요가 없습니다.

### 새 버전 알림 받기 (Obtainium)

[Obtainium](https://github.com/ImranR98/Obtainium)은 GitHub Releases를 확인해 새 버전이 나오면 알려 주고 바로 설치하게 해 주는 무료 앱입니다.

1. Obtainium을 설치합니다([Obtainium Releases](https://github.com/ImranR98/Obtainium/releases/latest)에서 `app-arm64-v8a-release.apk`).
2. Obtainium에서 **앱 추가(Add App)** → 주소에 `https://github.com/YoonJuneLim/newshanip-releases` 를 넣고 **추가(Add)**.
3. 이제 새 버전이 올라오면 알림이 오고, Obtainium에서 **업데이트**를 누르면 됩니다.

## 변경 내용

버전마다 [Releases](https://github.com/YoonJuneLim/newshanip-releases/releases)에 바뀐 점이 적혀 있습니다.

## 문의

앱의 설정 → 정보 → 문의하기
