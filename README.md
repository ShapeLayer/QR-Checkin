# QR Checkin
![](https://img.shields.io/badge/-expo-lightgrey)

[Download](https://github.com/ShapeLayer/QR-Checkin/releases/download/1/qrcheckin-1bdc4cb2c0a240c880ea502778206085-signed.apk)

안드로이드의 측면 버튼 앱 실행 기능은 iOS의 단축어 기능과 달리 웹사이트 링크를 바로 열기 어렵습니다. 그동안 PASS를 측면 버튼에 연결해놓고 QR 체크인을 사용했지만, 여전히 몇번 더 터치해야한다는 귀찮음이 있어 네이버 QR 체크인 화면을 바로 열어주는 앱을 만들었습니다.

## 설치 및 설정 방법
[애플리케이션 설치 / 설정](./docs/install.md) 문서를 확인하세요.  

## 알려진 문제 사항
[이슈 트래커](https://github.com/ShapeLayer/QR-Checkin/issues)에서 확인하세요.  

## 애플리케이션 직접 빌드하기
아래 세 명령줄 중 하나를 선택하여 빌드하세요.
```
expo build:android
expo build:android -t apk
expo build:android -t app-bundle
```
_Source: [Building Standalone Apps](https://docs.expo.io/distribution/building-standalone-apps/)_
