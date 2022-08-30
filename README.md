# Video-based Cross-modal Auxiliary Network for Multimodal Sentiment Analysis
The video-based cross-modal auxiliary network (VCAN) consists of two components: the Audio Feature Map Module (AFMM), which enhances multi-scale acoustic sentiment representation; and the Cross-Modal Selection Module (CMSM), which aims to improve the interactivity of audiovisual modalities and eliminate redundant computations.

Code for the TCSVT paper [Video-based Cross-modal Auxiliary Network for Multimodal Sentiment Analysis](https://ieeexplore.ieee.org/document/9852463)

![Fig 1  The overall framework of the Video-based Cross-modal Auxiliary Network (VCAN)](https://user-images.githubusercontent.com/50829408/187387055-3fb21d0b-fcbf-4f5d-b76f-ebfed7aea032.png)

## Gettinf Started
These instructions will providee you with a core copy of the VCAN. you can adapt it and run on your local machine for development and testing purposes. This model runs on a Windows system using the PyCharm Community Edition. See deployment for notes on how to deploy the project on a live system.

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
You must run the AFMM and the CMSM in order after installing the aforementioned packages. 
As shown in Figure 1 in the paper, the output of AFMM is part of the input of CMSM, thus 


## citation

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

## Running the tests

The encrypted code available for testing can be downloaded.
You can use this [https URL](https://cloud.189.cn/t/uaeeiavmuQ3u)（访问码：n3n7) or [pCloud URL](https://u.pcloud.link/publink/show?code=XZQr58VZRzrGxsst1yJoCA8WoKEs3SXMLoU7) to download the algorithm demo.   

## Images displayed in paper

20 images displayed in the paper can be downloaded at this [https URL](https://cloud.189.cn/web/share?code=qymAJzayuei2)（访问码：mgj4）or [pCloud URL](https://u.pcloud.link/publink/show?code=XZCNfHVZ4MYNMM5C8Buy29FaHGdDJh6tSYzV) (size = 13.51MB). 


## Modified version of HDR dataset

250 pairs of images in HDR dataset can be downloaded at this [https URL](https://cloud.189.cn/web/share?code=NZ7ZZbjeuAVz) or [pCloud URL](https://u.pcloud.link/publink/show?code=XZ2NfHVZChgPglepTRLgNkuMHbULgB9Ja2bV) (size = 352MB).

The zip file contains two folders, the 'lowlight' folder and the 'Refimg' folder.

'lowlight' folder contains 250 images under low light.

'Refimg' folder contains 250 images under normal light.

Note: 

1.Please do not change the serial number of the images. They correspond to each other. e.g.  'HDRR(1).PNG' is the reference image under normal illumination of 'HDRL(1).PNG'.

2.Please [click this address](https://live.ece.utexas.edu/research/HDRDB/hdr_index.html) to see more about the original HDR dataset.


## citation

If you think the data set and code we collate are helpful for your research, please cite:

```

@article{CDEF,
  title={Low-light Image Enhancement Using the Cell Vibration Model},
  author={Xiaozhou Lei, Zixiang Fei, Wenju Zhou, Huiyu Zhou and Minrui Fei},
  journal={IEEE Transactions on Multimedia},
  year={2022}
  month={05}
  day={19}
  doi={10.1109/TMM.2022.3175634}
}


```

