# FcvU
 We also trained ResNet-34 on the CIFAR-10 dataset and plotted the number of steps and the SFO complexities of SGD using the Armijo or constant condition for batch sizes smaller than 
. Please see https://anonymous.4open.science/r/FcvU-6354/ for details.

 We plotted the number of function calculations when using the Armijo or constant condition. When using the constant condition, it is the number of parameter updates. When using the Armijo condition, it is the sum of the number of parameter updates and the number of times that the Armijo condition was not satisfied in backtracking. Please see https://anonymous.4open.science/r/FcvU-6354/ for a detail.

 We checked the critical batch sizes for different values $\epsilon$
 and plotted the SFO complexities of SGD with the Armijo condition or a constant one when training loss is 0.001 or 0.1. We can see that, the smaller training loss is, the larger the critical batch size becomes. Please see https://anonymous.4open.science/r/FcvU-6354/
