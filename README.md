
## About

This repo is split into multiple packages:

| Package Name                            | Description                                                                                      |
| --------------------------------------- | ------------------------------------------------------------------------------------------------ |
| [@padloc/core](packages/core)           | Core Logic                                                                                       |
| [@padloc/app](packages/app)             | Web-based UI components                                                                          |
| [@padloc/server](packages/server)       | The Backend Server                                                                               |
| [@padloc/pwa](packages/pwa)             | The Web Client, a [Progressive Web App](https://developers.google.com/web/progressive-web-apps). |
| [@padloc/locale](packages/locale)       | Package containing translations and other localization-related things                            |
| [@padloc/electron](packages/electron)   | The Desktop App, built with Electron                                                             |
| [@padloc/cordova](packages/cordova)     | Cordova project for building iOS and Android app.                                                |
| [@padloc/tauri](packages/tauri)         | Cross-platform native app, powered by [Tauri](https://github.com/tauri-apps/tauri)               |
| [@padloc/extension](packages/extension) | Padloc browser extension                                                                         |

## How to use

As you can see in the [About](#about) section, there are lots of different
components to play with! But at a minimum, in order to set up and use your own
instance of Padloc you'll need to install and configure the
[Server](packages/server) and [Web Client](packages/pwa). In practice, there a
few different ways to do this, but if you just want to install and test Padloc
locally, doing so is really quite easy:

```sh
git clone git@github.com:padloc/padloc.git
cd padloc
npm ci
npm start
```

The web client is now available at `http://localhost:8080`!

In-depth guides on how to host your own "productive" version of Padloc and how
to build and distribute your own versions of the desktop and mobile apps are
coming soon!
