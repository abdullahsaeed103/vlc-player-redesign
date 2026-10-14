# VLC Player — Browser UI Recreation

A browser-based media player built from a VLC-inspired redesign concept. The project takes a visual direction from the reference below and implements it as an interactive player using standard web technologies.

> This is an independent fan project. It is not affiliated with, endorsed by, or an official product of VideoLAN or VLC media player.

## Links

- **Design reference:** [VLC Player Redesign Concept — YouTube](https://www.youtube.com/watch?v=ERFeOgqk324)
- **Live demo:** `https://YOUR-GITHUB-USERNAME.github.io/vlc-player-redesign/` *(available after GitHub Pages is enabled)*
- **Repository:** `https://github.com/YOUR-GITHUB-USERNAME/vlc-player-redesign`
- **GitHub Pages setup:** [Official GitHub documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

Replace `YOUR-GITHUB-USERNAME` after creating the repository.

## What it includes

- Browser-based audio and video playback
- Playlist and file-queue handling
- File picker, folder selection, and drag-and-drop importing
- Subtitle loading and subtitle-track controls
- Playback progress and resume support
- Keyboard shortcuts and accessible menu navigation
- Player appearance and playback settings
- Responsive layout for different screen sizes
- Wake Lock support where the browser provides it

Browser support and available codecs vary. Some controls depend on the media format and browser APIs.

## Run locally

No build step or package installation is required.

1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Use the file picker or drag media files into the player.

For the most consistent file-handling behavior, run it from a local static server rather than opening the HTML file directly. The project can also be published with GitHub Pages.

## Deploy with GitHub Pages

1. Create a **public** repository named `vlc-player-redesign`.
2. Add `index.html`, `README.md`, and `.nojekyll` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. Wait for the deployment to finish. GitHub will show the published URL in the Pages settings.

See the [official GitHub Pages guide](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) for details.

## Credits and implementation

- **Design inspiration:** [VLC Player redesign concept on YouTube](https://www.youtube.com/watch?v=ERFeOgqk324). Credit the original creator in any showcase or social post that features this recreation.
- **Implementation:** Built as a standalone HTML/CSS/JavaScript project, with assistance from Claude AI.
- **VLC / VideoLAN:** The VLC name is used only to identify the design inspiration. This project is unofficial and does not use the official VLC branding as an endorsement.

## Before sharing

Test playback with a few audio and video formats in your target browser. Also check subtitles, folder import, keyboard controls, settings, and the layout on a phone-sized screen. Browser APIs and supported codecs can differ between browsers.

## License

No license is included yet. Add a license only after deciding what permissions you want to grant for reuse, and make sure you have the rights to license the code and any included assets.
