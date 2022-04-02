# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Shawinderdeep Singh

Time spent: 10 hours spent in total

Link to project: https://glitch.com/edit/#!/lapis-extreme-henley

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
* [x] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] List anything else that you can get done to improve the app!
    
    - In order to improve the app, we can create a level of difficulty (Easy, Intermediate, Advanced). So, the difficulty can be distinguished by how fast the clueSquence is presented, the length of the sequence, the amount of time we get to complete each sequence. 
    - We can also create a multiplayer application: For instance, a sequence is displayed to two seperate users and are provided an equivalent amount of time to successfully complete the sequence, and who ever is the first to complete it correctly wins the round.


## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![x]Start/Stop Button Functionality: http://g.recordit.co/bwkYbfmmGA.gif
![x]Clue Sequence plays properly: http://g.recordit.co/wLVM5MiEOo.gif
![x]Strikes Feature and Game lost: http://g.recordit.co/V70Q0CU442.gif
![x]Game Won: http://g.recordit.co/o5LFpsizIB.gif


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

The only resources I used were the links provided in the prework.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

Since the prework came with all of the instructions on hoe to create the game, I chose to first think of how I would create the functions on my own and then followed through with the instructions. The main difficulty I had to overcome was debugging my code. The dilemma was that my clue sequence was not playing, the start/stop button was working, and it was also giving me the option of guessing the sequence. I spent some time checking back through my functions in my js file to see if i had missed out in calling my playClueSequence function. I then finally opened my console and it provided me of the line of error. The error was that I wrote "getElementId" instead of "getElementById". I once again realized how tedious it can be when having to debug our code, and it is best continuously run our program along the way in order to ensure that it is running accordingly.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

Before doing this project, I was only aware of the basic components of web development, in terms of how it is front-end development, and the make up of web development is just html, css, and javascript. However, I am still curious to how you can add more intricate features in order to make our application more intuitive and unique. For instance, how can we implement motion graphics to our project. I was also considering how we can better engage the user who is playing the game. For instance, we can create a reward system by using virtual coins or unlocking other features. When thinking about what web development is, I think of it from an artistic point of view as well. In other words, I wonder how we can increase the functionalities, make an application that is more interactive and we can make it visually more interesting.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had more time to work on this project, I would add more graphical features, like animations to make the game for engaging. Instead of the game just being color blocks with basic sound, it has an overall story to go along with it. For instance, it could be a music band, where each button represents an instrument with unique sounds and pitches. We can also link a database of various different songs that can be payed using the instruments in order to make the game more diverse. 


## Interview Recording URL Link

https://urldefense.proofpoint.com/v2/url?u=https-3A__us02web.zoom.us_rec_share_O7awgQW-2Dq-2DFoXjTua7ugMGDayrFS7f4G-2DEgfaEVyNd59JSw8I2zdxwmqUVYuN-2D-2Dl.ni-5Fzk4TLLDSs1SX7&d=DwMFAw&c=mRWFL96tuqj9V0Jjj4h40ddo0XsmttALwKjAEOCyUjY&r=AmEcJA9vmEil9C76yVuvrkmAJf2tm7lCAJ7fDMvPSyc1KL3YYjiSDfr0N7TRhL1F&m=z5Av5KWfgZEQ9nbZMjchegY79H17u8JhHiSnk0tm-tE&s=MmxaJmcASfjAy4sWQWzeA3NbXKYo2T4_VVtokVpeJcY&e=

Password: WZ!MW8CT

## License

    Copyright Shawinderdeep Singh

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.