# Saudi Riyal New Symbol Repository

![Saudi Riyal Symbol](https://argaamplus.s3.amazonaws.com/5df02013-fa26-45d6-b6de-6a97e5c871d5.png)

This repository provides the new Saudi Riyal (SAR) symbol in multiple formats for ease of use across different applications, including fonts and images.

## Available Formats

### Font Files
- **TTF**
- **OTF**
- **WOFF**
- **WOFF2**

### Vector Graphics
- **SVG**
- **EPS**

### Raster Images
- **PNG**
- **JPG**

## Font Usage
A custom font is included with a dedicated Unicode character for the Saudi Riyal symbol, allowing for greater flexibility in styling, including size, color, and weight.

## Installation via npm
You can install this package via npm:

```sh
npm install @abdulrysr/saudi-riyal-new-symbol-font
```

or using yarn:

```sh
yarn add @abdulrysr/saudi-riyal-new-symbol-font
```

## Using CDN
You can use this package via CDN without installation:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@abdulrysr/saudi-riyal-new-symbol-font@latest/style.css">
```

### Usage Options
#### Using the Provided Stylesheet
To use the font in your project, import the stylesheet in your main CSS file:
```css
@import '@abdulrysr/saudi-riyal-new-symbol-font/style.css';
```
```html
<span class="icon-saudi_riyal">&#xea;</span>
```

#### Adding the Style Yourself
Alternatively, you can define the font in your own CSS file using any font file format you wish:

```css
@font-face {
    font-family: 'SaudiRiyalSymbol';
    src: url('saudiriyal.woff2') format('woff2'),
         url('saudiriyal.woff') format('woff'),
         url('saudiriyal.otf') format('opentype');
}
.symbol {
    font-family: 'SaudiRiyalSymbol', sans-serif;
    font-size: inherit;
    margin: 20px auto;
    color: inherit;
    font-weight: bold;
}
```

```html
<span class="symbol">&#xea;</span>
```

## Usage Guidelines
To maintain visual consistency, please follow these guidelines provided by the Saudi Central Bank (SAMA):

- **Position**: Place the symbol to the left of the numeral.
- **Spacing**: Keep a space between the symbol and the number.
- **Proportions**: Maintain the correct shape without distortion.
- **Alignment**: The symbol height should match the surrounding text.
- **Direction**: The symbol should follow the text direction.
- **Contrast**: Ensure sufficient contrast against backgrounds.

Refer to the full usage guide: **[SAMA Guidelines](#)**

## Contributing
If you would like to contribute or suggest improvements, feel free to submit a pull request or open an issue.