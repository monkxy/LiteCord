# LiteCord [![Language Grade][lgtm-badge]][lgtm-link] [![GitHub Releases][downloads-badge]][downloads-link] [![Discord][discord-badge]][discord-link]

[lgtm-badge]: https://img.shields.io/lgtm/grade/javascript/g/BetterDiscord/BetterDiscord.svg?labelColor=0c0d10&style=for-the-badge
[lgtm-link]: https://lgtm.com/projects/g/BetterDiscord/BetterDiscord/context:javascript

[downloads-badge]: https://img.shields.io/github/downloads/BetterDiscord/Installer/total?labelColor=0c0d10&color=3a71c1&style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDgiIGhlaWdodD0iNDgiIHZpZXdCb3g9IjAgMCA0OCA0OCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTEyLjI1IDM4LjVIMzUuNzVDMzYuNzE2NSAzOC41IDM3LjUgMzkuMjgzNSAzNy41IDQwLjI1QzM3LjUgNDEuMTY4MiAzNi43OTI5IDQxLjkyMTIgMzUuODkzNSA0MS45OTQyTDM1Ljc1IDQySDEyLjI1QzExLjI4MzUgNDIgMTAuNSA0MS4yMTY1IDEwLjUgNDAuMjVDMTAuNSAzOS4zMzE4IDExLjIwNzEgMzguNTc4OCAxMi4xMDY1IDM4LjUwNThMMTIuMjUgMzguNUgzNS43NUgxMi4yNVpNMjMuNjA2NSA2LjI1NThMMjMuNzUgNi4yNUMyNC42NjgyIDYuMjUgMjUuNDIxMiA2Ljk1NzExIDI1LjQ5NDIgNy44NTY0N0wyNS41IDhWMjkuMzMzTDMwLjI5MzEgMjQuNTQwN0MzMC45NzY1IDIzLjg1NzMgMzIuMDg0NiAyMy44NTczIDMyLjc2OCAyNC41NDA3QzMzLjQ1MTQgMjUuMjI0MiAzMy40NTE0IDI2LjMzMjIgMzIuNzY4IDI3LjAxNTZMMjQuOTg5OCAzNC43OTM4QzI0LjMwNjQgMzUuNDc3MiAyMy4xOTg0IDM1LjQ3NzIgMjIuNTE1IDM0Ljc5MzhMMTQuNzM2OCAyNy4wMTU2QzE0LjA1MzQgMjYuMzMyMiAxNC4wNTM0IDI1LjIyNDIgMTQuNzM2OCAyNC41NDA3QzE1LjQyMDIgMjMuODU3MyAxNi41MjgyIDIzLjg1NzMgMTcuMjExNyAyNC41NDA3TDIyIDI5LjMyOVY4QzIyIDcuMDgxODMgMjIuNzA3MSA2LjMyODgxIDIzLjYwNjUgNi4yNTU4TDIzLjc1IDYuMjVMMjMuNjA2NSA2LjI1NThaIiBmaWxsPSIjM2E3MWMxIi8+Cjwvc3ZnPgo=
[downloads-link]: #auto-installers

[discord-badge]: https://img.shields.io/badge/support%20server-join-green?labelColor=0c0d10&color=7289da&style=for-the-badge&logo=discord&logoColor=7289da
[discord-link]: https://discord.gg/C57JMntkZy

BetterDiscord is a client modification for Discord. This allows you to add plugins and themes to your personal copy of Discord. BetterDiscord also adds a number of other features out of the box.

---

# Installation



### Prerequisites
- [Git](https://git-scm.com)
- [Node.js](https://nodejs.org/en/) with [pnpm](https://pnpm.io/).
- Command line of your choice.

### 1: Clone the repository
```ps
git clone https://github.com/ActuallyBarcode/LiteCord.git
```
### 2: Install dependencies
```ps
pnpm recursive install
```
### 3: Run Build Script
This will create a `injector.js`, `preload.js`, and `renderer.js` in the `dist` folder.
```ps
pnpm run build
```
### 4: Inject into your Discord client
#### Install to Stable
```ps
pnpm run inject
```
#### Install to PTB
```ps
pnpm run inject ptb
```
#### Install to Canary
```ps
pnpm run inject canary
```

## Additional Scripts

### Compiling & Distribution
This will create a `litecord.asar` file in the `dist` folder.
```ps
pnpm run dist
```

---

# FAQ

### What is this?
LiteCord is a lightweight, open-source alternative to the popular Discord client. It is designed to be faster and more efficient than the official Discord app, while still providing all the features and functionality that users have come to expect from Discord. The LiteCord client is built with a focus on simplicity, ease of use, and a clean, modern aesthetic. Some of its features include support for multiple accounts, customizable hotkeys, and a built-in dark mode. The LiteCord client is available for Windows, Mac, and Linux, making it a versatile and accessible option for users of all platforms.


### Support Servers?
There are two: [The main server][discord-link], and [the backup](https://discord.gg/C57JMntkZy).

