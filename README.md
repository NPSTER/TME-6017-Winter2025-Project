1. Uploading the NEU-DET Dataset
  Upload a zip file containing the NEU-DET dataset to Google Colab.
  **Instructions:**__ Modify zip_path and extract_dir as necessary.
2. Reading Data from Directory__
  Objective: Read data from the directory.
  **Instructions:** Ensure the dataset is separated into train, test, and validation folders before uploading.
3. Model Architecture
  OModify the model's architecture and base model in the provided code a base model called VGG16 is comment out that can be uncommented and be used as well.
  **Instructions:**__ Adjust the cell containing the model's information to change the architecture as needed.
4. Training Iterations
   To .Fit the classification model in history variable.
  Instructions: Increase or decrease the number of epochs to change the training iterations.
5. Visualizing Steel Defect Images
  Objective: Run a single batch generator to visualize different classes of steel defect images.
  Instructions: Execute the relevant cell to visualize the images.
6. Saved Classification Model
  **Instructions:**__ The model is saved as neu_model.keras in the default path for later use.
7. Model Evaluation
  Objective: Visualize and observe metrics necessary for evaluating the model.
  Instructions: Use the "Working Model Evaluation" section for this purpose.
8. Image Denoising
  Objective: denoise_images using an autoencoder.
  Instructions: Set noise_level to 0 if no synthetic noise is to be added.
9. AutoEncoder Activation
  Objective: Turn the AutoEncoder on or off.
  Instructions: Change the variable Active_Autoencoder to 1 for ON and 0 for OFF.
