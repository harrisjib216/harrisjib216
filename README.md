### Hey, I'm Jibril 👋🏾

I'm a self-taught engineer in New York, and I've been writing Swift since 2014, the year it came out. I build apps end to end: the iOS and Android app, the Go server behind it, and whatever is in the way.

At [Club](https://club.com) I'm the Technical Engineering Manager. I set the direction for mobile, write a lot of the code, and keep the team moving. I'd rather show someone a working version than pitch them an idea, and that habit is behind a lot of what's below.

![iOS](https://img.shields.io/badge/iOS-000000?style=flat&logo=apple&logoColor=white)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0D96F6?style=flat&logo=swift&logoColor=white)
![Objective-C](https://img.shields.io/badge/Objective--C-438EFF?style=flat&logo=apple&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=flat&logo=xcode&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![LLVM](https://img.shields.io/badge/LLVM-262D3A?style=flat&logo=llvm&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=flat&logo=claude&logoColor=white)

#### What I'm building

**[fastplusplus](https://github.com/harrisjib216/fastplusplus)**: find a faster library than the one you're using. Over 3,000 libraries that beat the usual defaults (the C++ standard library, zlib, OpenSSL, malloc, CPython), each with its published benchmark, the baseline it beats, and the catch. Every claim is graded A to D on how far it can be trusted. Built as a Python pipeline with Claude Code.

**[fastrust](https://github.com/harrisjib216/fastrust)**: the same for Rust. 134 crates, standard-library changes and build settings against serde_json, std's HashMap, Mutex, the default linker and more, checked by a Rust tool. 16 claims don't hold up, many because the standard library absorbed the crate: parking_lot is now slower than std's Mutex under heavy contention.

**[NoGaps](https://github.com/harrisjib216/NoGaps)**: the shortest workout that closes today's Activity rings, worked out from how fast your own workouts burn energy and sent to Apple Watch, with a widget that rises in the Smart Stack as the evening runs out. Replay any workout by scrubbing its heart-rate and pace charts while a marker runs the route, and read an on-device recap whose every number is checked against the workout.

**[WorkoutScript](https://github.com/harrisjib216/WorkoutScript)**: write Apple Watch interval workouts as text. `6x { 800m @ 3:50-4:00/km, recover 400m }` compiles to WorkoutKit's `CustomWorkout`, and mistakes get swiftc-style errors with fix-its. Comes with a SwiftUI editor that shows the workout's shape as you type and hands it to the Watch.

**[Immerse](https://github.com/harrisjib216/Immerse)**: a social feed in the language you're learning, where every post is written on the iPhone by Apple Intelligence, at your level. Tap a word to see what it means in that sentence, reply to anyone and they answer, and save words: the people in your feed start using them. Built on Foundation Models, NaturalLanguage and Translation, with no server.

**[fastswift](https://github.com/harrisjib216/fastswift)**: the same for Swift. JSONDecoder, NSLock, Core Data, Auto Layout and other defaults, against the libraries that claim to beat them. Every quote is re-checked against its source by a Swift tool, and 14 claims don't hold up, often because Apple's default caught up.

**[jos](https://github.com/harrisjib216/jos)**: an operating system with its own boot loader that gets into 32-bit protected mode.

**[My-Programming-Languages](https://github.com/harrisjib216/My-Programming-Languages)**: a bytecode VM in C (built through *Crafting Interpreters*), a Python-like language compiled with LLVM, and a small compiler that emits x86 assembly.

#### At work

- **Club:** built the prototype in under 90 days. It became the app we launched on the App Store and Google Play, and I was promoted to lead the team about six months in.
- **Meta:** shipped the collaborator post header to every Facebook user on Android, and rebuilt collaborator search, taking its success rate from 25% to 80%.
- **UX Cabin:** proposed chat with video, photo, audio, and location for an emergency management app (10,000+ installs on Google Play), then built it. Also got a Philips Hue lamp to show whether someone is free, through a Core Bluetooth module that writes to the lamp's undocumented GATT characteristics.
