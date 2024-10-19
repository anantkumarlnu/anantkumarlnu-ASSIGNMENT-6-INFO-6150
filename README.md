# anantkumarlnu-ASSIGNMENT-6-INFO-6150
ANANT KUMAR LNU
002050375

6th assignment for INFO 6150 

REQUIREMENTS 

WEBPAGE DESCRIPTION 

Being the metalhead that I am, I went with a metallica landing page and merch page website. never had so much fun creating an assignment, maybe because it was related to something that I am passionate about.😅
the landing page has a hero section, info section for current members, a card for the late Clifford D Burton and a footer.

LANDING PAGE 
- hero section has a nav, background image(with gradient for better visibility) and descriptive text that is absolutely positioned.
- Nav has link to the merch page as well, flexbox is used for this (nested flexbox, as I wanted to move the merch and user icon together to the right)
- the info sections have text and bootstrap carousel that are set to autorotate the images, buttons have been removed from the carousel. grid is used for this 
- Cliff section is designed similarly to the hero section, the text is kept on the top left, positioning suits well in my humble opinion.
- footer has the link to official metallica website and their instagram as well, usage of flexbox 

MERCH PAGE
- similar hero section with a different image 
- grid is used here for the product section 
- filter accordion is made to take the entire first column using span property of grid
- footer is similar as the landing page 

FLEXBOX IMPL
- header and footer for landing page 
- header and footer for the merch page 

CSS GRID IMPL
- current member section on the landing page. 2 columns, equal width using 1fr for both, 4 rows.
- merch-grid section of the merch page. span is used to span the filter entire first column and the rest of the sale-item cards take the open spaces 

SASS IMPL 
- FOLDER STRUCTURE - as required the structure of the sass is broken up into folder that make sense semantically 
- VARIABLES - used for colors, font-sizes and a few other css properties 
- CUSTOM PROPERTIES - used for colors of buttons for sale-items
- NESTING - hero section has nesting for user icon 
- INTERPOLATION - buttons scss implement interpolation for color of buttons, resulting in dynamically generated css classes 
- PLACEHOLDER - used for centering margins and box shadows 
- MIXIN - used for flex container for footer
- FUNCTIONS - used for spacing for padding across pages 
- IF - used with interpolation 
- FOR - used for looping over color values and dynamically creating classes
- MAP - used for fetching font values from the variable ..used all across the page

REFERENCES
IMAGES
https://www.facebook.com/LeeJeffriesphotographer/
https://www.facebook.com/rosshalfinofficial/
https://www.facebook.com/Metallica/
and other several other fan accounts for older images 

ICONS
https://heroicons.com/

COLORS
https://yeun.github.io/open-color/

BOOTSTRAP ELEMENTS
https://getbootstrap.com/docs/5.3/components/accordion/
https://getbootstrap.com/docs/5.3/components/card/
https://getbootstrap.com/docs/5.3/components/carousel/

PS
original scope of the webapp was way bigger than what has been implemented, hence the abundance of images, of past members and extra banners.