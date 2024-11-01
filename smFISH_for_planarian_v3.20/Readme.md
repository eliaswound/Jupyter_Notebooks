This is Elias Guan from Christian Petersen Lab at Northwestern University. 
This code is effective and developed in 10/30/2024. 
Further updates/help/functional debugging please contact qingxuguan2020@u.northwestern.edu.
----------------------------------------------------------------------------------------------------------
Installing instructions:

This code is based on two major packages, Stardist and bigfish/fish-quant. 
My recommendation is either for apple/mac users and windows/linux users please try to install stardist first. 

Please Refer to https://github.com/stardist/stardist to install stardist for your own platform. 
Also apple silicion (Mac with chip M1 or other M serires) refer to https://pypi.org/project/tensorflow-metal/ 
do version check using pip show tensorflow and pip show tensorflow-metal to check your version. 
If they do not match what you get from the previous link in pypi, please use pip install tensorflow==version 
To down/upgrade your tensorflow to fit the current metal, or the nuclei segmentation will not work. 

----------------------------------------------------------------------------------------------------------------
Input instructions: 

For now I will provide two types of input: 
You can run ordered input and unordered input. 
For ordered input, all images must be ending with channel names. For example, you should name all your images with ending 
like Image1_633.tif or Image2_633.tif for all 633 channels, same idea will apply to 565 and 405 channels. 
unordered input will give you prompt to jump out a window to selecte file you want to run each time. 