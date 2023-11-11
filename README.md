

# Custom Colors Palette

This repository contains a custom color palette with various shades for different colors. The color data is organized in a JSON format and can be used to extend your color palette in projects.

## Usage

Feel free to use this color palette in your projects. Each color has different shades represented by numerical values, and their corresponding hexadecimal color codes.

## How to Use

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/custom-colors-palette.git
   ```

2. Navigate to the repository:

   ```bash
   cd custom-colors-palette
   ```

3. Access the color data in the `colors.json` file.

## Color Categories

The color palette includes the following categories:

- Slate
- Gray
- Zinc
- Neutral
- Stone
- Red
- Orange
- Amber
- Yellow
- Lime
- Green
- Emerald
- Teal
- Cyan
- Sky
- Blue
- Indigo
- Violet
- Purple
- Fuchsia
- Pink
- Rose

Each category contains shades ranging from 50 to 950, providing a wide range of options for your design needs.


---
## 📑 material-tailwind component library usage in react

```javascript
import withMT from "@material-tailwind/react/utils/withMT";

export default withMT({
  darkMode: "media",
  content: [
    "./index.html",
    "./src/**/*.{js,jsx,ts,tsx}",
    "./src/components/**/*.{js,ts,jsx,tsx}",
    "node_modules/@material-tailwind/react/components/**/*.{js,ts,jsx,tsx}",
    "node_modules/@material-tailwind/react/theme/components/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {
      colors: {
        "o-slate": {
          50: "#f8fafc",
          100: "#f1f5f9",
          200: "#e2e8f0",
          300: "#cbd5e1",
          400: "#94a3b8",
          500: "#64748b",
          600: "#475569",
          700: "#334155",
          800: "#1e293b",
          900: "#0f172a",
          950: "#020617",
        },
      },
    },
  },
  plugins: [],
});
```


## Contributions

Feel free to contribute by adding new color categories or suggesting improvements. Simply fork the repository, make your changes, and submit a pull request.


Happy coding!


