# X ray - pneumonia categorization
Three CV models to predict pneumonia in X-ray images trained on this <a href = "https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia"> repo </a> on kaggle

<b> Problem </b>

In the light of current epidemic machine learning may come in handy to help radiologists, hence I decided to train a few models that would be a useful in this setting. I've set a goal of validation accuracy over 80%.

<b> Data </b>

As per of repository descirption: 
"The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care. "

<b> Models tested </b>

CNN

![CNN-1](https://user-images.githubusercontent.com/91603107/177183439-52e02c29-de9b-48c2-b3ae-fd0e4074a8df.png)

Efficenet

![EFF-1](https://user-images.githubusercontent.com/91603107/177183459-7609ed3e-a586-4eb0-986a-7eaa508a3728.png)

Mobilenet

![Mobile_1](https://user-images.githubusercontent.com/91603107/177183476-095019dd-99af-4a08-919c-4b8c9f6558ab.png)

<b> Model chosen </b>

As per chosen target - only the CNN has met over >80% validation accuracy, thus being the only project being ported to the ruidmentary implementation in "X_ray_implement.ipynb" via Keras' serialization. 
