# JavaScript-Coding-Quiz
This my practice application using JavaScript and APIs to create an interactive quiz. I have been working on this as part of my projec to practice JavaScript functions, eventListeners, if/else statements, arrays, objects and indices.

I started by creating the basic HTML structure, then pairing all of it with my JavaScript constants to create the basic display. I then added all of my questions into an array as shown in line 11 of my js. Afterwards, I added basic CSS so I could visually notice my elements in my index. 

Next, I wanted to name my question array, score, and timer for my later functions, so I used let expressions to do so.

I could finally begin working on my functions in js that would tie everything together. I had to (no pun intended) start with a start button to access the quiz, which would also erase the previous "Take the Quiz?" text. This, in practice should start the timer, set the score to 0, and display the first question. The showQuestion fuinction was designed to display the questions one after another after a user repsonse by using an index, called currentQuestionIndex. 

Finally, I added the elements that dock the user for incorrect answers and add to their scores based on how they answer in the choiceButtons. I added the endGame function to prevent the game from going on forever.

I am still struggling with getting the prompt to save a user's initials at the end of the quiz.

Many thanks to the Youtuber Ali Aslan for creating an example timed quiz using JavaScript. Link to their video is here: https://www.youtube.com/watch?v=xZXW5SnCiWI&t=1893s&ab_channel=AliAslan
