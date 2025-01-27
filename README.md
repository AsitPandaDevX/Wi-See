# Wi-See: Edge Wi-Fi Based Human Presence Sensing 🛜

Wi-Fi Based Human Presence Sensing for Privacy-Free Indoor Surveillance: This repository includes the code, datasets, and documents to create Wi-Fi-based systems for detecting and tracking indoor people. It uses Wi-Fi Channel State Information (`CSI_DATA`) signals and Deep Neural Networks (`DNNs`) to sense or detect human presence.



## Collecting CSI Data

* Use the [ESP32-CSI-Tool](https://github.com/StevenMHernandez/ESP32-CSI-Tool) for `CSI_DATA` collection.
* Follow the [ESP-IDF Programming Guide](https://docs.espressif.com/projects/esp-idf/en/release-v4.3/esp32/get-started/index.html) for a step-by-step backend installation.
* Finally, configure and build the project to flash it onto both ESP32 devices and monitor the `CSI_DATA`.

## Clone the Repository
To get started, clone this repository to your local machine or google drive using the following command:

```bash
git clone https://github.com/AsitPandaDevX/Wi-See.git
```

## Datasets⚠️(Available upon request!)

### Training
* [Wi-See](https://drive.google.com/drive/folders/1h4GPwkVPubNbSZTT0XTWdMcaFHULZhvZ?usp=drive_link) > [CSI_Training_Data](https://drive.google.com/drive/folders/1Sa8mVgmFoF8lAcrOV9FhMOoCU1UnqkGc?usp=drive_link) 
* Copy the `CSI_Training_Data` folder directly to your local machine or Google Drive.

### Testing (Unseen Dataset)

* [Wi-See](https://drive.google.com/drive/folders/1h4GPwkVPubNbSZTT0XTWdMcaFHULZhvZ?usp=drive_link) > [CSI_Test_Data](https://drive.google.com/drive/folders/1HxZY3fRLMox7MgIfYmDjMgGSZptE1Y5V?usp=drive_link)
* Copy the `CSI_Test_Data` folder directly to your local machine or Google Drive.

### Sample Dataset (for testing purpose)✅

* A sample dataset (for testing purposes) is available in the repository under the `sample_test_csi_data` folder.

### Trained Model✅

* Two pre-trained LSTM models (trained with different window sizes of 200 & 300) are available in the repository under the `trained_model` folder.
* These pre-trained models are available in `.h5` format. However, for new training the models can be trained and saved in `.keras` format.



## Training Phase

* Find `1-model_training.ipynb` inside the `Colab Notebooks` folder to run the Python scripts in each cell of the notebook.
* Check & update the correct `Path` of `CSI_Training_Data` folder.

## Testing Phase

* Find `1-model_test.ipynb` inside the `Colab Notebooks` folder to run the Python scripts in each cell of the notebook.
* Check & update the correct `Path` of `CSI_Test_Data`>`np_person` or `with_person` folder one by one.

## About Project and Datasets

* This research project was guided by [Dr. Sabarimalai Manikandan](https://iitpkd.ac.in/people/msm)
* The datasets were jointly prepared by [Jatin Sadhwani](https://in.linkedin.com/in/jatin-s13) and [Asit Panda](https://github.com/AsitPandaDevX)
* This repository can be run on both local machine and cloud drives, which makes it flexible for further development and testing (offline & real-time) purposes.

## Research Publications

1. https://doi.org/10.1109/ECAI52376.2021.9515148
2. https://doi.org/10.1109/ICMOCE57812.2023.10166072

## Citations
If you find this repository helpful, please consider citing our work and giving the project a star ⭐ on GitHub! Your support helps us improve and maintain this project.

* [[Cite this Repo with BibTeX]](https://github.com/AsitPandaDevX/Wi-See/blob/main/Docs/bibtex/repo1.bib)
* [[Cite Publication-2]](https://github.com/AsitPandaDevX/Wi-See/blob/main/Docs/bibtex/pub2.bib)
* [[Cite Publication-1]](https://github.com/AsitPandaDevX/Wi-See/blob/main/Docs/bibtex/pub1.bib)

