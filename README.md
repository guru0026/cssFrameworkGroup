# cssFrameworkGroup
CSS custom framework

We used a list of general utility variables like borders, padding, margins, width, etc. to be used across different components in the input.scss file.

Venushka's button framework
I have created 4 buttons with four different states that can be used for various options. the colors that were used for these buttons are from our theme colors, which is in the variables.scss file. you can simply add the button classes .button-primary, .button-secondary, .button-info and .button-warning in your HTML file code and add the button that you prefer. You can also customize any button styles according to your preference by going to input.scss and editing the @mixin btn-styles section. 

Mohamed's list framework
The list framework I created is a quick way to stylize your list. If you use the class "list-style"on your div or ul it will add padding a thick border and light background into the container while it has a border shadow beneath it. If that doesn't work for you you can always use the class "ul-style". It changes the background color of the container red and adds padding inside as well. The list items can also be customized with the classes as well. If you use the class "list item" it adds borders beneath each of the list items with padding and uses the color black for the font. If you use the class "li-style" it uses no borders adds padding and changes the font color to blue.

Hari's navbar framework
The nav framework, which can be trageted using the "navbar" class allows you to choose between three alignment variants. The default variant is aligned to the right. But if you add "-center" or "-left," the hyperlinks shift to those positions, as demonstrated in the page. The links have a hover-state which creates an underline, and when selected, the colors invert to white font against a rounded black background to match the styling of the buttons.

Hari's form framework
Three variants of the input form type were created which can be targeted using the "form" class. The default type without a suffix is a white form with black border, consistent with the list style. The other two variants, with suffixes of "-grey" and "-dark" create grey and black input forms respectively. This is also demonstrated in the actual page.
