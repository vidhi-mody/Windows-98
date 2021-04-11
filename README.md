# ![](https://win98icons.alexmeub.com/icons/png/windows-4.png) [Web98](https://web98.netlify.app)

Can't relate to those 90's kid tech memes? Relive the 90's with this retro web-based Windows 98 desktop remake.

## Technology Stack

- HTML
- CSS
- Javascript
- BrowserFS
- Node.js
- Bower
- Windows98 Icons

## Getting Started

### File Structure

```
|───games
├───img
├───paint
│   ├───.vscode
│   ├───cypress
│   │   ├───fixtures
│   │   ├───integration
│   │   ├───plugins
│   │   ├───snapshots
│   │   │   ├───tool-tests.spec.js
│   │   │   └───visual-tests.spec.js
│   │   └───support
│   ├───help
│   ├───images
│   │   ├───classic
│   │   ├───cursors
│   │   ├───dark
│   │   ├───icons
│   │   ├───meta
│   │   ├───modern
│   │   │   └───cursors
│   │   ├───occult
│   │   ├───transforms
│   │   └───winter
│   ├───lib
│   │   ├───gif.js
│   │   └───os-gui
│   ├───src
│   └───styles
│       └───themes
```

| **Files**  | **Content**                                                             |
| ---------- | ----------------------------------------------------------------------- |
| index.html | All the code for the HTML resides in this standalone file               |
| script.js  | All the javascript code for the project resides in this standalone file |
| style.css  | All the styling for this app resides in this standalone file            |

### Setup

The setup for this project is extremely simple. This is achieved in part due to our philosophy that to achieve a great UI, you don't need to use fancy libraries. The only external libraries used to make this project are [jQuery](https://jquery.com/browse) and [BrowserFS](https://github.com/jvilk/BrowserFS).

To setup this repo:

1. Clone the repo

`git clone https://github.com/vidhi-mody/Windows-98 && cd Windows-98`

2. Install dependencies

`npm install && npx bower install`

3. Use [VSCode Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in order to start this project on a live server.

## Contributing

If you have any suggestions for new features or want to improve the existing features, maybe report a bug and provide a fix, just open an issue! We will be more than happy to have you as a contributor!

For more information, check out our [Contributing Guide]().

## Live Demo

If you want to try out our application and indulge in the nostalgia, visit [https://web98.netlify.app](https://web98.netlify.app)

## License

[MIT](License) © 2021 Vidhi Mody 