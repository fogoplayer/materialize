# futuristic-materialize
It's material design, but cooler.

A fork of MaterializeCSS (materializecss.com)

## Customization

`futuristic-materialize` uses the same html structure as MaterializeCSS. See MaterializeCSS.com.
While there is a default blue theme, you can change the theme by calling `M.changeTheme()`, which takes one argument, a configuration object. The properties of that object correspond to the CSS variables used by `futuristic-materialize`:

|Property Name   |Type                                                 |Description                           |Examples|
|----------------|-----------------------------------------------------|--------------------------------------|--------|
|darkest_color   |String of any valid CSS color assignment             |Used for navbar                       |`"orange"`,`"#123456"`,`"rgb(123,234,321)"`|
|medium_color    |String of any valid CSS color assignment             |Used for raised elements              |`"orange"`,`"#123456"`,`"rgb(123,234,321)"`|
|background_color|String of any valid CSS color assignment             |Used for page background              |`"orange"`,`"#123456"`,`"rgb(123,234,321)"`|
|accent_color    |String of any valid CSS color assignment             |Used as accents throughout            |`"orange"`,`"#123456"`,`"rgb(123,234,321)"`|
|accent_rgb      |String of comma-separated red, green, and blue values|Defaults to RGB equivalent of accent, used for shadows color|`"orange"`,`"#123456"`,`"rgb(123,234,321)"`|
|text_color      |String of any valid CSS color assignment             |Used for text                         |`"orange"`,`"#123456"`,`"rgb(123,234,321)"`|
|light_text      |String of any valid CSS color assignment             |Lighter text for buttons              |`"orange"`,`"#123456"`,`"rgb(123,234,321)"`|

### Themes
The configuration object can also take a `theme` property. `futuristic-materialize` includes 3 built-in themes: `blue`, `red`, and `orange`. The theme is evaluated before the other properties, so themes can be customized by providing other properties.

## Things to know

Darkest elements (navbar) are #000
Background is #333
Intermediate elements are #222

I need to take a closer clook at scrollfire and scrollspy to figure out what they are doing.

Make sure there are no instances of #26a69a left

Card actions and cards aren't using variables