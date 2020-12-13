# Isomorphic Neotrellis Keyboard

This keyboard was created to support isomorphic keyboard type on the NeoTrellis M4. Isomorphic keyboard is a two dimensional grid layout on which any given sequence and/or combination of musical intervals has the "same shape" on the keyboard wherever it occurs [[1]](https://en.wikipedia.org/wiki/Isomorphic_keyboard).
This gives the advantage of different types of chords (major, minor, diminished) having the same shape across the keyboard.
The adafruit midi arduino example was used as a base, the only addition being a mapping of the 4x8 grid to a isomorphic key layout.
The root note in this example is C3, which can be modified or assigned to a variable so you can cycle through octaves.
The accelerometer is also used as pitch bend.

[1] https://en.wikipedia.org/wiki/Isomorphic_keyboard
