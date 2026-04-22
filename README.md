# 모두의 검도 - Releases

모두의 검도 앱의 APK 배포용 레포.

## 최신 버전
[`latest.json`](./latest.json)에 최신 버전 정보가 있음. 앱이 이 파일을 읽어 업데이트를 감지.

## 배포 방법
1. `flutter build apk --release`
2. `gh release create v{버전} build/app/outputs/flutter-apk/app-release.apk#kendo_v{버전}.apk --repo da6262/kendo-releases`
3. `latest.json` 업데이트 후 main에 push
