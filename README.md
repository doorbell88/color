# color
function to change terminal text color

hint: Add as an alias to your .bash_profile:
alias c='/PATH/TO/COLOR/color'


    color
      Set text foreground to an RGB color.
      (R,G,B values range from 0-5.)
    
    Usage:
      color [-h | --help]  Show this message
      color [RGB]          Set color to RGB (values 0-5 accepted)
      color                Set back to normal
    
    Example:  Setting the text color to bright yellow
      color 550 
