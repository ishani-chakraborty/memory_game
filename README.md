# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Ishani Chakraborty**

Time spent: **1.75** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

## Required Functionality

The following **required** functionality is complete:

- [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [ ] "Start" button toggles between "Start" and "Stop" when clicked.
- [ ] Game buttons each light up and play a sound when clicked.
- [ ] Computer plays back sequence of clues including sound and visual cue for each button
- [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [ ] User wins the game after guessing a complete pattern
- [ ] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
- [ ] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] More than 4 game buttons - 6 as opposed to 4 with different sound pitch frequencys set
- [ ] Using a random code pattern everytime the game is started

## Video Walkthrough

Here's a walkthrough of implemented user stories:
<img src="http://g.recordit.co/sVCpgtPKj7.gif"><br>

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
   [I referenced w3schools for understanding CSS syntax for styling button features and understanding the in-built library handling for responsive animation]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
   [I actually noticed when I got to the step of testing the clue sequence that when I used the developer tools it was showing the correct value on the console, however, my code was clearly buggy or incorrectly implemented because the buttons weren't making sounds or changing colors dynamically as I had set them up to be. While in the moment, I was confused and frustrated and made the most hasty choice to trace my work from the beginning, I quickly recognized that patience was going to help me gather my thoughts and think about what could have gone wrong practically. I noticed that the bug was in the CSS file with the braces for each of the buttons and how there was a gap between them which the HTML embedded file didn't catch or recognize. I also struggled with a couple of the optional features which I still attempted to implement most of them. This was an enjoyable project and nice to follow as well. I liked how were able to trace the logic of the prework with the help of understanding the flow of the game.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
   [This specific project gave me a better idea about game design using web development but for personal projects, I would be interested in how to learn how to use and have access to unique and pre-curated web templates for resume portfolios, as well as designing an e-commerce website, gaining experience in order to do freelance work and what not. I also am interested in using the visual and interactive benefits of HTML, CSS, and Javascript in a more data-driven and visually supportive platform because that is where my current interest in computer science lands. I want to leverage the existing tools of programming and development languages that are robust and supportive of an platform development project can translate into a project that can be implemented and put to use in qualitiable and quantifiable manner. Whether this be a person project or be put to use as a service or feature that can help many high-level clients, it's the experience from this internship that I strive to gain a deeper and larger technical and soft skill set to.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   [Beside the optional features that I didn't have the time to implement, I would change the logic and incentive of the game. This would require redesigning and refactoring the architechture and infrastructure that supports the current work flow. I would definitely like to address accessibility and an industry standard that is being hugely prioritized in the scope of clients of tech companies - basically a globally digestable platform that promotes the purpose of the inabiltated. I would focus on there being an alternative access to the game for people who are deaf as well as people who are visually-impaired/color-blind. This would mean that we would reach better audiences and make this game digestable to all our users. It's no longer an exclusive platform and is fun for everyone. I would also increase the level of difficulty if they win one round and have some sort of interactiove randomized trivia question setup to incentive beating their highest score!]

## License

    Copyright [Ishani Chakraborty]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
