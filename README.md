# Splash Screen Example

<p>
  <!-- iOS -->
  <img alt="Supports Expo iOS" longdesc="Supports Expo iOS" src="https://img.shields.io/badge/iOS-4630EB.svg?style=flat-square&logo=APPLE&labelColor=999999&logoColor=fff" />
  <!-- Android -->
  <img alt="Supports Expo Android" longdesc="Supports Expo Android" src="https://img.shields.io/badge/Android-4630EB.svg?style=flat-square&logo=ANDROID&labelColor=A4C639&logoColor=fff" />
</p>



https://github.com/EvanBacon/expo-splash-video-example/assets/9664363/a01f0f97-1629-4879-853f-8fb9a960c33b

## How it works

- Set everything to black in the `app.json`:
  - `backgroundColor: '#000'`
  - `splash.backgroundColor: '#000'`
  - `ios.splash.backgroundColor: '#000'`
- Keep the splash screen open until the video is loaded into memory (note: there's a different video for tablets).
- Once loaded, play the video and hide the native splash screen.
- After the video finishes, fade everything out to reveal the rest of the app.

Only requires a couple components, works on Android too!

## 🚀 How to use

- Run `yarn` or `npm install`
- Run `npx expo` to start the app.

## 📝 Notes

- [Expo Assets guide](https://docs.expo.dev/versions/latest/guides/assets/)
- [Expo Splash Screen guide](https://docs.expo.dev/versions/latest/guides/splash-screens/)
- [Universe - Website Builder](https://apps.apple.com/us/app/universe-website-builder/id1211437633)
