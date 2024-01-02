# Tool Learning Log

Tool: Kaboom

Project: clicking sprite till dead game

---

11/7/2023:
* [This is the link i used today and it showed me all the kaboom basics in code snippets where i can use to make a game](https://kaboomjs.com/doc/setup)

11/7/2023:
* [i remember like 3 days ago i looked up a tut where the man showed me how to make a flappy bird game using kaboom and here it is](https://www.youtube.com/watch?v=hgReGsh5xVU)


<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
11/20
splitting the code into multiple files
```html
 <html>
	<head>
		<title>Kaboom Tips</title>
	</head>
	<body>
		<script src="https://kaboomjs.com/lib/0.5.1/kaboom.js"></script>
		<script src="main.js"></script>
	</body>
</html>
```
This is how u start off a custom component
```js
// this is a new file: ./components/big.js
import k from '../kaboom'

export default function big() {
	return {}
}
```
11/27
this is how you remove or destroy a sprite
```
bean.onCollide("fruit", (fruit) => {
    destroy(fruit)
})
```
this is how you change a sprites color
```
add([
    sprite("bean"),
    color(0, 0, 255)
])
```
make a circle
```
add([
    pos(80, 120),
    circle(16),
])
```




12/4
``` js
setGravity(3200)
```
This is how u set the gravity of your sprite.
I tweaked with this by changing the numbers of gravity for example i changed 3200 to like 10000 and the sprites movement got harder and heavier


1/2
``` js
onKeyDown("up", () => {
  player.jump(100);
});
```
This code is used for whatever action to occur once the down key is pressed. For example to go down from a step down will take you down and up will take you up


``` js
onCollide("bullet", "platform", (bullet, platform) => {
  destroy(bullet);
});
```
this code is used for destroying the bullet if it hits a platform. For example if whatever object/im using bullet reaches a certain barrier it is therefor considered dead/destroyed