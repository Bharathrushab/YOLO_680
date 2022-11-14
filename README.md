# YOLO

The project involved the implementation of the instance segmentation algorithm defined in paper [YOLO](https://arxiv.org/pdf/1506.02640.pdf). The main idea behind the paper is that different instance categories can be differentiated by their location and size in an image. The image is divided into SxS grids. Each grid cell is responsible for locating the instance's center which falls in the pixels it corresponds to in the original image. Size is handled by detecting at different levels of Feature Pyramid Network.

- Dataset: 10,000 street scene images with pedestrians, cars, and traffic lights labels
- Implemented the whole pipeline from scratch and compared the performance of classifier in case of different targets for confidence loss
