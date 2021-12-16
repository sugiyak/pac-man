# pac-man
An animation that I made to learn about DOM and Javascript. The Pac-Man animation move side to side.  
## Descripion
* It has four images of packman, Pac-Man facing each directions with mouth open and closed. They are put in and array on .js file.
* pos is the PacMan image position variable- it is set to 0 initially. This is modified in the Run function.
* direction variable decide which direction PAc-man need to move.  0 = left to right and 1 = right to left (reverse). Default setting is 0.
* focus variable represent which images need to be used at a moment. This is used in Run function and flip between 1 and 0.
* Run function update Pac-man images and its position/direction. This function is called with setInterval below.
* checkPageBounds determine with direction the Pac-man image should move. It detect the screen edge and modify direction variable.
