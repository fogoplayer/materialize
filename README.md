# futuristic-materialize
It's material design, but cooler.

A fork of MaterializeCSS (materializecss.com)

## Customization

Futuristic Materialize uses the same html structure as MaterializeCSS. See MaterializeCSS.com for element templates.
While there is a default blue theme, you can change the theme by calling `M.changeTheme()`, which takes one argument, a configuration object. The properties of that object correspond to the CSS variables used by Futuristic Materialize:

|Property Name   |Description                           |
|----------------|--------------------------------------|
|darkest_color   |Used for navbar                       |
|medium_color    |Used for raised elements              |
|background_color|Used for page background              |
|accent_color    |Used as accents throughout            |
|text_color      |Used for text                         |

Currently only hex codes are supported.

### Themes
The configuration object can also take a `theme` property. Futuristic Materialize` includes 3 built-in themes: `"blue"`, `"red"`, and `"orange"`. The theme is evaluated before the other properties, so themes can be customized by providing other properties.

## Custom classes
Futuristic Materialize provides a few unique classes.

`.spinner-accent-only` can be applied to a spinner to make it use the accent color.


## todo
- Make sure all colors are variable-ized
- Card actions and cards aren't using variables
- Add rgb and color name values to `M.changeTheme()`
- Add green and test themes
- Add theme creator to site
- Add left media theme
- Checkbox labels
- Orange rgb
- Tab focus color
- FAB focus transparency
- carousel.indicators.indicator-item
- Anchor links