# Release Notes

## 1.5.1 (02-21-2025)
- fix sold out badge for hide price from guest

## 1.5.0 (01-20-2025)
- [CORNERSTONE] Add nonce to scripts in checkout and account pages [#2525](https://github.com/bigcommerce/cornerstone/pull/2525)
- [CORNERSTONE] Use fetch when updating variants in cart ([#2521](https://github.com/bigcommerce/cornerstone/pull/2521

## 1.4.1 (11-15-2024)
- Fix browser crash when editing options in Bulk Order layout with products that have an empty file
- Fix undefined 'input-font-color' in add payment methods account page
- Use Node 20.17
- bump stencil-utils to 6.18.0
- Fix scss error theme-mobile.scss

## 1.4.0 (08-02-2024)
- Update code from Beautify 1.5.1.

## 1.3.2 (09-22-2023)
- Fix cart quantity input change not working
- Fix to prevent mega menu from overflowing right edge of page
- Update Webpack 5 + Node 18

## 1.3.1 (06-29-2023)
- Fix issue with deleting cart item in version 1.3.0

## 1.3.0 (06-22-2023)
- Fix SCSS Compiler error in fonts-icons.scss
- Use Node 16.20.0
- Update from Beautify 1.4.0:
  - Fix edit cart item display incorrect message when product is unavailable / out of stock
  - Fixed unavailable options' strikeout display during cart edit
  - Fix SCSS compiler in fonts-icons.scss for Node 16
  - Increase warning of asset size limit to 500KB
  - Display final price after non sale price in price range on PDP
  - Fix SCSS Compiler
  - Style PayPal GPay Venmo additional checkout buttons
  - Update stencil-utils 6.15.0
  - Rename setting variables: fontSize-*, button-radius, carousel-bgColor-opacity, input-radius, container-border-radius, to change the variable types.

## 1.2.3 (06-16-2023)
- Fix phone icon and menu overlap on mobile when logo is centered

## 1.2.2 (05-12-2023)
- Fix bulk pricing no values on PDP

## 1.2.1 (04-20-2023)
- Fix SCSS Compiler

## 1.1.2 (03-04-2022)
- Hide Shop by Brand on the navigation if Sidebar Shop by Brand = Hide
- Remove header logo css on checkout page
- Added new region on the cart page [#1901](https://github.com/bigcommerce/cornerstone/pull/1901)
- Added custom event for product price change on PDP page. [#1948](https://github.com/bigcommerce/cornerstone/pull/1948)
- Fix PayPal Pay Later Message on Cart page
- Fix JS error & swatch thumbnail on hover on Choose Options popup

## 1.1.1 (02-21-2022)
- Fix "Image gallery position" displays in reverse order.

## 1.1.0 (02-18-2022)
- Fix view all links from products.php to categories.php
- Fix loading-40.gif not found
- Add option "Image gallery position"

## 1.0.0
- Initial release.
