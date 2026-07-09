# Galaxy Morphology Classifier

Classifying galaxies into 8 morphological types using ResNet-50 
fine-tuned on the Galaxy Zoo DECaLS dataset (155,951 images).

## Results
- Test accuracy: 83.11%
- Trained for 22 epochs with class-weighted loss to handle imbalance
- Grad-CAM explainability to visualize model attention

## Dataset
mrJordi0/galaxy-zoo-dataset on Hugging Face

## Classes
Round Elliptical, In-between Elliptical, Cigar-shaped Elliptical,
Edge-on Spiral, Barred Spiral, Unbarred Spiral, Irregular, Merger

