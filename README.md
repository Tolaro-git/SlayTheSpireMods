Language files for these mods:
  
  Red: https://steamcommunity.com/sharedfiles/filedetails/?id=3032112884
  
  Green: https://steamcommunity.com/sharedfiles/filedetails/?id=3219969350
  
  Blue: https://steamcommunity.com/sharedfiles/filedetails/?id=2970853759
  
  Purple: https://steamcommunity.com/sharedfiles/filedetails/?id=3342218134

Fork this, translate, and let me know once you are done. 

If you need any further help, catch me on Discord: https://discord.gg/GAnNc6d23Y


# Translation Guide

## Card Descriptions

### Symbols
  Below are the special symbols used in card descriptions. Do not alter them.
  
    [R] [G] [B] [W]: Single energy symbol. Red/Green/Blue/Purple respectively.
  
    !D!: Damage
    
    !B!: Block
    
    !M!: Other numerical values, such as debuff duration and draw count
    
    !kobeBlue:SecondMagic!: Same as above
    
    *: Manual word highlight. Keywords are highlighted automatically, so this is mainly for created cards like Shivs.

    NL: Manual line break. These are optional and you can add/remove/relocate them however you want. In practice though, you're only going to use them for visual separation between unrelated card effects as the game can handle long texts on its own.

### Base Game Keywords
  Special words such as Evoke and Block are called keywords. You need to format them properly so the game can recognize, otherwise there will be no highlights and no tooltips. They must be capitalized in the translation file, and must be separated from the rest of the text with spaces, even in languages that normally do not use spaces.

  If a keyword consists of two words in your language, you must replace the space with \u00A0.
  
    Translated\u00A0Keyword

### Mod Keywords
Mod-defined keywords look like this and unlike the symbols listed above, you do need to translate them:
  
    kobepurple:Common
    
    kobepurple:普通牌

## Power Tooltips

### General
  Each power tooltip consists of multiple strings so that the game can insert varying numbers between them. Since the order of those numbers can not be changed, you will need to adapt your translation to fit the English format.

### Symbols
  Power tooltips use different symbols from card descriptions:
    
    #y: Colored word (yellow)
    
    #b: Colored number (blue)

