## Firebase?

Firebase는 구글에서 제공하는 앱 내부 데이터 관리 서비스입니다.

개인 정보 등 민감한 정보를 안전하게 관리할 수 있고, 데이터베이스 및 클라우드 저장 공간처럼 사용할 수도 있습니다. 

현재는 구글의 다양한 인공지능 기술도 적용할 수 있습니다.

단, iOS 프로젝트를 등록하고 설정을 맞춰 줘야 편하게 이용할 수 있습니다.

이 과정에서 기존에 URL에서 받아오던 코드를 뜯어고쳐야 하고, CocoaPods를 사용해서 개발 환경이 바뀌는 등의 차이가 생깁니다.

## CocoaPods

[CocoaPods 공식 설명(영문)](https://guides.cocoapods.org/using/getting-started.html#getting-started "cocoapods")

저를 비롯한 iOS 초보 개발자들은 CocoaPods가 무엇인지, 왜 사용해야 하는지 다소 생소함을 느끼실 수도 있습니다.

CocoaPods 소개를 다음과 같이 번역해 봤습니다.

```
CocoaPods manages library dependencies for your Xcode projects.

CocoaPods는 당신의 Xcode 프로젝트의 라이브러리 의존성을 관리합니다.

The dependencies for your projects are specified in a single text file called a Podfile.

당신의 프로젝트의 (라이브러리) 의존성은 Podfile이라는 텍스트 파일에 정의됩니다.

CocoaPods will resolve dependencies between libraries, fetch the resulting source code, then link it together in an Xcode workspace to build your project.

CocoaPods는 라이브러리 간 의존성을 해결하고, 결과값 소스 코드를 가져오며, 이를 같이 Xcode workspace에 연결시켜 프로젝트를 빌드합니다.

Ultimately the goal is to improve discoverability of, and engagement in, third party open-source libraries by creating a more centralised ecosystem.

최종적인 목적은 더 중앙통제적인 개발 환경을 구축함으로써 서드파티 오픈소스 라이브러리를 활성화하고 참여를 유도하는 것입니다.
```

## iOS에서 Firebase 시작하기

제가 구현하고자 했던 기능을 중심으로 정리해 놓았습니다.

구글 Firebase 공식 문서 및 YouTube에 올려져 있는 자료들이며, CocoaPods를 정상적으로 설치했다면 쉽게 따라할 수 있습니다.

[iOS에서 시작하기](https://firebase.google.com/docs/storage/ios/start?hl=ko "Firebase Tutorial")

[iOS 프로젝트에 Firebase 추가](https://firebase.google.com/docs/ios/setup?hl=ko "Firebase Tutorial")

[iOS에서 Firebase 이미지 가져오기 (영문)](https://www.youtube.com/watch?v=GX4mcOOUrWQ "YouTube")

[iOS에서 Firebase 동영상 가져오기 (영문)](https://www.youtube.com/watch?v=4ISMTG-E3Po "YouTube")

[iOS에서 Firebase Storage 동영상 스트리밍하기 (영문)](https://www.youtube.com/watch?v=zG7qgyA5Gb4 "YouTube")


