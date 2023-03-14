---
title: "From bytes to structs and back"
place: "Online"
kind: Meetup
date: "2023-01-11"
splash: "splash.png"
---

All network and disk I/O requires converting from `[]byte` to some structs and back to `[]byte`. We took a deep dive into different ways of writing encoding and decoding. We'll start by looking at the standard library and then implement a bunch of alternative ways of marshaling your data.

[Github](https://github.com/golangestonia/structs-to-bytes)