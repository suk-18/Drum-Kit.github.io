This is a Drum Kit Web Aplication which allows to play different sounds similar like a original drum.

To play the drum sounds the corresponding buttons should be clicked.

The buttons are named on the based of alphabets as w,a,s,d,j,k and l.

The sounds are uploaded from the sounds folder.

When a particular button is clicked the soounds to that particular button is played.

Example: If the button w is clicked the sounds_crash.mp3  sound is played as it is the corresponding sound given.

The code html code for the drum kit is in index.html file and the styling code is in the style.css file.

Here is a step-by-step explanation of how the code works:

1.The index.html file loads the sounds/ folder.

2.The index.html file creates the buttons and assigns them onclick handlers.

3.The onclick handlers call the corresponding function to play the sound.

4.The functions play the sound by creating an Audio object and calling the play() method.
