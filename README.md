# Piccolo Theme

[![Documentation Status](https://readthedocs.org/projects/piccolo-theme/badge/?version=latest)](https://piccolo-theme.readthedocs.io/en/latest/?badge=latest)
[![PyPI](https://img.shields.io/pypi/v/piccolo-theme?color=%2334D058&label=pypi)](https://pypi.org/project/piccolo-theme/)

A clean and modern Sphinx theme.

![Screenshot](https://raw.githubusercontent.com/piccolo-orm/piccolo_theme/master/docs/screenshots/docs.png)

## Docs

See [Read the docs](https://piccolo-theme.readthedocs.io/en/latest/).

## Typography

Roboto is used for the body copy, and Roboto Mono for code snippets. As these
fonts belong to the same family, they look nice together. Both of them are
also highly legible on small screens.

We use bold, easy to read headers.

**Note** - this isn't a Material Design theme. The aim is to create a nice
theme, with our own aesthetic preferences, rather than implementing Google's
Material Design spec.

## Code docs

We make your autodoc code snippets nice and legible:

![Screenshot](https://raw.githubusercontent.com/piccolo-orm/piccolo_theme/master/docs/screenshots/api_docs.png)

This even works for C++ files via [breathe](https://breathe.readthedocs.io/en/latest/).

## Dark mode, and darkest mode!

We have a gorgeous dark mode 🥷:

![Screenshot](https://raw.githubusercontent.com/piccolo-orm/piccolo_theme/master/docs/screenshots/dark_mode.png)

And for users with OLED displays, we have the 'darkest' mode - where the
backgrounds are pure black 🧛‍♂️:

![Screenshot](https://raw.githubusercontent.com/piccolo-orm/piccolo_theme/master/docs/screenshots/darkest_mode.png)

## Other design features

 * Optimised for mobile and web.
 * A header bar gives the design a splash of colour.
 * Simple but elegant design.

## Contributing

### Building styles

In the root of the project:

```
npm install -g sass
```

Then:

```
./scripts/build-styles.sh
```
