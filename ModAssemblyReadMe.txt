Configuration file is very simple: 
- 1 line per argument. (case sensitive)
- no spaces between rgb numbers
- numbers are between 0 and 1 (inclusive). Some examples: .5, 1, 0, .75, .3333

Arguments are:
rgb (number,number,number) // (0,0,0) is default (black)
rainbow_grapple = true or false // if set to true, the rainbow grapple will override any rgb settings
grapple_size = number // 1 is default
perfectPingRgb (number,number,number) // (0,1,0) is default (green)
goodPingRgb (number,number,number) // (1,1,0) is default (yellow)
decentPingRgb (number,number,number) // (1,.5,0) is default (orange)
badPingRgb (number,number,number) // (1,0,0) is default (red)

Example:

// grapple modifications

rgb (.75,.5,1)
rainbow_grapple = false	
grapple_size = 5

// ping modifications

perfectPingRgb (0,1,0)
goodPingRgb (1,1,0)
decentPingRgb (1,.5,0)
badPingRgb (1,0,0)