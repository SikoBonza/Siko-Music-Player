# Siko Music Player (starter project)

A Flutter Android-first starter for the blue-and-white Siko Music Player.

## Included in this first build
- Blue-and-white interface with music-note branding
- Search imported music
- Add audio files from the phone
- Play, pause, next, and previous
- Favourites
- Category chips for PNG/local, international, gospel, and reggae

## Important
This is the editable Flutter source project, not an installable APK yet. It has not been compiled or tested on a physical Samsung phone in this environment.

Online streaming and downloading are not connected yet. Those features need a licensed music catalogue or another authorized music source. The category chips are currently visual filters only; imported tracks are not automatically classified.

## Build on a computer with Flutter installed
1. Install Flutter and Android Studio.
2. Unzip this project.
3. In the project folder run `flutter pub get`.
4. Connect an Android phone with USB debugging enabled, or start an emulator.
5. Run `flutter run`.
6. To build an APK, run `flutter build apk --release`. The APK will be in `build/app/outputs/flutter-apk/`.

For Android permissions and audio behavior, follow the current Flutter and package setup guidance for your installed versions.
