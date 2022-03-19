# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Utsha Kumar Saha**

Time spent: **5** hours spent in total

Link to project: https://glitch.com/edit/#!/showy-absorbed-tibia

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

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial

## Video Walkthrough (GIF)
![gif1](https://user-images.githubusercontent.com/83483386/159098586-c2020691-eb90-4307-9b41-a4f24bc071c4.gif)
![gif2](https://user-images.githubusercontent.com/83483386/159098587-d1411f41-96cc-4a43-86cd-ca2ba85548cc.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

The only external resource I had used was a website called “coolors,” which provides an array of color pallets. 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it?  

A challenge I had encountered in creating this submission was adjusting the game logic. While working on the submission, I noticed that my Start and Stop buttons were working perfectly fine but the player would only have one round. The rounds were not continuing. I stopped briefly and analyzed what I was doing wrong. I reviewed my playClueSequence() and playSingleClub(blt) functions. I noticed that these functions had correct logic but I was implementing them in my guess(btn) function incorrectly. After observing the guess(btn) function, I noticed that I should have put my playClueSequence() function in the else bracket if the game was not won. I was able to backtrack and observe the logic I was implementing to create a solution. Another challenge I endured was trying to make my project different than the one presented in the video. I first decided to play with the sounds, adjusting the frequencies to be different. This made the sounds sound different than the video. I also disliked the gray background and opted to find different color codes. This made me search the internet for a reliable source for color pallets and I stumbled across “coolors”. These were the challenges I had encountered when creating this submission. 




3. What questions about web development do you have after completing your submission? 

After completing this submission, I have many topics and questions about web development. My first one would be how would smooth animations be inserted or created? Another question would be how a backend would be connected to our submission. A backend would be allowed to assign each different user a special playerID, and that playerID could be assigned their unique number of points (dependent on the player's success). I also am interested in how to create a website that can take input from a user. For example, many websites have a place where users can 'leave a message,' taking in name, email, and inquiry. Another question I have for web development is how much Apache is necessary to know. Does a Web developer need to be fully skilled in Apache? I also wanted to know how someone would go to create an e-commerce website from scratch? Another question I would have is more about loading times. How could I reduce page loading times if I want to create a website that almost automatically loads within seconds? 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. 

If I had a few more hours to work on this project, I would make many adjustments. First, I would adjust the presentation of the website with more colors and allow the website to be more visually appealing to the eyes. I would also add custom sounds to make the game similar to the famous “Bop It” game. I would also add more buttons to make the game harder and use functions to create a more randomized game. A user currently could memorize the pattern and win every time. I would also like to have an animation for each time a user wins or loses, making the game more charming and enjoyable. To add a competitive nature to the game, I would make the game an endless game where the user would get the point for each successful round, and there would be a worldwide leaderboard to have each user ranked. This being said, I would also add a timer to the game for each round, slowly decreasing in time for the user to play. On top of all these features, having the colors change position for each round would also make the game much more difficult as not only is the player memorizing the color but also the position. 

## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/BGBe3GYsQd4)


## License

    Copyright [Utsha Kumar Saha]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
