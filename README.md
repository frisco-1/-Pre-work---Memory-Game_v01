# Pre-work - *Memory Game*_v01

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Francisco Guerrero

Time spent: 7 hours spent in total

Link to project: 
https://wandering-time-heliotrope.glitch.me/ - Recommended Steps
                 
https://chatter-absorbed-bream.glitch.me/ - My implementation

Github repo for my implementation:
https://github.com/frisco-1/Pre-Work_MyCode

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

This gif represents my own implementation of the pre-work:
![MemoryGame_v02_myCode](https://user-images.githubusercontent.com/72370940/161355900-87dc0435-66b5-465a-9d44-8e9b50c8bff7.gif)

This gif represents the implementation from the pre-work page:
![MemoryGame_v01_Pre_WorkCode](https://user-images.githubusercontent.com/72370940/161356404-e5c8b9da-5b7f-4313-bddd-9fcdb7cfbed6.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

https://youtu.be/W0MxUHlZo6U - Used this video to help me with my implementation, before I realized that there were steps in the pre-work page. The video provided the basic foundation of the game, so I had to add the rest of what's required for this pre-work.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
 
I initially started this project without knowing that the pre-work page provided steps for us. Regardless, this experience provided me with a learning experience on javascript. I had to figure out how to change the button value from "start" to "stop" in my implementation. I figured it was easy, but it took me a while to figure it out. There were so many implementations to do this task. Another challenge was figuring out the logic of the game. I needed to know when I should call a function in my code. Or how long of a pause I should have between the input and the gameplay. The pause required me to experiment with the "setTimeout" function. Another challenge was figuring out how to stop when clicking the stop button. I had to search up how to quit while executing a function, and again there were so many implementations I didn't know what would fit my code. When I was stuck at the moment, I checked the pre-work page and saw the solution. After seeing the steps from the pre-work page. I realize that a way to do that was to call a boolean to determine if it's true to execute or not.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

While website builders are out there, how do you persuade someone to make a website from scratch?

What is the average time someone can learn to become a full-stack developer? 

What is the sufficient amount of knowledge should someone get for looking for a front-end only job?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

I've already refactor some of the functions into the ES6 syntax. I would continue more shorthand code into the project. I would like to put in one the optional functions if had extra time.



## Interview Recording URL Link

https://youtu.be/LYBxR5XzCIk


## License

    Copyright [Francisco Guerrero]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
