![Header image](headerImage.png)
# iOS Developer Roadmap
Roadmap to becoming an iOS developer in 2018

## What is it?
This is a tree-like compilation of topics highly relevant to iOS development.

## Who is it for?
The roadmap will be helpul for:

- anyone who wants to become an iOS developer
- iOS developers who desire to become experts
- iOS developers who are preparing for interviews and need to brush up knowledge
- iOS developers who need to compile own set of interview questions


## Why these topics?
See [this article](https://medium.com/@borlov/c9a24f413457) explainig selection of topics.

## How to use this roadmap
1. Find a topic you want to study.
2. Go to corresponding resources section.
3. Study untill you can confidently explain the topic to your cat.
4. (Optional) tick the checkbox next to the topic. [How to tick a checkbox](Resources/HOWTOCHECKBOX.md).
4. Go to step 1.

`Essential topics` are topics which significantly contribute to understanding of iOS development. Consequently, it is a good idea to study them first as they are often encountered on interviews.

Start from `Getting started` section if you haven't done any iOS development yet.

## Resources
Use materials from [Resources](Resources/RESOURCES.md) section to master topics from the Roadmap.

## The roadmap

- [ ] Practical knowledge
	- [x] Getting started
		- [x] First pet project ideas
	- [ ] Languages
		- [ ] `Objective-C`
			- [x] `Blocks`
				- [x] `Memory Management`
			- [x] `KVC`
			- [x] `KVO`
			- [x] Toll-free bridging
			- [ ] `Runtime`
				- [x] `Method messaging`
				- [x] Swizling
				- [ ] NSZombies and KVO
implementation
		- [ ] `Swift`
			- [x] `Closures`
			- [ ] `Initializers`
			- [x] `Generics`
			- [x] `Protocols`
			- [x] `Structs`
			- [x] `Enums`
			- [x] `Runtime`
				- [x] `Method dispatch`
		- [x] `Memory management`
			- [x] `Stack and Heap`
			- [x] `Value vs Reference type`
			- [x] `MRC`
			- [x] `ARC`
				- [x] `weak references`
			- [x] `Retain cycles`
			- [x] Garbage collector
			- [x] `Memory leaks`
			- [x] Shallow and deep copying
			- [x] `Autorelease pool`
		- [x] `Multithreading and concurency`
			- [ ] POSIX threads
			- [x] NSThreads
			- [x] Perform selector family
			- [x] `GCD`
			- [x] `NSOperation(Queue)`
			- [x] `Runloop`
			- [x] `Methods of thread synchronisation`
			- [x] Problems
				- [x] Race condition
				- [x] Deadlock
				- [x] Reader-writer problems
		- [ ] `Cocoa Touch (iOSKit)`
			- [x] `UIKit`
				- [x] `UIApplication`
					- [x] `States`
					- [x] `UIApplicationDelegate`
				- [x] `UIViews`
					- [x] `UITableViews`
					- [x] `UICollectionViews`
				- [x] Layers
				- [x] `Layout`
					- [x] `Frame-based (manual)`
					- [x] `Constraint-based (autolayout)`
						- [x] UIStackView
				- [x] `Animations`
				- [x] `Transform`
				- [x] `Screen transitions (Navigation)`
				- [x] `ViewController`
					- [x] `Lifecycle`
				- [x] UserNotifications
			- [ ] `Foundation`
				- [x] `Notifications, Delegation and observing`
				- [x] Collections
				- [x] `Networking`
				- [ ] `Serialization`
					- [x] NSCoding
					- [x] `Codable`
					- [x] `JSON`
					- [x] XML
					- [ ] Protobuf
			- [x] Core Location
			- [x] `Work in background mode`
		- [ ] `Software Architecture`
			- [ ] `Design Patterns`
				- [ ] `Architectural`
					- [x] `MVC`
					- [x] `MVVM`
					- [ ] `MVP`
					- [ ] `Clean architecture`
						- [ ] `VIPER`
						- [ ] RIBs
				- [ ] `Creational`
					- [x] `Singleton`
					- [x] `Factory`
					- [ ] `Abstract Factory`
				- [ ] Structural
				- [ ] `Behavioural`
					- [ ] `Observer`
				- [ ] Concurrency
			- [ ] `Design Principles`
				- [x] `SOLID`
				- [x] `Inversion of Control`
					- [x] `Dependency Injection`
					- [x] Service Locator
			- [x] Object-Oriented Programming
			- [x] `Third-party dependencies management`
				- [x] `Cocoapods`
				- [x] `Carthage`
				- [x] Swift Package Manager
			- [ ] Functional programming
				- [ ] Functional Reactive Programming Frameworks
		- [x] Project structure and File/Group organisation
		- [x] `Version Control Systems`
			- [x] `Git`
		- [ ] Debugging
			- [x] Instruments
			- [ ] Best practices
				- [ ] Checklists
		- [ ] UX
		- [ ] `Caching and Persistency`
			- [ ] `Core Data`
			- [x] Realm
			- [ ] YAPDatabase
		- [ ] `Testing`
			- [x] `Unit Tests`
			- [ ] Snapshot Tests
			- [ ] Functional test
			- [ ] TDD
			- [ ] BDD
		- [ ] Performance optimization
			- [ ] Increase FPS
			- [ ] Decrease memory footprint
		- [x] Code signing
		- [ ] Tools
			- [x] `Swiftlint`
			- [ ] Sourcery
			- [x] Fastlane
		- [x] Continuous Integration
		- [x] Security
			- [x] Keychain
		- [ ] tvOS
		- [ ] WatchKit
- [ ] Computer Science knowledge
	- [ ] `Algorithms`
		- [ ] `Sorting`
		- [ ] `Graph Theory`
			- [ ] ` Trees`
		- [ ] `Strings`
		- [ ] Greedy
		- [ ] Dynamic Programming
		- [ ] Bit Manipulation
		- [ ] `Recursion`
		- [ ] Game Theory
		- [ ] NP Complete
		- [ ] `Big-O notation`
	- [ ] `Abstract Data Types`
		- [x] `Stack`
		- [x] `Array`
		- [x] `List`
		- [x] `Map`
		- [ ] Multimap
		- [x] `Set`
		- [ ] Multiset (Bag)
		- [x] `Graph`
		- [ ] `Queue`
		- [x] Priority Queue
		- [ ] Double-ended priority queue
		- [x] Double-ended queue
	- [ ] `System design`
		- [ ] Problems

## How to contribute
Submit a pull request with additional topics and/or study matterials or throw ideas at me on Twitter [![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/kamranahmedse.svg?style=social&label=@bohdan_orlov)](https://twitter.com/bohdan_orlov)

## TODO
- [ ] content file with topics and materials
- [ ] ability to generate README.md from the content file
- [ ] ability to generate Roadmap tree image from the content file

## License

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
