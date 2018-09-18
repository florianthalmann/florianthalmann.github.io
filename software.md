---
layout: page
title: Software
permalink: /software/
---
This page contains descriptions, links, and downloads for some software projects I have been working on, in the context of my research, past employments, and in my free time.

My specialties include Web and mobile apps and my most fluent languages are TypeScript/JavaScript, Python, Java, C++, Haskell, SuperCollider, and Pd/Max/MSP.


## Web Apps

#### Play it Again! Use it Together



Web application for the exhibition Play it Again! Use it Together with the Open Music Archive at Victoria Gallery in Liverpool, where Shellac records are being digitised, analyzed automatically, and fed into an archiving system based on Semantic Web technologies. A Node server generates an infinite growing composition created from recently digitized material and sent to all clients, one of which also plays in the exhibition.
<a href="https://www.playitagainuseittogether.com" target="blank">Live</a>
/
<a href="https://github.com/open-music-archive" target="blank">GitHub</a>

<img src="/assets/img/projects/piauit.png" width="400" />

#### Fast Dj

An automatic web-based minimal-UI automated DJing application that adapts to the user’s preference via simple interactive decisions and feedback on taste. Starting from a preset or custom-defined decision tree modeled on common DJ practice, the system can gradually learn a more customized and user-specific tree. At the core of the system are structural representations of the musical content based on semantic audio technologies and inferred from features extracted from the audio directly in the browser.
<a href="https://dynamic-music.github.io/fast-dj" target="blank">Live</a>
/
<a href="https://github.com/dynamic-music/fast-dj" target="blank">GitHub</a>

<img src="/assets/img/projects/fast-dj.png" width="400" />

#### Grateful Live

A platform for the representation and discovery of live music recordings and associated artefacts of the band The Grateful Dead. It links material from the Grateful Dead collection of the Internet Archive with data aggregated from several additional Web resources discussing and describing these events. These data include descriptions and images of physical artefacts such as tickets, posters and fan photos, as well as other information, e.g. about location and weather. The system uses signal processing techniques for the analysis and alignment of the digital recordings. During the discovery, users can juxtapose and compare different recordings of a given concert, or different performances of a given song by interactively blending between them.
<a href="https://grateful-dead-live.github.io" target="blank">Live</a>
/
<a href="https://github.com/grateful-dead-live" target="blank">GitHub</a>

<img src="/assets/img/projects/grateful-live.png" width="400" />

#### Performance Deformations

An educational web application for comparative performance analysis based on source separation and object-based audio techniques. The underlying system decomposes recordings of classical music performances into note events using score-informed source separation and represents the decomposed material using semantic web technologies. In a visual and interactive way, users can explore individual performances by highlighting specific musical aspects directly within the audio and by altering the temporal characteristics to obtain versions in which the micro-timing is exaggerated or suppressed. Multiple performances of the same work can be compared by juxtaposing and blending between the corresponding recordings. Finally, by adjusting the timing of events, users can generate intermediates of multiple performances to investigate their commonalities and differences.
<a href="https://github.com/florianthalmann/performance-playground" target="blank">GitHub</a>

<img src="/assets/img/projects/performance-playground.png" width="400" />

#### Dymo Designer

A prototypical Web app for creating and analyzing Dynamic Music Objects in a visual, interactive, and computer-assisted way. Implemented using Angular, D3, and the Web Audio API.
<a href="https://github.com/florianthalmann/dymo-designer" target="blank">GitHub</a>

<img src="/assets/img/projects/dymo-designer.png" width="400" />

#### Semantic Player

A Web and Mobile app for the playback of Dynamic Music Objects using the Web Audio API. The interface is fully modular and adjusts to the needs of the particular composition currently loaded. Users can use sensors, UI elements, data streams, etc and map them to parameters of predefined musical structures.
<a href="https://github.com/dynamic-music/semantic-player" target="blank">GitHub</a>

<img src="/assets/img/projects/semantic-player.png" width="300" />

#### Cooler than Open Season

In a collaboration with Tobias Vogler, we developed a web application where visitors can "produce" a song for the band Open Season. They can do this by simply recording their sounds using their cellphone microphone or any other input directly in the browser, where the sounds are processed in various ways and automatically added to some prerecorded sounds by the band, even while the song is being listened to. The signal processing part was programmed using the Web Audio API in javascript, with an added Midi playback engine.
<a href="http://cooler.openseason.ch" target="blank">Live</a>
/
<a href="https://github.com/florianthalmann/cooler-than-openseason" target="blank">GitHub</a>

