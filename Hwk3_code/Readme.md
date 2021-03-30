This code was an extention of https://github.com/NVIDIA-AI-IOT/trt_pose and https://github.com/NVIDIA-AI-IOT/trt_pose/pull/4/commits/136e053f0b9ae895752b09a13a48d2e10f1ca692

From the first website, download the resnet18_baseline_att_224x224_A and densenet121_baseline_att_256x256_B.
Make sure these files and the python script are located in the same file.
Using jupyter lab, run through it until you get the the torch.save. You can try contiuning but in my case the jetcam refuse to work in the live demo.
Run the python sript and this should work.

If you are still having issues, try following this: https://spyjetson.blogspot.com/2019/12/jetsonnano-human-pose-estimation-using.html
