# Figma icns/ico Generator

Generate .icns ([Apple Icon Image format](https://en.wikipedia.org/wiki/Apple_Icon_Image_format)) / .ico ([ICO (file format)](https://en.wikipedia.org/wiki/ICO_(file_format))) files directly from Figma.

![Preview](https://aaroniker.me/icnsicopreview.png)

## Usage

Download it at the Figma plugin library [figma.com/c/plugin/742318143106037364/icns%2Fico-Generator](https://www.figma.com/c/plugin/742318143106037364/icns%2Fico-Generator)

## Development

First clone this repository
```shell
git clone https://github.com/aaroniker/figma-icns-ico-generator.git
cd figma-icns-ico-generator
```

Install dependencies & build files
```shell
npm install
npm run build
# Or watch: npm run dev
```

After that open a project in Figma Desktop, select _Plugins -> Development -> New Plugin_. Click `Choose a manifest.json` and find the `manifest.json` file in this plugin directory.

Done! Now _Plugins -> Development -> icns/ico Generator_

## ToDo

- [ ] Set export size (e.x. if you design your icon in 128x128 but wanna export it in 8x)
- [ ] Select multiple frames for different sizes

## Authors

- Aaron Iker ([Twitter](https://twitter.com/aaroniker_me))
- Andreas Storm ([Twitter](https://twitter.com/st8rmi))
