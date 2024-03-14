# CNN Skin Condition Classification
# Overview
This project aims to classify erythemato-squamous diseases into six different skin conditions: psoriasis, seborrheic dermatitis, lichen planus, pityriasis rosea, chronic dermatitis, and pityriasis rubra pilaris using Convolutional Neural Networks (CNNs). The CNN model is trained on clinical features and histopathological features extracted from skin samples.

# Dataset
The dataset used in this project consists of clinical features and histopathological features of patients with erythemato-squamous diseases. The clinical features include erythema, scaling, definite borders, itching, koebner phenomenon, polygonal papules, follicular papules, oral mucosal involvement, knee and elbow involvement, scalp involvement, family history, and melanin incontinence. The histopathological features include eosinophils infiltrate, PNL infiltrate, fibrosis papillary dermis, exocytosis, acanthosis, hyperkeratosis, parakeratosis, clubbing rete ridges, elongation rete ridges, thinning suprapapillary epidermis, spongiform pustule, munro microabcess, focal hypergranulosis, disappearance granular layer, vacuolization damage basal layer, spongiosis, saw tooth appearance retes, follicular horn plug, perifollicular parakeratosis, inflammatory mononuclear infiltrate, band-like infiltrate, and age.

# Model
The CNN model is implemented using TensorFlow and Keras. The model architecture consists of multiple convolutional layers followed by max-pooling layers to extract features from the input images. The extracted features are then passed through one or more fully connected layers for classification.

# Training
The CNN model is trained on the clinical and histopathological features extracted from the skin samples. The dataset is split into training and testing sets to evaluate the model's performance. The model is trained using backpropagation and optimized using the Adam optimizer. The accuracy of the model on the training and testing sets is monitored during training.

# Evaluation
The performance of the CNN model is evaluated using metrics such as accuracy, precision, recall, and F1-score on the testing set. The model has achieved an accuracy of 1.0, indicating its effectiveness in classifying skin conditions.

# Usage
To use the CNN model for skin condition classification:

1. Install the required dependencies (TensorFlow, Keras, etc.)
2. Load the clinical and histopathological features of the patients
3. Preprocess the features (scaling, normalization, etc.)
4. Train the CNN model on the preprocessed features
5. Evaluate the model's performance using suitable metrics
6. Make predictions on new patient data using the trained model
