# Anti Spoofing Real Dataset
1. [ About the dataset ](#about)
2. [ Distributions ](#dist)
3. [ Content ](#cont)
4. [ Get the Dataset ](#getdat)
5. [ Links ](#link)

<a name="about"></a>
# About the dataset
We introduce a large image dataset Anti Spoofing Real for training a neural network to repel various attacks on biometric access systems. The dataset consists of selfie photos and selfie videos of people. "Anti Spoofing Real Dataset" solves the tasks of training algorithms to distinguish real users from scammers. Proposed dataset allows to build identity recognition systems, which can be used to develop anti-spoofing solutions, such as countermeasures and system configurations that can help make authentication systems more secure.

The dataset consists of 44,832 videos and selfies from 37,980 unique people from 170 countries. The data for the dataset is still gathering, so the number of videos and photos is getting bigger!

### The dataset includes 2 different types of files:
- **Photo** - a selfie of a person from a mobile phone, the person is depicted alone on it, the face is clearly visible.
- **Video** - filmed on the front camera, on which a person moves his/her head left, right, up and down. Duration of the video is from 10 to 20 seconds.

### Data in the dataset
- People from 18 to 94 age old are presented in the dataset.
- For each person in the dataset age, country, gender and phone model is presented.
- The data was mostly (approximately **90%**) collected indoor, however there are also selfies and videos made outdoors.
- The lighting is artificial in **80%** of cases,  **5%** natural daily lightning, **5%** evening outdoor lighting, **10%** - dark indoor lighting.
- People turn their heads, videos and photos are filmed so that the head takes up at least 1/2 of the frame.
- Distance from the camera is approximately 30 centimeters.

### People in the dataset
![Frame 17](https://github.com/Trainingdata-datamarket/Anti-Spoofing-Real-Dataset/assets/113421352/afc6d10b-b52c-4c4f-90dd-281a9220099e)

<a name="dist"></a>
# Distributions

### Gender of people in the dataset

![image](https://github.com/Trainingdata-datamarket/Anti-Spoofing-Real-Dataset/assets/113421352/1430c4ae-4105-4a8c-9dd8-1078f1a8834e)

### Ethnicity of people in the dataset

![image](https://github.com/Trainingdata-datamarket/Anti-Spoofing-Real-Dataset/assets/113421352/4a14f04f-6b9c-4085-903a-2d0760dfe56e)

### Age of people in the dataset

![image](https://github.com/Trainingdata-datamarket/Anti-Spoofing-Real-Dataset/assets/113421352/dd395138-35ef-428b-a981-496991fa409e)

### Phone model of people in the dataset

| Brand | % |
| --- | --- |
| Samsung | 21,99% |
| iPhone | 18,04% |
| Xiaomi | 15,54% |
| Infinix | 5,12% |
| Huawei | 4,97% |
| Oppo | 4,73% |
| Tecno | 4,67% |
| Vivo | 4,46% |
| Motorola | 4,23% |
| RealMe | 3,57% |
| Honor | 2,32% |
| Itel | 0,94% |
| LG | 0,94% |
| Nokia | 0,63% |
| OnePlus | 0,60% |
| ZTE | 0,35% |
| Alcatel | 0,23% |
| Asus | 0,23% |
| Google | 0,15% |
| Umidigi | 0,15% |
| Lenovo | 0,12% |
| Sony | 0,09% |
| Spark | 0,09% |
| Hisense | 0,07% |
| iPad | 0,04% |
| Ulefone | 0,03% |

<a name="cont"></a>
# Content
### The folder **"samples"** includes 30 folders:
- corresponding to each person in the sample
- containing of selfie and video of the individual

### File with the extension .csv
includes the following information for each media file:
- **phone**: the device used to capture the media files,
- **selfie_link**: the URL to access the photo
- **video_link**: the URL to access the video
- **worker_id**: the identifier of the person who provided the media file,
- **age**: the age of the person,
- **country**: the country of origin of the person,
- **gender**: the gender of the person,
- **selfie_file_type**: the type of the photo,
- **video_file_type**: the type of the video

<a name="getdat"></a>
# Get the Dataset
This is just an example of the data. If you need access to the entire dataset, contact us via [sales@trainingdata.pro](mailto:sales@trainingdata.pro) or leave a request on **[trainingdata.pro/data-market](https://trainingdata.pro/data-market?utm_source=github)**



<a name="link"></a>
# Links
| Resource | Link |
| --- | --- |
| TrainingData.pro | [trainingdata.pro/data-market](https://trainingdata.pro/data-market?utm_source=github) |
| Kaggle | https://www.kaggle.com/trainingdatapro |
| HuggingFace | https://huggingface.co/TrainingDataPro |


