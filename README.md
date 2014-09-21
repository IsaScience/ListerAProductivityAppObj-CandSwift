ListerAProductivityAppObj-CandSwift
===================================

I'm learning Swift and found myself in need of some real practical Swift code. So I found [Apple's ListerAProductivityAppObj-CandSwift](https://developer.apple.com/library/ios/samplecode/Lister/Listings/README_md.html) example app. This is in Obj-C/Swift. It targets both iOS and and OSX. This is perfect for me to learn how to create app in Apple's ecosystem. It lets me learn both the tools, development environmant and the new language Swift.

My end goal for this project is to create an minimal app with some TBD features, good enough to get into the App Store first for iOS, then OSX. Moving forward from this point to make new apps from here this codebase. Hopefully get to use Apple's arsenar frameworks (Metal, HealthKit, etc).

And this example app from Apple already contains:

>Lister is a list management app written in Swift that's built on top of iCloud and the powerful NSDocument and UIDocument architectures. In a single project you'll find both iOS and OS X targets, embedded frameworks, UI extensions, live rendering of custom views in Interface Builder, iOS and OS X Storyboards, Auto Layout, and more.

>Lister uses a {AAPL}ListController class that notifies the {AAPL}ListDocumentsViewController about new lists, lists that have been removed, and also lists that have been updated. The {AAPL}ListController has an {AAPL}ListCoordinator property which is resonsible for tracking the relevant URLs. In Lister, there are two types of {AAPL}ListCoordinator objects: the {AAPL}CloudListCoordinator object as well as the {AAPL}LocalListCoordinator object. The only place that these objects are used directly is within the {AAPL}ListController.

>The storage mechanism is determined by the {AAPL}AppDelegate, which asks the user what their storage preference is. Once their preference is known, the app delegate creates an {AAPL}ListCoordinator and passes it to the app delegate's {AAPL}ListController property. The app delegate passes the {AAPL}ListController object throughout the application to ensure that it's used as the single place to manage lists.

So we have got persistent already baked in to this example. We will extend from here. To quickly create an app to express who we are as ... human.

First, let's give it voice. So question #1 is how to use voice feature in an iOS app?

But first, we need to create a Xcode project...

At the meantime while I'm setting up my first Xcode project, visit some of my websites:

- http://litospectrum.org
- http://isascience.com (This site documents every step of this app's creation)
- http://hddigitalworks.com


I have literally millions of these domain names park at namecheap.com and I'm certain each and everyone of them will be stars in a Galaxieverse we shall create here for us to do whatever you please. As of now, they are hiding in the dark, seeking light....maybe enlightenment


1. 12beenlighten
2. http://litoinsane.com
3. http://youtu.be/yxRg3zCwYvU?list=PLE36E80A89C712940
4. 萍水相較
5. http://hoysun.me

luckymatty@gmail.com
(415) 213-2865

S..T....O........P................0..........................------------------
