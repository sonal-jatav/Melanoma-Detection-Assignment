# Melanoma Detection Assignment
> **Detect images and classify into 9 classes**

## Objective:

1. Build a model based on CNN to detect melanoma accurately
2. Detect images into the 9 classes
3. Handle class imbalances using augmentor library
4. Identify and prevent underfitting and overfitting
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1
**Class with least no. of samples** - seborrheic keratosis <br/>
**Classes that dominate the data in terms of proportionate no. of samples** - pigmented benign keratosis

- Conclusion 2
<ol>
    <b>Model is Overfitting</b>
   <li>As per the graph: Training loss is decreasing and validation loss is increasing which is a clear indication of overfitting. The model is learning noise alongside patterns in training data </li> 
    <li>Another evidence to overfitting is the accuracy scores for training data are drastically higher than the test data. This happens when the model is not able to generalise very well</li>
</ol>
<br/>
<ol>
    <b>How to fix overfitting in CNN</b>
    <li>Data Augmentation</li> 
    <li>Dropout Layers</li>
    <li>Regularization</li>
    <li>Reduce Model Complexity</li>
    <li>Early Stopping	</li>
    <li>Increase Training Data	</li>
</ol>

- Conclusion 3
<ol>
    <b>Overfitting</b>
    <li>As per the graph: Training and validation loss values are reducing to nearby values which indicates that overfitting is taken care of </li> 
    <b>Accuracy</b>
    <li>Train and test accuracy scores are still low</li> 
</ol>
<br/>
<ol>
    <b>How to increase Accuracy Score</b>
    <li>Data Augmentation</li> 
    <li>Data normalization</li>
    <li>Batch normalization</li>
    <li>Learning rate scheduling</li>
    <li>Weight Decay</li>
    <li>Gradient clipping</li>
</ol>

- Conclusion 4
<ol>
    <b>Accuracy</b>
    <li>Train and test accuracy scores have improved</li> 
    <li>Adam optimizer is appropriate for multiclass classification<br/>
        <ol>
            <li>Enhanced Learning Dynamics</li>
            <li>Faster convergence</li>
            <li>Improved Generalization</li>
        </ol>
    </li> 
</ol>


## Technologies Used
- Tensorflow
- Keras
- Matplotlib
