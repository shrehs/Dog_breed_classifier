# Image Classification for a City Dog Show

## Project Goal
The goal of this project is to improve programming skills using Python by applying an existing image classifier to identify dog breeds.

## Project Description
Your city is hosting a citywide dog show, and you have volunteered to help the organizing committee with contestant registration. Each participant must submit an image of their dog along with biographical information. The registration system tags the images based on the provided information.

To ensure that only dogs are registered, you will use a pre-developed Python classifier to verify the images. Some participants might try to register pets that are not dogs, so it's crucial to accurately identify dogs.

## Your Tasks
1. **Determine the Best Image Classification Algorithm:**
   - Use your Python skills to evaluate different image classification algorithms for identifying images as "dogs" or "not dogs".
   
2. **Evaluate Algorithm Performance:**
   - Assess how well the best algorithm identifies a dog's breed.
   
3. **Measure Algorithm Runtime:**
   - Time how long each algorithm takes to classify the images. Understand the trade-off between accuracy and runtime.

## Important Notes
- **Image Classification Application:**
  - You will use a convolutional neural network (CNN) for image classification. CNNs are effective at detecting features in images and identifying objects.
  
- **Pre-trained CNN Models:**
  - The provided classifier function uses a CNN pre-trained on the ImageNet dataset, which includes 1.2 million images.
  
- **CNN Architectures:**
  - Explore three different CNN architectures: AlexNet, VGG, and ResNet, to determine which one works best for your application.

- **Classifier Function:**
  - The classifier function is provided in `classifier.py`, and an example usage is shown in `test_classifier.py`. Focus on using your Python skills to complete the tasks using this function.

- **Similar-Looking Breeds:**
  - Some dog breeds look very similar, making classification challenging. Be aware of these similar breeds when evaluating the classifier's performance.

## Example Similar-Looking Breeds
- **Great Pyrenees** and **Kuvasz**
- **German Shepherd** and **Malinois**
- **Beagle** and **Walker Hound**

## FAQs
For further clarifications, please check our [FAQs](#).

## Files Provided
- `classifier.py`: Contains the classifier function.
- `test_classifier.py`: Demonstrates how to use the classifier function.
