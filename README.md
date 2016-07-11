# sumPause v1.0

## OVERVIEW
sumPause is a simple, lightweight, and open-source, Unity Asset for managing a paused/unpaused state. 
Drag-and-drop the prefab into your scene and instantly have a pause button. Uses the native Unity UI so you 
can easily change the look and feel of everything right in the editor. Licensed under MIT and CC0 so there 
are no worries on usage rights.

- Project Homepage: http://www.cyberlogical.com/sumpause/
- Repository: https://github.com/jerrydenton/sumPause

## USAGE
- Create a Canvas if there is not one in your scene already. [Create > UI > Canvas] in Hierarchy
- Copy the sumPause prefab into your Canvas.
- (Optional) Adjust position on screen in the RectTransform component
- (Optional) Select different icons from the 'Sprites' folder and attach it to the prefab
		(Don't forget the default sprite on the Image component)
- Your game now has a pause button!

**Check 'SampleScene' for example of proper setup**

## OPTIONS
The following options are available on the 'SumPause' component
- *Use Event* : Whether to trigger an event for other objects to listen for [bool, def: true]
- *Detect Escape Key* : Whether to pause on Escape Key press [bool, def: true]
- *Paused Sprite* : Sprite to display when game is paused (Additional sprites included in 'Sprites folder)
- *Playing Sprite* : Sprite to display when game is playing (Additional sprites included in 'Sprites' folder)

## EXAMPLE
'SampleScene' contains an example.

## PROJECT LICENSE
- The MIT License (MIT) - https://opensource.org/licenses/MIT
- Copyright (c) 2016 Jerry Denton

## OTHER ASSETS
- Icons are from the awesome CC0 collection by asset creator Kenney - https://kenney.itch.io/
- License (Creative Commons Zero, CC0) - http://creativecommons.org/publicdomain/zero/1.0/

## CREATED BY
- Jerry Denton
- http://www.cyberlogical.com

### CHANGE NOTES
----------------------------------------------------------

- v 1.0
- Initial version

----------------------------------------------------------

