# myeongjulbakgua-privacy

이 저장소는 iOS 앱 **명절백과**의 개인정보 처리방침을 공개합니다.

- 공개 페이지: <https://jungbtc.github.io/myeongjulbakgua-privacy/>
- 문의: <https://github.com/jungbtc/myeongjulbakgua-privacy/issues>

앱은 회원가입과 로그인 없이 친족 관계를 기기 안에서 계산합니다. 광고 지원 버전은 결과 화면에 Google AdMob 배너를 표시하며, 이 정책은 광고 SDK의 데이터 처리도 설명합니다.

`index.html`은 광고 지원 버전의 데이터 처리를 설명합니다. 이전 광고 없는 버전에는 광고 SDK 관련 처리가 적용되지 않습니다. GitHub Pages는 `main` 브랜치에 게시된 파일을 배포합니다.

## AdMob 앱 소유권 인증

`app-ads.txt`에는 AdMob 계정에서 제공한 다음 인증 줄이 포함되어 있습니다.

```text
google.com, pub-2346753641001676, DIRECT, f08c47fec0942fa0
```

이 저장소의 파일 주소는 <https://jungbtc.github.io/myeongjulbakgua-privacy/app-ads.txt>입니다. **이 주소에 파일을 게시하는 것만으로 AdMob 인증이 완료되지는 않습니다.** Google은 App Store의 개발자 웹사이트(Marketing URL)를 기준으로 도메인 루트의 `/app-ads.txt`를 조회합니다. 개인정보 처리방침 URL은 별도 항목입니다.

2026년 11월 10일 확인한 App Store 개발자 웹사이트는 `https://seungohjung.com`이며, 해당 사이트의 `/app-ads.txt`는 404를 반환했습니다. 인증을 완료하려면 다음 중 하나가 필요합니다.

- 기존 개발자 웹사이트의 `https://seungohjung.com/app-ads.txt`에서 이 파일을 제공하거나 이 저장소의 공개 파일로 HTTP 리디렉션합니다.
- GitHub Pages를 개발자 웹사이트로 사용할 경우 `https://jungbtc.github.io/app-ads.txt`에서도 이 파일을 제공하고, App Store Marketing URL을 GitHub Pages 웹사이트 주소로 변경합니다. 루트 호스팅에는 별도의 `jungbtc.github.io` 사용자 사이트 저장소 등이 필요합니다.

도메인 루트에서 파일이 조회되고 App Store의 개발자 웹사이트가 일치하면 AdMob에서 **Check for updates**를 실행합니다. Google의 확인에는 최대 24시간이 걸릴 수 있습니다.

공식 안내: <https://support.google.com/admob/answer/9363762?hl=en>

