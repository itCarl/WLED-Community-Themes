# Contributing

Thanks for helping make WLED look better! New themes, backgrounds and fixes are all welcome.

## Quick start

```bash
git clone https://github.com/itCarl/WLED-Community-Themes.git
cd WLED-Community-Themes
npm install
npm run dev     # compiles every themes/<name>/*.scss next to its source
```

Upload the compiled `.css` to your controller as `/skin.css` and enable
**Config → User Interface → Enable custom CSS**.

## Adding a theme

1. Create a branch: `git checkout -b feature/my-theme`
2. Copy an existing theme folder, e.g. `themes/xmas-pine` to `themes/my-theme`
3. Set your colours. WLED sets its colour variables at runtime, so override them on
   `html:root` with `!important`.
4. Reuse the shared parts in `shared/` where they fit:
   - `@import 'base/mobile';` for readable lists and sliders on phones and in PC mode
   - `@import 'xmas/santa-hats';` and the backgrounds in `shared/backgrounds/`
5. Add a short `README.md`, a `desktop.png` (1280×720, PC mode) and a `mobile.png`
   (390×844), both on the Effects tab
6. Open a pull request against `development`

## Guidelines

- Keep text readable: check contrast on phone and desktop.
- Keep animations optional or subtle and respect "reduce motion".
- Keep themes small; they are served from a microcontroller.
- One theme or fix per pull request.

## Reporting bugs

Use the bug report template and add a screenshot, your browser and your WLED version.
