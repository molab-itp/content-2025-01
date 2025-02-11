# Week 04 Swift UI 2, Audio

## [[Previous](./03_swiftui.md)] [[Next](./05_data.md)]

## Review

- [03-closures-ints-strings](https://github.com/molab-itp/03-closures-ints-strings)

  - Dictionary/Array/Struct/Class

- [Unwrap app](https://apps.apple.com/app/id1440611372)

  - Test your Swift coding fundamentals

- [03-ImageUiDemo-1-symbols](https://github.com/molab-itp/03-ImageUiDemo-1-symbols)

- [03-ImageUiDemo-2-urls](https://github.com/molab-itp/03-ImageUiDemo-2-urls)

- [03-UIGraphics-View](https://github.com/molab-itp/03-UIGraphics-View)

- [03-Canvas-Explore](https://github.com/molab-itp/03-Canvas-Explore)

## Lab

### [Week04-Demo](https://github.com/molab-itp/Week04-Demo)

<!-- - fix .gitignore

```
.DS_Store
**/xcuserdata/
``` -->

- using the asset catalog

```
Label("Shape1", image: "Shape1" )
```

- in class exercise:
  - remix and adapt for dynamic screen size
  - decode the docs for geometry reader

### prune Simulators list

```
>> Window : Devices and Simulators
  >> Simulators
    + To add one from list
>> Control click to delete
Prune to 16.4 and 17.2

>> Make sure iOS device selected as target
```

## data modeling

- [SwiftUI docs](https://developer.apple.com/documentation/swiftui)

- [Model data docs](https://developer.apple.com/documentation/swiftui/model-data)

  - Manage the data drive that drives your app interface.

- [Managing user interface state docs](https://developer.apple.com/documentation/swiftui/managing-user-interface-state)

  - Encapsulate view-specific data within your app’s view hierarchy to make your views reusable.

- [data modeling example code](https://developer.apple.com/documentation/swiftui/managing-model-data-in-your-app)

### Other App Exampples

- [100 days of swiftui - Starting SwiftUI](https://www.hackingwithswift.com/100/swiftui/36) Project7 iExpense Demo App

  - [HackingWithSwift repo](https://github.com/twostraws/HackingWithSwift.git)
  - [Project7 iExpense](https://github.com/twostraws/HackingWithSwift/tree/main/SwiftUI/project7)

#### the basics

- @Observable
- @State

```
@Observable
class DataModel {
    var name = "Some Name"

    @State private var model = DataModel() // Create the state object.
```

#### sharing data between views

- environment(
- @Environment(
- @Bindable

```
struct BookReaderApp: App {
    @State private var library = Library()
    LibraryView()
        .environment(library)

@Observable
class Library {
    var books: [Book] = [Book(), Book(), Book()]

struct LibraryView: View {
    @Environment(Library.self) var library: Library

@Preview {
    LibraryView()
        .environment(Library())

struct BookView: View {
    var book: Book

struct BookEditView: View {
     @Bindable var book: Book

```

## Audio State Demo App

- [04-SlideShowDemo](https://github.com/molab-itp/04-SlideShowDemo)

  - audio playback over slide show

- [04-Audio-State-Demo](https://github.com/molab-itp/04-Audio-State-Demo)

  - Demonstration of using AVAudioPlayer to play both internal and web based audio files
  - [AVAudioPlayer docs](https://developer.apple.com/documentation/avfaudio/avaudioplayer)

## Homework Week04

- create a Week04 folder for your homework project

- create your own SwiftUI app that incorporates time and/or audio playback. the app should have at least two pages

- add a link to your project stored in your Week04 folder on

  - [wiki home page week04](https://github.com/molab-itp/content-2025-01/wiki#week-04-homework)

- document your progress and questions on your wiki page

## Legacy code

### iOS 16 data modeling

- Warning! data modeling updated for iOS 17
- Projects that use ObservableObject must be updated

- [iOS 16 data modeling](./04_ObservableObject.md);
- [Migrating to iOS 17](https://developer.apple.com/documentation/swiftui/migrating-from-the-observable-object-protocol-to-the-observable-macro)

### UIKit & Storyboard UI

what came before SwiftUI

- https://developer.apple.com/documentation/uikit

  - ios 2.0+

- https://developer.apple.com/documentation/swiftui/
  - ios 13.0+

## Final Project Inspiration and Resources

- Possible basis and inspiration for final projects

- [Image-to-Ascii-Art](https://github.com/liamrosenfeld/Image-to-Ascii-Art)

  - An iOS app that can turn any image into ascii art

- [spritekit-using-spriteview](https://www.hackingwithswift.com/quick-start/swiftui/how-to-integrate-spritekit-using-spriteview)

  - SwiftUI’s SpriteView lets us render any SKScene subclass right inside SwiftUI

- [AudioKit/Cookbook](https://github.com/AudioKit/Cookbook)

  - "AudioKit Cookbook for iOS and macOS (via Catalyst)"
  - Consider audio capabities in this open source library for your final project

- [Simple SwiftUI](https://github.com/twostraws/simple-swiftui)

  - "Simple SwiftUI is a small but growing collection of projects designed to
    provide small sample projects for SwiftUI learners to read, learn from,
    modify, and even use as a basis for their projects in the future."

- [SwiftUI by Example](https://www.hackingwithswift.com/quick-start/swiftui)

  - "SwiftUI by Example is the world's largest collection of SwiftUI examples, tips, and techniques..."

- [creating_custom_symbol_images_for_your_app](https://developer.apple.com/documentation/uikit/uiimage/creating_custom_symbol_images_for_your_app)

<!--
## XCode indent preference\
- ![xcode pref indent](../assets/xcode-pref-indent.png)
-->
