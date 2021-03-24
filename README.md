# Pre-work - *Memory Game*
**Open in Microsoft Edge**

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Arsh Chaudhry**

Time spent: **6** hours spent in total

Link to project: https://slime-natural-coconut.glitch.me

## Required Functionality

The following **required** functionality is complete:

* [Yes] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [Yes] "Start" button toggles between "Start" and "Stop" when clicked. 
* [Yes] Game buttons each light up and play a sound when clicked. 
* [Yes] Computer plays back sequence of clues including sound and visual cue for each button
* [Yes] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [Yes] User wins the game after guessing a complete pattern
* [Yes] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [Yes] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [Yes] Buttons use a pitch (frequency) other than the ones in the tutorial
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
![](your-link-here)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

[W3Schools really helped with me understand and implement some HTML and CSS concepts.]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

[I think one of the more challenging parts was understanding the logic behind some of the methods created in Js. 
Specifically the ones regarding the playing of the tones like playTone and startTone. It was confusing to me at
first but upon reading the lesson within the pre-work helped a little bit. Especially with things like the page
initialization and sound synthesizer is all new to me. I did some of my own research and was able to understand 
a little bit better but not quite to where I want to be. I am still researching and trying to understand the
whole audio thing fully. However just searching some questions I had regarding it helped satisfy my interest. 
I am new to css too so understanding how styling works alongside HTML and Js took me some time. However, 
W3schools is a great resource I found that helped me drastically. I found it cool how we can add classes as we
did to hide buttons on screen using Js. Most of my challenges were during the Js logic portion of this assignment,
I realized logic was something I needed to work on so I spent most of my time researching to understand it. 
Another issue I am just now running into is that Chrome blocks AudioContext unless it is resumed with user
interaction. This webpage will work with Microsoft edge but if it is ran on chrome then the audio does not play.
I am trying to figure out a way to implement another button that will create and resume audiocontext. However,
time is tight because of midterms and the due date for this program so I will have to implement it after I submit.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

[So what we did was a logical game which was really cool. I would like to learn more about web developing that 
deals with user data and can do things such as search, store, rank, etc. Can that be done all through js or is 
is there more that needs to be done? Also, this glitch resource was helpful that displayed our code in real time.
However how would we actually deploy a website for users to access? What are the steps in regard to deploying a 
public website? With my current experience, I am still still learning the basics of CSS and js. I would like 
to know more about frameworks. Specifically what they are, their purpose, the uses, and how to use them.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

[Definitely I would add a function that creates a random pattern for the computer to play each time a new game is 
started. It seemed the preset pattern I had set up kept being repetitive when I was playing the game for testing 
frequencies and such. Another thing I would definitely add is randomly places buttons for each round. This would 
be so cool and actually challenging. Something like a panel in the middle of the screena and within the screen, 
the buttons display randomly at the start of each round. For example, lets say round one begins. The computer 
chooses randomly placement of 4 buttons within a panel and then does its pattern. The user repeates the pattern. 
Then round two the computer randomly chooses new locations for all the buttons and continues the game. I think 
something like that would be cool.]


## License

    Copyright Arsh Chaudhry

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
