=== Virtual Kalimba - A Web Audio experiment by Middle Ear Media. ===

Author: Obadiah Metivier
Author URI: http://middleearmedia.com/kalimba/
Tags: web audio api, kalimba, virtual kalimba, mbira, thumb piano, middle ear media, obadiah metivier
Stable tag: 1.6

This web app allows you to play a virtual kalimba in your browser.

== Description ==

This web app allows you to play a virtual kalimba in your browser. It uses the Web Audio API to load audio files into a buffer and trigger them when a user hovers over the tines.

== Changelog ==

= 1.0 =
* Finish coding. 03/01/2013.

= 1.1 =
* Add compressor to sweeten the mix. Add master gain to reduce overall volume. 04/04/2013.

= 1.5 =
* Add control section to alter the sound. Includes six sliders. Volume, Pan, Lowpass Frequency, Lowpass Resonance, Highpass Frequency, and Highpass Resonance. Moved the compressor after the filters.  04/08/2013.

* Add keyboard shortcuts as alternate method of adjusting controls. They're laid out in a logical grid to match the control panel. Each control has three shortcuts associated with it. Shortcut Keys for Volume are 1, 2, and 3. Shortcut Keys for Pan are 4, 5, and 6. Shortcut Keys for Lowpass Frequency are Q, W, and E. Shortcut Keys for Lowpass Resonance are R, T, and Y. Shortcut Keys for Highpass Frequency are A, S, and D. Shortcut Keys for Highpass Resonance are F, G, and H. 04/09/2013.

* Add a list of all keyboard shortcuts. Add tips & tricks section to help users play the kalimba. Hide control panel, keyboard shortcuts, and tips & tricks on page load. Add Options menu that toggles hidden content from control panel, keyboard shortcuts, and tips & tricks. Add styles for control section and Options menu. Create sections for all three arrangements, and hide ascending and descending on page load. Modify arrangement menu to toggle hidden content instead of loading separate pages. Create three sets of variables, one for each layout arrangement of the tines.  04/10/2013.

* Clean up code and comments. Update readme.txt. 04/11/2013.

= 1.6 =
* Port webkitAudioContext code to standards based AudioContext. Replace webkit audio context with flexible and smart audio context. Rename all three source.noteOn(0); to source.start(0);. Rename values for lowpass and highpass filters. Move nodes below buffering function. 07/22/2014.

* Uncaught TypeError: Cannot read property 'addEventListener' of null. This has not been fixed. 07/22/2014.

* Update audio files. Smoother, edited source files. WAV, MP3, and OGG formats are now available. Save as mono. 07/22/2014.

* Update comments. Update readme.txt. 07/22/2014.