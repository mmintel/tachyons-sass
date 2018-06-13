# tachyons-sass

Super flexible SCSS port of tachyons.

## Installation

```bash
npm install --save @mmintel/tachyons-sass
```

## Changes

* Breakpoints are used with `@` Suffx, e.g. `.fs3@ns`
* Breakpoints are now customizable, add new breakpoints to `$breakpoints` map
* Many settings are transformed into maps and automatically generate new classes when changed
    - `$font-sizes`
    - `$spacings`
    - `$sizes` (now used for widths and heights)
    - `$transparencies`
    - `$grays`
    - `$shadows`
    - `$text-shadows`
    - `$thicknesses`
    - `$radii`
* changed names of gray tones, now `.gray1`, `.gray2`...
* changed `.list` to `.no-list`
* changed `.mw` to `.max-w`
* added `.circle`
* added `.fill-*` classes, e.g. `.fill-gray5`
* added `.t-shadow*`
* removed colors completely
* removed `inherit` classes completely
* removed debugging classes
* removed unnecessary headline classes
    - `.f-headline`
    - `.f-subheadline`
    - `.f-5`
    - `.f-6`
* removed gradients
* removed font families
* removed hover effects

## Usage

```scss
@import "path/to/tachyons.scss";
```

## License

MIT

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
