# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Ojochilemi Okoka**

Time spent: **4** hours spent in total

Link to project: https://light-n-sound-memory-game-.glitch.me/

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

![](https://i.imgur.com/6nOBRwJ.gif)

![](https://i.imgur.com/bpWUsZR.gif)

![](https://i.imgur.com/U1aCNPX.gif)





## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
N/A

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
One challenge I encountered in creating this submission would be originally getting my stop and start button to properly dissapear and reappear on click. Due to my unfamiliarity with HTML, I didn't really realize how to properly format code into the tags. Even when I was able to properly format it, I was stuck trying to figure out why a duplicate button was created during the clicking of the start button. So, I cross referenced parts of the Javascript file and was able to see that the problem was as simple as there being differences in the id names for the button refernces and different functions associated with it. I was able to overcome this problem by making sure that every refernce had the correct id name. Another challenge I ran into would be trying to learn a bit more about the syntax for the programming languages, and staying focused on the task at hand. As mentioned in one of the resources, Javascript is a bit more easy to udnerstand than the other languages because it resembles things like C++ or Java. However, for CSS and HTML, I had to read and take notes on the syntax for the languages, as well as visit some of the websites for more information on the different things you could do with them, which also sometimes distracted me from finishing implementing the game.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
One question about web development I have after completing this submission would be what are some ways that we can develop websites that are more compatible with running efficiently and properly on every browser? I noticed one of the instructions talking about choosing font styles that were more universal, but in terms of run time and efficiency, what are some ways in Javascript that we can use to make the programs run smoother and faster as well as create a better user experience? I also would like to know a bit more about how to make the simple game we created more user-friendly and also appealing to the eye.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours to work on this project, I would probably spend them implementing more features in the game, as well as making the game a bit more customizable for the user. One feature I would want to add would be a menu that allows a user to select the difficulty, in which choosing a harder difficulty would yield longer passages, and faster melodies. This would involve functions that create longer arrays, and also even implementing a function that could generate integers at random intervals within the proper bounds so that there could be more variance. I would also like to like to spend some more time essentially making the website more appealling to the eye. I would add better style rules and spend some time centering things as well as making the button animations pop a bit more.



## Interview Recording URL Link

[My 5-minute Interview Recording]https://umich.zoom.us/rec/share/gY3ECFzf3J7WIpsed0qQ8zQR7I81MtU5-fjXoX6Qb7DS2-VPMwZCvodmbw6d4m8Y.J6oakOMiVb9X3RDk?startTime=1650603798000


## License

    Copyright Ojochilemi Okoka

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.