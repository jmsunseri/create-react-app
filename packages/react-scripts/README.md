# :warning: WARNING!

This is a fork of [`react-scripts`](https://github.com/facebook/create-react-app/tree/master/packages/react-scripts) that provides support for [Material Components Web React](https://github.com/material-components/material-components-web-react).

With this fork you should be able to:

- use MCWR in a Create React App
- use MCWR in a mono-repo
- compile MCWR SASS, allowing you to theme components

It changes two things:

- Fix for this [resolve-url-loader issue](https://github.com/bholloway/resolve-url-loader/issues/107#issuecomment-432957204).
- Allows CSS imports to append `_` or omit `.scss` for MCWR nested SASS file support. Using this [helper function](https://github.com/material-components/material-components-web-react/blob/master/packages/webpack.util.js).

_If this become out of sync with upstream `react-scripts`, please ping me with an issue._

# react-scripts

This package includes scripts and configuration used by [Create React App](https://github.com/facebook/create-react-app).<br>
Please refer to its documentation:

- [Getting Started](https://facebook.github.io/create-react-app/docs/getting-started) – How to create a new app.
- [User Guide](https://facebook.github.io/create-react-app/) – How to develop apps bootstrapped with Create React App.
