####### Final CV Project #######

The final zip file contain 3 folders:

1. Demo App:- Contains Code for our eye disease detection app.We have made a basic web app using streamlit where you simply upload your fundus eye image and it will show you which eye disease most probably you are having.The process to how you can run the app will be shown below.


2.Experiments Models:- This folder contains some of the code which we had tried during making our full fledge project.We are not able to add all the tried code as there were many which we were not able to save or had overwritten.


3.Final Code:- This contains subfolders AMD , Cataract , ......., under every folder it contains two file one for python notebook containing code to get the various model and it also contains the resultant models also.

AMD :- It contains the code for AMD disease prediction.

Cataract :- It contains the code for Cataract disease prediction.

DR :- It contains the code for DR disease prediction.

Glaucoma :- It contains the code for Glaucoma disease prediction.

Knowledge_Distillation :- It contains the code for implementing KD.

Pathological_Myopia :- It contains the code for Pathological_Myopia disease prediction.

Vision_Transformer Combine :- It contains the code for prediction of several disease all at once.



###### How to run the various files ######

You can run the notebook to train/test the model, or directly load the saved model for inference.

How to Run Notebooks (Google Colab)

Open the notebook (.ipynb) inside the disease folder.

Set runtime to GPU:
Runtime → Change runtime type → select GPU

Upload the notebook or open it directly in Colab.

Dataset will automatically download using gdown.

If the download fails (due to quota exceeded), manually replace the file ID in: https://drive.google.com/uc?id=<file_id>

Try any of these:

1vHCvd9ZFkY9lfNwUnnMUbDQZjjpby8lv

1QwItNnETzlWHgZ89EbHFYg04ijkDszF6

1NfuMblbAumQHfcuJAQCMFA4gR8gf0F8F

Run all cells:
Runtime → Run all

The model will train and save the .keras file in the same folder.

How to Run the Streamlit Demo App

Go to the Demo App folder.

Open terminal and run: streamlit run Final_Disease.py

Upload a retinal fundus image.

It will show the predicted disease using the trained model.

Notes

You don't need to upload any extra files — data is auto-downloaded in notebooks.

If a notebook fails to fetch data, change the file ID as shown above.

All notebooks run perfectly in Google Colab (with GPU enabled).

The Streamlit app is for local testing only.











