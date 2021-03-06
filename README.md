# Deep Back-Projection Networks for Super-Resolution (CVPR2018)

## Winner (1st) of [NTIRE2018](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w13/Timofte_NTIRE_2018_Challenge_CVPR_2018_paper.pdf) Competition (Track: x8 Bicubic Downsampling)

## Winner of [PIRM2018](https://arxiv.org/pdf/1809.07517.pdf) (1st on Region 2, 3rd on Region 1, and 5th on Region 3)

Project page: http://www.toyota-ti.ac.jp/Lab/Denshi/iim/members/muhammad.haris/projects/DBPN.html


Pretrained models can be downloaded from this link!
https://drive.google.com/drive/folders/1ahbeoEHkjxoo4NV1wReOmpoRWbl448z-?usp=sharing

It contains 4 files:
(1) DBPN_x2.pth, (2) DBPN_x4.pth, (3) DBPN_x8.pth are from the original architecture (CVPR2018).

(4) NTIRE2018_x8.pth is used for NTIRE2018 competition (Track 1: Classic Bicubic x8)

We also provide original [Caffe implementation](https://github.com/alterzero/DBPN-caffe)

##########HOW TO##########

#Training

    ```python3
    main.py
    ```

#Testing

    ```python3
    eval.py
    ```

![DBPN](http://www.toyota-ti.ac.jp/Lab/Denshi/iim/members/muhammad.haris/projects/DBPN.png)

## Citations
If you find this work useful, please consider citing it.
```
@inproceedings{DBPN2018,
  title={Deep Back-Projection Networks for Super-Resolution},
  author={Haris, Muhammad and Shakhnarovich, Greg and Ukita, Norimichi},
  booktitle={IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2018}
}
```
