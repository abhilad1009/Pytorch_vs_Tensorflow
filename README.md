# Pytorch_vs_Tensorflow
Abhi Lad al4363 - High Performance Machine Learning Project
# Project Description
Though Pytorch and TensorFlow are tremendous ML libraries with extensive support, if Github threads and Stackoverflow are any metrics, a lot of functionalities are still missing.
Especially in case of current trends of extremely large models, we need to identify and optimize model performance by reducing memory and time consumption.
Quantization is a simple and proven method, and in this project we aim to find the support and implementation gaps for this feature in both the libraries.

Since we were aiming for one-to-one comparison between TensorFlow and Pytorch, we had exponential increase in model iterations due to different implementation paradigms.
The following diagrams show the overall workflow of our project.

Workflow
![workflow](./workflow.png)
Experiments
![experiments](./experiment_flow.png)

# Code Structure
All codes are in jupyter notebooks and do not need any special commands to run.
Final Code:
* Pytorch Implementation : [notebook]("./Profile_pt_clf.ipynb")
* TensorFlow Implementation : [notebook]("./Profile_tf_clf.ipynb")
Failed and Scrapped Code:
* Pytorch Implementation : [notebook]("./Failed_Pytorch_image_captioning.ipynb")
* TensorFlow Implementation : [notebook]("./Failed_Tensorflow_image_captioning.ipynb")

# Results
Accuracy
![accuracy](./accuracy.png)
Infernce Time
![inference](./inference_time.png)
Model Size and Training Time
![modelsize](./model_size.png)
