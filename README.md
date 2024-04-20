# What is MNIST?
- Set of 70,000 small image of digit handwritten nby hugh school student and employee and employee of US Census Bureau.
- All image are labbled withh the respective digit they represent.
- MNIST is the " hello world " of Machine learning.
- There are 70,000 images and each image has 784 features.
- Each image is 28 X 28 pixels, and each feature simply represent one pixel's intensity, from 0 (white) to 255 (black)

 **Classification Drawbacks**:  
   - Can be biased towards majority classes.
   - Struggles with imbalanced data.
   - Sensitive to outliers.
   
**Precision, Recall, F1**:  
   - Precision: True positives over all predicted positives.
   - Recall: True positives over all actual positives.
   - F1 Score: Harmonic mean of precision and recall.
   
 **Precision-Recall Curve**:  
   - Graphical representation of precision and recall.
   - Useful for selecting optimal model thresholds.
   
**Interpretation**:  
   - Higher precision means fewer false positives.
   - Higher recall means fewer false negatives.
   
**Trade-offs**:  
   - Increasing precision often lowers recall, and vice versa.
