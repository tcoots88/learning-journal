# Design web pages with CSS
## Color
### Foreground Color
    - The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of 
    three ways:
    1. RGB Values
        - These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)
    2. Hex Codes
        - These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign.
        For example: #ee3e80
    3. Color Names
        - There are 147 predefined color names that are recognized by browsers. For example: DarkCyan
### Background Color
    - CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background 
    for that box.
### Understanding Color
    - Every color on a computer screen in comprised of various combinations of Red, Green, and Blue. 
        - RGB Values: Values for red, green, and blue are expressed as numbers between 0 and 255.
        - Hex Codes:Hex values represent values for red, green, and blue in hexadecimal code.
        - Color Names:Colors are represented by predefined names. However, they are very limited in number (147).
        - Hue: Hue is near to the colloquial idea of color. Technically speaking however, a color can also have saturation 
        and brightness as well as hue.
        - Saturation: Saturation refers to the amount of gray in a color. At maximum saturation, there would be no gray in the 
        color. At minimum saturation, the color would be mostly gray.
        - Brightness: Brightness (or "value") refers to how much black is in a color. At maximum brightness, there would be 
        no black in the color. At  minimum brightness, the color would be very dark.
### Contrast
    - When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to 
    be legible.
    - Having contrast too low or high can make it difficult to read
### CSS3: Opacity 
    - CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements. 
    - The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).
    - The CSS3 rgba property allows you to specify a color, just like you would with an RGB value, but adds a fourth value 
    to indicate opacity.
### CSS3: HSL Colors
    - The hsl color property has been introduced in CSS3 as an alternative way to specify colors.
        - Hue: This is expressed as an angle(between 0 and 360 degrees).
        - Saturation: This is written a a percentage
        - Lightness:  Similar to Brightness, written as a percentage. So, 0% is white and 100% is black
        - Alpha: This is the fourth value in hsla and represents the transparency.  It is written as a value between 0 and 1.0
