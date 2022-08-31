# Video-based Cross-modal Auxiliary Network for Multimodal Sentiment Analysis
The video-based cross-modal auxiliary network (VCAN) consists of two components: the Audio Feature Map Module (AFMM), which enhances multi-scale acoustic sentiment representation; and the Cross-Modal Selection Module (CMSM), which aims to improve the interactivity of audiovisual modalities and eliminate redundant computations.

Code for the TCSVT paper [Video-based Cross-modal Auxiliary Network for Multimodal Sentiment Analysis](https://ieeexplore.ieee.org/document/9852463)

![Fig 1  The overall framework of the Video-based Cross-modal Auxiliary Network (VCAN)](https://user-images.githubusercontent.com/50829408/187387055-3fb21d0b-fcbf-4f5d-b76f-ebfed7aea032.png)

## Getting Started
These instructions will providee you with a core copy of the VCAN. you can adapt it and run on your local machine for development and testing purposes. This model runs on a Windows system using the PyCharm Community Edition. See following deployment for notes on how to deploy the project on a live system.

### Prerequisites and Installing
What things you need to install the software and how to install them. you can download the [reuqirements.txt](https://drive.google.com/file/d/17iI_7iU2VYjPoos_vOjsOtGWZcYNNNvE/view?usp=sharing) to install the repated packages.
The list of some important installation packages is as follows:

```
--emd==0.4.0
--librosa==0.8.1
--scikit-learn==0.24.2
...
```

## Running the tests
We only provide the core code of the model, but for the data preprocessing and classification network part of the code is not available. If you need the corresponding demos, please refer to this [repository](https://github.com/WZMIAOMIAO/deep-learning-for-image-processing)

As shown in Fig.1. in the paper, the output of AFMM is part of the input of CMSM, you must run the AFMM and the CMSM in order after installing the aforementioned packages, i.e.,

1. data pre-processing. the adjustment of data types, data structures and  corresponding labels.
2. Run the AFMM to generate three MEL-spectrams (three kinds of audio feature sequences), which is the acoustic feature input part of CMSM.
3. Run the CMSM and output the filtered video keyframes
4. Classify video keyframes (images) using designed classifiers or a cooperative classifier group.

### Dataset 

You need to declare the related citations if you use the following datasets as benchmark datasets for your papers

1. [RAVDESS](https://zenodo.org/record/1188976#.YFZuJ0j7SL8)
2. [CMU-MOSI](http://multicomp.cs.cmu.edu/resources/cmu-mosi-dataset/)
3. [CMU-MOSEI](http://multicomp.cs.cmu.edu/resources/cmu-mosei-dataset/)

## Note

1. We provide a simple [demo](https://drive.google.com/drive/folders/1NoRldhJbrmzzt7Fnn7rmMT-x42k3ACtY?usp=sharing) of the basic raw data pre-processing so that users can easily adjust the data structure.
2. The cooperative classifier group mentioned in our paper is consisted of different CNN models, and users can retrieve the source code from the corresponding papers or refer to this [URL](https://github.com/WZMIAOMIAO/deep-learning-for-image-processing).
3. If you have any questions about using VCAN, please contact me by email (chenrongfei@shu.edu.cn) 

## Citation

If you think the data set and code we collate are helpful for your research, please cite:

```
@article{chen2022video,
  title={Video-based Cross-modal Auxiliary Network for Multimodal Sentiment Analysis},
  author={Chen, Rongfei and Zhou, Wenju and Li, Yang and Zhou, Huiyu},
  journal={IEEE Transactions on Circuits and Systems for Video Technology},
  year={2022},
  publisher={IEEE}
}

```
