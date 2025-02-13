# Dog Breed Classifier Project

**Project Goal**  
This project aims to improve your programming skills and understanding of machine learning basics using Python. The goal is to apply Python to work with an image classifier and identify dog breeds. Focus on learning Python and working with the classifier rather than creating the classifier itself.

**Project Description**  
This script classifies pet images using a pretrained CNN model, extracts pet labels from filenames, compares them with predicted labels, and evaluates model performance on dog classification. It processes images, adjusts results to check if the pet is a dog, calculates classification statistics, and prints a performance summary along with total execution time.

## Scenario
Your city is hosting a citywide dog show, and you’ve volunteered to help the organizing committee with contestant registration. Every participant that registers must submit an image of their dog along with biographical information. The registration system tags the images based on the biographical information.

However, some people may try to register pets that aren’t actual dogs.

To ensure the integrity of the registration system, you are tasked with using an already-developed Python image classifier to verify that the submitted images are dogs. You will also need to classify the breed of the dogs.

**What You Need to Do**  
In this project, you will use an image classifier to identify whether an image contains a dog and then classify the breed of the dog. The following tasks are required:

### Tasks:

1. **Classify images as "dogs" or "not dogs"**  
   Use the provided image classification algorithms to determine which one works best for identifying images as "dogs" or "not dogs". You will not be creating the classifier but applying it to solve the problem.

2. **Identify the dog's breed**  
   After determining the image is a dog, use the classifier to determine the breed of the dog. Take note that image classifiers are not always perfect, and there might be inaccuracies.

3. **Evaluate accuracy and performance**  
   - Assess how well the chosen algorithm classifies images accurately.
   - Measure how long each algorithm takes to classify the images. There’s often a trade-off between accuracy and runtime—more accurate algorithms might take longer and require more computational resources.

### Key Concepts:
- **Image Classifier**: A tool that takes an input (an image) and returns an output (the classification of the image, such as "dog" or "not dog").
- **Accuracy vs. Runtime**: More accurate classifiers may take longer to run, so finding the right balance is crucial.

---

## Installation

### Prerequisites

- Python 3.x
- Required libraries (usually provided in a `requirements.txt` file)

To install the necessary dependencies, you can use the following:

```bash
pip install -r requirements.txt
