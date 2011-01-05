# Custom Menu Active Trail

Out of the box in [Drupal](http://drupal.org) 7 the only menus whose items are in the active trail are the menus provided by core. Custom menus will not work in the active trail. This leads to problems like custom menus being used for secondary links and that not working properly.

This module adds custom menus to the active trail by using an internal variable.

For more details see the [issue on drupal.org describing this problem](http://drupal.org/node/942782). Once that issue is resolved this module is deprecated.

## Usage
In order for this to work you will need to edit and save any custom menus that should appear in the active trail.

## Known Issues:

* If a menu item/path appears in more than one menu on a page the active trail will only be applied to one of them.
* There is no upgrade path from Drupal 6.

## License

This is licensed under the GPL 2+ just like Drupal.