# Brain Tumor Detection
Brain Tumor is the common disease in today's world.People of all ages can be affect by this disease.In this AI world we can solve this problem by CNN or transfer learning model.My motivation is worked to solve this problem and generalize a web service that everyone can use it.
## 📌 Features

✅ Tensorflow

✅ Deep Learning and Transfer Learning

🔥 Trained on kaggle Brain tumor dataset

💡 Uses ONNX for optimized inference  

🎯 High accuracy prediction  
## Project Overview
```
brain-tumor-detection/
│── KaggleNotebook
│   │── brain-tumor.detection-full-notebook
│── Research/
│   ├── 01_data_ingestion.ipynb
│   ├── 02_prepare_model.ipynb
│   ├── 03_data_preprocessing.ipynb
│   ├── 04_model_evaluation.ipynb
│   ├── 05_model_converter.ipynb
│   ├── 06_transfer_learning.ipynb
│── config/
│   ├── config.yaml
│── models/
│   ├── model.onnx
│── params/
│   ├── params.yaml
src/
│── components/
│   ├── __init__.py
│   ├── base_model.py
│   ├── component_common.py      # Renamed for consistency
│   ├── data_ingestion.py
│   ├── data_loader.py           # Renamed to match purpose
│   ├── model_trainer.py
│── constants/
│   ├── __init__.py
│── pipeline/
│   ├── __init__.py
│   ├── prediction.py
│   ├── test_pipeline.py         # Renamed for clarity
│── utils/
│   ├── __init__.py
│   ├── common_functions.py      # Renamed for consistency
  ├── exception.py
  ├── logger.py
  
├── static
    ├── styles.css                              # style.css file include     
├── templates
    ├── home.html                               # html file include           
├── .gitignore             
├── LICENSE                                    
├── README.md                                   # reame file
├── app.py                                      # application 
├── requirements.txt                            # requirements file
└── setup.py                                    # setup 
```

## Dataset link 

```bash
https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection
```
# Describe the project
## Dataset deatils:
### About Dataset
This data set contains 253 image .There have two category in this dataset. One is no(which is determine that patient  have no brain tumor) and another class is yes(which is use to determine patient  have brain tumor).

#### Dataset dstribution:
we split our dataset in three set.Such as:

       Train dataset
       Validation dataset
       Test dataset 

Train dataset contained 0.70(70% of the entrire dataset)

Validation dataset contained 0.20(20% of the entire dataset)

Test dataset contained 0.10(10% of the entire dataset)



## preprocessesor 
    Normalization
    Augmentation
## Models we use :
    Lenet Model(accuracy: .9846 - val_accurac:1.00)

    ResNet152V2(accuracy: 0.9583 - val_accuracy:1.00) 

    DenseNet121( accuracy: 0.9852 - loss: 0.0719 - val_accuracy: 1.00)
 
    InceptionResNetV2(accuracy: 0.9526 - loss: 0.1390 - val_accuracy: 0.920)  

We use Lenet model for our application.Because it has less parameter than any other model.We take small space and work first than other mdoel.

## kaggle notebook link
```bash 
https://www.kaggle.com/code/azizashfak/brain-tumor-detection-full-notebook/notebook
```

## Installation
1. Clone the repository:
   ```bash
   git clone <https://github.com/aziz-ashfak/Brain-Tumor-Detection.git>
   ```
2. Navigate to the project directory:
   ```bash
   cd <Brain-Tumor-Detection>
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
4. Usage
Run the main application script:
```bash
python app.py
   ```

## use cloud servce 
```bash 
link : www.render.com
```
## Use Thyroid-Disease-Prediction web-service link

```bash
 https://brain-tumor-detection-8yp3.onrender.com/
```
## Contributing
If you would like to contribute, please fork the repository and submit a pull request.

## License
This project is licensed under the [LICENSE] file included in the repository.

## Author

👤 **Aziz Ashfak**  
📧 Email: [azizashfak@gmail.com](mailto:azizashfak@gmail.com)  
🔗 LinkedIn: [linkedin.com/in/aziz-ashfak](https://www.linkedin.com/in/aziz-ashfak-/)  
🐙 GitHub: [github.com/aziz-ashfak](https://github.com/aziz-ashfak/) 

# Acknowledgement 
![Python](https://img.shields.io/badge/Python-3.10%2B-blue) 
![Tenssorflow](https://img.shields.io/badge/Tenssorflow%20-orange)
![Computer Vision](https://img.shields.io/badge/Deep%20Learning-Tansfer%20Learning-red)
![Computer Vision](https://img.shields.io/badge/Lenet%20-DenseNet-blue)
![Computer Vision](https://img.shields.io/badge/Resnet%20-InceptionResNet-blue)
![Flask](https://img.shields.io/badge/Flask-Web%20App-orange)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
---
