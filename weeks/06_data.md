# Week 06 Local Data 2, More SwiftUI

## [[Previous](./05_data.md)] [[Next](./07_photo.md)]

## Plan

- review homework

- break

- review demos

## SwiftUI Demos

Examples of using data, typically stored as JSON, to describe the navigational layout of views.

- [iDine app](https://github.com/molab-itp/06-iDine)
  "restaurant app that lists items in a menu and helps folks place orders"

  - [source repo](https://github.com/twostraws/iDine)
  - [hackingwithswift.com swiftui-tutorial](https://www.hackingwithswift.com/quick-start/swiftui/swiftui-tutorial-building-a-complete-project)

## In Class Exercise

- Use the Router model for naviation
- Based on:

  - [03-ImageUiDemo-2-urls](https://github.com/molab-itp/03-ImageUiDemo-2-urls)
  - renaming and remixing Xcode project | recommended steps
  - [06-Router](https://github.com/molab-itp/06-Router)
    - Replaces NavigationView with Router @Observable class PageModel

- build BasicNav
  - from Build from Page9 [03-ImageUiDemo-1-symbols](https://github.com/molab-itp/03-ImageUiDemo-1-symbols)
  - add [03-UIGraphics-View](https://github.com/molab-itp/03-UIGraphics-View)
  - add PlayAudioView from [04-Audio-State-Demo](https://github.com/molab-itp/04-Audio-State-Demo)

## Saving Data Demos

- [05-ImageEditDemo](https://github.com/molab-itp/05-ImageEditDemo)

- [06-ImageEditDemoJSON](https://github.com/molab-itp/06-ImageEditDemoJSON/)

- [06-ChipsSaveJSON](https://github.com/molab-itp/06-ChipsSaveJSON)

- [06-Voice-Recorder](https://github.com/molab-itp/06-Voice-Recorder)
  - [source repo](https://github.com/pinlunhuang/Voice-Recorder)

## JSON saving and loading

- [06-ImageEditDemoJSON](https://github.com/molab-itp/06-ImageEditDemoJSON)
  - [use-codable-protocol-in-swift](https://www.kodeco.com/books/swift-cookbook/v1.0/chapters/4-use-codable-protocol-in-swift)
  - Generic functions in SaveLoadJSON.swift
  - Examine JSON file using Terminal App

## Evaluating open source resources

### AudioKit

- [AudioKit/Cookbook](https://github.com/AudioKit/Cookbook)
- [100-Lines-of-Code-AudioKit-Examples](https://github.com/NickCulbertson/100-Lines-of-Code-AudioKit-Examples)

```
# analyzing open source resources

https://www.youtube.com/watch?v=OoYEYCCJyCA&t=17s
How to Make a Synth App for iOS with AudioKit | 100 Lines of Code

https://github.com/NickCulbertson/100-Lines-of-Code-AudioKit-Examples
>> Disable DunneSamplerExample
>> Check out AppleSamplerExample
```

### Animation

- [animation repeatforever docs](<https://developer.apple.com/documentation/swiftui/animation/repeatforever(autoreverses:)>)
-
- [phase and keyframe animators ](https://developer.apple.com/documentation/swiftui/controlling-the-timing-and-movements-of-your-animations)
-
- [How to Pause and Resume Animation ](https://medium.com/@artemiusm/how-to-pause-and-resume-animation-in-swiftui-with-chaining-68003517449f)

  - https://github.com/artemiusmk/MovieClapper
  - https://github.com/jht9629-nyu/MovieClapper

- [airbnb lottie](https://airbnb.io/lottie/#/)
  - [github lottie ios](https://github.com/airbnb/lottie-ios)

```
## animation,

>> !!@ it ain't easy

https://medium.com/@artemiusm/how-to-pause-and-resume-animation-in-swiftui-with-chaining-68003517449f
https://github.com/artemiusmk/MovieClapper
https://github.com/jht9629-nyu/MovieClapper
How to Pause and Resume Animation in SwiftUI (with chaining)
Artem M -- Nov 22, 2022
https://medium.com/@artemiusm

[animation repeatforever docs](https://developer.apple.com/documentation/swiftui/animation/repeatforever(autoreverses:))

https://developer.apple.com/documentation/swiftui/controlling-the-timing-and-movements-of-your-animations
Controlling the timing and movements of your animations
https://developer.apple.com/videos/play/wwdc2023/10157/
https://developer.apple.com/videos/play/wwdc2024/10151/
https://developer.apple.com/documentation/SwiftUI/Creating-visual-effects-with-SwiftUI

## lottie

https://airbnb.io/lottie/#/
https://github.com/airbnb/lottie-ios

Lottie is named after a German film director
and the foremost pioneer of silhouette animation.
Her best known films are The Adventures of Prince Achmed (1926)
– the oldest surviving feature-length animated film,
preceding Walt Disney's feature-length Snow White
and the Seven Dwarfs (1937) by over ten years
https://www.youtube.com/watch?v=LvU55CUw5Ck
The Art of Lotte Reiniger parte 1

https://www.youtube.com/watch?v=poq0bf6M8Z8
Cinderella (Aschenputtel) —Lotte Reiniger, Karim Al-Zand

```

### User Interface service(s)

- [createwithplay.com](https://createwithplay.com/)

```

## createwithplay

https://createwithplay.com/

```

## Homework Week06

- Option 1: continue working on past homework

- Option 2: consider one of the options presented for saving data and add to your app

- create a Week06 folder for your project and add link to it here:

  - [wiki home page week06](https://github.com/molab-itp/content-2025-01/wiki#week-06-homework)

  - update your wiki page with your
    - progress,
    - problems,
    - plans, and
    - questions

## Final Project Inspiration and Resources

- [Hacking with iOS: SwiftUI Edition](https://www.hackingwithswift.com/books/ios-swiftui/)

  - [source repo](https://github.com/twostraws/HackingWithSwift)
    Follow steps to build app or start with completed app and study to adapt to your needs.

- [Project 8: Moonshot](https://www.hackingwithswift.com/books/ios-swiftui/moonshot-introduction)
  "Teach users about space history with scroll views"
  "How can we compose smaller views into larger ones to help keep our project organized?"

  - [source repo sub directory](https://github.com/twostraws/HackingWithSwift/tree/main/SwiftUI/project8)

- [Wiggles 🐶 app](https://github.com/molab-itp/06-Wiggles-iOS)
  "Beautiful Puppy adoption app built to Demonstrate the use of SwiftUI and MVVM Architecture."

  - [source repo](https://github.com/sameersyd/Wiggles-iOS)

- [Clubapartment app](https://github.com/molab-itp/06-swiftui.builds)
  "building cool stuff with swiftui"

  - [source repo](https://github.com/FranckNdame/swiftui.builds)

## WWDC Sample Code

Sample code is recommend starting point for exploring what's possible for a final project.
Download and verify the sample works before investing your time in further research.

- [WWDC sample code 2024](https://developer.apple.com/sample-code/wwdc/2024/)
  - AVCam: Building a camera app
- [WWDC sample code 2023](https://developer.apple.com/sample-code/wwdc/2023/)
- [WWDC sample code 2022](https://developer.apple.com/sample-code/wwdc/2022/)
- [WWDC sample code 2021](https://developer.apple.com/sample-code/wwdc/2021/)
- [WWDC sample code 2020](https://developer.apple.com/sample-code/wwdc/2020/)
