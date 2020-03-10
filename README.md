us-flag-colors
===
*The official colors of the United States flag.*

This repository contains hexadecimal RGB approximations of the [official U.S. flag colors][1].

| Color | Hex RGB | Name           |
|-------|---------|----------------|
| red   | #B22234 | Old Glory Red  |
| white | #FFFFFF | Standard White |
| blue  | #3C3B6E | Old Glory Blue |

## Use

Install with NPM or Yarn:

```bash
npm i @newswrench/us-flag-colors
```

Access RGB flag colors as needed:

```js
const ufc = require('us-flag-colors');
console.log( ufc.rgb.red );
console.log( ufc.rgb.white );
console.log( ufc.rgb.blue );
// > B22234
// > FFFFFF
// > 3C3B6E
```

You can also access a CMYK representation:

```js
console.dir( ufc.cmyk.red );
// > [.196, 1.0, .757, .118]
```
## Notes

- These are *on-screen approximations* of the official colors defined for physical (cloth) flags produced for the U.S. government and/or armed forces.

    > The exact red, white, and blue colors to be used in the flag are specified with reference to the CAUS Standard Color Reference of America, 10th edition. Specifically, the colors are "White", "Old Glory Red", and "Old Glory Blue".[79] The CIE coordinates for the colors of the 9th edition of the Standard Color Card were formally specified in JOSA in 1946.[80] These colors form the standard for cloth, and there is no perfect way to convert them to RGB for display on screen or CMYK for printing. The "relative" coordinates in the following table were found by scaling the luminous reflectance relative to the flag's "white".

- It's considered acceptable to use slightly different colors in a digital or civilian context.

## License

[ISC][isc]. See [LICENSE.md][lic] for details.


[1]: https://en.wikipedia.org/wiki/Flag_of_the_United_States#Colors
[scra]: https://en.wikipedia.org/wiki/Standard_Color_Reference_of_America
[lic]: LICENSE.md
[isc]: https://choosealicense.com/licenses/isc/
