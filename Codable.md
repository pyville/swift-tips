## 서론

`Codable`에 호환되는 struct를 사용하면 `JSON`과의 상호 변환이 굉장히 편하다는 이점이 있습니다. 

앱 내부에서는 자체 데이터 형식으로 처리되고, 앱 바깥에서는 `JSON`을 사용하는 겁니다. 놀랍게도 `JSON`에 대한 깊은 지식도 필요하지 않습니다. 

이 부분을 더 알아보고, 현재 앱 내부에 저장되어 있는 정보를 빼내어 최종적으로는 웹의 `JSON` 파일을 가져오는 것을 구현해 보았습니다.

## Codable

[Codable 공식 문서](https://developer.apple.com/documentation/swift/codable, "Documentation")

[Codable 튜토리얼](https://developer.apple.com/documentation/foundation/archives_and_serialization/encoding_and_decoding_custom_types, "Tutorial")

`typealias Codable = Decodable & Encodable`

`Swift 4`에서 지원하기 시작한 규약(Protocol)입니다.

데이터를 내보내는 Encodable, 데이터를 가져오는 Decodable 방식이 합쳐진 것입니다.

개발자가 정의한 자료형을 JSON 파일로 변환해 내보내기, 가져온 JSON 파일을 개발자가 정의한 자료형으로 변환하기 두 가지가 자동적으로 수행됩니다.

## JSON

JavaScript Object Notation

JavaScript에서 처음 사용된 데이터 전송 양식입니다.

내부는 대략적으로 다음과 같이 작성되어 있으며, `XML`에 비해 간결한 표기법을 제공합니다.

```
{
    "회사": [
        {
           "이름": "Apple",
           "운영체제": [
               "macOS",
               "iOS"
           ]
        },
        {
           "이름": "Microsoft",
           "운영체제": [
               "MS-DOS",
               "Windows"
           ]
        }
    ]
}
```

JSON 예제 출처: [나무위키](https://namu.wiki/w/JSON, "namuwiki")


## References

[How to use Codable to load and save custom data types](https://www.hackingwithswift.com/example-code/language/how-to-use-codable-to-load-and-save-custom-data-types, "Reference")

[Parsing JSON Just Became Super Easy in Swift 4 with Decodable](https://www.youtube.com/watch?v=YY3bTxgxWss,"YouTube")

[Codable Hierarchies - Saving Data in iOS 11, Xcode 9, and Swift 4](https://www.youtube.com/watch?v=ZgILaLb0EcE,"YouTube")
