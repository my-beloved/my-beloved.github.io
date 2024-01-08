# my-beloved.github.io
This is the website creative response to Toni Morrison's Beloved.

Then, in the same directory run `hugo`

Afterwards if you can on Linux or WSL run `find . -type f -exec dos2unix {} \;`, otherwise, please wait for someone else to update the website, because the difference between unix and dos will break the website css.

Then commit and push changes to publish them.

If you just want to see how the website looks locally, install hugo and clone then run `hugo server` and you will be able to see what the website currently looks like.

Need to add the below to index.html for background music every hugo update:
`
<audio id="sketch-on-beloved-background" control autoplay loop preload="auto">
		<source src="music/Sketch_on_Beloved_Audio.mp3" type=audio/mpeg>
        Your browser does not support the audio element.
</audio>
`
