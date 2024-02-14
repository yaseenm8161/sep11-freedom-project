# Entry 3
##### 2/11/24
## Yaseen Magaouri
Text

[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)

## Context
I have been looking back and forth on my plan and it looks great just a little modifications. My plan so far is to make a game that loads the button "start" and once the button is pressed/clicked the game has begun. The next part is for my code is using  loops because i want my game to keep looping over and over again if the user would like to reset the game should reset back to how it started. Now lets say the player completed the game it would tell the player CONGRATULATIONS. Now lets say the player hasent yet completed the game, the game will keep going on and on and on untill the player wins. Now there will be a reset button just incase the player wants to reset then it will. I am making a start and reset button for my game right now.



## Kaboom

by researching [Kaboom](https://kaboomjs.com/) special qualities and explaining to myself how they work i had everything in my eyes. i started by looking at the. `Add()` function which adds new elements to a current set to form a new collection.
```js
add([text("Hello, Kaboom!", 32), pos(80, 120)])
```

In this example this code adds text to the game scene with the specified content and position.

Another functionality I learned was

``` js
const player = add([
        rect(32, 32),
        pos(80, 120),
        color(0, 1, 0),
        "player"
    ]);
```
`const player = add([...]) creates a player character represented by a green rectangle.`
``` js
player.collides("collectible", (c) => { ... })
 ```

This code checks for collisions between the player and  object it collided with triggering a callback function when the collision happens.
``` js
const characters = add([...], "character").color("blue");
const sprites = characters.map(char => char.sprite("player"));
```

``` js
sprites.addBack().color("lightgray");
```
Each of the players in the example above were originally chosen and dressed in blue. Then their matching sprites are selected and given. And lastly.The characters are styled with a light gray color after being added back into the chosen set using addBack().

this is what i learned so far and how im looking forward to using these in my future designed game


``` js
keyDown("left", () => { ... }) and keyDown("right", () => { ... })
```
these establish controls for the player character's left and right movement respectively in Kaboom.js.

## Engineering Design Process
i am on the 2nd step of the EDP which is to Conduct research on the problem and its context. I will be using what i learned throught out looking at all the games of kaboom that involve click registering and start buttons and will use that to make my game WAPPA SMASHA
## Skills i learned
I learned to research my tool before i use my tool because everything you have memorised might not be enough because there is always more to learn.                                                                                  I also learned that taking your time to study the tool and where code snippets you learned should be used in certain places to better your project/idea
