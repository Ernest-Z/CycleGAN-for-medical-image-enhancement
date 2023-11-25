# CycleGAN

The framework of network is based on the paper below: 
[Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks](https://arxiv.org/pdf/1703.10593.pdf). 

Some changes are taken during learning, and matlab module folder is increased 


## Prerequisites
- tensorflow r1.1 or tensorflow 2.6
- numpy 1.11.0
- scipy 0.17.0
- pillow 3.3.0


### Train procession
```bash
python main.py --dataset_dir=med_image
```

### Test procession
```bash
python main.py --dataset_dir=med-image --phase=test --which_direction=AtoB
```

## References
- CycleGAN implementation, https://github.com/XHUJOY/CycleGAN-tensorflow
- Torch CycleGAN, https://github.com/junyanz/CycleGAN