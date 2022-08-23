# Deeply Vocal Characterizer Dataset
---
## Summary
The Vocal Characterizer Dataset is <u>*__a human nonverbal vocal sound dataset__*</u> consisting of <u>*__56.7 hours__*</u> of short clips from <u>*__1419 speakers__*</u>, crowdsourced by the general public in South Korea. Also, the dataset includes metadata such as age, sex, noise level, and quality of utterance. 16 classes of Included human nonverbal sound contain <u>*__‘teeth-chattering’, ‘teeth-grinding’, ‘tongue-clicking’, ‘nose-blowing’, ‘coughing’, ‘yawning’, ‘throat clearing’, ‘sighing’, ‘lip-popping’, ‘lip-smacking’, ‘panting’, ’crying’, ‘laughing’, ‘sneezing’, ‘moaning’, and ‘screaming’.__*</u>

  **Device** | **Android phones** |
  :-:|:-:|
  **Volume(Sample)** | **\~ 57(~ 3) hours, ~ 70,000(~ 3,600) utterances,<br /> ~ 18(~ 0.5) GB, ~ 1500(~ 730) speakers** |
  **Format** | **wav/h5(16/44.1kHz, 16-bit, mono)** |


Refer to the dataset descriptions in 'Document' for detailed description and statistics of the full set of the dataset.

The dataset is a subset(approximately 5%) of a much bigger dataset which were recorded under the same circumstances as these open source datasets. Please visit our website(http://deeplyinc.com/) or contact us for the full set with commercial license.

## Dataset statistics
The illustrations below are the statistics about the Deeply Vocal Characterizer dataset. The first two are from the sample dataset, And the others are from the full dataset. To attain more insight about the dataset, please refer to the detailed description in 'Document'.

<p float="left">
  <img src="https://github.com/deeplyinc/Deeply-Dataset/blob/main/etc/Vocal%20Characterizer/fig0.png" width="500" />
  <img src="https://github.com/deeplyinc/Deeply-Dataset/blob/main/etc/Vocal%20Characterizer/fig1.png" width="500" /> 
</p>
<p float="left">
  <img src="https://github.com/deeplyinc/Deeply-Dataset/blob/main/etc/Vocal%20Characterizer/fig2.png" width="500" />
  <img src="https://github.com/deeplyinc/Deeply-Dataset/blob/main/etc/Vocal%20Characterizer/fig3.png" width="500" /> 
</p>
  <img src="https://github.com/deeplyinc/Deeply-Dataset/blob/main/etc/Vocal%20Characterizer/fig4.png" width="1000" /> 

## Structure
```
├── Dataset
│   ├── Vocal_Characterizer_metadata.json
│   ├── coughing
│   │   ├── 0C1S_4_8_0_27_0_1_1.wav
│   │   ├── ...
│   ├── crying
│   │   ├── 1TCO_11_10_0_20_0_0_0.wav
│   │   ├── ...
│   ├── ...
│   ├── ...
│   ├── tongue-clicking
│   │   ├── 06RU_2_7_1_38_0_0_0.wav
│   │   ├── ...
│   └── yawning
│       ├── 0DYI_5_10_1_12_0_1_0.wav
│       ├── ...
└── Document
    ├── Deeply\ Vocal\ Characterizer\ Dataset\ description_Eng.pdf
    └── Deeply\ Vocal\ Characterizer\ Dataset\ description_Kor.pdf
```

```
Vocal_Characterizer_metadata.json
{
    'LAA7': {'sex': 'Male',
    'age': 22,
    'class': ['teeth-chattering', 'teeth-grinding', 'lip-smacking']},
    ...
    'WVST': {'sex': 'Female',
    'age': 15,
    'class': ['nose-blowing','coughing','yawning','throat-clearing','sighing',
    'lip-popping','sneezing','screaming']}
}
```

### Filename convention
{speaker_ID}\_{class}\_{trial}\_{sex}\_{age}\_{location}\_{quality}\_{noise}.wav
```
Class: {0: ‘teeth-chattering’, 1: ‘teeth-grinding’, 2: ‘tongue-clicking’, 3: ‘nose-blowing’, 
    4: ‘coughing’, 5: ‘yawning’, 6: ‘throat-clearing’, 7: ‘sighing’, 8: ‘lip-popping’, 
    9: ‘lip-smacking’, 10: ‘panting’, 11: ‘crying’, 12: ‘laughing’, 13: ‘sneezing’, 14: ‘moaning’, 15: screaming’}
Sex: {0: ‘Female’, 1: ‘Male’}
Location: {0: ‘indoor’, 1: ‘outdoor’}
Quality: {0: ‘High’, 1: ‘Low’}
Noise: {0: ‘Noiseless’, 1: ‘Noisy’}
```

## License
Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)  
![Vue](https://github.com/deeplyinc/Deeply-Dataset/blob/main/etc/by-nc-nd.png)

## Contact
Tel:   (+82) 70-7459-0704  
Web:   http://deeplyinc.com/  
Email: contact@deeplyinc.com

