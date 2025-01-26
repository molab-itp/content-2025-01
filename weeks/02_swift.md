# Week 02 Swift Programming 2, Anatomy of an iOS App

## [[Previous](./01_intro.md)] [[Next](./03_swiftui.md)]

## Plan

- review homework & corrections

- setting up and using github repo

- where to write stuff

- wiki page update

## Resources

- [markdownguide quick summary](https://www.markdownguide.org/cheat-sheet/)

- [docs.swift.org - A Swift Tour](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/guidedtour/)
- [Optional-Binding](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/thebasics#Optional-Binding)

- [Unwrap app - test your Swift programming fundamentals](https://apps.apple.com/us/app/unwrap/id1440611372)

## Setup

### Finder config

- finder preference to show full file names

  - settings / advanced

- finder command-/ show available disk space

- finder show hidden files
  - Press Command + Shift + . (period)

### Terminal basics

- Use Terminal to clone [course wiki](https://github.com/molab-itp/content-2025-01/wiki)

```
# script to clone the class wiki
# enter in Terminal app

# select location of wiki
cd ~/Documents

# clone local copy of wiki
git clone https://github.com/molab-itp/content-2025-01.wiki.git

# basic commands

cd ~
ls -la

# setup for useful alias

code ~/.zshrc
alias ll='ls -l -a'
alias og='open -a /Applications/GitHub\ Desktop.app'
source ~/.zshrc

```

### global .gitignore

```

# keep unneeded files out of repo

# create global .gitignore in user home directory
cd ~
code .gitignore
.DS_Store
**/xcuserdata/
node_modules

```

## review

- [github.com/molab-itp](https://github.com/molab-itp) Our class repos

- [01-Javascript-to-Swift](https://github.com/molab-itp/01-Javascript-to-Swift)

- [01-Playground](https://github.com/molab-itp/01-Playground)

## new stuff

- animals in ascii

  - [02-Ascii-Play](https://github.com/molab-itp/02-Ascii-Play)

- breakout rendering options for unicode and system images

  - [01-UIRender-playground](https://github.com/molab-itp/01-UIRender-playground)
  - reading the docs

- swiftui in the playground - creating an icon

  - [02-Icon-Image](https://github.com/molab-itp/02-Icon-Image)

## lab activity

## break

## Demos Apps

- Intro to Playgrounds and Xcode
- Building on Apple sample code to create your own app

### Xcode targets

- Preview
- Simulator
- Device

### example apps

- [03-About-Me](https://github.com/molab-itp/03-About-Me)

  - https://developer.apple.com/tutorials/sample-apps/aboutme
  - using SwiftUI to display information across multiple tab views

- [Capturing and Displaying Photos](https://developer.apple.com/tutorials/sample-apps/capturingphotos-browsephotos)

  - Browsing Your Photos - Apple Tutorial Tutorial
  - [Uses Playgrounds app](https://apps.apple.com/us/app/swift-playgrounds/id1496833156?mt=12)

  - [98-CaptureCameraStorage](https://github.com/molab-itp/98-CaptureCameraStorage)

    - Tutorial adapted to Xcode project
      - build to simulator | device

- [Voice-Recorder](https://github.com/molab-itp/06-Voice-Recorder)

  - Storage to local file system

- [98-MoGallery](https://github.com/molab-itp/98-MoGallery)

  - MoGallery is a mobile app for students to quickly create their own mobile multi user experiences
  - public version required firebase config file
  - private version can be built to access firebase backend
  - [98-MoGallery-Private](https://github.com/molab-itp/98-MoGallery-Private)
    - build to simulator | device

## Homework Week02

- continue learning Swift programming fundamentals and document your progress on your wiki page

- create a folder named Week02 in your class repo to store this weeks homework

- Option 1:

  - create an Xcode playground that creates an image using ascii text based on the techniques demonstrated in
    [02-Ascii-Play](https://github.com/molab-itp/02-Ascii-Play)

- Option 2:

  - create an Xcode playground that makes an 1024x1024 image based on the techniques demonstrated in
    [01-UIRender-playground](https://github.com/molab-itp/01-UIRender-playground)

- add a link to your Week02 folder on the

  - [wiki home page](https://github.com/molab-itp/content-2025-01/wiki#week-02-homework)

  - update your wiki page with any issues
