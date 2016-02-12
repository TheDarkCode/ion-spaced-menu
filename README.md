# ion-spaced-menu
Fork of mAmged's ionic-ion-airbnbmenu repo with changes. Inspired by SpacedOut.

[![Packagist](https://img.shields.io/packagist/l/doctrine/orm.svg)](https://github.com/TheDarkCode/ion-spaced-menu/blob/master/LICENSE)

##Demo: http://codepen.io/DarkCode/pen/yeRory

###Usage:

Requires Ionic Framework 1.x. Has been tested and works with the latest nightly builds (confirmed up to 1.2.1). As in the demo, you need to use both a right and left side menu.

Include the ion-spaced-menu.css file in the header after all other ionic css files. Include ion-spaced-menu in footer with other javascript being loaded.

In your main app module, you need to add "ion-spaced-menu" to your app's dependencies.

Modify CSS as necessary to your liking. Currently set to left: 40px, with 90% height, and 5% top/bottom margins.

It is recommended that you use drag-content="false" on ion-side-menus and ion-side-menu-content. Otherwise you can crash your app from trying to swipe too much on some platforms (not in browsers).

Menu-right will work like a normal right side menu and get tagged as inactive (modify with css to liking if you want to show it on wide-format displays).

####ionic-ion-airbnbmenu repo:
https://github.com/mAmged/ionic-ion-airbnbmenu

####SpacedOut repo:
https://github.com/ace-subido/spaced-out
