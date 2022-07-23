# IBC-Icons
IBC icons is an unofficial icon font for the Cosmos Network

#### Demo

[https://pud.wtf](https://pud.wtf)

#### Using a font

The `fonts` folder contains pre-generated font files that can be included in a project. This is especially convenient for the web; however, it is generally better to link to the web font hosted on Google Fonts:

```html
<link rel="stylesheet" href="style.css">
```

To use your icon font on a website 1) copy the CSS code that came in “style.css” to your own CSS file and 2) copy the “fonts” folder to your root website folder. Make sure that the uploaded fonts are linked from the imported CSS and properly placed in “fonts/”.

An icon can be inserted with the following HTML code:

The classes are referred to styling definitions in the included CSS file:

```html
.ibc-osmo:before {
content: “\e90e”;
}
```

#### License

We have made these icons available for you to incorporate into your products under the [Apache License Version 2.0](https://www.apache.org/licenses/LICENSE-2.0.txt). Feel free to remix and re-share these icons and documentation in your products.
I'd love attribution in your app's *about* screen, but it's not required.
