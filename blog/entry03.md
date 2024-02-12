# Entry 3
##### 2/11/24
## Yaseen Magaouri
Text

[Previous](entry02.md) | [Next](entry04.md)

[Home](../README.md)

## Context
Building on and on to this blog i have learned more than one thing about the setup of my game called wappa smasha (name idea) like `destroy(whatever it is you want to destroy);)` and most games that exist have to do with something being destroyed and so that gave me the idea to make my game. All the work i have researched on my tool [Kaboom](https://kaboomjs.com/). I will keep researching and trying to get a better layout for my game and i will continue showing you.

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
Plenty of clicking games dont display the time it took to achieve what you were clicking for and dont display the exact second so therefore i will add a clock that tracks the exact second for example 1:8.4 this means that they finished in 1 minute and 8.4 seconds

## Skills i learned
I learned to research my tool before i use my tool because everything you have memorised might not be enough because there is always more to learn.                                                                                  I also learned that taking your time to study the tool and where code snippets you learned should be used in certain places to better your project/idea
