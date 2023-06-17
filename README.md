# Scene-Recognition-CNN

### Introduction
Indoor scene recognition is a challenging open problem in high level vision. Most scene recognition models that work well for outdoor scenes perform poorly in the indoor domain. The main difficulty is that while some indoor scenes (e.g. corridors) can be well characterized by global spatial properties, others (e.g., bookstores) are better characterized by the objects they contain. More generally, to address the indoor scenes recognition problem we need a model that can exploit local and global discriminative information.

### Dataset
The dataset used for this project is the [MIT Indoor Scenes](https://paperswithcode.com/dataset/mit-indoors-scenes) dataset. Salient features of this dataset:-

- The dataset contains 67 Indoor categories, such as restaurant, concert hall, gym, etc.
- The dataset contains 15620 images in total.
- The number of images varies across categories, but there are at least 100 images per category.
- All images are in jpg format.

For the purpose of this project, images have been taken from the ```Leisure``` category of the dataset, which further contains 11 subcategories: ```buffet```, ```fast food```, ```concert hall```, ```restaurant```, ```bar```, ```movie theatre```, ```game room```, ```casino```, ```bowling```, ```gym``` and ```hair salon```.
