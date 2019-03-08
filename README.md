# css_gradient_transitions (using javascript)

I have been playing around with random color generators that smoothly transition from one randomly generated color 
to another with a semi-randomized amount of time between each transition.  
I also really like the look of overlaying different gradients with varying opacities.

I wanted a way to combine the two - generating random gradients that smoothly transition from one to the next using css,
however, gradients can't be animated using the css transition property!

So, I wrote some javascript that creates two random gradients and layers them on top of each other. The bottom layer 
fades in from 0 opacity while the top layer fades out from 100 opacity, creating the illusion of a css transition.
