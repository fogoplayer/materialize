# futuristic-materialize
It's Material Design, but cooler.

A fork of MaterializeCSS (materializecss.com)

## Get started
Get the files from jsDelivr:
```html
<!--Futuristic Materialize-->
<script src="https://cdn.jsdelivr.net/gh/fogoplayer/materialize@1.0.1/futuristic-materialize.js"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fogoplayer/materialize@1.0.1/futuristic-materialize.min.css">
<!--noUISlider (Only needed if using the noUISlider range selector)-->
<script src="https://cdn.jsdelivr.net/gh/fogoplayer/materialize@1.0.1/noUISlider/nouislider.min.js"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fogoplayer/materialize@1.0.1/noUISlider/nouislider.min.css">
```

Download the source files from GitHub:  
[.zip](https://github.com/fogoplayer/materialize/archive/1.0.1.zip)  
[.tar.gz](https://github.com/fogoplayer/materialize/archive/1.0.1.tar.gz)

View the [example components](https://fogoplayer.github.io/materialize).

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
|invalid_color   |Used for invalid text fields          |
|valid_color     |Used for valid text fields            |

Hex, RGB, and HSL color formats are supported

### Themes
The configuration object can also take a `theme` property. Futuristic Materialize includes 4 built-in themes: `"blue"`, `"red"`, `"green"` and `"orange"`. The theme is evaluated before the other properties, so themes can be tweaked by combining a theme delcaration with additional customizations.

## Custom classes
Futuristic Materialize provides a few unique classes.

- `.spinner-accent-only` can be applied to a spinner to make it use the accent color.
- When using the `left` class on a brand-logo, if it has a `.sidenav-trigger` as a preceding sibling, they won't overlap each other.