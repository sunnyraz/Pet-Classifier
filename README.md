# Pet Classifier

Pet Classifier is a deep learning project aimed at distinguishing between images of cats and dogs. Leveraging transfer learning techniques with a ResNet50 architecture, the model is trained on a dataset containing labeled images of cats and dogs.

## Key Features

- **Data Preparation**: The dataset, comprising images of cats and dogs, is preprocessed and split into training and testing sets.
   
- **Model Training**: The ResNet50 model, pretrained on ImageNet, is utilized as the base model. The final fully connected layer is replaced with a custom classifier, and the model is fine-tuned on the training data.
   
- **Evaluation**: The trained model is evaluated on a separate test set to measure its accuracy in classifying new images of cats and dogs.
   
- **Inference**: Once trained and evaluated, the model is capable of predicting the class labels (cats or dogs) for new images.
   
- **Visualization**: The project includes visualizations of sample images from the test set, along with the model's predictions and probability distributions.
   
- **Export and Deployment**: Finally, the trained model is saved along with its associated metadata, such as class indices, and can be deployed for making predictions on new images.

1. **Clone the repository:**

    ```bash
    git clone https://github.com/sunnyraz/Pet-Classifier.git
    ```

2. **Kaggle Notebook:**

    This project is part of a Kaggle competition for Dogs vs Cats classification. You can access the notebook on Kaggle by following this link:

    [Dog vs Cat Classifier Kaggle Notebook](https://www.kaggle.com/code/sunnyraz/dog-vs-cat/)

    Feel free to explore and run the notebook to delve deeper into the project.
