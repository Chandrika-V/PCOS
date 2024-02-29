# Auto-PCOS Classification Challenge

#### Team Name: PCOS_Helper

#### Team members name and Affiliation

| Members | Member Name | Affiliation |
|----------|----------|----------|
| Member 1   | Abhishek  | NIT Durgapur  |
| Member 2 | Chandrika  | NIT Durgapur  |
| Member 3 | Arjo Kundu  | NIT Durgapur  |
| Member 4 | Soumik Roy   | NIT Durgapur  |

#### Contact Number: +91 9494849124
#### Email address: chandrikavengala@gmail.com

#### Brief write up about the pipeline:
Our model consists of 17-Convolution layers, 5-MaxPool layers and 3-Inception Modules followed by 3-fully connected layers.
The first inception module consists of 4 parallel convolution opearations with (1x1), [(1x1), (3x3)], [(1x1), (5x5)], [(1x1), (7x7)] kernel-sizes respectively followed by (2x2) MaxPooling layer.
The Second inception module consists of 3 parallel convolution opearations with (3x3), (5x5), (7x7) kernel-sizes respectively followed by (2x2) Maxpooling layer.
The Third inception module consists of 3 parallel convolution opearations with (9x9), (13x13), (15x15) kernel-sizes respectively followed by (2x2) Maxpooling layer.

#### Figure of the developed pipeline:
<img width="650" alt="CNN_Architecture" src="https://github.com/Chandrika-V/PCOS/assets/161706175/c785eb69-d633-47df-aeec-cc40be59b165">

### Achieved results on validation dataset:
#### Accuracy on training and validation dataset for automatic classification of healthy and un-healthy frames in ultrasound imaging:
<img width="473" alt="Accuracy" src="https://github.com/Chandrika-V/PCOS/assets/161706175/6845903a-1708-46da-b5bc-683daafa9da4">

#### Pictures (resolution 600 DPI) of any 5 best frames selected from validation dataset showing its classification:

| ![1](https://github.com/Chandrika-V/PCOS/assets/161706175/dd2b3aef-46a8-4747-bfbc-bc9fcbf03322)   | ![2](https://github.com/Chandrika-V/PCOS/assets/161706175/7b3e4d2a-f95d-4b53-bebc-52b77effb8ff)  | 
| ![3](https://github.com/Chandrika-V/PCOS/assets/161706175/a6ab516a-cec8-4dda-80cb-1174b026d68b) | ![4](https://github.com/Chandrika-V/PCOS/assets/161706175/26f49a83-11b5-4408-83e9-ea0bded38be2)  | 


