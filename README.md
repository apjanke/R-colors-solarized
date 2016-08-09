Solarized - R.app GUI color presets
===================================

Original Solarized colorscheme developed by Ethan Schoonover (<es@ethanschoonover.com>). See the [Solarized homepage] for details.

Adapted for R.app by Andrew Janke (<andrew@apjanke.net>).

[Solarized homepage]:   http://ethanschoonover.com/solarized

Solarized for R.app
------------

This project applies the Solarized colorscheme to R.app, the R GUI for OS X. The colors are used in the main console and editor, not in plots.

The source code and bug tracker for this port can be found on GitHub at https://github.com/apjanke/R-colors-solarized.

Installation
-------------

1. Exit R.app
2. Run setup-Rapp-solarized
3. Restart R.app

Implementation notes
-------------

R.app does not have support for importing or exporting its color schemes. This theme is installed by directly modifying the values in R.app's preferences file.

R.app's preferences file format is undocumented. The values used here were reverse-engineered from the preferences file for R.app 3.3.1 on OS X 10.11. It may not work for other versions. If you find a version of R.app this does not work with, please report it on the [project GitHub issue tracker].

[project GitHub issue tracker]:   https://github.com/apjanke/R-colors-solarized/issues
