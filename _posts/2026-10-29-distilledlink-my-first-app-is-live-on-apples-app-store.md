---
layout: post
permalink: /distilledlink-my-first-app-is-live-on-apples-app-store/
title:  "DistilledLink: My first app is live on Apple's App Store!"
categories: [technology, software, development, icloud-drive]
tags: [distilledlink, apple, app-store, swift, swiftui, app-store-connect, xcode, software-development, icloud-drive]
comments: true
---

I've been determined to build an app for iOS since at least 2024. I caught the Apple bug in 2013 with my first retina MacBook (thanks Vanilla!); at the time I didn't quite know how deep into the ecosystem I'd go. The environment for writing software was so rich in first-class tooling that by day two I had completely forsaken the previous five years I spent developing on Windows. That was the genesis, I'd say.

While writing software for the Web, there was a slow-growing and persistent curiosity around writing native apps for iOS. That goal was esoteric and felt completely out of reach. Given the hurdle of learning a new language, frameworks, and toolsets when you also have a day job and other life responsibilities, the best description of my comitment to making this happen was ultimately reduced to fleeting and fanciful scenarios where I suddenly had _all this time_ to actually do it, being a mostly absurd kind of [Why Can't I Hold All These Limes](https://knowyourmeme.com/memes/limes-guy-why-cant-i-hold-all-these-limes) situation, but with time.

In spite of that, the publication of Apple's [Develop in Swift](https://developer.apple.com/tutorials/develop-in-swift) tutorials in early 2024 seemed like the right moment, so I took my first crack at it. The documentation was clear and authoritative, and SwiftUI had seemingly entered its stride after WWDC23's announcement of `SwiftData`, which I think helped a lot of people take it more seriously as a one-stop-shop, so to speak. That's at least how I understood it, and the appeal of having to learn one thing instead of many was the impetus I needed to make the effort. I got pretty far with the tutorials, but time ultimately did not permit further progress. 

I restarted again in 2025, this time with [Paul Hudson's 100 Days of SwiftUI](https://www.hackingwithswift.com/100/swiftui), but again time was simply not on my side.

Then, summer 2026, I had time. Evidently that's what happens when you no longer have to trade it for a [company](/my-career-at-fortnine/)'s money. 🤯

About a thousand hours of intermittent days and nights later I published [DistilledLink](https://apps.apple.com/ca/app/distilledlink/id6820685281) on Apple's App Store. It took exactly two weeks for Apple to review, and on October 29th I got the notification of approval from App Store Connect.

Despite the time put in, my knowledge of Swift and SwiftUI still pales in comparison to my knowledge of building Web applications at scale. I hope to eventually document this in more detail, and reduce that chasm, because while there is overlap insofar as they both require writing code, developing for iOS was such a radically different development experience for me.

Anyway, enough of this preamble. What does the app actually do?

![DistilledLink header]({{site.url}}/assets/img/DistilledLink-Header-v1.png)

## DistilledLink: Direct links for iCloud Drive

Put simply, DistilledLink lets users of iCloud Drive share _direct links_ to their files already stored on it.

The distinction between how iCloud Drive natively lets you share a file and how DistilledLink lets you share a file comes down to one simple distinction. **When you share a link to a file using DistilledLink, the person, site, automation, script, or app on the receiveing end will get that file opened immediately**, no intermediate "are you sure?" or "click here" download page that interrupts that direct flow, and no requirement for the receiving end to authenticate with an Apple account.

### Some examples of how to use direct links

- Pass a file to a script for a headless automation.
- Embed an image directly on a Web site as the `src` in an `<img />` tag.
- Stream a video in your favourite video player directly from iCloud Drive, without having to first download the entire file to device.

You can read more about the app on its [App Store listing](https://apps.apple.com/ca/app/distilledlink/id6820685281).

### Finding support

You can find support for the app on a dedicated GitHub [support repository](https://github.com/danemacmillan/DistilledLink-support). 

### Download and share!

 <a href="https://apps.apple.com/ca/app/distilledlink/id6820685281"><img src="{{site.url}}/assets/img/download-on-the-app-store.png" alt="Download on the App Store" width="144"></a>

If you happen to find this post before the end of November 2026, you can redeem the first in-app purchase for free using [`BLOGLAUNCH`](https://apps.apple.com/redeem?ctx=offercodes&id=6820685281&code=BLOGLAUNCH).



<p align="center">
  <a href="https://apps.apple.com/ca/app/distilledlink/id6820685281"><img src="{{site.url}}/assets/img/DistilledLink-Light-v2.png" alt="DistilledLink: Download on the App Store"></a>
</p>

