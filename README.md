# squisite_corpse

## user Interface Description

Squisite Corpse is a game where the user and an AI collaboratively draw a sketch. When the user navigates to the site, there is a full screen canvas and a single modal that describes how to play the game and a button to start the game.

When the user clicks the start game button, the modal disappears, the prompt of what the user should draw is displayed, and the game commences. 

The user clicks and drags on the canvas to draw a single stroke, and then the AI will draw a single stroke that makes the drawing look more like the prompt. The user can continue to draw, and the AI will continue to follow. The user can also click and drag to move the canvas, and the AI will follow.

When the user is happy with the drawing, they can click the "Share" button, which will take a screenshot of the canvas and display it full screen. The user can then download the image, at which point the modal will reappear and the user can start a new game.

## Technologies

- Transformers.js - model inference and generation of next stroke should be handled by the transformers.js library in the client browser
- Optimum - to load the quantized model
- Xenova/quickdraw-mobilevit-small - the model that will be used for the AI

## 
