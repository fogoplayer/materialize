# futuristic-materialize
It's material design, but cooler.

A fork of MaterializeCSS (materializecss.com)

## Customization

`futuristic-materialize` uses the same html structure as MaterializeCSS. See MaterializeCSS.com.
While there is a default blue theme, you can change the theme by calling `M.changeTheme()`, which takes one argument, a configuration object. The properties of that object correspond to the CSS variables used by `futuristic-materialize`:

|Property Name   |Description                           |
|----------------|--------------------------------------|
|darkest_color   |Used for navbar                       |
|medium_color    |Used for raised elements              |
|background_color|Used for page background              |
|accent_color    |Used as accents throughout            |
|text_color      |Used for text                         |
|light_text      |Lighter text for buttons              |

Currently only hex codes are supported.

### Themes
The configuration object can also take a `theme` property. `futuristic-materialize` includes 3 built-in themes: `"blue"`, `"red"`, and `"orange"`. The theme is evaluated before the other properties, so themes can be customized by providing other properties.

## TODO

I need to take a closer clook at scrollfire and scrollspy to figure out what they are doing.

Make sure there are no instances of #26a69a left

Card actions and cards aren't using variables

Add rgb and color name values to `M.changeTheme()`