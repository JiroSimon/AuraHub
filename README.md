**# AuraHub**  
Mood-based Music Player built with Flutter

Beautiful glassmorphism UI • Animated mood particles • Gradient backgrounds

## Screenshots

<img width="276" height="492" alt="image" src="https://github.com/user-attachments/assets/71a68528-1099-4858-a530-ca34481cfe81" /><img width="275" height="489" alt="image" src="https://github.com/user-attachments/assets/13d3cef5-d04c-497f-9ef7-a7605375b801" />
<img width="269" height="492" alt="image" src="https://github.com/user-attachments/assets/3e681e16-4b35-4ee6-b49b-835f1054f748" />







## Features

- 6 mood-themed songs (Happy, Sad, Calm, Energetic, Romantic, Rock)  
- Dynamic gradient background changing per mood  
- Animated floating particles (hearts, stars, bolts, drops…) matching mood  
- Smooth album art transitions with bounce & shadow effects  
- Pulsing play/pause button with glow  
- Progress slider + time display  
- Skip previous/next controls  
- Single-screen elegant player experience

## Tech Stack

- Flutter 3.x  
- just_audio ^0.9  
- Firebase Core & Auth (Google Sign-In configured but not used yet)  
- Glassmorphism package  
- Custom particle engine with AnimationController

## Installation

```bash
# 1. Clone
git clone https://github.com/JiroSimon/AuraHub.git
cd AuraHub

# 2. Get dependencies
flutter pub get

# 3. Run (choose platform)
flutter run
# or
flutter run -d chrome          # web
flutter run -d windows         # desktop
```

Assets (audio + images) are already bundled in `/assets/`.

## Project Status

Prototype / MVP stage  
Single player screen only  
Authentication & playlists planned but not implemented

## Future Plans

- User authentication + Google Sign-In flow  
- Create / save custom playlists  
- Mood detection from music or user input  
- Cloud song upload / personal library  
- Better onboarding & mood selector screen  
- Animations polish & performance tweaks

## License

MIT (add LICENSE file when ready)

Made with ❤️ in Parañaque City

Feel free to star ⭐ or fork!
