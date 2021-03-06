---
layout: app

permalink: /stash-electron/
description: Cryptographically secure team password manager built on open technologies and standardized encryption algorithms.

icons:
  - stash-electron/icons/128x128/stash-electron.png

screenshots:
  - stash-electron/screenshot.png

authors:
  - name: Doccrazy
    url: https://github.com/Doccrazy

links:
  - type: GitHub
    url: Doccrazy/stash-electron
  - type: Download
    url: https://github.com/Doccrazy/stash-electron/releases

desktop:
  Desktop Entry:
    Name: Stash
    Comment: Cryptographically secure team password manager built on open technologies
      and standardized encryption algorithms.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: stash-electron
    X-AppImage-Version: 1.1.0.1
    X-AppImage-BuildId: 50d33310-e75e-11a7-1e55-03b0d3b37efb
    StartupWMClass: Stash
    MimeType: x-scheme-handler/stash
    Categories: Utility
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  description: Cryptographically secure team password manager built on open technologies
    and standardized encryption algorithms.
  main: "./main.prod.js"
  browserslist: electron 1.7
  repository:
    type: git
    url: https://github.com/Doccrazy/stash-electron.git
  author:
    name: Matthias Piepkorn
    email: mpiepk@gmail.com
    url: https://github.com/Doccrazy
  license: GPL-3.0
  bugs:
    url: https://github.com/Doccrazy/stash-electron/issues
  homepage: https://github.com/Doccrazy/stash-electron#readme
  dependencies:
    "@types/classnames": "^2.2.3"
    "@types/diacritics": "^1.3.1"
    "@types/electron-settings": "^3.0.0"
    "@types/fs-extra": "^4.0.1"
    "@types/keytar": "^4.0.1"
    "@types/lodash": "^4.14.85"
    "@types/mousetrap": "^1.5.34"
    "@types/nodegit": "^0.18.4"
    "@types/react": "^16.0.23"
    "@types/react-dnd": "^2.0.34"
    "@types/react-dnd-html5-backend": "^2.1.8"
    "@types/react-dom": "^16.0.3"
    "@types/react-hot-loader": "^3.0.4"
    "@types/react-redux": "^5.0.7"
    "@types/react-redux-toastr": "^7.0.2"
    "@types/react-router-dom": "^4.0.7"
    "@types/react-router-redux": "^5.0.8"
    "@types/reactstrap": "^5.0.3"
    "@types/redux-logger": "^3.0.3"
    "@types/source-map-support": "^0.4.0"
    "@types/ssh2-streams": "^0.1.2"
    "@types/sshpk": "^1.10.3"
    bootstrap: "^4.0.0-beta"
    classnames: "^2.2.5"
    devtron: "^1.4.0"
    diacritics: "^1.3.0"
    electron-debug: "^1.2.0"
    electron-log: "^2.2.11"
    electron-settings: "^3.1.1"
    electron-unhandled: "^0.2.0"
    electron-updater: "^2.16.1"
    electron-window-state: "^4.1.1"
    font-awesome: "^4.7.0"
    font-awesome-filetypes: "^1.0.1"
    fs-extra: "^4.0.1"
    history: "^4.6.3"
    immutable: "^3.8.1"
    jquery: "^3.2.1"
    kdbxweb: "^1.0.1"
    keytar-prebuild: "^4.0.4"
    lodash: "^4.17.4"
    moment: "^2.18.1"
    mousetrap: "^1.6.1"
    natural-compare: "^1.4.0"
    nodegit: "^0.20.3"
    popper.js: "^1.12.3"
    react: "^16.1.1"
    react-dnd: "^2.5.4"
    react-dnd-html5-backend: "^2.5.4"
    react-dom: "^16.1.1"
    react-hot-loader: "^3.1.3"
    react-redux: "^5.0.6"
    react-redux-toastr: "^7.1.6"
    react-router: "^4.2.0"
    react-router-dom: "^4.2.2"
    react-router-redux: "^5.0.0-alpha.8"
    react-transition-group: "^2.2.0"
    reactstrap: "^5.0.0-alpha.4"
    redux: "^3.7.1"
    redux-thunk: "^2.2.0"
    source-map-support: "^0.5.0"
    ssh2-streams: "^0.1.19"
    sshpk: "^1.13.1"
    tai-password-strength: "^1.1.1"
  engines:
    node: ">=7.x"
    npm: ">=4.x"
    yarn: ">=0.21.3"
---
