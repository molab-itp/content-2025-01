# Week 07 Photo Media

## [[Previous](./06_data.md)] [[Next](./08_video.md)]

## Plan

- questions

- review homework

- summarize your challenges (and progress) on your wiki page

- feedback

- break

- photo library access

### Github .gitignore file

```

# How to establish global .gitignore file for github.com accouint

# create .gitignore in home directory
code ~/.gitignore
.DS_Store
**/xcuserdata/
node_modules

# verify created
more .gitignore

# establish global gitigore
git config --global core.excludesfile ~/.gitignore

# verify settings
more .gitconfig
...
[user]
        name = John Henry Thompson
        email = 78864877+jht9629-nyu@users.noreply.github.com
[core]
        excludesfile = /Users/jht2/.gitignore

```

### Animation

- [animation repeatforever docs](<https://developer.apple.com/documentation/swiftui/animation/repeatforever(autoreverses:)>)
-
- [phase and keyframe animators ](https://developer.apple.com/documentation/swiftui/controlling-the-timing-and-movements-of-your-animations)
-
- [How to Pause and Resume Animation ](https://medium.com/@artemiusm/how-to-pause-and-resume-animation-in-swiftui-with-chaining-68003517449f)

  - source: https://github.com/artemiusmk/MovieClapper
  - forked here: https://github.com/jht9629-nyu/MovieClapper

- [airbnb lottie](https://airbnb.io/lottie/#/)
  - [github lottie ios](https://github.com/airbnb/lottie-ios)

### Demo Apps

<!-- - [07-SlideShowDemo](https://github.com/molab-itp/07-SlideShowDemo)

  - use AudioDJ as environmentObject so that audio can presists between views
 -->

- [07-Instafilter](https://github.com/molab-itp/07-Instafilter)

  - A photo manipulation program using Core Image filters
  - uses PhotosPicker from import PhotosUI

  <!-- - [Hacking with iOS: SwiftUI Edition](https://www.hackingwithswift.com/books/ios-swiftui)
  - [Instafilter article](https://www.hackingwithswift.com/books/ios-swiftui/instafilter-introduction)
  - [source repo](https://github.com/twostraws/HackingWithSwift/tree/main/SwiftUI/project13)
  - uses ImagePicker: UIViewControllerRepresentable to access UIKit PHPickerViewController -->

- [07-PhotoPickBlender](https://github.com/molab-itp/07-PhotoPickBlender)

  - use Vision framework VNGeneratePersonSegmentationRequest to blend two photos
  - using legacy api via UIViewControllerRepresentable

- [07-FaceMesh](https://github.com/molab-itp/07-FaceMesh)

  - Face Mesh with ARKit and SwiftUI
  - using legacy api via UIViewControllerRepresentable

### Resources

- [PhotosPicker Apple Sample Code](https://developer.apple.com/documentation/photokit/bringing-photos-picker-to-your-swiftui-app)

  - click on pencil to edit profile pict

- [@Observable class - iOS 17](https://developer.apple.com/documentation/swiftui/managing-model-data-in-your-app)
- [from ObservableObject interface to @Observable macro](https://developer.apple.com/documentation/swiftui/migrating-from-the-observable-object-protocol-to-the-observable-macro)

### hackingwithswift

- [sharing-swiftui-state-with-observable](https://www.hackingwithswift.com/books/ios-swiftui/sharing-swiftui-state-with-observable)
- [adding-codable-conformance-to-an-observable-class](https://www.hackingwithswift.com/books/ios-swiftui/adding-codable-conformance-to-an-observable-class)

#### Legacy api's - prior to iOS 17

- [What’s the difference between @ObservedObject, @State, and @EnvironmentObject?](https://www.hackingwithswift.com/quick-start/swiftui/whats-the-difference-between-observedobject-state-and-environmentobject)

- [managing-model-data-in-your-app - apple dev doc](https://developer.apple.com/documentation/swiftui/managing-model-data-in-your-app)

- [Meet the new Photos picker - wwdc video tutorial](https://developer.apple.com/videos/play/wwdc2020/10652/)

- [Selecting Photos and Videos in iOS - apple dev doc](https://developer.apple.com/documentation/photokit/selecting_photos_and_videos_in_ios)

<!-- - [How to select images using PHPickerViewController with SwiftUI](https://levelup.gitconnected.com/how-to-select-images-using-phpickerviewcontroller-with-swiftui-da8bd3ec3d05) -->

<!-- - [How to obtain photo data/metadata after being picked in PHPickerViewController?](https://developer.apple.com/forums/thread/654898) -->

- [Creates a background color based on the average color of an image](https://github.com/bbaars/UIImageAverageColor)

  - [Article](https://medium.com/swlh/swiftui-read-the-average-color-of-an-image-c736adb43000)

- [CoreImageFilterReference ](https://developer.apple.com/library/archive/documentation/GraphicsImaging/Reference/CoreImageFilterReference/index.html)

<!-- - [methods_and_protocols_for_filter_creation - apple dev doc](https://developer.apple.com/documentation/coreimage/methods_and_protocols_for_filter_creation) -->

## Homework Week07

- Option 1: continue working on past homework

- Option 2: create an app to access or manipulate photos

  - you can base it on one of the resources presented in class, adding your own twist

- create a Week07 folder for your project and add link to it here:

  - [wiki home page week07](https://github.com/molab-itp/content-2025-01/wiki#week-07-homework)

  - update your wiki page with your
    - progress,
    - problems,
    - plans, and
    - questions

## Final Project Inspiration and Resources

- [Create 3D models with Object Capture - wwdc video 2021](https://developer.apple.com/videos/play/wwdc2021/10076/)

- [augmented-reality realitykit](https://developer.apple.com/augmented-reality/realitykit/)

- [augmented-reality object-capture/](https://developer.apple.com/augmented-reality/object-capture/)

## Example apps

- [Hacking with iOS: SwiftUI Edition](https://www.hackingwithswift.com/books/ios-swiftui/)

  - [Hacking with iOS: SwiftUI Edition - source github repo](https://github.com/twostraws/HackingWithSwift)
    Follow steps to build app or start with completed app and study to adapt to your needs.

  - [Hacking with iOS: SwiftUI Edition - Project 8: Moonshot](https://www.hackingwithswift.com/books/ios-swiftui/moonshot-introduction)
    - "Teach users about space history with scroll views"
    - "How can we compose smaller views into larger ones to help keep our project organized?"
    - [source repo sub folder](https://github.com/twostraws/HackingWithSwift/tree/main/SwiftUI/project8)
    - [extracted example jht9629-nyu/Moonshot](https://github.com/jht9629-nyu/Moonshot.git)
    - [fork jht9629-gmail/Moonshot](https://github.com/jht9629-gmail/Moonshot)

## WWDC Sample Code

Sample code is recommend starting point for exploring what's possible for a final project.
Download and verify the sample works before investing your time in further research.

- [WWDC sample code 2024](https://developer.apple.com/sample-code/wwdc/2024/)
  - [AVCam: Building a camera app](https://developer.apple.com/documentation/avfoundation/avcam-building-a-camera-app)
- [WWDC sample code 2023](https://developer.apple.com/sample-code/wwdc/2023/)
  - [Implementing an inline Photos picker](https://developer.apple.com/documentation/photokit/implementing-an-inline-photos-picker)
- [WWDC sample code 2022](https://developer.apple.com/sample-code/wwdc/2022/)
- [WWDC sample code 2021](https://developer.apple.com/sample-code/wwdc/2021/)
- [WWDC sample code 2020](https://developer.apple.com/sample-code/wwdc/2020/)
