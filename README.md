[![BSD License](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)
[![Latest Stable Version](https://poser.pugx.org/ttree/stylesheet/version)](https://packagist.org/packages/ttree/stylesheet)

# StyleSheet Fusion Prototypes

This package contains Fusion prototypes to work with StyleSheets in your Flow Framework and Neos CMS project.

## Available Objects

### Ttree.StyleSheet:Resource

Generate a HTML link element in HTML5:

    stylesheets.main = Ttree.StyleSheet:Resource {
        uri = 'resource://Your.Package/Public/Styles/Main.css'
        cacheBusting = true
    }

You can disable HTTP cache busting by setting ```cacheBusting``` to ```false```.

Set ```inline``` to ```true``` to inline the content of the resource.

### Ttree.StyleSheet:External

Generate a HTML link element in HTML5:

    stylesheets.main = Ttree.StyleSheet:External {
        uri = 'http://www.domain.com/main.css'
    }

## Acknowledgments

Development sponsored by [ttree ltd - neos solution provider](http://ttree.ch).

We try our best to craft this package with a lots of love, we are open to sponsoring, support request, ... just contact us.

## License

The MIT License (MIT). Please see [LICENSE](LICENSE) for more information.
