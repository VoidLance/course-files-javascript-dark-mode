# JavaScript Dark Mode Toggle

A small, dependency-free web project demonstrating a light/dark theme toggle. The sample is a “Wolf Appreciation” page; visitors can switch themes, and their choice is saved in the browser for their next visit.

## Why use this project?

- See a complete theme toggle using plain HTML, CSS, and JavaScript.
- Save and restore the selected theme with `localStorage`.
- Use the CSS `dark-mode` class to define the alternate theme.
- Start experimenting without installing packages or setting up a build.

This is an educational example, not a published package or production-ready theme library.

## Get started

Clone the repository and enter its directory:

```sh
git clone https://github.com/VoidLance/course-files-javascript-dark-mode.git
cd course-files-javascript-dark-mode
```

There are no dependencies or build steps. To serve the project locally with Python 3:

```sh
python3 -m http.server 8000
```

Open <http://localhost:8000> in your browser. You can also open `index.html` directly, though using a local server provides a consistent browser origin for saved preferences.

Click **🌙 Dark Mode** to enable the dark theme. Click **☀️ Light Mode** to return to the light theme. The selection is stored in `localStorage` under the `theme` key.

## Project files

- [`index.html`](index.html) — sample page and theme toggle button.
- [`styles.css`](styles.css) — light and dark theme styles.
- [`script.js`](script.js) — reads and saves the theme preference and updates the button.

To try the toggle in another page, include the stylesheet, add an element with the `theme-toggle` ID, and load `script.js` after that element. The script applies the `dark-mode` class to the page’s `<body>`.

## Help

For questions or to report a problem, [open an issue](https://github.com/VoidLance/course-files-javascript-dark-mode/issues). The project’s HTML, CSS, and JavaScript files are the primary documentation for how the example works.

## Maintainers and contributions

This repository is maintained by [VoidLance](https://github.com/VoidLance) and contributors. Contributions are welcome: open an issue to discuss a change, then submit a pull request with a focused update. Before submitting, check the page in a browser in both themes and verify that the saved preference is restored after reloading.

There is no separate contribution guide or automated test/build setup in this repository.
