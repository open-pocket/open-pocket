# Open Pocket

## Update: Pocket is shutting down on July 8, 2025

[Pocket is Saying Goodbye: What You Need to Know](https://support.mozilla.org/en-US/kb/future-of-pocket)

There is no mention if any other part of the codebase will be open-sourced.

## Recent Discussions

[Ask HN: What Pocket alternatives did you move to?](https://news.ycombinator.com/item?id=44597668)

## Background

[Pocket](https://en.wikipedia.org/wiki/Pocket_(service)), previously known as Read It Later, is an application and web service for managing a reading list of articles and videos from the Internet.

In February 2017, Mozilla [acquired Pocket](https://blog.mozilla.org/blog/2017/02/27/mozilla-acquires-pocket/) and stated that Pocket "will become part of the Mozilla open source project".

A [ticket](https://bugzilla.mozilla.org/show_bug.cgi?id=1343006) to open source the code was opened the same day, but closed in 2018.

It's now over six years since that promise, and although some code has been shared on https://github.com/Pocket, the majority remains closed, including the core server and client applications.

There have been [continued requests](https://discourse.mozilla.org/t/pocket-source-code/43686/7) for Mozilla to open source the code. The most recent public responses on this, from Pocket CEO [Matt Koidon](https://twitter.com/mkoidin?lang=en), were:

* https://discourse.mozilla.org/t/pocket-source-code/43686/7 (June 2020)
* https://github.com/Pocket/extension-save-to-pocket/issues/75 (July 2020)

The issues raised are valid. Open-sourcing a previously private codebase has many challenges.

## The Open Pocket Mission

Pocket is a great app and ecosystem, but its future success isn't guaranteed.

In 2020, Mozilla had [large lay-offs](https://arstechnica.com/information-technology/2020/08/firefox-maker-mozilla-lays-off-250-workers-says-covid-19-lowered-revenue/). Although these didn't appear to impact Pocket, it does raise questions about Mozilla's financial health.

The purpose of the Open Pocket organization is to gather those who are interested in building a '[clean room](https://en.wikipedia.org/wiki/Clean_room_design)' open-source implementation of Pocket comprising of:
* A web site replicating the behavior of https://getpocket.com/
* An API compatible with the current ([v3](https://getpocket.com/developer/docs/v3/retrieve)) Pocket API.
* Clients such as an iOS and Android app

## How to Help

* Star and Watch this repo to follow the latest updates.
* If you have thoughts on how to help build Open Pocket, create an [issue](https://github.com/open-pocket/open-pocket/issues) or [discussion topic](https://github.com/open-pocket/open-pocket/discussions) to help find others to work with.
* If you've already started building something, consider joining forces with the Open Pocket organization.

## Available Projects

The following projects have already been open-sourced. (This list excludes infrastructure projects, and those not updated in the past 5 years).

* https://github.com/mozmeao/pocket-marketing-pages marketing pages for [getpocket.com](https://getpocket.com)
* https://github.com/Pocket/apollo-utils Utilities for Apollo gateway and implementing services
* https://github.com/Pocket/cloudwatch-metrics-aggregator nodejs lib to easily aggregate and process cloudwatch metrics in the background
* https://github.com/Pocket/curation-tools-frontend
* https://github.com/Pocket/extension-pocket-new-tab Pocket New Tab is a browser extension that serves as a replacement to the default new tab.
* https://github.com/Pocket/extension-save-to-pocket Save to Pocket is a browser extension that is used to save pages to a connected Pocket account
* https://github.com/Pocket/Firefox-Integration-Add-On-Prototype
* https://github.com/Pocket/front-end-build-tools Modified Create React App for use with Pocket extensions
* https://github.com/Pocket/pocket-ff-addon
* https://github.com/Pocket/proxy-server Service to deliver sponsored content while preserving privacy
* https://github.com/Pocket/recommendation-api Rank and serve recommendations
* https://github.com/Pocket/pocket-ios This appears to be the Pocket iOS app but there no is no README or description yet and it does not seem possible to build.
* https://github.com/Pocket/pocket-monorepo "This repo contains all the Pocket Typescript systems built as a monorepo but deployed as microservices."

## Legal

* Any open source code should follow Pocket's [branding guidance](https://getpocket.com/developer/docs/branding).
* It is not yet known if Pocket/Mozilla hold any patents on Pocket behaviour.
* [Pocket is a registered trademark](https://news.ycombinator.com/item?id=9520668)

## Background

Open Pocket was founded by [@andyw8](https://github.com/andyw8). I was a long-term fan of Pocket. and a Premium subscriber from 2014 to 2023.
My favorite way to consume Pocket articles is with the Android app on a [Boyue Likebook](https://twitter.com/BoyueTechnology) e-reader.
I'm also one of the maintainers of the [pocket-ruby](https://github.com/turadg/pocket-ruby) API client.
For full transparency, I am also building a commercial product relating to Pocket (not yet released).

Update (2024): I'm no longer working on my own product since [Readwise Reader](https://readwise.io/read) is a very promising successor to Pocket.

## Related and Similar Open Source Projects

* https://github.com/omnivore-app/omnivore (Node)
  * The company [shut down after joining ElevenLabs](https://web.archive.org/web/20250428194155/https://blog.omnivore.app/p/details-on-omnivore-shutting-down) but the open source version is still active.
* https://github.com/wallabag/wallabag (PHP) (formerly known as Poche)
* https://github.com/ArchiveBox/ArchiveBox (Python)
* https://github.com/go-shiori/shiori (Go)
* ~https://github.com/burtonator/polar-bookshelf (last updated in 2021)~
* https://github.com/cleverdevil/indiepaper (Python) (last updated in 2018)
* https://github.com/zhy0216/OhMyPocket (Python) (last updated in 2016)
* https://github.com/kavinderd/icebox (Ruby) (last updated since 2015)

## Related and Similar Commercial Products

* [Readwise Reader](https://readwise.io/read) ([announcement blog post](https://blog.readwise.io/the-next-chapter-of-reader-public-beta/))
