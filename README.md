Dark Soda (Monokai) Theme
=========================
Nylas N1 Theme - Dark Soda (Monokai). This will theme your N1 client to look more like the text editor
theme Dark Soda or Monokai.

Installation
------------

1. Download and unzip or clone this repo `git clone https://github.com/adambullmer/N1-theme-DarkSoda`

1. Download and run N1

1. From the menu, select `Developer > Install a Package Manually...`
   The dialog will default to the examples directory. Navigate to the directory you
   cloned this repo in and select the root folder.

   > When you install packages, they're moved to `~/.nylas/packages`,
   > and N1 runs `apm install` on the command line to fetch dependencies
   > listed in the package's `package.json`

1. Make sure you are running the dark theme from the N1 preferences.
   Select `Nylas N1 > Preferences > Appearance` and check the `Use dark color scheme` box


Updates
-------
As it is right now, packages are a very manual thing in N1, so be sure to check the [Release Section](https://github.com/adambullmer/N1-theme-DarkSoda/releases)
for releases. You'll have to reinstall via the steps above.


Who?
----
This package is a theme only and is intended for developers who have experience with LESS / CSS


Issues
------
This project was born out of some incomplete styling of the default dark theme, and has grown into a bigger
theme than just style fixes. I add to the stylesheet as I see new sections that should be themed.
To report an issue an I need to have:

- A screenshot of the affected area, preferrably with some surrounding context
- A suggestion for what color should be used (for a comprehensive list, see the [Colors](https://github.com/adambullmer/N1-theme-DarkSoda/blob/master/stylesheets/colors.less) list)
- How you arrived at that section
- If it is the result of another plugin, which plugin

Contributing
------------
I'm open to pull requests, but the base color scheme has been solidified. Only using colors within the theme
will be allowed. However, I am open to different / better color usage within the app.
