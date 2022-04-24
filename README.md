# Codepath-Salesforce-Prework
Prework including a memory game, reflection about the game and a short interview recording. 

# Pre-work - *Match the Sequence! - A Memory Game*

**Match the Sequence! - A Memory Game** is a Light & Sound Memory game to apply for CodePath's FTL Program. 

Submitted by: **Nitya Vaidya**

Time spent: **3** hours spent in total

Link to project: https://glitch.com/edit/#!/admitted-viridian-tang

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
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

Here is a GIF with a game lost and a game won.

![](http://g.recordit.co/QTj5hCDUJp.gif)


## Reflection Questions
**1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.**

https://www.w3schools.com/cssref/css_colors.asp

**2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)**

The most challenging concept for me when creating the game was perfecting the game logic. Though I have a good grasp on the nestled conditional if/else statements, I would keep running into incorrect implementation due to simple errors. I had to make sure my code reflected when to output “game lost”, when to move on to the next sequence and when to output “game won”. In order to overcome this challenge, I made a flowchart for myself, that was based on the chart given in the pre-work instructions. I broke it down into each scenario: Losing the game, Next Sequence, Winning the Game. Then I made sure, each of the scenarios individually was working well and then I came back to make sure my if/else statements worked with each other as well. Then I tested each of the scenarios again in the preview until I was satisfied.

So steps to rectify included:

Step 1: Identify the section of the code that is causing errors.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I identified that the game logic section of javascript needed improvement.

Step 2: Identify where in the section code is the problem rooting from.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I identified that my if/else statements were causing the error.

Step 3: Review the underlying concept.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I mentally recalled the basics of the nestled conditional if/else statements.

Step 4: Create a roadmap to the resolution.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I decided I would create a flowchart to break down my conditions

Step 5: Reference relevant material

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I referred to the pre-work instructions to cross-check my flowchart.

Step 6: Break down the task into smaller pieces

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I separated my scenarios in the flowchart and worked on them individually.

Step 7: Integrate the pieces.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I then made sure my if/else statements worked with each other.

Step 8: Test and Repeat

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;I used preview to test out each scenario until it ran as intended.

**3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)**

Creating this game gave me a ton of complex ideas about how to improve this game. One of the ideas I had was to make the game adaptive to the user. Not in terms of levels but to make the game such so it changed sequence each time and the speed and length of the next sequence would entirely depend on the user’s old behavior. So, if the user had been getting guesses correct, the game would speed up and the sequence would be longer but if the user had been getting guesses incorrect the game would slow down and the sequence would shorten. I know that Dynamic/Adaptive Difficulty Adjustment is a concept that is already widespread in game development but I want to know more about the probability and the algorithms involved in making the game adaptive according to user behavior.


**4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)**

If I had a few more hours to work on the game, I would add a couple of features to this game. The first one would be to incorporate pictures when the buttons are lit up. My game reminds me of the classic card game ‘Taco, Cat, Goat, Cheese, Pizza’ so I would incorporate that into the game. I would add the word ‘Fox’ to the list of 5 words. Then I would correspond each of these words to a color in the lit-up versions of my buttons or the darker colors. I really like my current color palette so I would find a clipart of each image and insert it onto a background of the current lit-up color. And then I would add these images to my buttons only when they are lit up. So, the icons aren’t visible by default but when the computer shows the sequence or the user guesses it, it shows up as a pleasant surprise. I would also change the audio of each button to speak out the word associated with the icon to create a complete experience.



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)

## My LinkedIn URL Link

[My LinkedIn](your-link-here)


## License

    Copyright Nitya Vaidya

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
