Originally posted to the fourth [72 hour game development competition](https://github.com/featherless/72hourgdc)
from December 17, 2004 to December 20, 2004.

[Download the submitted entry](https://github.com/72hourgdc-2004-december/wands/archive/submission.zip).

    --------------------
    Wizards at 20 Paces!
    --------------------

    Eron Steger
    Kevin Forbes
    Mike Pratscher


    ------------
    Story
    ------------

    Two wizards enter.  Only one will survive!

    Wizards must strategically customize the map with spell sources.  By powering
    up their magical spells through these spell sources, they can inflict
    far greater damage.


    ------------
    Running
    ------------

    Load 'wizard.exe'


    ------------
    Instructions
    ------------

    THIS GAME REQUIRES THE USE OF GESTURES!  PLEASE READ ON TO LEARN HOW
    THEY WORK.  HOLD 'H' OR 'F1' IN THE GAME TO SEE DIAGRAMS OF THE GESTURES 
    POSSIBLE.  GESTURES REQUIRE HOLDING THE LEFT-MOUSE BUTTON, MOVING THE
    MOUSE IN THE GESTURE SHAPE, AND RELEASING THE MOUSE BUTTON.


    The wizards take turns casting spells at one another.  Once a wizard has
    finished casting a spell, it is the next wizard's turn.  This continues
    until one of the wizards is no more.


    Moving
    ------

    To move your wizard, right-click to the position you want him to walk to.
    You can only walk once per turn.  You must stay on your side of the map,
    and you cannot walk into the chasm.


    Casting spells
    --------------

    1)
    First, you must wave the wand in the shape of the spell you wish to perform.
    To do this, hold the left-mouse button, perform the gesture, and let go.
    If you were successful, your wizard will recite an incantation.  If you hear
    nothing, you didn't perform the gesture correctly.  If the wizard sounds
    pissed, that's because he doesn't have enough mana to do the spell.

    There are two types of spells: shot spells and creation spells.

    Hold 'h' or 'F1' to see the gestures for the various spells.  Those on the
    left are shot spells, those on the right are creation spells.


    2)

    (a) Shot spells

    The shot will glow near your wizard till you shoot it out.  Click in the
    direction you want it to go.

    You can manipulate the shot as it moves by holding the left-mouse button, 
    but it will drain mana.


    (b) Creation spells

    Click where you want the creation spell to occur.  Creation spells allow 
    you to customize the landscape by building spell sources.



    Magic Elements
    --------------
    Magic shots and magic sources can be one of several elements.  There are
    four basic elements: Fire, Water, Earth, and Electricity.

    When a shot goes over a source of the same type, it increases in power.
    Going over multiple sources with one shot increases it's power incredibly.
    Beware: Some sources cancel spells out.

    In addition to elemental magic, there is also the basic mana magic.
    It's gesture is simply moving the wand up.  It does not have any power on 
    it's own, and thus must go through a spell source in order to pick up its 
    power.  When it goes over a spell source, it gains that elemental type.


    Mana
    ----

    All spells, along with shot manipulation, cost mana.  There is both
    energy mana and elemental mana.  Elemental mana comes in the four types
    of elements.

    The mana shot spell, shot manipulation, and creation spells only take
    energy mana.  The elemental shot spells take elemental mana.  You
    must have enough mana to perform the spell, or else it will not work.


    ------------
    Libraries
    ------------

    We used the following libraries to construct Wizards at 20 Paces:
    Simple Directmedia Layer (SDL)
    Simple Directmedia Layer Mixer (SDL mixer)
    glpng (libpng, zlib)
    glfont (Brad Fish - bhf5@email.byu.edu)
    libstroke 
    tinyxml


    ------------
    Licence
    ------------

    This program is licensed under GPL version 2.
    See COPYING for more information.

