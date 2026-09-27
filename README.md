# AIML-Recruitment-2026-Tharun

## AI-ML Recruitment 2026 — Second Year

### Candidate Details
- **Name:** Tharun
- **Program:** CSE AIML
- **Year:** Second Year

## Task Completed
**Task 2 — Neural Network: MNIST Handwritten Digit Classification**

## Problem Statement
Build and train a simple neural network to classify handwritten digits from 0 to 9 using the MNIST handwritten digit dataset.

## Approach
1. Load and inspect the MNIST dataset.
2. Understand image dimensions, classes, and labels.
3. Normalize image pixel values.
4. Build a simple neural network with:
   - Input layer
   - Flatten layer
   - Hidden dense layer with ReLU
   - Output layer with Softmax
5. Train the model and record training/validation loss and accuracy.
6. Evaluate the model on the test dataset.
7. Generate a confusion matrix and classification metrics.
8. Perform an experiment by increasing the hidden-layer size from 128 to 256 neurons.
9. Compare the original and modified models.

## Technologies Used
- Python
- Google Colab / Jupyter Notebook
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

## Results

- Original model test accuracy: **97.56%**
- Modified model test accuracy: **97.95%**
- Original model test loss: **0.0828**
- Modified model test loss: **0.0665**

## Key Learnings
1. Learned how MNIST image data is represented and preprocessed.
2. Learned the basic structure of a neural network.
3. Learned the roles of ReLU and Softmax activation functions.
4. Learned how to train and evaluate a classification model.
5. Learned how a confusion matrix can be used to inspect classification errors.
6. Learned how changing a model's architecture can affect its performance.

## Challenges
One challenge was understanding how image data needs to be normalized and prepared before being given to a neural network. This was addressed by inspecting the pixel values, normalizing them to a 0–1 range, and using a Flatten layer before the dense layers.

## Files
- `AIML_Recruitment_2026_Tharun_MNIST.ipynb` — complete notebook.

## How to Run
1. Open the notebook in Google Colab.
2. Select **Runtime → Run all**.
3. Wait for the model training and evaluation to finish.
4. Check that all graphs, metrics, and the confusion matrix are displayed.
5. 5. Confirm that the README results match the notebook results.
