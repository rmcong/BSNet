# BSNet-TCE2022
Runmin Cong, Yumo Zhang, Ning Yang, Haisheng Li, Xueqi Zhang, Ruochen Li, Zewen Chen, Yao Zhao, and Sam Kwong, Boundary guided semantic larning for real-time COVID-19 lung infection segmentation system, IEEE Transactions on Consumer Electronics, 2022.

* Results:
  - We provide the resutls of our BSNet on the merged dataset. 
```
Baidu Cloud: https://pan.baidu.com/s/1E9etJ1lPCGsHuZW_LbwdYw  Password: 1234
```
* Pretrained model:
  - We provide our testing code. If you test our model, please download the pretrained model, unzip it, and put the checkpoint `BSNet.pth` to `weights/` folder.
  - Pretrained model download:
```
Baidu Cloud: https://pan.baidu.com/s/1f3xn1pr7unIIZ1_6xRnqHg  Password: 1234
```

# Data Preprocessing
If you test our model, please download the testing subset of merged dataset, and put the data to `TestingSet/` folder.
* Testing subset of merged dataset:
```
Baidu Cloud: https://pan.baidu.com/s/1qNE82vL9gT4qmc_9_PeKFg  Password: 1234
```

# Test
please run the following code for a quick start:
```
python test.py
```


# If you use our BCS-NET, please cite our paper:

    @article{crm/tce22/covid,
     author    = {Runmin Cong and Yumo Zhang and Ning Yang and Haisheng Li and Xueqi Zhang and Ruochen Li and  Zewen Chen and Yao Zhao and Sam Kwong},
     title     = {Boundary guided semantic larning for real-time {COVID-19} lung infection segmentation system},
     journal   = {IEEE Trans. Consum. Electron.},
     year      = {early access, doi: 10.1109/TCE.2022.3205376},
    }

# Contact Us:
If you have any questions, please contact Runmin Cong (rmcong@bjtu.edu.cn).
