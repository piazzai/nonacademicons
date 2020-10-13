# nonacademicons

Nonacademicons is an icon pack I developed for my personal website. It extends [Academicons](http://jpswalsh.github.io/academicons) with additional logos not necessarily related to academia. It can be used by itself or in conjunction with Academicons and/or [Font Awesome](https://github.com/FortAwesome/Font-Awesome). These fonts intentionally share the same metrics and can be used in a similar fashion.

| Name                 | Image                                           |
| -------------------- | ----------------------------------------------- |
| `nai-uc3m`           | <img src="png/uc3m.png" width="50" />           |
| `nai-uc3m-square`    | <img src="png/uc3m-square.png" width="50" />    |
| `nai-lichess`        | <img src="png/lichess.png" width="50" />        |
| `nai-lichess-square` | <img src="png/lichess-square.png" width="50" /> |

## Usage

There are two ways to use this font on your website. One is to download the `fonts` and `css` folders, copy them to the root directory of your website, and link to the stylesheet by adding the following line to your HTML head:

```html
<link rel="stylesheet" href="/css/nonacademicons.min.css" />
```

Alternatively, you can use the jsDelivr CDN to call the latest release from the content distribution network. In this case, you can add the following line to your HTML head without copying any folder:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/piazzai/nonacademicons@v1.0.0/css/nonacademicons.min.css" />
```

At this point, icons can be deployed in a similar way as Font Awesome and Academicons ([go to instructions](https://fontawesome.com/how-to-use/on-the-web/referencing-icons/basic-use)), just remember the `nai` prefix. You can also resize them with classes like `nai-lg` or `nai-2x` ([read here](https://fontawesome.com/how-to-use/on-the-web/styling/sizing-icons)). For example:

```html
<i class="nai nai-lichess nai-2x"></i>
```

## Requests

I am happy to incorporate additional icons if I can. Please submit your requests at <https://github.com/piazzai/nonacademicons/issues> providing a link to the image you need.
