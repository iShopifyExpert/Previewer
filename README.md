Previewer
=========

For customizable products in Shopify

Ingredients: 1) javascript.liquid, 2) initial-assignments.liquid, 3) display-box.liquid, 4) dropdowns.liquid

The options dropdowns are taken from the product image names. So make sure to name your images: optionLabel_optionName. The label should be consistent
between all your options in a dropdown. For example, your background images should be named: background_blue.png, background_green.png, and so on.

The javascript is what changes the images in the display boxes. The initial assignments grab and parse the image titles from the product images. The display boxes are just that. And the dropdowns is the real meat -- if you can simplify that code, please let me know.

A major key is your css. Your images should all be the same dimensions. You should also make your display box that same dimension. It also needs a position value of absolute and, subsequently, a bottom margin equal to its height. 

You can also add customizable text. I didn't integrate it with the image example, but I've thrown it in the files if you want to mess with that too. 

Oh yeah, the key to all this, in Shopify, is to use the line-item properties to send this info through the cart and to the order details.