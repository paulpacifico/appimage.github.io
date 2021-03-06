---
layout: app

permalink: /jira-timer/
description: Jira Timer

icons:
  - jira-timer/icons/128x128/jira-timer.png

screenshots:
  - jira-timer/screenshot.png

authors:
  - name: alexcroox
    url: https://github.com/alexcroox

links:
  - type: GitHub
    url: alexcroox/jira-timer-menubar
  - type: Download
    url: https://github.com/alexcroox/jira-timer-menubar/releases

desktop:
  Desktop Entry:
    Name: Jira Timer
    Comment: Jira Timer
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: jira-timer
    StartupWMClass: Jira Timer
    X-AppImage-Version: 1.0.16
    Categories: Utility
    X-AppImage-BuildId: 1DyRbVqSJeNnxxQGIfpvwbwQtkw
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  productName: Jira Timer
  main: index.js
  author: Alex Crooks
  repository:
    type: git
    url: https://github.com/alexcroox/jira-timer
  license: MIT
  engine-strict: true
  dependencies:
    "@fortawesome/fontawesome": "^1.1.8"
    "@fortawesome/fontawesome-free-solid": "^5.0.13"
    "@fortawesome/react-fontawesome": 0.0.20
    array-flatten: "^2.1.2"
    auto-launch: "^5.0.5"
    contra: "^1.9.4"
    date-fns: "^1.29.0"
    delay: "^4.1.0"
    electron-log: "^2.2.17"
    electron-store: "^2.0.0"
    electron-updater: 4.0.5
    fix-path: "^2.1.0"
    hh-mm-ss: "^1.2.0"
    history: "^4.7.2"
    keytar: "^4.3.0"
    keytar-prebuild: "^4.1.1"
    lodash.filter: "^4.6.0"
    lodash.find: "^4.6.0"
    lodash.findindex: "^4.6.0"
    lodash.isboolean: "^3.0.3"
    lodash.isempty: "^4.4.0"
    lodash.orderby: "^4.6.0"
    lodash.remove: "^4.7.0"
    lodash.sortby: "^4.7.0"
    menubar: github:mantou132/menubar#master
    node-loader: "^0.6.0"
    object-get: "^2.1.0"
    opn: "^5.4.0"
    parse-duration: "^0.1.1"
    performance-now: "^2.1.0"
    pretty-ms: "^4.0.0"
    prop-types: "^15.6.2"
    ramda: "^0.26.1"
    react: "^16.6.3"
    react-dom: "^16.6.3"
    react-hot-loader: "^4.3.12"
    react-redux: "^6.0.0"
    react-router: "^4.3.1"
    react-router-dom: "^4.3.1"
    react-select: "^1.2.1"
    redux: "^4.0.1"
    redux-persist: "^5.10.0"
    redux-seamless-immutable: "^0.4.0"
    redux-thunk: "^2.3.0"
    request: "^2.88.0"
    request-promise: "^4.2.2"
    revalidation: "^0.12.1"
    seamless-immutable: "^7.1.4"
    string-template: "^1.0.0"
    styled-components: "^4.1.2"
    styled-components-spacing: "^3.1.1"
    uuid: "^3.3.2"
---
