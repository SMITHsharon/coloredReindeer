# NSS Colored Reindeer

### Project Description 
This exercise loops through two different arrays, to output paired elements from the two arrays to the DOM.

#### Screen Grab Colored Reindeer Output
![Colored Reindeer Screen Grab](https://raw.githubusercontent.com/SMITHsharon/coloredReindeer/screen/screen/Colored%20Reindeer%20Screen%20Grab.png)


### Project Specs
- Given, the following `html` code:

	`<div id="coloredReindeer"></div>`

- Given, the following `javascript` code:

	```
	var colors = ["Blue", "Red", "Orange", "Purple", "Hazel", "Aquamarine", "Periwinkle", "Azure", "Fuchsia", "Chocolate", "Amber", "Amaranth"];

	var reindeer = ["Dasher", "Dancer", "Prancer", "Vixen", "Comet", "Cupid", "Donner", "Blitzen"];

	var hohohoElement = document.getElementById("coloredReindeer");
	```

- Looped through all the reindeer in the array.
- Added the name of the reindeer to the single `html` `<div>` element provided. 
- The name of the reindeer are prepended with the corresponding color from the other array.

#### Example:
Blue Dasher
Red Dancer
etc...

### Technologies Used
- `html`
- `javascript`


### How To Run the App
#### (Node must be installed on your machine):
```
git clone https://github.com/SMITHsharon/coloredReindeer.git
cd reindeer
npm install http-server -g
http-server -p 8080
```

This will show in your browser (at the console) at: `http://localhost:8080`


### Contributor
[Sharon Smith](https://github.com/SMITHsharon)

