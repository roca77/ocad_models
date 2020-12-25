# OCAD Universirty - Machine Learning models (Private repot)

## Project Description
to do

## Notes on Models
### V.1.0

### V.1.2
This second version of the model is focused mainly on the scars themselves, instead of the whole profile in the drawing. It's accuracy rate is more stable, and score higher on the validation image set.

![Training plot](/images/training_v1.2.png)

## Front-end Preprocessing
In this model, due to the dimension of the cropped scars I am trying with 120x120px; what this mean is that the line 22 in `predict.js` must be set to:
` .resizeNearestNeighbor([120,120])`
This is the most important change required while this model is activated.
