# Breast Cancer Prediction

This project tackles a binary classification problem: predicting whether a breast mass is **malignant** or **benign**. The dataset is derived from features computed on digitized fine-needle aspirate (FNA) images of breast tissue, capturing measurable properties of the cell nuclei.

## Dataset Information

Each record includes:

- **ID Number** — unique sample identifier  
- **Diagnosis** — target label:  
  - **M** = Malignant (cancerous)  
  - **B** = Benign (non-cancerous)

### Feature Set

Ten real-valued attributes are calculated per cell nucleus:

1. **Radius** — average distance from the center to the perimeter
2. **Texture** — standard deviation of gray-scale intensities
3. **Perimeter** — length of the nucleus boundary
4. **Area** — surface area of the nucleus
5. **Smoothness** — local variation in radius lengths
6. **Compactness** —  
   \[
   \text{Compactness}=\frac{(\text{Perimeter})^2}{\text{Area}}-1.0
   \]
7. **Concavity** — severity of concave segments on the contour
8. **Concave Points** — count of concave contour points
9. **Symmetry** — degree of bilateral symmetry
10. **Fractal Dimension** — contour complexity (coastline approximation)

## Project Objective

Build and evaluate machine learning models that, using the above features, accurately classify a mass as malignant or benign, providing a dependable aid for early detection and clinical decision-making.

## Features Overview (at a glance)

1. **Radius** — indicative of nucleus size  
2. **Texture** — variability of pixel intensities  
3. **Perimeter** — boundary length measurement  
4. **Area** — total region covered by the nucleus  
5. **Smoothness** — boundary evenness  
6. **Compactness** — how tightly the boundary encloses area  
7. **Concavity** — depth of inward curves along the edge  
8. **Concave Points** — number of inward-curving points  
9. **Symmetry** — shape balance  
10. **Fractal Dimension** — edge complexity

## Machine Learning Approach

Algorithms considered include:

- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Support Vector Machine  
- XGBoost Classifier  

Models are assessed with **accuracy**, **precision**, **recall**, and **F1-score**.

## Conclusion

Using quantitative features extracted from FNA images, we can train robust models to distinguish malignant from benign tumors with high reliability. Such tools support earlier diagnosis and can enhance clinical workflows by highlighting cases that merit closer review.
