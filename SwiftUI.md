## Storyboard와 SwiftUI

Storyboard: XML 기반 기존 방식. GUI를 이용한 직관적 UI 디자인에 코드를 입히는 형식. App의 화면이 많아질수록 느려지고 효율성이 떨어지는 문제가 있음.

[SwiftUI](https://developer.apple.com/kr/xcode/swiftui/ "SwiftUI"): Swift 기반 새로운 방식. 기본적으로 코드를 이용하며 미리보기를 통해 UI를 실시간으로 확인 및 편집 가능. 효율적이나 코드가 다소 낯설고 Storyboard에 익숙한 경우 개발 속도가 떨어질 수 있음.

## 병행하여 개발? 한쪽으로 통일?

*SwiftUI*로 프로젝트를 만들었으나, 다음과 같은 변칙적인 방법으로 실질적으로 *Storyboard*만 사용할 수 있음 [유튜브 링크](https://www.youtube.com/watch?v=AUaRegVfGBk "YouTube")

*Storyboard*와 *SwiftUI*를 병행하여 개발할 경우, 화면에 따라 다른 방식을 사용할 수 있음 [참고 링크](http://mtsparrow.blogspot.com/2019/10/xcode-11-storyboard-swiftui.html "Reference")

혹은 온라인에 공개된 Converter를 이용하여, *Storyboard*를 *SwiftUI*로 변환할 수 있음 [Converter](http://storyboard2swiftui.com/ "google link")

