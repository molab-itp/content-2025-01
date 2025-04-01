# Week 09 Multi User Experience 1

## [[Previous](./08_video.md)] [[Next](./10_multi.md)]

## Plan

- review homework

- questions

- summarize your challenges (and progress) on your wiki page

- saving data local on the device and remotely in the cloud

- Testflight update of MoGallery confirm - post an image

## Review - tracking time

- [Slide Show Delay](https://github.com/molab-itp/09-SlideShowDelay)

  - slide show with slider for delay

- [CaptureRecorder](https://github.com/jht9629-nyu/CaptureRecorder.git)
  - apply core image filters to live video stream from camera
  - record button to save video to Photo library
  - minminal ObservableObject Model
  - no need for Combine!

## Map Demo Apps

- [09-Location](https://github.com/molab-itp/09-Location)

  - in Simulator > Location > Features > Custom Location

- [09-Bucketlist](https://github.com/molab-itp/09-Bucketlist)

  - Saves data to local Documents folder as SavedPlaces JSON file

## Saving Data - Local

- [05-ImageEditDemo](https://github.com/molab-itp/05-ImageEditDemo)

- [06-ChipsSaveJSON](https://github.com/molab-itp/06-ChipsSaveJSON)

- [07-ImageEditDemoJSON](https://github.com/molab-itp/07-ImageEditDemoJSON)

## Saving Data - Cloud

- [09-ChipsSaveCloud](https://github.com/molab-itp/09-ChipsSaveCloud)
  - in private class repo

## The big picture

- [Firebase Fundamentals video](https://www.youtube.com/watch?v=p9pgI3Mg-So&list=PLl-K7zZEsYLnfwBe4WgEw9ao0J0N1LYDR&index=7) ~40 minutes

- [Getting started with the Firebase Realtime Database on the web](https://www.youtube.com/watch?v=pP7quzFmWBY) ~11 minutes

## MoGallery App

- [98-MoGallery-Private](https://github.com/molab-itp/98-MoGallery-Private)

  - private repo with MoGallery/MoGallery/GoogleService-Info.plist
  - run on the your iOS device to access firebase project configured for this class
  - Use MoLobby project for Lobby only functions

- [98-MoGallery](https://github.com/molab-itp/98-MoGallery)
  - public repo, no GoogleService-Info.plist
  - must create your own [firebase project - a container for you app](https://firebase.google.com/)

## MoGallery cloud data

- [firebase realtime database](https://console.firebase.google.com/u/0/project/molab-485f5/database/molab-485f5-default-rtdb/data/~2Fmo-1)
- [firebase storage](https://console.firebase.google.com/u/0/project/molab-485f5/storage/molab-485f5.appspot.com/files/~2F-mo~2Fmo-1)

## Re-using Example Code

- in class exercises
- removed unused code
- renaming project

## Firebase Resources

### Firebase Offical Docs

- https://firebase.google.com/docs/auth
- https://firebase.google.com/docs/database
- https://firebase.google.com/docs/firestore
- https://firebase.google.com/docs/storage

### Firebase Tutorial - FireCards

- https://www.kodeco.com/11609977-getting-started-with-cloud-firestore-and-swiftui

  - FireCards Firebase Console
    - https://console.firebase.google.com/u/0/project/firecards-77c11/firestore

- FireCards project updated for current SDK in class private repo
  - https://github.com/molab-itp/09-FireCards

### Firebase Tutorial - MakeItSo

- https://peterfriese.github.io/MakeItSo/tutorials/makeitso/

  - Chapter 1 to chapter 4
    - https://peterfriese.github.io/MakeItSo/tutorials/makeitso/#building-a-simple-ui
    - https://peterfriese.github.io/MakeItSo/tutorials/makeitso/#storing-data-in-the-cloud
  - Skip
    - https://peterfriese.github.io/MakeItSo/tutorials/makeitso/02-developing-locally-with-the-emulator-suite
  - MakeItSo Firebase Console
    - https://console.firebase.google.com/u/0/project/makeitso-faa35/firestore

- MakeItSo project updated for current SDK in class private repo
  - https://github.com/molab-itp/09-MakeItSo

## combine-vs-async docs

- https://peterfriese.dev/blog/2022/combine-vs-async/
  - https://github.com/peterfriese/SwiftUI-Concurrency-Essentials
- https://peterfriese.dev/blog/2022/firebase-async-calls-swift/

## Homework Week09

- Prepare first draft of your final project proposal. Ok to entertain more than one initial concept.

- Option 1:

  - setup a firebase project and build one of the firebase tutorial apps
    - FireCards
    - MakeItSo

- Option 2:

  - customize the **MoLobby** app in
    - [98-MoGallery-Private](https://github.com/molab-itp/98-MoGallery-Private)
    - with your own multi-user experience twist
    - fork the repo and create a branch labeled with your name

- create a Week09 folder for your project and add link to it here:

- [wiki home page week09](https://github.com/molab-itp/content-2025-01/wiki#week-09-homework)

  - update your wiki page with your
    - progress,
    - problems,
    - plans, and
    - questions

<!-- ### navigation demos revisted

- [06-TabViewDemo](https://github.com/molab-itp/06-TabViewDemo)

- [06-MenuNestedDemo](https://github.com/molab-itp/06-MenuNestedDemo)

- [07-SlideShowDemo](https://github.com/molab-itp/07-SlideShowDemo)

### SwiftUI Demos - navigation

- [Clubapartment app](https://github.com/molab-itp/swiftui.builds) 06_swiftui.builds/clubhouse

  - [View Figma design](https://www.figma.com/file/8DwfJi51F88IW1xNVrDMP4/Clubapartment?node-id=0%3A1)
  - [Watch me build](https://www.youtube.com/watch?v=UVTRKeIm3JA&feature=youtu.be)

-
- [Puppy adoption app](https://github.com/molab-itp/06-Wiggles-iOS) 06-Wiggles-iOS
- [iDine app](https://github.com/molab-itp/iDine) 06-iDine
  - Reference: [hackingwithswift.com swiftui-tutorial-building-a-complete-project](https://www.hackingwithswift.com/quick-start/swiftui/swiftui-tutorial-building-a-complete-project) -->

<!-- - https://www.kodeco.com/21133526-firebase-tutorial-getting-started
- https://www.kodeco.com/22067733-firebase-tutorial-real-time-chat
- https://www.kodeco.com/4203-beginning-firebase

Review for next class -->
