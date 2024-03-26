# Hotspot-Detection
This Repo Contains the Source Code and Pretrained Model for the Paper "Algorithm for Imbalanced Hotspot Detection based  on Capsule Network and Data Augmentation".
# Dependencies
pytorch(tested on2.1.0),torchvision,numpy,matplotlib,cv2,sklearn,collections,os,time,random,BottleStack,tqdm,logging
# Content
.
│  dataset       Iccad dataset
├─data_augment   Three methods used for data augmentation         
│      geo_aug
│      rep_aug
│      wgan_aug
|  model          The currently provided pre-trained models.
│  src            Evaluating the performance of a hotspot detector          
# Test
`python main.py --dataset<name>  --dataset_dir<dir_path>  --model<model_path>  --batch_size<batch_zie> --logdir<logdir_path> `
# Other
In the future, we will continue to release the source code openly.
