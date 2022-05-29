---
title: "My First Two Month as an Indie Dev"
date: 2022-05-29T18:01:14+08:00
draft: false
tags:
  - Indie Dev
  - iOS
author: pomodorozhong
---

(Sorry, the graph used in this article is not readable in the dark mode. Please switch to light mode by clicking the button on the top right as needed.)

It's a mix of fun and pain for my first two months as an independent developer working on an iOS project. I will put on some graph to better explain it.

The Gantt graph below is what I expected. One month, app on the store.

- two weeks to learn iOS development and to build a minimum viable product (MVP)
- a week to iterate the product
- a week to go through the review process, to put the app on the store

```mermaid
gantt
    title an overly optimistic expectation
    dateFormat  YYYY-MM-DD
    axisFormat  %m-%d
    todayMarker off

    learning SwiftUI             : 2022-04-01, 2w
    making the MVP of my app     : 2022-04-08, 1w
    iterate the MVP              : 2022-04-15, 1w
    get feedback from user       : 2022-04-15, 1w
    put the app on the App Store : 2022-04-22, 1w
```

And here is what actually happened. Two month, app only on the Testflight.

- constantly learning iOS development, because there is too much quirk in SwiftUI
- taking 20 days to build the MVP because "Share Extension" is a pain in the ass
- after building the MVP, have to wait 20 days to get feedbacks from users
- appstoreconnect blocks me from distribute the app for 2 weeks, Because of something that's not my fault

```mermaid
gantt
    title what actually happened
    dateFormat  YYYY-MM-DD
    axisFormat  %m-%d
    todayMarker off

    section Development
    learning SwiftUI/UIkit                    : 2022-04-01, 8w
    making the MVP of my app                  : 2022-04-08, 23d
    adding function without any feedback      : 19d
    iterate the MVP                           : 2022-05-20, 1w
    get feedback                              : 2022-05-20, 1w

    section appstoreconnect
    wait for the Payment processing of Apple Developer Program : 2022-05-01, 2d
    put the app on TestFlight                                  : 17d
    ask support to solve their bug                             : 2022-05-05, 14d
```
