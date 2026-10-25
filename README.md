# Deepak Choudhary

**SDE 3 · Tech Lead, Client SDKs** at [VideoSDK](https://www.videosdk.live) · real-time video and voice · Rust core · AI agents

- **Engineer:** 6+ years on Android; tech lead for VideoSDK's 4 client SDKs (Android, iOS, Flutter, React Native) on a shared Rust core.
- **Educator:** co-founded [FaangX](https://faangx.com); trained developers through its Kotlin Training Program.
- **Entrepreneur:** incubated under MeitY Startup Hub; now building Buddy, an AI-agent assistant.

## What I work on now

**At VideoSDK.** The SDK repos are private, so here is the work in words. My work commits are on [@HiDeepakk](https://github.com/HiDeepakk).
- Led the move of all 4 SDKs to one shared Rust core: Android 3.0, iOS 4.0, Flutter 5.0 and React Native 2.0 shipped the same day (Oct 2026). [Android release notes](https://docs.videosdk.live/android/guide/video-and-audio-calling-api-sdk/release-notes)
- Shipped 22 Android SDK releases in 11 months and wrote 91% of their commits; top contributor to the Rust core.
- Built GPU camera effects (auto-framing, low-light, styles) in Rust on OpenGL ES and Metal.
- Rebranded libwebrtc's JNI layer so VideoSDK runs beside another WebRTC SDK in one app.
- Added AI voice-agent support: agents join calls as participants with live state, metrics and transcripts.

**Agentic engineering.**
- Built rusty, the SDK team's Claude Code plugin: 13 agents, 18 commands, 7 hooks and a 70-page wiki that triage, fix, build and test on real phones. 4 engineers merged 103 PRs into it in its first 4 weeks. (Private to the team.)
- Building **Buddy**: you talk to your phone; a daemon on your PC spawns and supervises fleets of Claude Code agents that do the work. Kotlin Multiplatform, Ktor, Koog, MCP, A2A. Overview: [Hey-Buddy](https://github.com/Hey-Deepak/Hey-Buddy) (source private for now).

## Public code

- [Murmur-rs](https://github.com/Hey-Deepak/Murmur-rs): on-device audio AI pipeline in Rust (decode, diarization, Whisper STT) for Android over JNI; decode 73.5× and diarization 4.3× faster than the Kotlin version.
- [Murmur](https://github.com/Hey-Deepak/Murmur): the Android app on top of it; transcribes on-device and analyzes the day with Claude.
- [Lipu](https://github.com/Hey-Deepak/Lipu): AI-powered "Learn in Public" post builder (Gemini, Ktor, MongoDB).
- [CMP-CurrencyApp](https://github.com/Hey-Deepak/CMP-CurrencyApp): Compose Multiplatform app for Android and iOS from one codebase.

## Writing and teaching

[Medium](https://medium.com/@HeyDeepak) · [FaangX](https://faangx.com) · [YouTube](https://www.youtube.com/@faangx)

## Contact

[LinkedIn](https://www.linkedin.com/in/hey-deepak) · choudharydeepak990@gmail.com

Open to SDE 3 / Tech Lead roles in client SDKs, real-time communication and AI agents. Remote OK.
