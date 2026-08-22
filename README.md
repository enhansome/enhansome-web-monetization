<img src="assets/wm_icon_animated.svg" alt="Logo Web Monetization" align="right" width="120px" />

# Awesome Web Monetization with stars

> Awesome stuffs about Web Monetization. Learn more, check modules and others tools.

**Web Monetization** is a web service that allows you to send money directly in your browser.
This is a JavaScript browser API that allows the creation of a payment stream from the user agent to the website

## Contents

* [About Web Monetization](#about-web-monetization)
* [How to start monetize my website](#how-to-start-monetize-my-website)
* [Resources](#resources)
  * [Packages](#packages)
  * [Tutorials](#tutorials)
  * [Articles](#articles)
  * [Newsletters](#newsletters)
  * [Tools](#tools)
  * [Community](#community)
* [Contribute](#contribute)
* [Donate](#donate)

## About Web Monetization

* [Webmonetization.org](https://webmonetization.org/)
* [Documentation](https://webmonetization.org/docs/)
* [How Web Monetization work for paying payments](https://webmonetization.org/docs/intro/sending-payments/)
* [How Web Monetization work for receiving payments](https://webmonetization.org/docs/intro/receiving-payments/)
* [Specifications](https://webmonetization.org/specification/)
* [ILP Forum (read only)](https://forum.interledger.org/)
* [Grant For The Web](https://www.grantfortheweb.org/)

***

* [Interledger : Open protocol suite for sending payments across different ledgers](https://interledger.org/)

## How to start monetize my website

If you would like to monetize your content, you must have a Wallet and Provider account. See below the platforms that allow you to use them.

<details><summary>More details about Wallet and Provider account</summary>
<p>

***

| **Wallets** |                                                                                             |                                                                                                                                                                                                                                           |     |
| :---------: | :-----------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-: |
|     Name    | [![GateHub](https://webmonetization.org/img/logo-wallet-gatehub.svg)](https://gatehub.net/) | [New Wallet ?<br>Create a issue !](https://github.com/thomasbnt/awesome-web-monetization/issues/new?assignees=thomasbnt\&labels=Wallet%2C+%E2%86%94+WM+repository\&template=new-wallet.md\&title=%5BWa%5D) ⭐ 355 \| 🐛 0 \| 📅 2026-07-23 |     |
|     Fees    |                   SEPA: 1.00 EUR < 50,000 EUR<br>Wire: $15 min ($150 max)                   |                                                                                                                                                                                                                                           |     |

| **Payments** |        |
| ------------ | ------ |
| Name         | Empty. |

***

</p>
</details>

On your webpage, integrate your `monetization` tag on meta

```html
<link rel="monetization" href="https://ilp.example.com/alice">
```

and detect if `monetization` is possible, then work

```js
if (document.monetization) {
  document.monetization.addEventListener("monetizationstart", () => {
    console.log(
      "🎉 Awesome ! You use Web Monetization.\nMore information https://webmonetization.org",
    );
  });
}
```

## Resources

### Packages

*Any packages/modules and plugins*

* [awesome-jsgames](https://github.com/proyecto26/awesome-jsgames) ⭐ 965 | 🐛 18 | 📅 2026-03-22 - A curated list of awesome JavaScript Games ![](assets/small_icons/javascript.png)
* [react-monetize](https://github.com/guidovizoso/react-monetize) ⭐ 37 | 🐛 25 | 🌐 TypeScript | 📅 2024-02-02 - Helpers and hooks to speed up your integration with Web Monetization API. ![](assets/small_icons/react.png)
* [eleventy-plugin-monetization](https://github.com/DanCanetti/eleventy-plugin-monetization) ⭐ 24 | 🐛 1 | 🌐 JavaScript | 📅 2024-09-18 - An Eleventy plugin to monetize posts and site content. ![](assets/small_icons/11ty.png)
* [web-monetized-video](https://github.com/Jasmin2895/web-monetized-video) ⭐ 17 | 🐛 2 | 🌐 JavaScript | 📅 2023-07-05 - A web component with has play and pay policy and charges you for the amount of video watched. ![](assets/small_icons/javascript.png)
* [monetize.js](https://github.com/sunchayn/monetize.js) ⭐ 16 | 🐛 2 | 🌐 JavaScript | 📅 2024-08-31 - An event-driven library to manage and simulate Web Monetization. ![](assets/small_icons/javascript.png)
* [gridsome-plugin-monetization](https://github.com/Sergix/gridsome-plugin-monetization) ⚠️ Archived - Web monetization for Gridsome. ![](assets/small_icons/gridsome.png)
* [vuepress-plugin-web-monetization](https://github.com/spekulatius/vuepress-plugin-web-monetization) ⭐ 15 | 🐛 1 | 🌐 JavaScript | 📅 2023-05-28 - Adds the web-monetization metatag to your VuePress website. ![](assets/small_icons/vuejs.png)
* [jekyll-web\_monetization](https://github.com/philnash/jekyll-web_monetization) ⭐ 12 | 🐛 0 | 🌐 Ruby | 📅 2022-04-05 - A Jekyll plugin to add Web MonetizationAPI payment pointers to your site. ![](assets/small_icons/jekyll.png)
* [react-hook-wm](https://github.com/dacioromero/react-hook-wm) ⭐ 9 | 🐛 2 | 🌐 TypeScript | 📅 2023-03-04 - React hooks for integrating with Web Monetization. ![](assets/small_icons/react.png)
* [web-monetization-components](https://github.com/philnash/web-monetization-components) ⭐ 9 | 🐛 0 | 🌐 HTML | 📅 2020-05-24 - A collection of web components you can use on your web monetized websites. ![](assets/small_icons/javascript.png)
* [ngx-monetization (archived)](https://github.com/CDDelta/ngx-monetization) ⚠️ Archived - Web Monetization API for Angular. ![](assets/small_icons/angular.png)
* [revshare](https://github.com/kewbish/revshare) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2023-07-13 - A JS library for revenue sharing. ![](assets/small_icons/javascript.png)
* [react-webmonetization-meta](https://github.com/uchibeke/react-webmonetization-meta) ⭐ 6 | 🐛 7 | 🌐 TypeScript | 📅 2023-07-15 - A Web Monetization meta tag manager for React. ![](assets/small_icons/react.png)
* [web-monetization-electron-app](https://github.com/Jasmin2895/web-monetization-electron-app) ⭐ 4 | 🐛 7 | 🌐 CSS | 📅 2023-03-01 - Project demonstrate basic setup to enable web monetization in Electron App. ![](assets/small_icons/electron.png)
* [money-chat](https://github.com/dfoderick/money-chat) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2020-05-25 - Web Monetization chat app ![](assets/small_icons/javascript.png)
* [types-wm](https://github.com/dacioromero/types-wm) ⭐ 3 | 🐛 0 | 📅 2022-05-11 - TypeScript definitions for Web Monetization ![](assets/small_icons/typescript.png)
* [web-monetization-proxy](https://github.com/tcdowney/web-monetization-proxy) ⭐ 3 | 🐛 1 | 🌐 Go | 📅 2020-08-11 - Simple Go proxy for injecting Web Monetization meta tags. ![](assets/small_icons/go.png)
* [web-monetization-polyfill](https://github.com/immers-space/web-monetization-polyfill/) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2021-02-06 - Ensure the JavaScript Web Monetization API is available, even in environments with Content Security Policies enabled. ![](assets/small_icons/javascript.png)
* [web-monetization-demo](https://github.com/peter279k/web-monetization-demo) ⭐ 2 | 🐛 1 | 🌐 PHP | 📅 2022-09-30 - This is a Web Monetization Demo ![](assets/small_icons/javascript.png)
* [ep\_monetization](https://github.com/ISNIT0/ep_monetization) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2020-05-27 - Plugin for applying payment pointer meta tag to Etherpad site. ![](assets/small_icons/javascript.png)
* [mediadisclosures](https://github.com/oofdere/mediadisclosures) ⭐ 0 | 🐛 7 | 🌐 HTML | 📅 2022-09-01 - An open-source, always evolving, universal content rating system. ![](assets/small_icons/javascript.png)
* [wp-connect-coil](https://wordpress.org/plugins/wp-connect-coil/) - Plugin for applying Coil payment pointer meta tag to WordPress site. ![](assets/small_icons/wordpress.png)
* [xrptipbot-wordpress-widget](https://wordpress.org/plugins/widget-xrptipbot/) - WordPress Widget based on XRPTIPBOT embed code to donate content creators. ![](assets/small_icons/wordpress.png)
* [Monetization](https://github.com/KNawm/monetization) - A wrapper around the Web Monetization API to monetize apps. ![](assets/small_icons/dart.png)
* [web-monetization-video-ads](https://www.npmjs.com/package/web-monetization-video-ads) - Linking Web Monetization with video advertising to allow a freemium business model to be implemented for Web Monetization. ![](assets/small_icons/javascript.png)
* [web-monetization-revenue-share](https://www.npmjs.com/package/web-monetization-revenue-share) - Automated redistribution of funds to a community via smart contracts. ![](assets/small_icons/javascript.png)

### Tutorials

* [Getting started](https://webmonetization.org/docs/guides/monetize-page/) - Official documents from webmonetization.org.
* [Exclusive content](https://webmonetization.org/docs/guides/provide-exclusive-content/) - Put exclusive content on your website.
* ['A Web Monetization Story'](https://esse-dev.github.io/a-web-monetization-story/) - An interactive, story-based Web Monetization tutorial for online creators.
* [Web Monetization like I'm 5](https://dev.to/hacksultan/web-monetization-like-i-m-5-1418) - Monetizing the web!

### Articles

* [Monetizing Content in View](https://dev.to/godwinagedah/monetizing-content-in-view-paying-for-what-you-see-462a) - Paying for what you see.
* [Web Components](https://dev.to/philnash/web-components-for-the-web-monetization-api-4ed9) - For the Web Monetization API (serie).

### Newsletters

* [Newsletter of grantfortheweb.org](https://www.grantfortheweb.org/signup) - Sign up for email updates.

### Tools

* [Akita](https://github.com/esse-dev/akita) ⭐ 23 | 🐛 24 | 🌐 JavaScript | 📅 2025-03-01 - A browser extension that gives you insight into your involvement with Web Monetization.

  > Akita presents your top visited monetized sites, how much time you're spending on them, and how much you're contributing (or could contribute) to them.

* [Open Monetization Wallet](https://github.com/kristianfreeman/openmonetizationwallet) ⭐ 12 | 🐛 13 | 🌐 JavaScript | 📅 2023-06-10 - Tools for managing your vanity Web Monetization wallet.

  > Open Monetization Wallet (OMW) makes it easier to accept payments with the Web Monetization API at scale. Some features:
  >
  > * Custom wallet URLs: own your own "Payment Pointer", e.g. $wallet.signalnerve.com, instead of $pay.stronghold.co/abcdef123
  > * Change between wallets/providers with no downtime
  > * Logs of incoming payment requests
  > * Revenue sharing between multiple wallets, e.g. for multiple team members
  > * Infinitely scalable with serverless technology
  > * Free and open-source

* [Is web monetized](https://github.com/jkga/is-web-monetized) ⭐ 5 | 🐛 4 | 🌐 JavaScript | 📅 2026-01-24 - A very simple tool for checking if Web Monetization is enabled.

  > ```bash
  > npm install is-web-monetized -g
  > monetized example.com
  > ```
  >
  > You can also test your website with the dependency.

* [Probabilistic Revshare Generator - Web Monetization](https://webmonetization.org/prob-revshare/) - Probabilistic revenue sharing (revshare) is one way to share a portion of a web monetized pages earnings between multiple payment pointers.

  > Use this tool to define a list of payment pointers and their weights.
  > Then, add the generated monetization link element to your site.
  > The link will contain a unique URL hosted on <https://webmonetization.org/api/revshare/pay/>.
  > If you'd prefer to not use a hosted URL, you can set up revshare by adding a script to your site.

* [Paytrackr](https://github.com/thomasbnt/paytrackr) - (Forked from [wobsoriano/paytrackr](https://github.com/wobsoriano)) - Track and manage your micropayments into one place.

  > PayTrackr is the easiest and safest way to track and manage your micropayments to web monetized websites, having a web monetization provider membership.

### Community

* [Web Monetization Community](https://community.interledger.org/)
* [@GrantForTheWeb on Twitter](https://twitter.com/GrantForTheWeb)
* [Web Monetization tag on DEV](https://dev.to/t/webmonetization)

***

## Contribute

Contributions welcome ! Read the [contribution guidelines](contributing.md) first.
You can also contribute to share this repository and Web Monetization with your friends. 😄

If you want to add a new small icon, the height must be **16px**. Put in `assets/small_icons/NAME.png`. Format PNG only accepted.

> **Powered by Netlify** ✨

Netlify powering [the website](https://awesomewebmonetization.netlify.app/). Thanks to them! 💚

[![Deploys by Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge\&logo=netlify\&logoColor=white)](https://netlify.com)

## Donate

Feel free to help [me](https://github.com/thomasbnt) for the maintenance of this project !
Thanks to all **Sponsors on GitHub** !

![GitHub Sponsors](https://cdn.jsdelivr.net/gh/thomasbnt/sponsors/sponsors.svg)

[![GitHub Sponsors](https://img.shields.io/badge/Sponsor%20me-%23EA54AE.svg?\&style=for-the-badge\&logo=github-sponsors\&logoColor=white)](https://github.com/sponsors/thomasbnt) [![Support me on Buy Me a Coffee](https://img.shields.io/badge/Support%20me-on%20Buy%20Me%20a%20Coffee-white?style=for-the-badge\&logo=buy-me-a-coffee\&logoColor=black\&labelColor=%23FFDD00)](https://www.buymeacoffee.com/thomasbnt?via=thomasbnt)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-22._
