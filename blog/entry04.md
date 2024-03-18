# Entry 4
##### 3/17/2024

Text

[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)





## Context
Throughout my time working with my tool i was inconsistant with my use of [Kaboom](https://kaboomjs.com/). Later on as i was working with kaboom as much as i did i researched many things like animations i can add so my game isnt boring or just basic. My game is called the WAPPA SMASHA, cool right?


## Kaboom
As i was using kaboom the only sources i used was , [Kaboom](https://kaboomjs.com/), [w3schools](https://www.w3schools.com/), and sometimes i watched kaboom videos on [youtube](https://www.youtube.com/) so i can get the hang of what i want and what i dont want in my WAPPA SMASHA game. I tried making a system where it tracks how many clicks you missed and how many clicks were accurate as you can see below.
```js
let numClicks = 0;

mouseClick(() => {
    numClicks++;
    debug.num("Clicks: ", numClicks);
});
```
So this code is all about keeping track of how many times you click the mouse. And then it's gonna show the total number of clicks in that window while it doesnt yet track how many clicks were missed but were gonna fix that in a minute.

```js
const bgMusic = play("WAPPA SMASHA SONG", {
    volume: 0.5,
    loop: true
});
```
This code starts playing background music named "WAPPA SMASHA SONG" at 50% volume. It keeps playing the music on repeat without any breaks, so it's always there in the game. I will be using this so that even when you die the music doesnt pause but it will continue running inthe backround but i will also try to to make a mute button for those who dont want background music at all but ill do that later on.



### Engineering Design Process
I am on the 2nd step of the EDP which is to Conduct research on the problem and its context. I will continue researching kaboom and taking notes on what i want and what i dont want in my game so therefore I will still be in stage 2 of engineering design process.

## Skills
### Be Productive At All Times. i was not being productive but i did enough to where i didnt have to do much last second so it made everything easier on me. I also managed my time (time management) like today, i realised i had a blog to do before i sleep because i know i wont wake up at 3 in the morning to do an assignment so i went home and started before it was too late. I also learned to proofread my code before i start coding because errors arent hard to find when theres always someone around you who knows what you dont.