# css-text-transform

Functional CSS for text-transform

## Filesize

| File | Size |
|------|------|
| `dist/text-transform.css` | 1001 bytes |
| `dist/text-transform.min.css` | 717 bytes (185 Gzipped) |

## Install

```sh
npm install css-text-transform
```

## Usage

### Import

```css
@import "css-text-transform";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-text-transform/dist/text-transform.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-text-transform/dist/text-transform.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.ttc` | `text-transform: capitalize;` |
| `.ttu` | `text-transform: uppercase;` |
| `.ttl` | `text-transform: lowercase;` |
| `.ttn` | `text-transform: none;` |
| `.ttf` | `text-transform: full-width;` |
| `.ttc-s` | `text-transform: capitalize;` |
| `.ttu-s` | `text-transform: uppercase;` |
| `.ttl-s` | `text-transform: lowercase;` |
| `.ttn-s` | `text-transform: none;` |
| `.ttf-s` | `text-transform: full-width;` |
| `.ttc-m` | `text-transform: capitalize;` |
| `.ttu-m` | `text-transform: uppercase;` |
| `.ttl-m` | `text-transform: lowercase;` |
| `.ttn-m` | `text-transform: none;` |
| `.ttf-m` | `text-transform: full-width;` |
| `.ttc-l` | `text-transform: capitalize;` |
| `.ttu-l` | `text-transform: uppercase;` |
| `.ttl-l` | `text-transform: lowercase;` |
| `.ttn-l` | `text-transform: none;` |
| `.ttf-l` | `text-transform: full-width;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.ttc-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/text-transform.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/text-transform.css` — formatted
- `dist/text-transform.min.css` — minified

## License

MIT
