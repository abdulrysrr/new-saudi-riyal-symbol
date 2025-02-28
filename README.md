# Saudi Riyal New Symbol Repository

This repository provides the new **Saudi Riyal (SAR) symbol** in multiple formats for ease of use across different applications, including fonts and images.

## Available Formats

### Font Files
- TTF
- OTF
- WOFF
- WOFF2

### Vector Graphics
- SVG
- EPS

### Raster Images
- PNG
- JPG

## Font Usage

A custom font is included with a dedicated Unicode character for the Saudi Riyal symbol, allowing for greater flexibility in styling, including size, color, and weight.

### Example Usage in HTML

```html
<style>
    @font-face {
        font-family: 'SaudiRiyalSymbol';
        src: url('saudiriyal.ttf') format('truetype');
    }
    .symbol {
        font-family: 'SaudiRiyalSymbol', sans-serif;
        font-size: inherit;
        margin: 20px auto;
        color: inherit;
        font-weight: bold;
    }
</style>
<p class="symbol">&#xea;</p>
```

## Usage Guidelines

To maintain visual consistency, please follow these guidelines provided by the **Saudi Central Bank (SAMA)**:

1. **Position**: Place the symbol to the left of the numeral.
2. **Spacing**: Keep a space between the symbol and the number.
3. **Proportions**: Maintain the correct shape without distortion.
4. **Alignment**: The symbol height should match the surrounding text.
5. **Direction**: The symbol should follow the text direction.
6. **Contrast**: Ensure sufficient contrast against backgrounds.

Refer to the full detailed usage guide provided by Saudi Central Bank SAMA: **[SAMA Guidelines](https://www.sama.gov.sa/ar-sa/Currency/SRS/Documents/Guidelines.pdf)**

## Installation

### Using the Font

1. Download the **TTF/OTF** file from this repository.
2. Install it on your system or import it into your application.
3. Use it in your preferred software.

### Using SVG/PNG

Simply download and embed it in your design or website.

## Contributing

If you would like to contribute or suggest improvements, feel free to submit a **pull request** or open an **issue**.


