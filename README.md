# Handwritten Digit Recognizer

My version of a common introductory data science project with a twist: Instead of throwing the data at a CNN, I tried to code 'from scratch' and manually engineer features from the raw pixel data to achieve a 96% accuracy, compared to a baseline of 10%.

# Notebooks
1. Capstone 3: Main notebook where I load and clean the data, and engineer all of the features that make up the core of this project. There are som basic visualizations of the features at the end.
2. Capstone 3 model testing: I try running my data from various supervised learning models and tune parameters to achieve the highest accuracy possible.
3. Product: Some supporting functions used in the previous notebooks
4. Capstone 3 Animation: A helper animation used to illustrate how one of my feature engineering functions works
5. Image processing: Convert jpgs into usable filesizes to run my model on. I can use this to pull images of digits from the web to see if the model can correctly identify the digit. Note, this does not work very well since the model is trained on handwritten digits. According to my model, a selfie I took is a '3.'
