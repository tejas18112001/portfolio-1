---
title: "CI/CD Pipeling With Github Integration"
description: "Automate software development, testing, and deployment with a streamlined CI/CD pipeline using Docker, GitHub, Jenkins, AWS, and Node.js."
dateString: Mar 2023 - Apr 2023
draft: false
tags: ["AWS" , "Jenkins" , "Docker" , "GitHub"]
showToc: false
weight: 203
cover:
    image: "projects/automated-image-captioning/cicd-poster.png"
--- 
### 🔗 [Youtube demonstration](https://www.youtube.com/watch?v=oDqqGSlxqtk)

## Intro
Implemented CI/CD pipeline  using GitHub Actions with integration to AWS, Jenkins, Docker, and GitHub. The Docker Jenkins Pipeline was built to showcase the continuous integration and continuous delivery workflow. A node.js todo list application was deployed on AWS as part of the pipeline. The project was tracked on GitHub, ensuring that each code commit to the repository was versioned. To facilitate this process, a Docker Jenkins Pipeline was created. This pipeline would generate a Docker image from the Dockerfile, as well as pull and run the Docker image as a container.

## Final Thoughts
The CI/CD pipeline automates various stages of the software development lifecycle, including building, testing, and deploying applications. This automation improves efficiency, reduces manual errors, and enables faster and more frequent releases.



<!-- ## Description
In this project, I implemented the paper **[Show, Attend and Tell: Neural Image Caption Generation with Visual Attention](https://arxiv.org/abs/1502.03044)**. The neural network, a combination of **CNN** and **LSTM**, was trained on the **MS COCO** dataset and it learns to generate captions from images. 

As the network generates the caption, word by word, the model’s gaze (attention) shifts across the image. This allows it to focus on those parts of the image which is more relevant for the next word to be generated. 
![Attention Mechanism](/projects/automated-image-captioning/img1.jpg)

Furthermore, beam search is used during inference to enhance the prediction result. The network was trained in **PyTorch** on an **Nvidia GTX 1060** graphics card for over 80 epochs. -->