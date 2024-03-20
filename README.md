Questions
1. What is the overall accuracy of the classifier?
- Train Acc      0.9426222443580627
- Validation Acc 0.8515999913215637
    
2. What modifications would you do in order to improve the classification accuracy?
   - at first, I used the same network we use in the lesson for the MNIST problem, but it was with low accuracy,
   - increasing numbers of kernels, accuracy some increase too
   - I compiled a lot of times with different combination of filters numbers, but it didn't have enough effect.
   
3. Make one modification (that you think can help) and train the classifier again. Does the accuracy improve?
   - I decided to use AlexNET as default and adapted it for my needs. I had new problem, validation accuracy was
   - sgnificantly behind train accuracy, that could indicate about retraining model (model is to comlex for 50000 images)
   - so I used dropout to decide this problem. I tried to solve task with empirical method and I configured model every time after
   - training (more layers, dropouts, neurons, ets.).
   - When time for training had become significant, change model to take result was harder and harder, sometime result was worse than I had before.
   -  So my best result in 1 answer. And I don'n think that it is the good model for this result.
