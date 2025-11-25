**E-Waste** **Segregation** **using** **Random** **Forest**

**Overview**

The following project classifies the images of ewaste into
categories-mobile, laptop, battery, charger, and PCB, using a Random
Forest classifier trained on the flattened image pixels.

Dataset Store the dataset on Google Drive under E_waste_dataset/with
subfolders for each class. Use 50 images per class, modify this if
needed.

**How** **to** **run** **(Google** **Colab)**

> 1\. Upload dataset to Google Drive.
>
> 2\. Open notebooks/colab_notebook.ipynbin Colab. 3. Mount Drive and
> set DATA_DIRto the dataset path.
>
> 4\. Run cells: load → preprocess → train → evaluate → save model.

**Files**

> ● src/: scripts used in the notebook
>
> ● notebooks/colab_notebook.ipynb: main notebook ● report.pdf: project
> report for submission

Requirements

> ● scikit-learn ● scikit-image ● joblib
>
> ● matplotlib
