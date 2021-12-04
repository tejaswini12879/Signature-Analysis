# Automatic Signature Stability Analysis And Verification Using Local Features

## Installation

Clone the repository [here](https://github.com/Digital-Image-Processing-IIITH/project-morphers.git).

```bash
   >>> git clone https://github.com/Digital-Image-Processing-IIITH/project-morphers.git
```

## Requisites
 - `opencv-contrib-python:` Contains implementation of SURF
 ```bash
    >>> pip3 install opencv-contrib-python==3.4.2.16

 ```
 
 - As the required version of opencv is dissolved and no longer available we moved to Google-Colab. All the installations are done within the code
 
 
## Usage

 - The project.ipynb can be run directly from Google colaboratory but make sure to give your Drive path to the datasets.All the paths in the code are mentioned in our perspective.


## Folders
 - `Documents:` Research Paper , Project Proposal and Project Presentaion
 - `Pickles:` Pickle files containing reference database and other intermediate values
 - `Plots:` Contains all generated plots
 - `Verification Data:` Contains the dataset created by our own signatures for verification.
 - `TestSet:` Test Set of 4NSigComp2010 Dataset
 - `TrainSet:` Train Set of 4NSigComp2010 Dataset

## Code File

 - `project.ipynb:`   The final code with Traing and test and also the verification part.
 - `Training.ipynb:` This code contains the traing part.
 - `classify_final.ipynb:` The Classification and Validation part
 - `creating a database.ipynb:` The feature extraction and database creation part.

## Dataset
Dataset and instructions to download can be found [here](http://www.iapr-tc11.org/mediawiki/index.php/ICFHR_2010_Signature_Verification_Competition_(4NSigComp2010)). TrainingSet and TestSet folders must be place in the repository's root folder

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
[Raja Vechalapu](https://github.com/rajamkv), [Mohit Pavan](https://github.com/mohitpavan123), [Tejaswini suma](https://github.com/tejaswini12879), [Gowtami](https://github.com/Gowthami-gongati).


## License
[MIT](https://choosealicense.com/licenses/mit/)

