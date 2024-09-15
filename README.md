control bar play button malfunctioning due to unable to detect state change . Every time an artist is clicked a value is added to the global audio variable .
The event listener on the control bar play button is used to detect the state change of audio i.e. if it was paused then upon clicking it should play the audio and if it was playing it should pause the audio
Suppose an artist is  clicked 2 times now the global audio variable has two values i.e. true and false. Now upon clicking the control bar play button the it malfunctions to play or pause since it is unable to detect a state change .
similary with every subsequent click on an artist a value is added to the Globalaudio variable
if i click three times on an artist or if i perform single clicks on 3 different artists , three values are added to the Global audio variable .


Bottom line is  that the  globalaudio variable is holding multiple values  upon clicking on an artist 
Pov: tried resetting src of globalaudio upon click but it didnt work .
