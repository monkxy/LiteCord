# LiteCord [![Language Grade][lgtm-badge]][lgtm-link] [![GitHub Releases][downloads-badge]][downloads-link] [![Discord][discord-badge]][discord-link]

[lgtm-badge]: https://img.shields.io/lgtm/grade/javascript/g/BetterDiscord/BetterDiscord.svg?labelColor=0c0d10&style=for-the-badge
[lgtm-link]: https://lgtm.com/projects/g/BetterDiscord/BetterDiscord/context:javascript

[downloads-badge]: https://img.shields.io/github/downloads/Actuallybarcode/LiteCord/total?logoColor=blue&style=for-the-badge
[downloads-link]: #auto-installers


LiteCord is a client modification for Discord. This allows you to add plugins and themes to your personal copy of Discord. LiteCord also adds a number of other features out of the box.

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

