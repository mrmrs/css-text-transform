# css-text-transform 0.0.6

Css module of single purpose classes for text transform

#### Stats

230 | 20 | 20
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-text-transform
```

#### With Git

```
git clone https://github.com/tachyons-css/css-text-transform
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-text-transform";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-text-transform">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   TEXT TRANSFORM
*/
.ttc { text-transform: capitalize; }
.ttu { text-transform: uppercase; }
.ttl { text-transform: lowercase; }
.ttn { text-transform: none; }
.ttf { text-transform: full-width; }
@media screen and (min-width: 48em) {
 .ttc-ns { text-transform: capitalize; }
 .ttu-ns { text-transform: uppercase; }
 .ttl-ns { text-transform: lowercase; }
 .ttn-ns { text-transform: none; }
 .ttf-ns { text-transform: full-width; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .ttc-m { text-transform: capitalize; }
 .ttu-m { text-transform: uppercase; }
 .ttl-m { text-transform: lowercase; }
 .ttn-m { text-transform: none; }
 .ttf-m { text-transform: full-width; }
}
@media screen and (min-width: 64em) {
 .ttc-l { text-transform: capitalize; }
 .ttu-l { text-transform: uppercase; }
 .ttl-l { text-transform: lowercase; }
 .ttn-l { text-transform: none; }
 .ttf-l { text-transform: full-width; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

MIT

