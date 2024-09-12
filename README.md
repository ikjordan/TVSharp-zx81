## TVSharp ZX81
This version adds extra configuration to allow manual syncing to the non-standard ZX81 PAL signal.

It also has changes to enable compilation with VS2019.

Copy `libusb-1.0.dll` and `rtlsdr.dll` from `TVSharp.zip`
to the same directory as the executable

**Note:** With a standard R82T base SDR dongle the maximum horizontal resolution is 128 pixels, so don't expect a clear picture!

## Configuration

Values will vary, depending on the ZX81 and how long it has been switched on (i.e. the temperature of the crystal).

For one ZX81 the values were:

| Entry    | Value |
| -------- | ------- |
| Sample Rate  | 2.0 MSPS pal secam  |
| Frequency | 591.250     |
| Adjustment X    | -72    |
| Adjustment Y    | 6    |

## Original Readme

Decompiled TVsharp files for archive.\
used dotPeek\
keywords: TVSharp source code, TVSharp, TVSharp code, ATV decoding with rtsdr, rtl-sdr\
added V4 support with the new blog-rtl-sdr driver

![Screenshot_37](https://github.com/Sultan-papagani/TVSharp-archive/assets/69393574/178a7400-3557-499e-8d67-a1de48d1dc7f)
![Screenshot_49](https://github.com/Sultan-papagani/TVSharp-archive/assets/69393574/ad30f676-4fef-4914-912a-814949b64109)

