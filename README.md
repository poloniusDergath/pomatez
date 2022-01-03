<p align="center">
  <a href="https://roldanjr.github.io/pomatez/">
    <img src=".github/assets/logo.png" alt="Pomatez logo" width="56" height="56">
  </a>
</p>

<h1 align="center">Pomatez</h1>

<h3 align="center">Stay Focused. Take a Break.</h3>

<p align="center">
  <br>
  <a href="#sparkles-features">Features</a>
  .
  <a href="#call_me_hand-development">Development</a>
  .
  <a href="#computer-installation">Installation</a>
  .
  <a href="#shield-privacy">Privacy</a>
  .
  <a href="#newspaper-license">License</a>
  <br>
  <br>
</p>

<p align="center">
   <a href="https://github.com/poloniusDergath/pomatez-web/blob/master/LICENSE">
      <image src="https://img.shields.io/github/license/poloniusDergath/pomatez-web" alt="License" />
   </a>
</p>

![App Preview](.github/assets/preview.png)

## Features

- **Customizable rules**. You can easily modify the default rules of the Pomodoro Technique to be fitted to your personal liking.

- **Keyboard shortcuts**. Usable keyboard shortcuts letting you to use the app conveniently.

- **Auto-start work time**. If enabled, the next interval will automatically start after the timer ends.

- **Voice assistance**. If enabled, the notification will have a voice to inform you from time to time. Useful when you are away from your computer while taking a break.

- **Coloured themes**.

- **Strict mode**. If enabled, the app will strictly follow the rules you have set and preventing you from pausing, skipping and resetting the timer when it started.

## Development

This app is built using [React](https://reactjs.org/), [Electron](https://www.electronjs.org/), and [Typescript](https://www.typescriptlang.org/).

It also used [Lerna](https://lerna.js.org/) and [Yarn Workspaces](https://classic.yarnpkg.com/en/docs/workspaces/) for better project management.

### :zap: Quick Setup

1. Install all app dependencies.

   ```sh
   yarn install or npm install
   ```

2. Start the development.

   ```sh
   yarn dev:app or npm run dev:app
   ```

### 🛠 Building for Production

1. Build Windows installer.

   ```sh
   yarn build:win or npm run build:win
   ```

2. Build macOS installer.

   ```sh
   yarn build:mac or npm run build:mac
   ```

3. Build Linux installer.

   ```sh
   yarn build:linux or npm run build:linux
   ```

4. Build macOS, Windows and Linux installer at once.

   ```sh
   yarn build:mwl or npm run build:mwl
   ```

## :computer: Installation

Available for Windows, macOS, and Linux.

Download the latest version from the [Releases Page](https://github.com/roldanjr/pomatez/releases/latest) or from the :point_right: [Download Page](https://roldanjr.github.io/pomatez/) .

**For Linux users:**

> If you want to be always updated with latest release, recommended way to install it is using the Snap Store.

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/pomatez)

Please consider starring this project to show your :blue_heart: and support.

Thank you friends! :vulcan_salute:

## :shield: Privacy

This app has analytics that will track number of users only ([analytics.ts](https://github.com/roldanjr/pomatez/blob/master/packages/main/src/helpers/analytics.ts)).

## :newspaper: License

MIT © [Roldan Montilla Jr](https://github.com/roldanjr)
