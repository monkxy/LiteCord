# LiteCord [![Language Grade][lgtm-badge]][lgtm-link] [![GitHub Releases][downloads-badge]][downloads-link] [![Discord][discord-badge]][discord-link]


### Prerequisites
- [Git](https://git-scm.com)
- [Node.js](https://nodejs.org/en/) with [pnpm](https://pnpm.io/).
- Command line of your choice.

### 1: Clone the repository
```ps
git clone https://github.com/BetterDiscord/BetterDiscord.git
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
This will create a `betterdiscord.asar` file in the `dist` folder.
```ps
pnpm run dist
```

---

# FAQ

### What is this?
LiteCord is a lightweight, open-source alternative to the popular Discord client. It is designed to be faster and more efficient than the official Discord app, while still providing all the features and functionality that users have come to expect from Discord. The LiteCord client is built with a focus on simplicity, ease of use, and a clean, modern aesthetic. Some of its features include support for multiple accounts, customizable hotkeys, and a built-in dark mode. The LiteCord client is available for Windows, Mac, and Linux, making it a versatile and accessible option for users of all platforms.
BD has some other built-in features such as Emotes from Twitch, FFZ, and BBTV, as well as an in-client server browser.


### Support Servers?
There are two: [The main server][discord-link], and [the backup](https://discord.gg/C57JMntkZy).

