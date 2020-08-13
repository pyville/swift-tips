# swift-tips
프로그래밍 언어 Swift 및 iOS 개발에 대한 다양한 Tip을 공유합니다.

Slack에서 작업할 때 개인적으로 조사 및 번역한 내용을 Github에 옮겨 놓았습니다.

## 목차
### Storyboard와 SwiftUI

iOS의 대표적인 GUI 개발 환경으로 `Storyboard`가 있으나,

애플은 2019년 전격적으로 `SwiftUI`를 공개했습니다.

기술적인 차이 및 상호 보완에 대해 간략하게 작성했습니다.

[더 알아보기](https://github.com/pyville/swift-tips/blob/master/SwiftUI.md, "SwiftUI")

### DispatchQueue

멀티 쓰레드 (MultiThread) 처리를 위한 핵심적인 개념입니다.

`TableView`의 내용을 업데이트하는 것을 중심으로 정리해 보았습니다.

[더 알아보기](https://github.com/pyville/swift-tips/blob/master/DispatchQueue.md, "DispatchQueue")

### UIBlurEffect

`UIView`의 `UIVisualEffect`를 상속하여 블러 효과를 적용해 줍니다.

[더 알아보기](https://github.com/pyville/swift-tips/blob/master/BlurEffect.md, "BlurEffect")

### Codable과 JSON 데이터

`Codable`은 데이터를 안전하게 주고받기 위한 하나의 규약(Protocol)입니다.

`Codable`을 따르는 클래스나 구조체를 생성할 수 있습니다.

이를 통해 `JSON` 데이터를 내보내고 가져오는 과정에 대해 알아봅니다.

[더 알아보기](https://github.com/pyville/swift-tips/blob/master/Codable.md, "Codable")

### Firebase

`Firebase`는 Google에서 제공하는 솔루션으로, 

앱의 인증 정보, 데이터베이스, 저장 공간 등 백엔드 서버의 역할을 합니다.

`Firebase`를 사용하며 거친 시행착오에 대해 적어 보았습니다.

[더 알아보기](https://github.com/pyville/swift-tips/blob/master/Firebase.md, "Firebase")

### Skeleton View

`Skeleton View`는 Facebook 등의 앱에서 데이터가 로드될 때까지 나오는 회색 애니메이션인데요.

편리하게 구현하는 방법을 알아 보았습니다.

더 알아보기
