# Mana Icons Flutter

Lets you use Magic: The Gathering symbols as icons in your flutter project! 

This is a package which wraps the symbol font [mana](https://github.com/andrewgioia/mana) by Andrew Gioia, and allows it to be used as icons in flutter.

## Getting started

### Install

```yaml
dependencies:
  mana_icons_flutter: ^0.0.1
```

## Usage

```dart
// import the package
import 'package:mana_icons_flutter/mana_icons_flutter.dart';

// use the icons directly
const Icon(ManaIcons.ms_w)

// use icons by string
const Icon(ManaIcons.icons["ms_w"])
```

Check out mana's [docs](https://mana.andrewgioia.com/icons.html) for available icons.


## License

All symbol images are trademarks of Wizards of the Coast ([http://magicthegathering.com](https://magicthegathering.com)). This package is lisenced under GNU AGPL v3.0 or later. 

Please see mana's [license](https://github.com/andrewgioia/mana?tab=readme-ov-file#license) for information about the mana icon font's license.
