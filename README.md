# Swiftui loop video player

  ![The concept](https://github.com/The-Igor/coreml-stable-diffusion-swift-example/blob/main/img/img_01.png)

## How to use the package
### 1. Create PlayerView

```swift
   PlayerView(resourceName: "swipe")
```

### Params

| Strategy | Description |
| --- | --- |
|**resourceName**| Name of the video to play|
|**extention**| Video extension |
|**errorText**| Error message text|
|**videoGravity**| A structure that defines how a layer displays a player’s visual content within the layer’s bounds |

## SwiftUI example for the package

[CoreML stable diffusion image generation](https://github.com/The-Igor/coreml-stable-diffusion-swift)

## Documentation(API)
- You need to have Xcode 13 installed in order to have access to Documentation Compiler (DocC)

- Go to Product > Build Documentation or **⌃⇧⌘ D**


* At the current time XCode 15 is in beta and in the console you might see message "A structure that defines how a layer displays a player’s visual content within the layer’s bounds" I found on Stack-overflow that many came across this message and at the time it is treated like XCode 15 beta bug
