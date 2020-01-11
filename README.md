## How to visualize sounds ?

We have for instance the classical waveform representation - a wavy line along a horizontal time axis, vertical axis being the amplitude.
<br/>
Unfortunately, an actual graphical waveform on a screen is not "bitperfect", details are lost, amplitude is scaled down.
<br/>
Usually a sound sample is encoded on 16 bits which means we can have 65536 distinct amplitude values.
<br/>
To accurately represent these values we would need a vertical screen resolution of about 64k. No such thing exists ...
<br/>
Therefore let us map amplitude to pixel color ...
<br/>
Here is a simple example
<br/>

