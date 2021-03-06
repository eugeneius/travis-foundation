---
layout: post
title: CocoaPods - An amazing ride
author: Fabio Pelosin
twitter: fabiopelosin
---
*Fabio Pelosin is the co-author of CocoaPods. Travis Foundation has secured funding for CocoaPods from [SoundCloud](http://soundcloud.com) so that Fabio could work on CocoaPods for three months.*

---


Thanks to [SoundCloud](http://soundcloud.com) and to the Travis Foundation support I have been able to focus on CocoaPods… and I'm really excited to tell you all about it! This experience has been nothing less than an amazing ride.

During the sponsorship I was able to work on many features which helped CocoaPods to move a step closer to a stable release (i.e., version 1.0).

One of the major features introduced by the sponsored work on CocoaPods was the support for the specification of dependencies per build configuration. This functionality allows to scope code intended for debugging. I'm very enthusiast about it, because it has been one of the most frequently asked enhancements by our users.

Another feature that I could focus on was the support for the definition of the specification sources in the Podfile. An important limitation carried on by CocoaPods since its infancy. The lack of this feature could lead different machines to produce different outputs during CocoaPods installations. Being predictable is one the best traits of great software and I'm very happy that this weak point has finally been addressed.

Moreover, the sponsorship allowed me to focus on an area often neglected: the internally developed dependencies of CocoaPods. Polishing the dependencies allows the Core team to focus on a higher level as we can be confident about the robustness of our vital foundations. While the stable release of CocoaPods is still far in the horizon, most of the dependencies have greatly matured and I am very satisfied by their progress. This effort also lead to concrete benefits like faster downloads, the reorganisation of the files generated by CocoaPods and a simplified installation process.

Lastly, I would like to mention that the contribution lead to progress that unfortunately has not been capitalised on shipping code yet. Important discussion and research had been done on other features like the support for editing dependencies without requiring a manual step to prepare them and the usage of the targets of Xcode projects without the need of specification as Pods.

Working with the Travis Foundation has been a wonderful experience. They have been very helpful and comprehensive about the perils of Open Source development. I wholeheartedly would recommend to any Open Source developer a similar experience. 

I would like to thank SoundCloud and the Travis Foundation for their support. Without their contribution, I wouldn't have been able to focus so much effort on CocoaPods. Initiatives like this constitute an important engine to foster the development of the CocoaPods community and of the Open Source community in general.
