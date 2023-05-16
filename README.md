# Cat-or-Dog-Image-Classification-Using-CNN-DL-

I started learning Deep Learning and it's my first project on it. I did took help from few youtube videos and documentations.

## DataSet Used

[dogs vs cats](https://https://www.kaggle.com/datasets/salader/dogs-vs-cats) 

![image](https://github.com/pat3rmars/Cat-or-Dog-Image-Classification-Using-CNN-DL-/assets/123369753/d581f2cc-af80-4d65-ae52-947c51132481)

## Requirements

* Kaggle Account
* Tensorflow
* Keras
* CV2

## Steps to get your kaggle.json (kaggle api) :

* Step-1: Goto Kaggle.com and sign in with your account.
* Step-2: Goto Your Profile -> Account -> API
* Step-3: Click on "Create New Token" and it will download 'kaggle.json'   which would contains the api linking to your kaggle account.

![image](https://github.com/pat3rmars/Cat-or-Dog-Image-Classification-Using-CNN-DL-/assets/123369753/963b3033-e796-4959-9bfc-b5332dadb208)


* Step-4: Goto the dataset, here you can either download( by clicking on the **Download** button ) or you can use the kaggle api to let google collab download it for you.

To use the API method, just Click on the 3 dots -> **Copy API Command**.

![image](https://github.com/pat3rmars/Cat-or-Dog-Image-Classification-Using-CNN-DL-/assets/123369753/1d3cb74a-26ef-4e2c-837d-55a992bf69c1)


Then , just put this into your notebook cell:

```
!mkdir -p ~/.kaggle

!cp kaggle.json ~/.kaggle

!the_api_command_you_just_copied
```

## Steps to install the required modules:

1. **Tensorflow**

    ```
    pip install tensorflow

    ```
    ```
    pip install tensorflow-gpu
    ```

2. **Keras**

    ```
    pip install keras
    ```
3. **OpenCV**

    ```
    pip install opencv-python

    ```
*Since I didn't had a powerful GPU in my system so I used Google Colab to run my notebook. It came pre-installed with the modules needed for the project.*

---


**Feel Free to use and explore my project.**

**Have a Good Day : )**
