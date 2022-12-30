# stable--diffusion-algorithm-machine-learning
this algorithimic program is used to convert text to image
this program will definetly require a "cuda" in your system 
If cuda is not pesent you will get a certain errors such as 
 ***raise AssertionError("Torch not compiled with CUDA enabled")
AssertionError: Torch not compiled with CUDA enabled***
at you last line of error
To check whether the cude is present in your system:
*open your powershell terminals on vs code
>> python
>>import torch
>> torch.cuda.is_available()
if False the cuda is not present in your system
