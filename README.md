BDA-J-Component - Two Way Sign Language Convertor using Deep Learning

This repository provides Jupyter Notebook-based tools for:

Sign Language to Text/Speech Conversion.
Speech/Text to Sign Language Conversion.
Both functionalities utilize machine learning and computer vision techniques, supported by relevant datasets.

Features
SignToTextSpeechConversion.ipynb: Processes sign language input and translates it into text or speech output.
SpeechTextToSignLanguageConversion.ipynb: Converts speech or text into sign language animations.
Requirements
Dependencies
Ensure Python 3.8+ is installed along with the following libraries:

tensorflow
numpy
opencv-python
matplotlib
Install dependencies:

```bash
pip install tensorflow numpy opencv-python matplotlib
```
Environment Setup
Clone the repository:
```bash
git clone https://github.com/SAIKRISHNA2005/BDA-J-Component.git
cd BDA-J-Component
```
Ensure you have Jupyter Notebook installed:
```bash
pip install notebook
```
How to Use
Running Notebooks
Open the notebooks using:
```bash
jupyter notebook
```
Select and open either:
SignToTextSpeechConversion.ipynb
SpeechTextToSignLanguageConversion.ipynb
Update Filepaths
Modify Dataset Paths: Locate and edit the dataset file paths in the code sections where files are loaded:
python
```bash
dataset_path = "path/to/sign_language_dataset1"
```
Update these paths based on your system.
Executing Code
Run the cells in the notebook sequentially to process data and view results.

Example Commands
Clone and Run Example:
```bash
# Clone repository
git clone https://github.com/SAIKRISHNA2005/BDA-J-Component.git
cd BDA-J-Component

# Open Jupyter Notebook
jupyter notebook SignToTextSpeechConversion.ipynb
```
Handling Issues
If you encounter issues:

Ensure file paths are correctly set.
Install missing dependencies using pip.
