# Inference Code for RetinaFace with MobileNet Backend in PyTorch

### Step 1:
```Shell
cd cython
python setup.py build_ext --inplace
```

### Step 2:
```Shell
python inference.py
```

### Evaluation(WIDERFACE):
Easy   Val AP: 0.8872715908531869
<br>
Medium Val AP: 0.8663337842229522
<br>
Hard   Val AP: 0.771796729363941
<br>

### Test Results:
<img src="https://github.com/bogireddytejareddy/retinaface-pytorch-inference/blob/master/test_results/t6.jpg" width="480" height="300">
<img src="https://github.com/bogireddytejareddy/retinaface-pytorch-inference/blob/master/test_results/t3.jpg" width="480" height="300">

### References:
@inproceedings{deng2019retinaface, title={RetinaFace: Single-stage Dense Face Localisation in the Wild}, author={Deng, Jiankang and Guo, Jia and Yuxiang, Zhou and Jinke Yu and Irene Kotsia and Zafeiriou, Stefanos}, booktitle={arxiv}, year={2019} }
