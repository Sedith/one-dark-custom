## Modified One Dark Syntax theme

This package is forked from the Atom One Dark Syntax theme, which is now available in atom core repository.

The only change from the original theme is the reduction of the amount of red, in the case of chained '.' variables.
For Python, this means no aggresive red for the calls of class attributes (_self.attr_) or packages (_np.empty(.)_).
> The modifications are in styles/syntax/\_base.less:85-96

Here will be a comparison :

> !

The package is still matching the [UI theme](https://atom.io/themes/one-dark-ui).
