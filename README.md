# CSS TEXT TRANSFORM

  Mobile-first classes for css-text-transform.
  Set the desired css-text-transform on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-text-transform
```
View on [npm](https://www.npmjs.org/package/css-text-transform)


## File Size

943B text-transform.css
757B text-transform.min.css 
201B minified and gzipped

## The Code
```
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

@media screen and (min-width: 48em) and (max-width: 64em) {
  .ttc-m { text-transform: capitalize; }
  .ttu-m { text-transform: uppercase; }
  .ttl-m { text-transform: lowercase; }
  .ttn-m { text-transform: none; }
  .ttf-m { text-transform: full-width; }
}

@media screen and (min-width: 64em)  {
  .ttc-l { text-transform: capitalize; }
  .ttu-l { text-transform: uppercase; }
  .ttl-l { text-transform: lowercase; }
  .ttn-l { text-transform: none; }
  .ttf-l { text-transform: full-width; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

