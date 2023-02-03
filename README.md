
# <p align="center">Techno-Hero!</p>
  
Techno-Hero! is a techno rythm game made by Kilian Pouliquen, as a project during the IronHack Web Development Bootcamp.<br>
It was made in four days.

![techno-hero-screenshot](https://github.com/lekix-lekix/Techno-Hero/blob/main/Screenshot.png)


----------



## 🛠️ Tech Stack
- [JavaScript](https://www.javascript.com/)
- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [Howler.js](https://howlerjs.com/)
- [audiosprite](https://www.npmjs.com/package/audiosprite)
- [FFMPEG](https://www.ffmpeg.org/)



----------



The idea was to make a quick game using only JavaScript, HTML and CSS.<br>
The project uses : <br>
- DOM Manipulation : All the notes going down are actually divs generated by JS, and moving down by incrementing their top position.
- Asynchronous functions : This is the core "engine" of the game. A setInterval() is set on a rate of 1000/60, which is a standard monitor refresh rate. With a variable keeping track of every frame, it is then possible to generate a beat on a predermined BPM (120, for this game).
- Howler.js : An audio engine used to play the samples when the keys are pressed. The audio samples were grouped in a single .mp3 file with timestamps, thanks to audiosprite and FFMPEG, allowing them to be played smoothly.
- A tiny bit of CSS for the styling !



----------

There is obviously a lot of things to fix in the game (starting by the accuracy system), but I'm pretty happy with the result.<br>
To try this game : [Techno-Hero!](https://lekix-lekix.github.io/Techno-Hero/)
    
