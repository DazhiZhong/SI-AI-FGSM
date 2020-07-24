# SI-AI-FGSM

### Requirements 
* Python 3.6.5
* Tensorflow 1.12.0
* Numpy 1.15.4
* opencv-python 3.4.2.16
### Experiments
Download the  [data](https://drive.google.com/open?id=1CfobY6i8BfqfWPHL31FKFDipNjqWwAhS) and [pretrained models](https://drive.google.com/open?id=10cFNVEhLpCatwECA6SPB-2g0q5zZyfaw)

#### Running
* `python agi_fgsm.py`generate adversarial examples for inception_v3 using AGI-FGSM
* `python ri_fgsm.py` generate adversarial examples for inception_v3 using RI-FGSM
* `python ai_fgsm.py` generate adversarial examples for inception_v3 using AI-FGSM

### Acknowledgements
Code refer to [NAG attack](https://github.com/JHL-HUST/SI-NI-FGSM)
