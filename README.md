# Style guide resources for Sketch
A template containing SEEK UI components, for designers using [Sketch](https://www.sketchapp.com/).

- [Prerequisites](#prerequisites)
- [Installing the template](#installing-the-template)
- [What's in the template](#whats-in-the-template)
- [Using the template](#using-the-template)
- [Naming conventions](#naming-conventions)

## Prerequisites
1. Mac OS X 10.9+
2. Download and install Bohemian Coding's [Sketch app](https://www.sketchapp.com/).
3. Download and install the following Roboto fonts on your computer:
    - [Roboto](https://www.google.com/fonts#UsePlace:use/Collection:Roboto).
    - [Roboto Condensed](https://www.google.com/fonts#UsePlace:use/Collection:Roboto+Condensed).
    - [Roboto Mono](https://www.google.com/fonts#UsePlace:use/Collection:Roboto+Mono).

## Installing the template
Make sure the template is stored in:

```
/Users/USER_NAME/Library/Application Support/com.bohemiancoding.sketch3/Templates
```

This will make the template available in the `File > New From Template >` menu.

If you are using GitHub you can clone the repository directly to the folder above.

**Note:** On most Macs, the `~/Library/` folder is not shown by default. [Read how to show it](http://osxdaily.com/2013/10/28/show-user-library-folder-os-x-mavericks/).

## What's in the template
1. **Sticker sheet**

    This is the main art board which showcases all the UI elements defined in the template.
    When adding new symbols, add them to the sticker sheet.

2. **SEEK Employment desktop template**

    A template page containing the standard SEEK Employment header and footer.
    The grid (using Sketch's 'Layout' tool) is defined for this page, according to our grid design.

3. **SEEK Advertiser desktop template**

    A template page containing the standard SEEK Advertiser header and footer.
    The grid (using Sketch's 'Layout' tool) is defined for this page, according to our grid design.

## Using the template
All the UI elements are created as symbols. Keep this in mind when changing symbols as part of your design. Always 'detach from symbol' if you are making a change that you do not want to apply to the original symbol.

The building blocks of symbols are generally defined as styles.

For example, a button consists of two elements:
1. A rectangle which has colour, border and shadow properties.
2. A text label which has all the usual text properties.

When defining a symbol like a button, both of the items above should be defined as 'Shared styles'.

## Naming conventions
Follow the naming convention in the template. Using '/' allows Sketch to organise your symbols and styles into folders.

For example, consider the following button symbols:
1. `Button/SEEK Employment/Primary - default`
2. `Button/SEEK Employment/Secondary - default`

In this examples, both buttons are placed in the `Button/SEEK Employment` folder.

This structure makes the symbols and styles easy to navigate.