<img src="/assets/img/projects/cooler.jpg" width="300" />

#### Recorder.js with a Threshold

A version of Matt Diamond's Web Audio API Recorder.js that automatically starts recording when a specified threshold is crossed and then stops after the signal is lower than the threshold for a given time. It also normalizes and fades the recorded buffer before returning or exporting it.
<a href="/assets/files/recorder.zip" target="blank">Download</a>
/
<a href="https://github.com/mattdiamond/Recorderjs" target="blank">Github</a>


## Android/iOS

<!--#### Semantic Machine

#### Semantic player

ios/android store links...-->

#### Harmony of the Spheres

An Android app that investigates the sonic potential of objects in n-dimensional physical spaces with transforming properties. Using gestural multi-touch and accelerometer control, users can create musical objects in these spaces and interact with them, while they move and react to the physical conditions of the spaces. The properties of these objects can be arbitrarily mapped to sound parameters, either of an internal synthesizer or external systems, and they can be visualized in flexible ways. On a larger scale, users can make soundscapes by defining sequences of physical space conditions, each of which has an effect on the motion and properties of the physical objects.
<a href="https://play.google.com/store/apps/details?id=org.flobot.hots" target="blank">Google Play</a>

<img src="/assets/img/projects/hots.png" width="500" />

#### Open Season Airhorn

An Android application lets users play airhorn and other sounds, bend and filter them, and add a delay with variable delay time and feedback. Reacts to multitouch and accelerometer gestures. Built with libpd and processing for Android.
<a href="https://play.google.com/store/apps/details?id=org.flobot.openseasonairhorn" target="blank">Google Play</a>

<img src="/assets/img/projects/osairhorn.jpeg" width="300" />

#### Valves

An iOS application for mental trumpet practicing. Tracks multitouch finger movements, evaluates them regarding accuracy and correctness, and keeps long-term statistics. Based on my extension and generalization of Nicolas Slonimsky's symmetrical scales.
<a href="/assets/files/valves.zip" target="blank">Download</a>

<img src="/assets/img/projects/valves.jpg" width="300" />




## Rubato Composer / Java

#### BigBang

The BigBang rubette brings gestural composition to Rubato Composer. It allows users to create and interact with its mathematical structures in an intuitive way and tracks their creative process. BigBang is still being expanded and I am currently adapting it as a standalone software on Android. In the meantime, a current version of Rubato Composer including BigBang can be obtained via email to <a href="mailto:thalm007@umn.edu">thalm007@umn.edu</a>.

<img src="/assets/img/projects/bigbang.jpg" width="300" />

#### Rubato Composer

Rubato Composer is a music software based on mathematical music theory, allowing users to compose, analyze, and interpret music. It allows users to model, process, and transform musical data with mathematical constructs and operations from category theory and topos theory. It offers numerous components, each of them adding specific functionality. The project was initiated by Gérard Milmeister and was recently extended and adapted during my work on BigBang and other rubette.
The current version and the source of Rubato Composer is available on <a href="https://sourceforge.net/projects/rubatocomposer/" target="blank"> SourceForge</a>.
The <a href="http://www.rubato.org" target="blank">Rubato home page</a> contains a lot of documentation and links to various software components.

<img src="/assets/img/projects/rubatocomposer.jpg" width="300" />

#### Image Rubettes

A brief project in 2013 led to the development of the ImageFileIn and ImageFileOut rubettes. They convert image files into mathematical structures and back, in a similar way as the MidiFileIn and MidiFileOut rubettes do this for Midi files. Once converted, any transformations and operations can be performed for visual data, as can be done with musical data structures. Even BigBang can be used on image data, since it has been generalized to work with any non-musical and musical format.
The ImageFile rubettes can be obtained here: <a href="/assets/files/ImageFileInRubette.jar" target="blank">ImageFileIn</a>, <a href="/assets/files/ImageFileOutRubette.jar" target="blank">ImageFileOut</a>.

<img src="/assets/img/projects/paintbrushes.jpg" width="300" />

#### Wallpaper, Alteration, and Morphing Rubettes

