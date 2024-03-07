<h3 align="center"><img width="80" alt="Puter.com, The Personal Cloud Computer: All your files, apps, and games in one place accessible from anywhere at any time." src="https://assets.puter.site/puter-logo.png"></h3>

<h3 align="center">Internet OS and Desktop Environment in the Browser!</h3>

<p align="center">
    <a href="https://puter.com/"><strong>« LIVE DEMO »</strong></a>
    <br />
    <br />
    <a href="https://github.com/HeyPuter/terminal">Original</a>

</p>

<h3 align="center"><img width="700" style="border-radius:5px;" alt="screenshot" src="https://assets.puter.site/puter.com-screenshot-2.webp"></h3>

<br/>

## Rethinking the interface
<h2>What is done</h2>
- Nothing yet, wait for updates;
<br/>

<h2>What's planned</h2>
- Move all colors to a separate css file, to dynamically load colors and custom themes;
- Fix the graphic part of the default theme;
- Add a dark theme;
- Add a switch theme and save the state in localstorage;
- Add a default wallpaper package;
- If possible, make a design system;
- Develop a design system in Figma for prototyping applications;
- Implement a theme change while minimally interfering with the system
<br/>

## Puter

Puter is an advanced open-source desktop environment in the browser, designed to be feature-rich, exceptionally fast, and highly extensible. It can be used to build remote desktop environments or serve as an interface for cloud storage services, remote servers, web hosting platforms, and more.

<br/>

## Getting Started

```bash
git clone https://github.com/HeyPuter/puter
cd puter
npm install
npm start
```

This will launch Puter at http://localhost:4000 (or the next available port).

<br/>

## Deploy to Production

Detailed guide on how to deploy Puter in production: [docs/prod.md](docs/prod.md)

<br/>

## FAQ

### ❓ What's the use case for Puter?

Puter can be used as:

- An alternative to Dropbox, Google Drive, OneDrive, etc. with a fresh interface and powerful features.
- Remote desktop environment for servers and workstations.
- A platform for building and hosting websites, web apps, and games.
- A friendly, open-source project and community to learn about web development, cloud computing, distributed systems, and much more!

<br/>


### ❓ Why isn't Puter built with React, Angular, Vue, etc.?

For performance reasons, Puter is built with vanilla JavaScript and jQuery. Additionally, we'd like to avoid complex abstractions and to remain in control of the entire stack, as much as possible.

Also partly inspired by some of our favorite projects that are not built with frameworks: [VSCode](https://github.com/microsoft/vscode), [Photopea](https://www.photopea.com/), and [OnlyOffice](https://www.onlyoffice.com/).

<br/>

### ❓ Why jQuery?

Puter interacts directly with the DOM and jQuery provides an elegant yet powerful API to manipulate the DOM, handle events, and much more. It's also fast, mature, and battle-tested. 

<br/>

## Credits

The default wallpaper is created by [Milad Fakurian](https://unsplash.com/photos/blue-orange-and-yellow-wallpaper-E8Ufcyxz514) and published on [Unsplash](https://unsplash.com/).

Icons by [Papirus](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) under GPL-3.0 license.

Icons by [Iconoir](https://iconoir.com/) under MIT license.

Icons by [Elementary Icons](https://github.com/elementary/icons) under GPL-3.0 license.

Icons by [Tabler Icons](https://tabler.io/) under MIT license.

Icons by [bootstrap-icons](https://icons.getbootstrap.com/) under MIT license.
