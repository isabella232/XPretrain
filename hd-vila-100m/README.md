# HD-VILA-100M Dataset

## What is HD-VILA-100M?
HD-VILA-100M is a large-scale, high-resolution, and
diversified video-language dataset to facilitate the multimodal representation learning. 

<p align="center">
<img src="figs/examples.png" alt="examples for hd-vila"/>
</p>
<p align="center">
<font size=2 color="gray">Examples of video clips and ASR generated transcriptions in the proposed HD-VILA-100M dataset.</font>
</p>

## Data statics
The dataset contains 3.1M videos in total with high-quality and distributed in 15 categories in balance.
<p align="center">
<img src="figs/statics.png" alt="statistics" width="60%"/>
</p>
<p align="center">
<font size=2 color="gray">The distribution of categories in HD-VILA-100M dataset.</font>
</p>

The details of our dataset are presented in the table below.
| Dataset | Domain |  #Video clips | #Sentence | Avg len(sec) | Sent len | Duration(h) | Resolution
| :-----| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| HD-VILA-100M | open | 100M | 100M | 13.4 | 32.5 | 371.5K | 720p |


## News

***03/02/2022***

HD-VILA was accepted by CVPR 2022.

## Download

You can download all the urls through this [link](./). We also offer all the timestamps to divide the videos into clips.

We will release all the code to download and process the data soon.


## License

The license of the collected dataset is [here](./LICENSE).

## Citing HD-VILA

If you find this dataset useful for your research, please consider citing our paper. :blush:

```bibtex
@inproceedings{xue2022hdvila,
    title={Advancing High-Resolution Video-Language Representation with Large-Scale Video Transcriptions},
    author={Xue, Hongwei and Hang, Tiankai and Zeng, Yanhong and Sun, Yuchong and Liu, Bei and Yang, Huan and Fu, Jianlong and Guo, Baining},
    booktitle={International Conference on Computer Vision and Pattern Recognition (CVPR)},
    year={2022}
}
```