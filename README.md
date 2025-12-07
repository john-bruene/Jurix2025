# Jurix 2025 Presentation

This repository contains the Quarto presentation for Jurix 2025 - International Conference on Legal Knowledge and Information Systems.

## Files

- `presentation.qmd` - The main Quarto markdown presentation source file
- `presentation.html` - The rendered HTML presentation (RevealJS format)

## Prerequisites

To edit and render this presentation, you need:

- [Quarto CLI](https://quarto.org/docs/get-started/) (version 1.4 or higher)

## How to Edit

1. Open `presentation.qmd` in your favorite text editor
2. Edit the content following Quarto markdown syntax
3. Customize the YAML header for different themes, transitions, and settings

## How to Render

To render the presentation to HTML:

```bash
quarto render presentation.qmd
```

This will create/update the `presentation.html` file.

## How to View

Open `presentation.html` in a web browser. You can:

- Press `F` for fullscreen mode
- Use arrow keys to navigate slides
- Press `S` for speaker notes view
- Press `O` for overview mode
- Press `?` to see all keyboard shortcuts

## Presentation Features

- Professional serif theme
- Slide transitions
- Slide numbers
- Chalkboard support for annotations
- Footer with conference information
- Incremental content reveal on selected slides
- Multi-column layouts

## Customization

### Changing the Theme

Edit the `theme` option in the YAML header. Available themes include:
- `simple`, `dark`, `black`, `white`, `league`, `beige`, `sky`, `night`, `serif`, `solarized`, `blood`, `moon`

### Changing Transitions

Edit the `transition` option. Available transitions:
- `none`, `fade`, `slide`, `convex`, `concave`, `zoom`

## About Jurix

Jurix is the International Conference on Legal Knowledge and Information Systems, bringing together researchers and practitioners in the field of AI and Law.

## License

Add your license information here.