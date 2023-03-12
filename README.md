# My Iosevka font configuration

## Installation

First clone the Iosevka repo:
```
git clone --depth 1 https://github.com/be5invis/Iosevka.git
```
Then (in the repo):

1. Ensure that [`nodejs`](http://nodejs.org) (≥ 14.0.0) and [`ttfautohint`](http://www.freetype.org/ttfautohint/) are present, and accessible from `PATH`.
2. Run `npm install`. This command will install **all** the NPM dependencies, and will also validate whether external dependencies are present.
3. `npm run build -- ttf::iosevka-custom`.

This will take some time. Once done, move fonts to `~/.local/share/fonts` and run `fc-cache`.

## Usage

I've experienced best results (on Konsole) with Iosevka Custom variant, 15pt font size.
