# Splash Screen Example


<a href="https://snack.expo.dev/@bacon/splash-video-demo">
  <!-- iOS -->
  <img alt="Run in Expo Snack" longdesc="Run in Expo Snack" src="https://img.shields.io/badge/Run%20in%20Expo%20Snack-fff.svg?style=for-the-badge&logo=EXPO&labelColor=000&logoColor=fff" />
</a>

Recreates the animated splash screen effect from the [WWDC 2023 finalist](https://developer.apple.com/design/awards/) "Universe - website builder".

## Demo Video

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
