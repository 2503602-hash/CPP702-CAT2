The CSS Box Model treats every HTML element as a rectangular box made of four layers, from the inside out:

Content: the actual text, images or buttons. Its size is set by width and height. In a product card, it holds the product photo, name, price and “Add to Cart” button.
Padding: the transparent space between the content and the border. In a product card, it stops the text from touching the card edge and makes the card look roomy and readable.
Border: the line that wraps the padding and content. In a product card, it gives the card a visible outline that separates it from the page background.
Margin: the transparent space outside the border, which pushes other elements away. In a product card, it creates gaps between neighbouring cards so the grid looks organised.

Total width of an element = content width + left/right padding + left/right border + left/right margin. For the card above, that’s 220 + 30 + 4 + 30 = 284px.