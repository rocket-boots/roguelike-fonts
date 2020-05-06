# Roguelike Retro Fonts

* "Fix15Mono-Bold" from Allure (SIL Open Font License) and LambdaHack - nicely square-shaped, so is great for ASCII tiles
* "Apple II" - retro pixelated 8x8 style
* "White Rabbit" by Matthew Welch

## How to use

* Install with npm: `npm install --save github:rocket-boots/roguelike-fonts`
* ...Or just download the files
* Put the files into a directory your css can access
* Add [`@font-face` rules](https://developer.mozilla.org/en-US/docs/Web/CSS/@font-face)

### Example CSS

```css
@font-face {
	font-family: "AppleII";
	src: url("fonts/AppleII.ttf");
}

@font-face {
	font-family: "Fix15MonoBold";
	src: url("fonts/Fix15Mono-Bold.woff");
}

@font-face {
	font-family: "White Rabbit";
	src: url("fonts/whitrabt.ttf");
}

body {
	font-family: 'AppleII', monospace;
}
```

### Examples in use

* https://deathraygames.github.io/runestar-origins/
