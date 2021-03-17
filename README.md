# How to become an iOS Developer
The propose of this document is the creation of a repository with information about how to start and grow in my career becoming an expert iOS developer. Also, this document could works as an interview guide to cover the most important topics.

# ⚠️Disclaimer⚠️
The following information is **work in progress**. Feel free to create a pull request if you think a topic/tutorial/course is important to be here.

# How to start?
If you aren't new in the programming world, but yes for iOS, follow this [quick guide](https://github.com/pitt500/how-to-become-an-ios-developer/blob/master/QuickGuide.md) first. If you have experience with iOS already and you wanted to dominate more about all the topics to become an expert, please continue reading the document.

# Two sides
Let's divide the roadmap in two major topics:
* [Computer Science](#computer-science).

This topic is frequently ignored by some developers thinking that mobile devs "don't need" to build complex algorithms. This is a wrong assumption. If you want to become the best developer (doesn't matter the language or platform), you should study algorithms and know the most used data structures very well.

* [iOS](#ios).

iOS world is vast. There are a lot of topics to learn from Cocoa/Cocoa Touch, design patterns, software architectures and of course, Swift and Objective-C languages. This guide will help you to focus and find a way to study all those concepts.

# Computer Science
The following list are the base concepts to learn and being on shape with computer science topics:
* [Algorithms](#algorithms)
* [Data Structures](#data-structures)

### References for studying:
* [Swift Algorithm Club](https://github.com/raywenderlich/swift-algorithm-club)
* [Cracking the coding interview](http://www.crackingthecodinginterview.com/)
* [CLRS](https://www.amazon.com.mx/gp/product/0262033844/ref=ox_sc_saved_title_6?smid=AVDBXBAVVSXLQ&psc=1)

## Algorithms
* [Big-O Notation](https://www.youtube.com/watch?v=D6xkbGLQesk)
* [Bit Manipulation](https://docs.swift.org/swift-book/LanguageGuide/AdvancedOperators.html)
* [Sorting](https://github.com/raywenderlich/swift-algorithm-club#sorting)
* [Recursion](https://www.youtube.com/watch?v=B0NtAFf4bvU)
* [Dynamic Programming](https://www.byte-by-byte.com/dpbook/)

> Check [Cracking the coding interview](http://www.crackingthecodinginterview.com/) for more details

## Data Structures
* [Arrays](https://docs.swift.org/swift-book/LanguageGuide/CollectionTypes.html)
* [Strings](https://docs.swift.org/swift-book/LanguageGuide/StringsAndCharacters.html)
* [Sets](https://docs.swift.org/swift-book/LanguageGuide/CollectionTypes.html)
* [Dictionaries](https://docs.swift.org/swift-book/LanguageGuide/CollectionTypes.html)
* [Lists](https://github.com/raywenderlich/swift-algorithm-club/tree/master/Linked%20List)
* [Stacks](https://github.com/raywenderlich/swift-algorithm-club/tree/master/Stack)
* [Queues](https://github.com/raywenderlich/swift-algorithm-club/tree/master/Queue)
* [Trees](https://github.com/raywenderlich/swift-algorithm-club#trees)
* [Graphs](https://github.com/raywenderlich/swift-algorithm-club#graphs)

> Check [Swift Algorithm Club](https://github.com/raywenderlich/swift-algorithm-club) for more details


# iOS
The following list include the most important concepts you should know in order to develop apps for iOS:
* [Languages](#languages)
* [Memory Management](#memory-management)
* [Multithreading](#multithreading)
* [Testing](#testing)
* [App Distribution](#app-distribution)
* [Design Patterns](#design-patterns)
* [Human Interface Guidelines](#human-interface-guidelines)
* [Cocoa Touch](#cocoa-touch)
* [Networking](#networking)
* [Push Notifications](#push-notifications)
* [Persisting Data](#persisting-data)
* [SwiftUI](#swiftui)
* [Internationalization](#internationalization)
* [Reactive Funtional Programming](#reactive-functional-programming)
* [Architecture](#architecture)

# Languages
iOS Support two languages: Objective-C (used for two decades) and Swift from 2014. You can create apps with a single of these languages or mix them if it's convinient. Nowadays, Apple take Swift as its main language for development, however, there are a lot of legacy apps that still require support from Objective-C (because is expensive and time consuming doing a migration), that's why it's important to know both of them.

## Which language to learn?
If you are new and wonder where to start, I recommend you to start with Swift, because it's well robust and supported today, keep it as the main language to develop iOS apps, but also keep knowledge of Objective-C, that will help you in interviews or situations when you require to interact with it.

## Swift
* [Official website](https://swift.org/)
* [Language guide](https://docs.swift.org/swift-book/LanguageGuide/TheBasics.html)
* [Design guidelines](https://swift.org/documentation/api-design-guidelines/)
* [Swift style guide](https://google.github.io/swift/) (by Google)
* [Swift style guide](https://github.com/raywenderlich/swift-style-guide) (by RayWenderlich)

## Objective-C
* [Official Objective-C documentation](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/ProgrammingWithObjectiveC/Introduction/Introduction.html)
* [Blocks](https://www.youtube.com/watch?v=FS4JAy1Wy3w)
* [KVO](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/KeyValueObserving/KeyValueObserving.html)
* [KVC](https://developer.apple.com/library/archive/documentation/Cocoa/Conceptual/KeyValueCoding/index.html)
* [Bridging with Swift](https://developer.apple.com/documentation/swift/imported_c_and_objective-c_apis/importing_objective-c_into_swift#:~:text=Xcode%20offers%20to%20create%20this,by%20%22%2DBridging%2DHeader.)

# Memory Management
* [Automatic Reference Counting](https://docs.swift.org/swift-book/LanguageGuide/AutomaticReferenceCounting.html)
* [Memory Safety](https://docs.swift.org/swift-book/LanguageGuide/MemorySafety.html)
* [Value vs Reference Types](https://docs.swift.org/swift-book/LanguageGuide/MemorySafety.html)
* [Understanding Swift Performance](https://developer.apple.com/videos/play/wwdc2016/416/)
* [Improving Battery Life and Performance](https://developer.apple.com/videos/play/wwdc2019/417/)
* [iOS Memory Deep Dive](https://developer.apple.com/videos/play/wwdc2018/416/)

# Multithreading
* [Grand Central Dispatch Tutorial](https://www.raywenderlich.com/5370-grand-central-dispatch-tutorial-for-swift-4-part-1-2)
* [Operations Tutorial](https://www.raywenderlich.com/5293-operation-and-operationqueue-tutorial-in-swift)
* [Concurrency By Tutorials](https://store.raywenderlich.com/products/concurrency-by-tutorials)
* [Concurrent Programming with GCD](https://developer.apple.com/videos/play/wwdc2016/720/)
* [Modernizing Grand Central Dispatch Usage](https://developer.apple.com/videos/play/wwdc2017/706/)
* [Apple Documentation for GCD](https://developer.apple.com/documentation/DISPATCH)
* [Apple Documentation for Operations](https://developer.apple.com/documentation/foundation/operation)

# Testing
* [XCTest Framework](https://developer.apple.com/documentation/xctest)
* [Unit and UI Testing in iOS](https://www.raywenderlich.com/960290-ios-unit-testing-and-ui-testing-tutorial)
* [Testing in Xcode](https://developer.apple.com/videos/play/wwdc2019/413/)
* [UI Testing in Xcode](https://developer.apple.com/videos/play/wwdc2015/406/)
* [Getting Started with UI Testing](https://www.swiftbysundell.com/articles/getting-started-with-xcode-ui-testing-in-swift/)
* [Integration tests](https://www.swiftbysundell.com/articles/integration-tests-in-swift/)
* [Test Driven Developments in iOS](https://store.raywenderlich.com/products/ios-test-driven-development)

## Beta Distribution
* [TestFlight](https://developer.apple.com/videos/play/app-store-connect/101/)

# App Distribution
* [App Store Connect](https://developer.apple.com/videos/play/wwdc2019/301/)
* [App Distribution from Ad-hoc to Enterprise](https://developer.apple.com/videos/play/wwdc2019/304/)

# Design Patterns
Design patterns are templates to problems well known and help us to builds apps with great quality, maintenance, and scalability. The following resources will help you to learn more about those patterns used in iOS.

* [Design Patterns in Swift](https://refactoring.guru/design-patterns/swift)
* [Design Patterns by Tutorials](https://store.raywenderlich.com/products/design-patterns-by-tutorials)
* [Advanced iOS Architecture](https://store.raywenderlich.com/products/advanced-ios-app-architecture)
* [SOLID principles applied to Swift](https://marcosantadev.com/solid-principles-applied-swift/)
* [Clean Architecture](https://www.amazon.com/-/es/Clean-Architecture-Craftsmans-Software-Structure-ebook-dp-B075LRM681/dp/B075LRM681/ref=mt_kindle?_encoding=UTF8&me=&qid=1591475974)
* [Protocol-Oriented Programming](https://developer.apple.com/videos/play/wwdc2015/408/)

# Human Interface Guidelines
Apple provide us some design principles for all the different platforms in its ecosytem like macOS, WatchOS, tvOS and of course iOS (iPadOS included). Learn this topic in order to provide a better user experience for your users in all your apps. That's makes the difference between "another random app" and "the app taht everybody wants and know how to use it".

* [Human Interface Guidelines for iOS](https://developer.apple.com/design/human-interface-guidelines/ios/overview/themes/)

# Cocoa Touch
* [UIKit](https://developer.apple.com/documentation/uikit)
* [Foundation](https://developer.apple.com/documentation/foundation)

## Auto layout
* [Auto Layout](https://developer.apple.com/library/archive/documentation/UserExperience/Conceptual/AutolayoutPG/index.html)
* [Auto Layout tutorial](https://www.raywenderlich.com/811496-auto-layout-tutorial-in-ios-getting-started)
* [Auto Layout by tutorials](https://store.raywenderlich.com/products/auto-layout-by-tutorials)

# Networking
* [URLSession](https://developer.apple.com/documentation/foundation/urlsession)
* [URLSession Tutorial](https://www.raywenderlich.com/3244963-urlsession-tutorial-getting-started)
* [URLSession Best Practices](https://developer.apple.com/videos/play/wwdc2016/711/)

# Push Notifications
* [Push Notifications by tutorials](https://store.raywenderlich.com/products/push-notifications-by-tutorials)

# Persisting Data
* [Saving Data in iOS](https://www.raywenderlich.com/5429634-saving-data-in-ios)
* [UserDefaults](https://developer.apple.com/documentation/foundation/userdefaults)
* [Saving data with UserDefaults](https://www.hackingwithswift.com/example-code/system/how-to-save-user-settings-using-userdefaults)
* [Property Lists](https://www.youtube.com/watch?v=2Fed9NbSXqw)
* [Encoding and Decoding objects](https://developer.apple.com/documentation/foundation/archives_and_serialization/encoding_and_decoding_custom_types)

## Core Data
* [Core Data](https://developer.apple.com/documentation/coredata)
* [Beginning Core Data](https://www.raywenderlich.com/7104-beginning-core-data)
* [Intermadiate Core Data](https://www.raywenderlich.com/3815-intermediate-core-data)
* [Multiple Contexts in Core Data](https://www.raywenderlich.com/7586-multiple-managed-object-contexts-with-core-data-tutorial)
* [Core Data by tutorials](https://store.raywenderlich.com/products/core-data-by-tutorials)
* [Core Data for SwiftUI](https://www.raywenderlich.com/9335365-core-data-with-swiftui-tutorial-getting-started)

## External libraries
* [Realm](https://realm.io/docs/swift/latest)
* [SQLite](https://www.raywenderlich.com/6620276-sqlite-with-swift-tutorial-getting-started)

# SwiftUI
* [Official Apple SwiftUI Tutorials](https://developer.apple.com/tutorials/swiftui/)
* [Thinking of SwiftUI](https://www.objc.io/books/thinking-in-swiftui/)
* [Hacking with iOS: SwiftUI Edition](https://www.hackingwithswift.com/books/ios-swiftui)
* [SwiftUI Essentials](https://developer.apple.com/videos/play/wwdc2019/216/)
* [SwiftUI on all Devices](https://developer.apple.com/videos/play/wwdc2019/240/)

## Xcode Previews
* [Mastering Xcode Previews](https://developer.apple.com/videos/play/wwdc2019/233/)

# Internationalization
* [Localize an App](https://developer.apple.com/documentation/xcode/localizing_your_app)
* [Localized Experience in iOS 13](https://developer.apple.com/videos/play/wwdc2019/403/)


# Reactive Functional Programming

## Combine
* [Combine Documentation from Apple](https://developer.apple.com/documentation/combine)
* [Combine: Asynchronous Programming with Swift](https://www.raywenderlich.com/books/combine-asynchronous-programming-with-swift/v2.0)

## RxSwift
* [Official Repo](https://github.com/ReactiveX/RxSwift)
* [RxSwift: Reactive Programming with Swift](https://www.raywenderlich.com/books/rxswift-reactive-programming-with-swift/v4.0)

# Architecture
* [Composable Architecture](https://github.com/pointfreeco/swift-composable-architecture)
