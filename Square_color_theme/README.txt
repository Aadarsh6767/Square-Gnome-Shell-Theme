Square_color_theme
==================

This package contains two GNOME Shell theme variants:

- Square_color_theme: dark appearance, based on MY_Theme-Dark
- Square_color_theme-Light: light appearance, based on MY_Theme

Requirements
------------

- GNOME Shell 50. CSS compatibility with other Shell versions is not verified.
- The GNOME Shell "User Themes" extension must be installed and enabled to
  select this custom Shell theme in GNOME Tweaks.
- The Theme Color Sync extension must be enabled to switch variants
  automatically with GNOME's Appearance color-scheme setting.

The stylesheets have no external imports, images, fonts, or bundled asset
dependencies. They do not set or change the system icon theme.

Some optional styling rules target OpenWeather, COSMIC Dock, and Dash to Dock.
Those rules only apply when the corresponding extension is installed; none of
these extensions is required to use the Shell theme itself.

Installation
------------

Copy both theme folders into ~/.themes, enable the User Themes and Theme Color
Sync extensions, then choose either variant in GNOME Tweaks under
Appearance > Shell. The Theme Color Sync extension keeps the selection in
sync with the system light/dark preference.
