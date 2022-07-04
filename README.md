# X-ray-project
Three CV models to predict pneumonia trained on this <a href = "https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia"> repo </a> on kaggle

<b> Problem </b>

In the light of current epidemic a NN may come in handy to help radiologists, hence I decided to train a few models that would be a useful in this setting. I've set a goal of validation accuracy over 80%.

<b> Data </b>

As per of repository descirption: 
"The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care. "

<b> Models tested </b>

CNN

![CNN-1 1](https://user-images.githubusercontent.com/91603107/177183090-ea689ba8-5168-4eb7-9f2b-23e39a0388f3.png)

![CNN-2](https://user-images.githubusercontent.com/91603107/177183102-825b83f6-12be-48e0-bea1-a3ae61a54df5.png)

Efficenet

![obraz](https://user-images.githubusercontent.com/91603107/176995877-acd624e7-de3d-4bda-8ca5-2e0a4a64ee91.png)
![obraz](https://user-images.githubusercontent.com/91603107/176995879-37d8d583-10ed-4355-9daf-892b54ea79ce.png)

Mobilenet

![obraz](https://user-images.githubusercontent.com/91603107/176995890-4deddd5e-b374-49a8-af71-ba4656b51965.png)
![obraz](https://user-images.githubusercontent.com/91603107/176995891-8588badd-74aa-459a-8b7a-8a663276dfe2.png)

<b> Model chosen </b>

As per chosen target - only the CNN has met over >80% validation accuracy, thus being the only project being ported to the ruidmentary implementation in "X_ray_implement.ipynb".
