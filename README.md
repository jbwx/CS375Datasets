1. My dataset consists of images of the hand-drawn characters 'a', 'b', and 'c'. 
   I have 33 images for each class - adding up to 99 total.
   I drew the images using the web app that you made.
2. 80 files were used for training, and 19 were used for validation.
3. It isn't terribly good. Perhaps more training data is needed, or I should draw better letters.
   It's best at classifying the letter C – possibly because it's the most distinct letter?
   It usually gets confused with the letter A. Perhaps because it can be easily confused with both C and B (but C and B are distinct from each other)?
   It probably won't classify other images well – especially ones that aren't mouse-drawn on a 224x224 canvas. Overall, I think it could only guess 40% or so of the images.
4. I made the decision to gather the maximum data allowed (or close to it) – 99 images. I also chose to draw the letters using the web app that you made. I also chose the same model we used in the lab. I also chose to represent each letter equally – each getting 33 training images.
   I need a diverse range of data. Different handwriting styles, different formats (like drawn on a chalkboard instead of an HTML canvas), and larger amounts of said data.
   If I had done that instead, I believe the model would be more accurate – and robust, since it would be trained on letters in a variety of mediums.
