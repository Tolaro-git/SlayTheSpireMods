Translation files for mods below:

  Red: https://steamcommunity.com/sharedfiles/filedetails/?id=3032112884
  
  Green: https://steamcommunity.com/sharedfiles/filedetails/?id=3219969350
  
  Blue: https://steamcommunity.com/sharedfiles/filedetails/?id=2970853759
  
  Purple: https://steamcommunity.com/sharedfiles/filedetails/?id=3342218134

Fork this, and notify me via the workshop page once you are done. I may not be active here. Or show me your files somehow if you don't do GitHub


# Translation Guide

## Card Descriptions:

  Vulnerable, Evoke and Exhaust are keywords. They are explicitly defined in the code. Keywords are automatically colored yellow and display a tooltip when hovered over. They must be capitalized in the translation file, and must be separated from the rest of the text with spaces, even in languages that normally do not use spaces. Otherwise, they may not be recognized.
  
  Below are the special symbols used in card descriptions. Do not alter them.
  
    [R] [G] [B] [W]: Red, Green, Blue and Purple energy symbols respectively
  
    !D!: Damage amount
    
    !B!: Block amount
    
    !M!: Other values, such as debuff duration and draw count
    
    !kobeBlue:SecondMagic!: Same as above
    
    kobepurple:Common: This is how you put a mod-defined keyword. It's case sensitive.
    
    *: Colored word. Game automatically color keywords, so this is mainly for created cards.

    NL: Manual line break. These are optional and you can add/remove/relocate them however you want. In practice, you only use them for visual separation between unrelated card effects. Game automatically inserts line breaks to fit the text in the text box.
  
  
## Power Tooltips:
  
  Each power tooltip consists of multiple strings separated by commas so that the game can insert varying numbers between them. Since the order of numbers can not be changed, you will need to adapt your translation to fit the English format.
  
  Power tooltips use different symbols from card descriptions:
    
    #y: Colored word (yellow)
    
    #b: Colored number (blue)
