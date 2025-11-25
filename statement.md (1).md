**E-Waste** **Segregation** **using** **Random** **Forest**

*Overview*

In this project, e-waste images are classified into categories using a
Random Forest classifier trained on the flattened image pixels: mobile,
laptop, battery, charger, and PCB.

> ***<u>Dataset</u>***

Store the dataset in Google Drive under \`E_waste_dataset/\`, and create
subfolders for each class. Use 50 images per class, as needed.

How to run (Google Colab)

1\. Upload dataset to Google Drive.

2\. Open \`notebooks/colab_notebook.ipynb\` in Colab.

3\. Mount Drive and update \`DATA_DIR\` with the dataset path.

4\. Run cells: load -\> preprocess -\> train -\> evaluate -\> save
model.

***<u>Files</u>***

\- \`src/\`: scripts used in the notebook

\- \`notebooks/colab_notebook.ipynb\` : main notebook - \`report.pdf\` :
project report for submission

***<u>Requirements</u>***

\- scikit-learn

\- scikit-image

\- joblib

\- matplotlib

***<u>Project Statement</u>***

Problem Statement: E-waste segregation is slow and error-prone if
performed manually. In this work, we propose an image-based classifier
to automatically identify e-waste item types to assist sorting.

***<u>Scope:</u>***

Classification of common e-waste items: mobile, laptop, battery,
charger, and PCB. Target users: Recycling centers, waste-collection
teams, small-scale recyclers. \*\*High-level features:

Upload image -\> predicts e-waste class - Using Google Drive Images for
Training Pipelines Model evaluation and sample predictions
