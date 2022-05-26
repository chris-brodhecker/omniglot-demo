# omniglot-demo

Demonstration of how to make language phrases play 'in-line' rather than link to another page.

### General Approach ###

The way to get 'inline' sounds to play is with an <audio> element. This element can load audio data from 
a specific url and then play it once it is loaded.

I thought of two approaches:
    1. Create the audio element when the user clicks
    2. Create all of the audio elements when rendering the page

The second approach is simpler and uses less javascript. The downside is that it will increase the number of HTML elements on the page. 
Personally I don't think that will be much of an issue unless you have over 1000 phrases per page or something.
