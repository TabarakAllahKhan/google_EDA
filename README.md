# About the Dataset

>Aurthor: Tabarak Allah Khan\
Date: 1-24-2025

The Dataset is gathered from the following [Link](https://www.kaggle.com/datasets/lava18/google-play-store-apps/)

# _**Dataset Cols Explaination**_

The dataset I used is `googleplaystore` the dataset containes 13 cols. Here is the explaination of Each Col of the dataset



| Column Name | Description | Data Type |
|---|---|---|
| **App** | Name of the App on the Google Playstore | Object |
| **Category** | The Type of app like entertainment , Sport,For Adults | Object |
| **Rating** | The Rating given to the app by the users | Float |
| **Reviews** | The number of reviews given to the particular app | Object |
| **Size** | The installation memory size of the app  | Object |
| **Installs** | The Total number of installs of the app | Object |
| **Type** | The type of app like paid or free | Object |
| **Price** | The price of the app if it is free type it is 0 and if it is paid the price will be written | Object |
| **Content Rating** | The content rating of the app | Object |
| **Genres** | The Genres of the app (`Containes same entries as the Category column`) | Object |
| **Current Ver** |  The current version of the app | Object |
| **Android ver** | The minimum android version required to run the app | Object |


> ## To Use The Note Book You Need Following Libraries

+ `pandas` for data manipulation and analysis
+ `Seaborn` for data visualization
+ `ydata prfiling` for genrating the dataset report 






_**Pandas installation**_
```python
pip install pandas

```

_**Sea born installation**_
```python
pip install seaborn

```


_**ydata Profiling installation**_

```python
pip install ydata-profiling

```

> ## Important Note

It is advised to create a seprate conda enviroment for ydata-profiling if you have either Anaconda or Miniconda installed on your system.
