##CSS3 Textmate Bundle

- - - - - - - - - - - - - - - - - - - - - - -

###Motivation
Inspired and gleaned by [http://css3please.com](http://css3please.com/),
I wanted to create a handy set of css3 snippets with vendor support and fallback code without having to google search every time :) These snippets support tab completion and all values entered update any repeated values on the fly.

###Usage 
Usage is simple: From the list of snippets below, enter the name followed by the tab key __eg__  <code>round[tab]</code>
__Note__ In some cases you may find more than one option for convenience:  
  
![Snippet Options](http://f.cl.ly/items/320C403N2Q210i2Y3z1L/screenshot.png)

###Snippet List:

*  __round &#8594;|__ border-radius(s)
* __shadow &#8594;|__ text-shadow, box-shadow:inset, box-shadow
* __gradiant &#8594;|__: gradiant
* __rgba &#8594;|__: rgba
* __rotate &#8594;|__: rotate
* __transition &#8594;|__: transition
* __fontface &#8594;|__: $font-face

###Installation

    $ cd ~/Library/"Application Support"/TextMate/Bundles
    $ git clone git://github.com/tristen/css3-tmbundle.git "css3.tmbundle"
    $ osascript -e 'tell app "TextMate" to reload bundles'
    
###TODOs
*  Add 'stops' options to gradiants
*  [2D and 3D Animation support](http://css3.bradshawenterprises.com/)