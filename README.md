# Modified One Dark Syntax theme

This package is forked from the Atom One Dark Syntax theme, which is available in atom core repository. Most of the changes concern Python syntax coloring.

The main change from the original theme is the reduction of the amount of red, in the case of chained '.' variables.

For Python, this means no aggresive red for the calls of class attributes (_self.attr_) or packages (for instance _np.empty(.)_).

Most of the colors are also redefined and have more explicit names.

Here will be a comparison, someday :

> !

The package is still matching the [UI theme](https://atom.io/themes/one-dark-ui).
