# delphi.tools: Studio Utility Selection

Curated tools from [delphi.tools](https://delphi.tools) selected for 0xleetv Studio (UI/UX, interaction design, motion production, and frontend engineering).

The complete toolkit is open source (0BSD license) and runs client-side in the browser with zero server uploads, no logins, and no telemetry. The full source is mirrored in the studio fork at [github.com/0xleetv/delphitools](https://github.com/0xleetv/delphitools).

---

## 1. Colour and Theming

* [Tailwind Shade Generator](https://delphi.tools/tailwind-shade-generator): Generates complete 50 to 950 shade steps from any base color, ready to copy into Tailwind configuration or CSS custom properties.
* [Contrast Checker](https://delphi.tools/contrast-checker): Evaluates text and background contrast against WCAG 2.1 and APCA standards for web accessibility compliance.
* [Colour Converter](https://delphi.tools/colour-converter): Real-time conversion across HEX, RGB, HSL, OKLCH, OKLAB, and Display P3 color spaces.
* [Palette Generator](https://delphi.tools/palette-generator) and [Palette Extractor](https://delphi.tools/palette-extractor): Builds harmonious color schemes and extracts dominant color accents from uploaded hero images or video frames.
* [Colour Blindness Simulator](https://delphi.tools/colour-blindness-simulator): Tests UI accessibility across protanopia, deuteranopia, tritanopia, and achromatopsia.
* [Gradient Generator](https://delphi.tools/gradient-generator): Creates multi-stop CSS gradients with easing interpolation.

## 2. Typography and Responsive Layout

* [Font File Explorer](https://delphi.tools/font-file-explorer): Inspects OpenType, WOFF, and WOFF2 font tables, variable font axes, OpenType features, ligatures, and character maps.
* [PX to REM Calculator](https://delphi.tools/px-to-rem): Converts pixel values from design handoffs into responsive rem units based on customizable root font sizes.
* [Line Height Calculator](https://delphi.tools/line-height-calculator): Computes vertical rhythm, modular line heights, and proportional leading for body and display typefaces.
* [Typography Calculator](https://delphi.tools/typography-calculator): Generates fluid type scales across viewport breakpoints.
* [Glyph Browser](https://delphi.tools/glyph-browser): Searches and copies Unicode characters, mathematical symbols, and icon glyphs.

## 3. Images and Vector Assets

* [SVG Optimiser](https://delphi.tools/svg-optimiser): In-browser SVGO processing to strip metadata, collapse paths, and minimize SVGs for web components and icons.
* [Background Remover](https://delphi.tools/background-remover): Client-side background removal for clean product cutouts and transparent assets.
* [Image Compressor](https://delphi.tools/image-compressor) and [Image Converter](https://delphi.tools/image-converter): Lossy and lossless conversion between WebP, AVIF, PNG, and JPEG for fast website hero assets.
* [Image Tracer](https://delphi.tools/image-tracer): Vectorizes bitmap logos and hand-drawn raster sketches into editable SVG paths.
* [Favicon Generator](https://delphi.tools/favicon-generator): Exports full multi-resolution favicon sets (16x16, 32x32, 180x180 Apple touch icon, and web manifest).
* [Base64 Image Encoder](https://delphi.tools/base64-image-encoder): Converts small graphics directly into data URIs for inline CSS backgrounds.

## 4. Audio and Video for Motion Production

* [Video to GIF](https://delphi.tools/video-to-gif): Converts short MP4 recordings into compact GIFs for UI documentation, pull request demos, and case studies.
* [Frame Extractor](https://delphi.tools/frame-extractor): Extracts individual frames as high-resolution PNGs at exact video timestamps for website hero stills.
* [Audio Extractor](https://delphi.tools/audio-extractor): Demuxes audio tracks from reference videos into clean WAV/MP3 stems.
* [Audio Normaliser](https://delphi.tools/audio-normaliser): Matches loudness across multiple sound clips to prevent volume spikes in UI interactions.
* [Waveform Generator](https://delphi.tools/waveform-generator): Produces SVG/PNG audio waveform visualizations for media player interfaces.
* [Screen Recorder](https://delphi.tools/screen-recorder): In-browser recording for micro-interaction showcases and motion design handoffs.

## 5. Developer and Metadata Utilities

* [Meta Tag Generator](https://delphi.tools/meta-tag-generator): Generates Open Graph, Twitter Cards, and SEO meta tags with visual social share previews.
* [JSON Formatter](https://delphi.tools/json-formatter): Cleans, validates, and indents design token schemas and API fixtures.
* [Regex Tester](https://delphi.tools/regex-tester): Tests and debugs regular expressions for client-side form validation.
* [UUID Generator](https://delphi.tools/uuid-generator): Generates RFC 4122 UUIDs for mock datasets and database fixtures.

---

## Running Locally

To run the full suite offline or integrate its client-side components into studio builds:

```bash
git clone https://github.com/0xleetv/delphitools.git
cd delphitools
bun install
bun start
```
