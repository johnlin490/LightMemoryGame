# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **John Lin**

Time spent: **2** hours spent in total

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

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

Shows Loss
<img src='http://g.recordit.co/EzNwbyxLpm.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />


Shows Win
<img src='http://g.recordit.co/N6fPkSJ0CB.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [recordit](http://www.cockos.com/licecap/).

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
None

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
When I was testing out the sound, I realized that there wasn’t any noise coming out. I checked over my code multiple times with the guide and my volume. I was initially showing my program in a new window. I decided to show my program on the side of the screen to see what would happen. When I tested it on the side, the sound started playing and my issue was solved. Another issue that I had was the guess function. I was getting an error where the message would display that I lost the game even when I won. After looking at the flowchart and looking at the code provided, I realized that I never called the win function. Once I put that in, my program worked.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[YOUR ANSWER HERE]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had more time, I would focus on the other optional features. The ones that look the most interesting to me are adding a countdown and adding three strikes. For the countdown, I would have to do some outside research on implementing a timer in javasript. When the timer reaches 0, the game ends and the user loses. I would also have to spend time figuring out how to display the clock. For the strikes, I would create a new variable that increases when the user selects the wrong button. Once the variable reaches 3, the game is over. I would also need to spend time figuring out how to display the strikes.




## License

    Copyright [Michelel Cheng]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
