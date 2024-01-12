English | [简体中文](README_cn.md)

<h2 align="center">HFMRE: Constructing Huffman Tree in Bags to Find Excellent Instances for Distantly Supervised Relation Extraction</h2>
<p align="center">
<!--     <a href="https://github.com/lyuwenyu/RT-DETR/blob/main/LICENSE">
        <img alt="license" src="https://img.shields.io/badge/LICENSE-Apache%202.0-blue">
    </a> -->
    <a href="https://github.com/shaocong-qy/HFMRE/main/LICENSE">
        <img alt="license" src="https://github.com/shaocong-qy/HFMRE">
    </a>
    
    <a href="mailto: 10431220590@stu.qlu.edu.cn">
        <img alt="emal" src="https://img.shields.io/badge/contact_me-email-yellow">
    </a>
</p>



## Introduction

XXX（模型介绍）

<div align="center">
  <!-- <img src="https://github.com/qluinfo/HFMRE/blob/main/HFMRE_model.png" width=300 /> -->
  <img src="https://github.com/qluinfo/HFMRE/blob/main/HFMRE_model.png" width=500 >
</div>



---
<details>
<summary>Fig</summary>
![ppdetr_overview](https://github.com/lyuwenyu/RT-DETR/assets/17582080/737f0d94-e028-4793-967e-201bdde57a5a)
</details>

This paper was published in ***CVPR2023*** and is titled "[论文名称](论文地址)".




## Result

（根据自己的结果修改下图）

|       Model       | Epoch | Input shape |      Dataset      | $AP^{val}$ | $AP^{val}_{50}$ | Params(M) | FLOPs(G) |
| :---------------: | :---: | :---------: | :---------------: | :--------: | :-------------: | :-------: | :------: |
|    RT-DETR-R18    |  6x   |     640     |       COCO        |    46.5    |      63.8       |    20     |    60    |
|    RT-DETR-R34    |  6x   |     640     |       COCO        |    48.9    |      66.8       |    31     |    92    |
|   RT-DETR-R50-m   |  6x   |     640     |       COCO        |    51.3    |      69.6       |    36     |   100    |
|    RT-DETR-R50    |  6x   |     640     |       COCO        |    53.1    |      71.3       |    42     |   136    |
|   RT-DETR-R101    |  6x   |     640     |       COCO        |    54.3    |      72.7       |    76     |   259    |
| RT-DETR-HGNetv2-L |  6x   |     640     |       COCO        |    53.0    |      71.6       |    32     |    11    |
|    RT-DETR-R18    |  5x   |     640     | COCO + Objects365 |  **49.2**  |    **66.6**     |    20     |    60    |
|    RT-DETR-R50    |  2x   |     640     | COCO + Objects365 |  **55.3**  |    **73.4**     |    42     |   136    |
|   RT-DETR-R101    |  2x   |     640     | COCO + Objects365 |  **56.2**  |    **74.6**     |    76     |   259    |

**Notes:**
- 填写结果中的细节信息（选填）



## Quick start

<details>
<summary>Install</summary>

```bash
pip install -r requirements.txt
```

</details>



<details>
<summary>Data</summary>

- download_nyt10.sh
- download_nyt10m.sh
- download_wiki20m.sh

</details>



<details>
<summary>Training & Evaluation</summary>

```shell
# training 
train_nyt10d.sh
train_nyt10m.sh
train_wiki20m.sh
```

```shell
# evaluation
(填写测试的指令)
```

</details>



<details>
<summary>Export</summary>

```shell
（填写导出结果的指令）
```
</details>



<details open>
<summary>Train custom data</summary>
（填写训练自定义数据的流程）



## Citation
If you use `模型名称` in your work, please use the following BibTeX entries:
```
（填写自己的BibTeX）
```
