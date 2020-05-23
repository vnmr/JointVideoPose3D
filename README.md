### 3D Human Pose Estimation
![Pose](pose.png)

This work extends [Pavllo '19](https://arxiv.org/abs/1811.11742) FAIR [VideoPose3D](https://github.com/facebookresearch/VideoPose3D)

|                   | Protocol #1   | Protocol #2   | Protocol #3  |
| ------------------| ------------- |---------------|--------------|
| [Pavllo '19](https://arxiv.org/abs/1811.11742) (CVPR) | 46.8          | 36.5          | 44.9         |
| [Chen'19](https://arxiv.org/abs/1904.05547) (CVPR)    | 46.8          | 41.6          | 50.3         |
| **Ours**              | **45.9**          | **35.9**      | **44.2**     |

|            | Velocity   |  Acceleration  |
| -----------| -----------|----------------|
| [Pavllo '19](https://arxiv.org/abs/1811.11742) (CVPR) | 2.83          | 2.44           |
| **Ours**       | **2.63**      | **2.12**       | 




**Requirements**
CUDA + 
Follow instructions at [VideoPose3D](https://github.com/facebookresearch/VideoPose3D)

```
pip3 install vg  # vector calculations (really shouldn't be needed)
pip3 install numpy==1.16.2 # pickle breaks later numpy releases
python run.py -e 80 -ch 2048 -k cpn_ft_h36m_dbb -arc 3,3,3,3,3 -bm #run with -ch 2048  and -bm flag ie:
```

**Model**
1.1 GB - please contact
