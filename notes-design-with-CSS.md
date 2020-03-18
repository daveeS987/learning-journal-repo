# Design with CSS Notes

- Block level elements look like they start on new line
- inline elements flow within the text

Example styles: boxes, text, specific

**Terms to know:** 
- rule set
- selector, declaration
- inside the declaration is the property, value

Ruleset:  
.banana {  
      background-color: red;  
}
 
### Box model
- content - text
- Padding - clear area around the content
- border - around the content and padding
- margin - around the border. is transparent

### CSS Selectors

`.class {}` Class Selector    
`#id {}` ID Selector    
`* {}` Universal Selector   
`h1 {}` Type Selector   
`li>a {}` Child Selector (targets any a elements that are childeren of li elements)  
`p a {}` Descendent Selector (targest any a elements inside p elements even if there are other elements nested between)  
`h1 + p {}` Adjacent Sibling Selector (targets the first p element after any h1 element but not other p elements)  
`h1~p {}` General Sibling Selector (if you had two p elements that are siblings of an h1 element, this rule would apply to both)  

### How CSS Rules Cascade

- Last Rule
- Specificity
- Important: you can add !important to a property value 

- Note: CSS rules usually appear in a separate document

### CSS Color

Colors can be specified using colornames, hex codes, RGB, HSL.

**hsla**
- Hue - the colloquial idea of color
- saturation - amount of gray in color. maximimu saturation there is no gray. minimum saturation means its mostly gray
- brightness - how much black is in a color. maximum brightness means no black in color. minimum means color woudl be very dark
- lightness - amount of white or black in a color. sometimes refered to as luminosity. 0 lightness is black. 100% lightness is white. and 50% is normal. 
- alpha - expressed as number between 0 and 1.0. Represents transparency


water falls from top to bottom



