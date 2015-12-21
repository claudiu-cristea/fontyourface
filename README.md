# @font-your-face

## Overview

@font-your-face provides an administrative interface for browsing
and applying web fonts (using CSS @font-face, supported in all popular browsers) from a variety of sources.

## Features

* A font browsing interface allows selection of fonts from from several providers:
  - [Typekit.com](http://typekit.com/)
  - [Google Fonts](http://www.google.com/webfonts)
  - [Font Squirrel](http://www.fontsquirrel.com/)
  - [Fontdeck](http://fontdeck.com/)
  - [Fonts.com](http://webfonts.fonts.com/)
  - [Adobe Edge Web Fonts](http://html.adobe.com/edge/webfonts/)
* Fonts are automatically loaded on site simply by clicking "Enable"; no need to create font files, write CSS, add JS, nor figure out different methods for every font provider.
* Clear indication of license restrictions on provided fonts.
* Fonts can be applied to specific text on the site either by using the provided font-family identifier in theme CSS, or by typing a CSS selector directly in the @font-your-face interface.
* The @font-your-face code is designed for re-use, so other modules can both supply and read active and available font information.
* Fonts can be exported/imported using Features (7.x-2.x only).
* You can also import your own local fonts in all web formats: EOT, TTF, WOFF and SVG.

## Install and Configure

Install the module as any other Drupal module. Configure the module at /admin/config/user-interface/fontyourface.
