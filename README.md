# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Brian Balthazar**

Time spent: **2.3** hours spent in total

Link to project: https://glitch.com/edit/#!/fancy-cliff-mailbox?path=README.md%3A18%3A7

## Required Functionality

The following **required** functionality is complete:

- [*] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [*] "Start" button toggles between "Start" and "Stop" when clicked.
- [*] Game buttons each light up and play a sound when clicked.
- [*] Computer plays back sequence of clues including sound and visual cue for each button
- [*] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [*] User wins the game after guessing a complete pattern
- [*] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [*] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [*] Buttons use a pitch (frequency) other than the ones in the tutorial
- [*] More than 4 functional game buttons
- [*] Playback speeds up on each turn
- [*] Computer picks a different pattern each time the game is played
- [*] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [*] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!
- Text is improved and colored.
- Button is recolored to have eyes drawn there.

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://im.ezgif.com/tmp/ezgif-1-b1837ef4dca2.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
   https://www.w3schools.com/cssref/css_colors.asp 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
   When trying to implement the random pattern to work for all cases, I had to ensure that I passed the array into the function and change each index of the array to a random number within the array. The problem was that in different programming languages, the length of an array is usually given with a function call, but not a property, so it took a bit of time to figure that out. There was also the issue with getting the numbers to get chosen properly, so I had to floor the number to not get decimals, decide what the maximum number is (or the number of the biggest button) and decide what the minimum number is, and come up with a function that works with the random() function. It did not take long as I had experience with other random functions in other languages. I also had the issue with not being able to export the glitch project through GitHub using the built-in exporter. To overcome this problem, I used my git program to clone the glitch repository using the link provided by glitch, created another remote repository on GitHub, then pushed the files to the repository on GitHub. All of this was done in the command line since I had experience creating and pushing GitHub repositories there.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
   What frameworks would allow me to complete the project efficiently and in less time? In what ways can I think about improving and implementing features when designing software? What standards do I have to keep in mind when programming to create well-designed and testable code for future projects and programmers to use? What design techniques can I learn to be a better front-end developer and designer? How do I solve problems more quickly? How would I learn about styling according to how the employer wants the software to look? What more complicated projects will be in store after completing this assignment? How do I make sure that the code is clean and the website loads quickly?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
  If I had a few more hours to work on the project, I would refactor the guess function and the functions for the buttons to make them easier to program with, especially for adding new buttons. I would be able to add an image to each of the buttons and add sounds to make the game more complex. Although I added a shortened amount of time per turn, I would like to add a display to see how much time the user has. I would also like to use the W3C validators for HTML and CSS more frequently to ensure that I am writing clean code that does not cause problems down the line. I would also reformat the CSS and HTML to ensure that it is much easier for fellow programmers to quickly dissect and add to for the future. I commit to releasing high-quality products, and if I had a bit more time, I would try to make the memory game the best I can.

## License

    Copyright Brian Balthazar

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
