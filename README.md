# image-matching-challenge-2022
Kaggle competition 2022-06

https://www.kaggle.com/competitions/image-matching-challenge-2022

## Overview
For most of us, our best camera is part of the phone in our pocket. We may take a snap of a landmark, like the Trevi Fountain in Rome, and share it with friends. By itself, that photo is two-dimensional and only includes the perspective of our shooting location. Of course, a lot of people have taken photos of that fountain. Together, we may be able to create a more complete, three-dimensional view. What if machine learning could help better capture the richness of the world using the vast amounts of unstructured image collections freely available on the internet?

The process to reconstruct 3D objects and buildings from images is called Structure-from-Motion (SfM). Typically, these images are captured by skilled operators under controlled conditions, ensuring homogeneous, high-quality data. It is much more difficult to build 3D models from assorted images, given a wide variety of viewpoints, lighting and weather conditions, occlusions from people and vehicles, and even user-applied filters.

The first part of the problem is to identify which parts of two images capture the same physical points of a scene, such as the corners of a window. This is typically achieved with local features (key locations in an image that can be reliably identified across different views). Local features contain short description vectors that capture the appearance around the point of interest. By comparing these descriptors, likely correspondences can be established between the pixel coordinates of image locations across two or more images. This “image registration” makes it possible to recover the 3D location of the point by triangulation.

Google employs Structure-from-Motion techniques across many Google Maps services, such as the 3D models created from StreetView and aerial imagery. In order to accelerate research into this topic, and better leverage the volume of data already publicly available, Google presents this competition in collaboration with the University of British Columbia and Czech Technical University.

In this code competition, you’ll create a machine learning algorithm that registers two images from different viewpoints. With access to a dataset of thousands of images to train and test your model, top-scoring notebooks will do so with the most accuracy.

If successful, you'll help solve this well-known problem in computer vision, making it possible to map the world with unstructured image collections. Your solutions will have applications in photography and cultural heritage preservation, along with Google Maps. Winners will also be invited to give a presentation as part of the Image Matching: Local Features and Beyond workshop at the Conference on Computer Vision and Pattern Recognition (CVPR) in June.
