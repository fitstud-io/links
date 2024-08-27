<a id="readme-top"></a>

<div align="center">

![Astro](https://astro.build/assets/press/astro-icon-light-gradient.svg)

</div>

<h1 align="center">FITSTUD.IO LINKS</h1>

<div align="center">

![Astro](https://img.shields.io/badge/Astro-0C1222?style=for-the-badge&logo=astro&logoColor=FDFDFE)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

Open source links page, customizable via JSON. Made with Astro 4.

</div>

## Table of Contents

  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li>
      <a href="#json">JSON</a>
      <ul>
        <li><a href="#icons">Icons</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>

## About The Project

- Create your very own links page for FREE.
- Use the colors you want and give yourself all the credits for it.
- And most importantly, update it very easily using JSON.

<p align="right"><a href="#readme-top">Back to top ⬆</a></p>

## Getting Started

### Prerequisites

- **Node.js** -> `v18.17.1` or `v20.3.0` or higher. (`v19` is not supported)
- **Visual Studio Code** -> with the [Official Astro Extension](https://marketplace.visualstudio.com/items?itemName=astro-build.astro-vscode).

Personally I prefer using `pnpm` instead `npm` and to install it you can use:

  ```sh
  npm install -g pnpm
  ```
### Installation

1. Clone this repo to your computer:
   ```sh
   git clone git@github.com:fitstud-io/links.git
   ```
2. Install Astro dependencies:
   ```sh
   cd links
   pnpm install
   ```
3. Run the Astro dev server:
   ```sh
   pnpm dev
   ```
<p align="right"><a href="#readme-top">Back to top ⬆</a></p>

## JSON

You can modify every aspect of the website very easily, you just have to edit the `index.json` file. This JSON contains the following sections:

- **html** -> Edit language, title, description and favicon (replace it in `/public`).
- **background** -> Use the same color twice for a solid color or use two colors for a gradient color.
- **header** -> Edit your image (replace it in `/public`), name and description.
- **socials** -> Add more icons with your socials URL (see the networks available).
- **featured** -> Highlight links with a background image or color (same as buttons).
- **buttons** -> Add more buttons with your socials URL (see the networks available).
- **footer** -> Edit the copyright and URL of the developer (Made just for you 😎).

### Icons

Just edit the key `network` with any of the following values (case-sensitive):

- BuyMeCoffee
- Discord
- Facebook
- GitHub
- Instagram
- Link
- LinkedIn
- Mail
- Map
- Medium
- Spotify
- TikTok
- Twitch
- WhatsApp
- X
- YouTube

> [!NOTE]
> If you need more open-source icons, visit: [Tabler Icons](https://tabler.io/icons)

<p align="right"><a href="#readme-top">Back to top ⬆</a></p>

## Buy Me a Coffee

If you like this project then  [buymeacoffee](https://buymeacoffee.com/fitstud.io) so I can spend more time being creative. Please and thank you in advance 😁.

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "feature".

**Don't forget to give the project a star!** ⭐

<p align="right"><a href="#readme-top">Back to top ⬆</a></p>

## License

Distributed under the MIT License. `Open Source` is pretty self-descriptive.

<p align="right"><a href="#readme-top">Back to top ⬆</a></p>