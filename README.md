# Dark Theme for Upmind

A custom dark theme for the Upmind client portal interface. This theme provides a modern, eye-friendly dark mode experience while maintaining the platform's functionality and visual hierarchy.

## Features

- Complete dark mode implementation
- Maintains brand colors and visual hierarchy
- Improved contrast and readability
- Consistent styling across all portal sections
- Support for all major components:
  - Navigation and menus
  - Forms and inputs
  - Tables and data displays
  - Cards and containers
  - Buttons and interactive elements
  - Tooltips and notifications

## Installation

1. Install a CSS injection extension for your browser (e.g., Stylus for Chrome/Firefox)
2. Create a new style for the Upmind client portal domain
3. Copy and paste the contents of `dark-theme-master.css` into the style editor
4. Save and enable the style

## Usage

The theme is designed to work automatically once installed. No additional configuration is required.

### Customization

You can customize the theme by modifying the CSS variables in the `:root` section of the CSS file:

```css
:root {
    /* Brand colors */
    --brand-color: #0099ff;
    --brand-color-contrast: #ffffff;
    
    /* Background colors */
    --dark-background: #111;
    --dark-background-primary: #222;
    --dark-background-secondary: #333;
    /* ... other variables ... */
}
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details. 