# Virtual Caregiver for teenagers with body dysmorphic disorder

This project was developed with help of Serendeepia Research for psicobotica, The main aim of this virtual caregiver is to detect emotions in teenager’s facial expressions. The caregiver is very important the emotion detection via facial gesture recognition because it allows the detection of negative and positive emotions in real time. This process creates a daily report with the patient progress which can be of help for the doctor to implement the appropriate therapies according to the emotional state of the patient.

## Getting Started

To start, the procedure that it show involves two standpoints where it training with datasets for Facial Expression Recognition and Facial Keypoints Detection, you can download them here:
[facial expression recognition](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data) & [facial key points detection](https://www.kaggle.com/c/facial-keypoints-detection)
These datasets must upload in google drive because the notebook already is prepared for be running on google collaboratory. Next, you should download the  [the notebook](https://github.com/DavidIngx/FER_VirtualCaregiver/blob/master/VirtualCaregiver.ipynb) and upload in google drive too together with the files previous. 

Now since Google Drive you can open the notebook and should allow acces the google colaboratory 
```
# Google Colaboratory requires authorization for access your drive run the next code for get the security code.
from google.colab import drive
drive.mount('/content/gdrive')
```
Next, you should change the file url for that pandas find the dataset **facial expression recognition**
```
# Using the library pandas you can import the file csv
dataset_facial_expression = pd.read_csv("/content/gdrive/My Drive/fer2013.csv")
```
the previous procedure should apply in the dataset **facial key points detection**
```
df = pd.read_csv('/content/gdrive/My Drive/Colab Notebooks/training.csv')

```


## Authors

* **David Peña** - [Linkedin](https://www.linkedin.com/in/brian-david-pe%C3%B1a-morales-4629b3167/)

## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/DavidIngx/FER_VirtualCaregiver/blob/master/LICENSE) file for details

