to re-enable purchase buttons etc do this:

1. remove or comment all the styles in the section of the style.css.liquid >

```/* /disable store buttons, dropdowns, cart
==================================== */
```


2. remove the {% comment %}{% end comment %} tags from line 65 product-header.liquid


3. re-add menu items to Main menu:
Cart > web address > /cart
Checkout > web address >/checkout
