# Multiclass text classification

Project uses Tensorflow to train multiclass text classification models on a sintetic dataset produced with Google Gemini

#### Launching the environment
Suggested way to run the project
It is suggested to run with docker, using the base image tensorflow/tensorflow:-gpu-jupyter. Adapt the following command:

`sudo docker run --name tensorflow-dev -p 8888:8888 -v {your_repository_dir}:/tf/classification  tensorflow/tensorflow:2.18.0-jupyter`

Then get the jupyter notebaook link by seeing the container logs:

`sudo docker logs tensorflow --details`

#### Overview
In this project, neural network models were trained to create an expense classifier. However the training notebook can be applied at any other context.

Due to the limitation of data for such a context, Gemini was used to generate a sintetic dataset. 

#### Demonstration
The following demonstration is for an API created with the best trained model. The details of creating the API are not presented in this repository.

[Screencast from 25-02-2025 17:48:28.webm](https://github.com/user-attachments/assets/1633e62b-cc58-42d7-aec7-835e0248d299)
