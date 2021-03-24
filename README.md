# Pre-work - *Memory Game*

**Light and Sound Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Catherine Huang

Time spent: 3 hours spent in total

Link to project: https://glitch.com/edit/#!/tar-massive-snowboard?path=README.md%3A6%3A0

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://i.imgur.com/LjpDSoO.gif)
![](https://i.imgur.com/XM1alwE.gif)
![](https://i.imgur.com/25bLE7l.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I didn't use any outside resources (except ezgif to create the GIFs).

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
I found it challenging to create the GIFs, seeing as I have minimal experience with video
editing. I couldn't figure out how to open Quicktime, so
I ended up using the Windows 10 Game Bar to record my screen. Then, because my recording 
exceeded the maximum 100 MB for ezgif uploads, I had to trim the video into two videos. 
Ideally I would've cropped the video so that the game display filled the entire frame, but
I did not have the time to figure this out. Once my video was uploaded, I learned to adjust 
the frame rate in order to control the maximum duration of the GIF. Now that I've used ezgif
for the first time, I believe the process will be much quicker in the future.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I am curious about sound synthesis and music in JavaScript. I have used Adobe Audition to
create electronic music, but I didn't know there exists a JavaScript library to process
sounds. What are the productive differences between a library such as AudioContext and programs such as
Adobe Audition? Does AudioContext allow for more automation than Adobe Audition? How do 
the quality of sounds and the user's degree of control compare between the two? Finally,
what types of professional web/app developers opt to use AudioContext instead of relying on
pre-made music? (In other words, what sorts of programs benefit most from the AudioContext
library?)

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I would have added additional sound effects, such as a jingle when the user wins. I also 
would've liked to add confetti falling across the screen when the user wins. Also, I think
it'd be fun to have different levels of difficulty so that the user can try their hand at 
even longer sequences. Furthermore, I would've like to try implementing an "expert" mode in
which the squares change colors after every clue (this would mess with the user's mental
associations between colors, location, and sound). The correct answer would be the button
in the same position as the clue (alternatively, it could be the button with the same color
as the clue). Another feature I would implement is
a gameplay mode in which there are two simultaneous sequences playing. There would be two
separate clusters of colored blocks, and each time step in the clue sequence would consist 
of a lit block and tone from each cluster. This would be a sort of "multitasking" memory
game.


## License

    Copyright Catherine Huang

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.