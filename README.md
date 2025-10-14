# MABe-Challenge-Social-Action-Recognition-in-Mice
A deep learning pipeline to detect and log complex mouse behaviour from video tracking data for the MABe challenge, hosted by Kaggle.

## Downloading the Dataset
The dataset can be downloaded and extracted using the official [Kaggle API](https://github.com/Kaggle/kaggle-api) in the command line.
```
kaggle competitions download -c MABe-mouse-behavior-detection
```
To unzip the files:

```
python -c "import zipfile; zip_ref = zipfile.ZipFile('MABe-mouse-behavior-detection.zip', 'r'); zip_ref.extractall('.'); zip_ref.close()"
```
