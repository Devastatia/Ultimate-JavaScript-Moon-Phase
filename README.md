# Ultimate JavaScript Moon Phase

Acknowledgment:

This project is based on a moon phase calculator written by Graham Fairweather (@Xotic750) in 2013, found here:

https://jsfiddle.net/Xotic750/YQqcj/

The original script was released under the GPL; therefore I have done the same here.

I've modified the original as follows:

Math and Date related functions recast as methods of their respective built-in JavaScript objects or prototypes.

Refactored as a JavaScript "class" with the following public methods:

setDate(month, day, year)

If not called, the MoonPhase object is initialized with today's date.

getPhase()

Returns an integer {0...29} representation of the moon phase.

render(containerId)

Renders the moon phase image as a CSS background-image on the specified container element.

toString()

Returns a string containing an emoji and English name of the moon phase.
