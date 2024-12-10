# Wi-See: Edge Wi-Fi Based Human Presence Sensing 🛜

Wi-Fi Based Human Presence Sensing for Privacy-Free Indoor Surveillance: This repository includes the code, datasets, and documents to create Wi-Fi-based systems for detecting and tracking indoor people. It uses Wi-Fi Channel State Information (`CSI_DATA`) signals and Deep Neural Networks (`DNNs`) to sense or detect human presence.



## Collecting CSI Data

* For `CSI_DATA` Collection follow [ESP32-CSI-Tool](https://github.com/StevenMHernandez/ESP32-CSI-Tool).
* Follow [ESP-IDF Programming Guide](https://docs.espressif.com/projects/esp-idf/en/release-v4.3/esp32/get-started/index.html) for the step by step backend installation. 
* Finally, configure and build the project to flash them on to both ESP32 devices and monitor `CSI_DATA`.

## Clone the Repository
To get started, clone this repository to your local machine or google drive using the following command:

```bash
git clone https://github.com/AsitPandaDevX/Wi-See.git
```

## Datasets

* [Wi-See](https://drive.google.com/drive/folders/1h4GPwkVPubNbSZTT0XTWdMcaFHULZhvZ?usp=drive_link) > [CSI_Training_Data](https://drive.google.com/drive/folders/1Sa8mVgmFoF8lAcrOV9FhMOoCU1UnqkGc?usp=sharing)
* Copy the `CSI_Training_Data` folder directly in your local machine or google drive.
* Check and verify the correct `Path` of `CSI_Training_Data` folder.

## Training

* Find `1-model_training.ipynb` inside Colab Notebooks folder, to run `python` scripts in each cell of the notebook.
* Update the correct `Path` of `CSI_Training_Data` folder.
* This repository can be run on both local machine and cloud drives, which makes it flexible for further development and testing purposes.

## About Project and Datasets

* This research project was guided by [Dr. Sabarimalai Manikandan](https://iitpkd.ac.in/people/msm)
* The datasets were jointly prepared by [Jatin Sadhwani](https://in.linkedin.com/in/jatin-s13) and [Asit Panda](https://github.com/AsitPandaDevX)

## Research Publications

1. https://doi.org/10.1109/ECAI52376.2021.9515148
2. https://doi.org/10.1109/ICMOCE57812.2023.10166072

## Citations
If you find this repository helpful, please consider citing our work and giving the project a star ⭐ on GitHub! Your support helps us improve and maintain this project.

* [[Cite this Repo with BibTeX]](https://github.com/AsitPandaDevX/Wi-See/blob/main/Docs/bibtex/repo1.bib)
* [[Cite Publication-2]](https://github.com/AsitPandaDevX/Wi-See/blob/main/Docs/bibtex/pub2.bib)
* [[Cite Publication-1]](https://github.com/AsitPandaDevX/Wi-See/blob/main/Docs/bibtex/pub1.bib)

