# UF27 — Unity Android football prototype

This is an early playable **source-code prototype**, not a finished commercial football game or APK. It generates a simple 3D pitch, placeholder teams, a physics ball, basic opponent AI, a scoreboard, match clock and touch controls.

## Open and run
1. Install Unity Hub and a compatible Unity 6 editor.
2. In Unity Hub choose **Add > Add project from disk** and select this folder.
3. Wait for Unity to import the project.
4. In Unity's top menu choose **UF27 > Create Playable Prototype Scene**.
5. Open `Assets/Scenes/UF27.unity` if it did not open automatically, then press **Play**.
6. On desktop use WASD/arrow keys, Space to shoot, E to pass and Shift to sprint. On a touchscreen, use the on-screen buttons.

## Build an Android APK
1. In Unity Hub, install Android Build Support, Android SDK & NDK Tools, and OpenJDK for your Unity version.
2. In Unity open **File > Build Profiles**, select **Android**, and choose **Switch Platform**.
3. In Player Settings set Minimum API Level to **Android 12 (API 31)** or higher.
4. Confirm `Assets/Scenes/UF27.unity` is included in the build scene list.
5. Connect an Android device with USB debugging enabled, or choose Build to create an APK.
6. Test on real devices and profile performance before distributing.

## What is not included yet
- This archive does not contain an APK; Unity must compile it.
- Placeholder capsule players and a basic pitch; no real player likenesses, licensed club badges, official kits, stadiums or official league scoreboards.
- Basic arcade movement and simple opponent behavior; not full 11v11 simulation.
- No online multiplayer, full match rules, career saves, transfer market, player-card database, commentary or unique player celebrations yet.
- The 2.5 GB target is a future install-size budget, not the current prototype size. Achieving it requires original/licensed art, audio, compression, streaming and device testing.

Use original artwork and properly licensed assets. Do not copy eFootball or UFL assets, logos, player likenesses or other protected material.
