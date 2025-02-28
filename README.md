# Implement the new Saudi Riyal Symbol in your Website & Apps

![Saudi Riyal Symbol](https://argaamplus.s3.amazonaws.com/5df02013-fa26-45d6-b6de-6a97e5c871d5.png)

This repository offers the new Saudi Riyal (SAR) symbol in various formats, optimized for seamless integration into websites. By utilizing a custom font with a dedicated Unicode character, you can easily adjust the color, size, and styling to match your design needs. 

## Unicode

The &#xea; entity represents the hexadecimal Unicode U+00EA which we're using in our font files to represent the new symbol.

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

## Demo Preview  
Here is a screenshot of the `index.html` page:  

![Screenshot of index.html](/demo/index.JPG)  

## Installation via npm
You can install this package via npm:

```sh
npm install @abdulrysr/saudi-riyal-new-symbol-font
```

or using yarn:

```sh
yarn add @abdulrysr/saudi-riyal-new-symbol-font
```

### Usage Options
#### Using the Provided Stylesheet
To use the font in your project, import the stylesheet in your main CSS file:
```css
@import '/node_modules/@abdulrysr/saudi-riyal-new-symbol-font/style.css';
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

Refer to the full usage guide: **[SAMA Guidelines](https://www.sama.gov.sa/en-US/Currency/SRS/Pages/Guidelines.aspx)**

## LinkedIn   
[My LinkedIn Profile](https://www.linkedin.com/in/abdulrehmanyaser/)


## 🌍 Available Languages
- 🇺🇸 [English](README.md)
- ar [العربية](README.ar.md)


## Contributing
If you would like to contribute or suggest improvements, feel free to submit a pull request or open an issue.

