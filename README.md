# Ink Bleed

**Ink Bleed** is a Codemure concept project exploring a tactile ink-spread transition between light and dark themes. It is an interactive front-end demo built around a sample portfolio page, not a production-ready theme package.

Created by [Codemure](https://www.codemure.com).

## What it demonstrates

- An animated, click-originating ink reveal when switching themes
- WebGL2 rendering with a CSS fallback
- A control panel for tuning the transition
- Keyboard shortcuts and optional automatic playback
- Persistent theme and demo settings in local storage

The portfolio text and case studies in the demo are illustrative placeholder content, not client work or claims about real projects.

## Run locally

You’ll need Node.js and npm installed.

```bash
npm install
npm run dev
```

Open the local URL printed by Vite. To create and preview a production build:

```bash
npm run build
npm run preview
```

## Demo controls

- Click the sun/moon button or press **T** to toggle the theme.
- Press **D** to open or close the transition controls.
- Press **R** to replay the last transition.
- Add `?panel=1` to the URL to open the controls on load.
- Add `?auto=1` to enable automatic theme changes.
- Add `?gl=0` to force the CSS fallback.

## Use and adapt

You’re welcome to use, modify, and redistribute Codemure-authored project files under the [MIT License](./LICENSE). The license does not apply to third-party dependencies or fonts; those remain under their respective licenses. See the dependency packages for their terms, including the font licenses.

The demo portfolio content is only sample copy. Replace it with your own content before using the page in a real project.

## Credits

This project uses [GSAP](https://gsap.com/), [html2canvas](https://html2canvas.hertzen.com/), and the [Fraunces](https://fonts.google.com/specimen/Fraunces) and [Inter](https://fonts.google.com/specimen/Inter) typefaces. These components are distributed under their own licenses.

## About Codemure

Visit [codemure.com](https://www.codemure.com) to learn more about Codemure.
