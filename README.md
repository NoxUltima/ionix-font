# Ionix

Ionix is a customized monospaced font based on Iosevka, a Node.JS-generated monospaced font developed by @be5invis. Current version is 5.0.beta.1.

It combines many ideas from different programming fonts such as Fira Code, Gintronic, Recursive Mono, Novel Mono Pro, Vivala Code, Dank Mono, TheMix Mono, ITC Avant Garde Mono, Rotis Semi Serif, League Mono and countless others. Enjoy.

The font contains 9 weights across 5 widths with italics, and also a Sans and Slab counterpart.

### How to build the fonts manually

- Clone this repository [https://github.com/be5invis/Iosevka/tree/dev]---`dev` branch always gets the latest features
- Copy and paste `private-build-plans.toml`
- Get `ttfautohint.exe` installed and put it in the directory (not in any other folder)
- Go to the repo and copy-paste these commands <pre>
npm i
npm run build ttf::ionix
npm run build ttf::ionix-compressed
npm run build ttf::ionix-condensed
npm run build ttf::ionix-expanded
npm run build ttf::ionix-extended
npm run build ttf::ionix-slab
npm run build ttf::ionix-slab-compressed
npm run build ttf::ionix-slab-condensed
npm run build ttf::ionix-slab-expanded
npm run build ttf::ionix-slab-extended
</pre>

Or you can build your own by using [the Customizer](https://typeof.net/Iosevka/customizer)

TODO
: Upload fonts
