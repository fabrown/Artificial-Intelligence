Project taken at Wilmington University College of Technology.
Course: CSC470 - Computer Vision and Image Analysis
Project Overview:

Agriculture requires significant manual labor to ensure plants grow correctly. Manually identifying different plants and weeds is time-consuming. AI and Deep Learning can revolutionize this trillion-dollar industry by automating the identification of plant seedlings, leading to better crop yields and sustainable practices.

Objective:

Use the provided dataset from the Aarhus University Signal Processing group and the University of Southern Denmark to build a CNN model that classifies plant seedlings into 12 categories.

List of Plant Species:

Black-grass
Charlock
Cleavers
Common Chickweed
Common Wheat
Fat Hen
Loose Silky-bent
Maize
Scentless Mayweed
Shepherds Purse
Small-flowered Cranesbill
Sugar beet
Dataset Description:

Dataset Files:
images.npy Download images.npy– Contains the images of the unique plants.
Labels.csv Download Labels.csv– Contains labels corresponding to each image.
Goal: Create a classifier to determine a plant’s species from an image.
Project Steps and Requirements:

Step 1: Create a Google Colab Account
Google Colab InstructionsDownload Google Colab Instructions
Step 2: Load Dataset and Summary
Load Data – Load image.npy and Labels.csv.
Open your Colab notebook
In the left sidebar, click on the folder icon to open the "Files" pane
In the Files pane, click on the upload button (icon looks like a file with an up arrow)
Select your images.npy and Labels.csv files from your local machine
Wait for the upload to complete
Print Overview – Print the shape of the data and the proportion of each class.
Plot Images – Plot sample images from each class with labels.
Step 3: Perform EDA on the Images
Count Plot – Plot the count of each category to understand class distribution.
Deep Dive – Additional visualizations, like plotting the first image of each species.
Step 4: Illustrate Insights from EDA
Observations – Note key insights from EDA
The dataset is balanced, with each species having a similar number of samples.
Visual inspection of the images shows that plant species have distinct visual characteristics.
Step 5: Data Pre-Processing
Noise Removal – Apply Gaussian Blurring to remove noise from the images.
Normalization – Normalize images to a range of 0-1.
Visualization – Plot images before and after preprocessing.
Split Data – Split data into training and testing sets
Step 6: Make Data Compatible
One-Hot Encoding - Convert labels to one hot vectors for multi-class classification.
Reshape Data – Ensure data shape is compatible with Keras models
Step 7: Model Building
CNN Model – Build a CNN with appropriate layers.
Step 8: Model Training
Fit Model – Train the CNN model with training data.
Plot Training History – Visualize the training and validation accuracy and loss.
Step 9: Model Performance Evaluation
Evaluate Model – Evaluate the model on the test set using various metrics
Confusion Matrix – Plot the confusion matrix for model predictions.
Step 10: Conclusion and Key Takeaways