Most of the rubettes created for my Master's thesis have been superseded by the BigBang rubette, which makes much of their functionality available gesturally. However, with the original Wallpaper rubette one can work with specifically defined morphisms, which can be defined numerically. The Alteration rubette allows more precisely higher-dimensional alterations, independent of the dimension in which the alteration takes place. Finally, morphing has not yet been incorporated in BigBang.
The former two are available on <a href="http://www.rubato.org/rubettes.html" target="blank"> Rubato home page</a>.
The Morphing rubette is available <a href="/assets/files/MorphingRubette.jar" target="blank">here</a>.

<img src="/assets/img/projects/wprubette.jpg" width="300" />

#### Basic and Advanced Musical Rubettes

Some other example rubettes performing basic musical tasks and some more advanced operations emerged during the work with Rubato Composer. The Melody, Rhythmize, and Scale rubettes can be downloaded on <a href="http://www.rubato.org/rubettes.html" target="blank"> Rubato.org</a>, while some others can be obtained here: <a href="/assets/files/LilyPondOutRubette.jar" target="blank">LilyPondOut</a>, <a href="/assets/files/QuantizeRubette.jar" target="blank">Quantize</a>, <a href="/assets/files/ShuffleRubette.jar" target="blank">Shuffle</a>, <a href="/assets/files/NToneRubette.jar" target="blank">NTone</a>, and <a href="/assets/files/AddVoiceRubette.jar" target="blank">AddVoice</a>. More rubettes will be made available here soon.

<img src="/assets/img/projects/rhythmize.jpg" width="300" />

#### Stereographic Random Triangle Generator

A small Java/OpenGL app that displays randomized triangles rotating in 3D space. It juxtaposes two perspectivally differring versions of the space so that can be looked at stereographically.
<a href="/assets/files/TriangleImageDisplayer.jar" target="blank">Download</a>

<img src="/assets/img/projects/triangles.png" width="300" />




## Pd/Max/MSP

#### Variable Delay

A delay written in Pd that avoids changes in pitch when the delay time is altered, by automatically fading between three delays.
<a href="/assets/files/variabledelay.zip" target="blank">Download</a>

<img src="/assets/img/projects/variabledelay.jpg" width="300" />

#### Infinite Player

A number of Pd patches that extend sounds to arbitrary length, while keeping their attack and decay the same, using macro granular synthesis so to speak.
<a href="/assets/files/infiniteplayer.zip" target="blank">Download</a>

<img src="/assets/img/projects/infiniteplayer.jpg" width="300" />

#### Midi Grand Piano Testing Software

A small testing software written in Max/MSP to monitor the velocity accuracy of a MIDI grand piano. Every key of the piano is automatically pressed with the same velocity with a configurable duration, which results in note on signals, the velocities of which are kept track of and displayed in a graph.
<a href="/assets/files/velocity_test.maxpat" target="blank">Download</a>

<img src="/assets/img/projects/maxpiano.png" width="300" />

#### Reactive Player Piano

A Max/MSP patch with Java external I made to improvise with the Midi grand piano. It automatically adds additional melodies or fractal patterns based on what is played by the performer, based on configurations in the Java file.
<a href="/assets/files/playerpiano.zip" target="blank">Download</a>

<img src="/assets/img/projects/playerpiano.png" width="300" />


#### Piano Overtone Recorder

A Max/MSP patch with a Java external that records the decay of player piano strings sympathetically vibrating with a certain recurring note (the respective keys are depressed silently). Recording only sets in after the recurring note has decayed and only the strings are vibrating. This way, complex spectra can be composed and recorded automatically.
<a href="/assets/files/overtoneplayer.zip" target="blank">Download</a>

<img src="/assets/img/projects/overtoneplayer.png" width="300" />

#### Pd EWI Synthesizer

A configurable synthesizer for the Akai EWI written in Pd. It reacts appropriately to all control changes and note messages sent by the EWI's many sensors and can be combined with any matching Pd patches.
<a href="/assets/files/EWIsynth.zip" target="blank">Download</a>

<img src="/assets/img/projects/ewi.jpg" width="300" />

#### Random Score Generator

A Max/MSP patch that generates random monophonic midi files based on configurable intervallic constraints and ranges. The resulting files can easily be transformed into scores and used for practicing melodic instrumental techniques and random chord changes.
<a href="/assets/files/randomscore.zip" target="blank">Download</a>

<img src="/assets/img/projects/randomscore.png" width="300" />


