# Pre-work - *Sound and Light Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Charles Yu**

Time spent: **1** hours spent in total

Link to project: (insert your link here, should start with https://github.com/charles001203/sound-and-light-game.git)

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

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

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://i.imgur.com/Dutck3t.gif)



## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
**none**

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
**Overall, the prework project wasn't too bad. It was due to large part that I knew some fundamental knowledge in web development beforehand. 
However, I did struggle a little when I was coding up the project: I was stuck on debugging light button function because of my button name is
capitalized and it didn't match with the function. However, I did not give up. I walked through the project spec over and over again, I 
realized that it was my button name that messed up the code: the name is the javascript does not match with the ones in the CSS style file. 
So I changed the name and the game worked!**

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
**After completing my submission, I have several questions that are related to web development in my mind. First of all, why are there three
different type of languages (HTML, CSS, JavaScript) for web development instead of just one web development language? Wouldn't that be convenient
for beginners to start learning front-end design? Also, is there a way to use back-end programming language to code up a website or a web game?**

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
**If I had a few more hours to work on this project, I would try to reduce the time delay of clicking the button because when the pattern involves more than 
like five buttons, it took a while to play the pattern and it might be too slow for players who are inpatient. Alternatively, I'll implement different
levels of game: easy, medium, hard based on how long the delay time of clicking a button. Intuitively, the delay time for clicking a button is the longest
while the delay time for clicking a button in hard mode is the shortest.**



## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.