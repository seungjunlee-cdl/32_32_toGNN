# 32_32_toGNN
## 32*32 optimal topology prediction with initial Von Mises stress, strain energy density, volume fraction

### Input node features
Von Mises stress, strain energy density, volume fraction on 1st iteration of topology optimization
![input_feat](https://user-images.githubusercontent.com/56711947/149689108-51b46661-89d8-40d9-b1ef-95ab75f4663c.jpg)

### Graph Structure
32*32 mesh to graph structure  
![mesh2graph](https://user-images.githubusercontent.com/56711947/149689229-18ff40ba-4aa1-4daf-8696-10849a0418b6.jpg)

### Network Architecture
6 graph convolution layer with batch normalization of hidden node features  
![model](https://user-images.githubusercontent.com/56711947/149693233-51c4cf81-4428-4266-9202-fbc5d945ce64.jpg)

### Results
Target and prediction visualization  
![res](https://user-images.githubusercontent.com/56711947/149691141-f954ec7e-0622-42f2-8160-981003d1ab84.jpg)
