# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Ryan Zhao**

Time spent: **6** hours spent in total

Link to project: (https://glitch.com/edit/#!/cliff-palm-string)

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
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [X] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![Win](https://media.giphy.com/media/axgJ4hani5R83uCDdx/giphy.gif)
![Lose](https://media.giphy.com/media/GnPwBUUV3eJl2m2xy0/giphy.gif)
![Timer](https://media.giphy.com/media/H7xM3EWVI6lQeu0kly/giphy.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
  - https://www.w3schools.com/jsref/met_win_setinterval.asp
  - https://www.w3schools.com/jsref/met_win_clearinterval.asp
  - https://stackoverflow.com/questions/31559469/how-to-create-a-simple-javascript-timer

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it?

When working on creating this submission, I wanted to challenge myself and implement the most appealing additional feature which was adding a timer. I wasn’t sure where to start other than finding resources and reading up on how setInterval and clearInterval functions work. I decided to trace my thought process and break the timer feature down into small subproblems. To begin, I began to implement the HTML and give my timer an id so I can change the time inside the DOM. The next step I did was setInterval so I can call on a function every single second to decrement the timer. I ran into a lot of errors while testing the game because the new function to decrement the timer was being called on another time when I press the start button. To resolve this issue, I added clearInterval to stop the time and reset the clock by changing the values back. Additionally, I added a new game alert to check if the timer has run out. When the timer runs out, the player will lose the game. Through lots of testing by playing the game, I was able to implement a timer feature that I am very proud of.

3. What questions about web development do you have after completing your submission?

After completing this submission, I was wondering what technologies and frameworks I will be able to work within web development and which one is best for certain projects and objectives. How does security work in terms of websites what does cybersecurity looks like? I am curious about these questions and I am interested in learning how to use tools to best prepare me for the future. I am also intrigued by how websites keep personal data safe in databases. There are many things about web development I do not know about, but I am excited to gain more project experience and learn!

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific.

If I had a few more hours to work on this project, I would create three difficulty settings: easy, medium, and hard. As the difficulty increases, I want to add more buttons. For example, easy has 4 buttons, the medium has 8 buttons, and hard has 12 buttons. I also want an option for the player to set their own time limit with a few pre-settings at 30 seconds and 1 minute. This would mean I would have to add more user interactions and also heavily change the DOM so the page becomes a little more dynamic depending on the setting. Moreover, I would experiment more in CSS by playing around with adding cool audio files, changing the buttons, and adding new designs to the webpage.



## Interview Recording URL Link

[My 5-minute Interview Recording](https://emory.zoom.us/rec/share/Sxn_C_fqk_dSI7Kh66StSf_LQ3SK_oUXeD71bueenGBOfV87lMHxw9mETNSLDCCH.olOS7mPYlkfMoAl9?startTime=1648769957000)


## License

    Copyright Ryan Zhao

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
