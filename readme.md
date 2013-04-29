# Sassy Modular Scale
<<<<<<< HEAD
My fork of Team-Sass' [Modular Scale](https://github.com/Team-Sass/modular-scale) that adds the option for a separate scale for negative muliples. 

I really like the idea of a modular scale but multiples lower than the base size always get too small too quickly to be of much use. To correct this, a smaller scale for negative multiples can now be defined. 

I have also removed the multibase and multiratio features because they made things much more complicated and their use never made much sense to me. The idea of two scales laid on top of each other, IMO, breaks the scale. I understand that there may be a need for multiple scales on a page—but I think they should be indepentant of each other. 
=======
My fork of Team-Sass' [Modular Scale](https://github.com/Team-Sass/modular-scale) that adds the option for a separate scale for negative muliples.

I really like the idea of a modular scale but multiples lower than the base size always get too small too quickly to be of much use. To correct this, a smaller scale for negative multiples can now be defined.

I have also removed the multibase and multiratio features because they made things much more complicated and their use never made much sense to me. The idea of two scales laid on top of each other, IMO, breaks the scale. I understand that there may be a need for multiple scales on a page—but I think they should be interacted with independent of each other.
>>>>>>> Revised readme

Multiratios also don't appear to be [working correctly](https://github.com/Team-Sass/modular-scale/issues/33) in the current version of Modular Scale.

To avoid issues with the Modular Scale gem, I have "de-Gemified" the code so it is now a self-contained .scss file with no dependancies.

## License
Copyright (c) 2011 [Scott Kellum](http://www.scottkellum.com/) ([@scottkellum](http://twitter.com/scottkellum)), [Adam Stacoviak](http://adamstacoviak.com/) ([@adamstac](http://twitter.com/adamstac)) and [Mason Wendell](http://thecodingdesigner.com/) ([@codingdesigner](http://twitter.com/codingdesigner))

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
