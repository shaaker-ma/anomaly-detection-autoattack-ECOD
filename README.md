There are 3 files to run for this project:

1. Implementation_on_CIFAR10.ipynb
2. Implementation_on_CIFAR100.ipynb
3. AnomalyDetection.ipynb

To successfully run this project please follow these steps in order below. 

1. Generating Anomaly data for CIFAR10:

1.1 Run "Implementation_on_CIFAR10.ipynb" completely

1.2 You can see that in the directory of your workspace, there is a folder "aa-cifar-ResNet18", please open it and you will see 2 folders in the names of "AA_results_cifar10_L2" and "AA_results_cifar10_Linf".

1.3 Open "AA_results_cifar10_L2" folder and download "CIFAR10_L2_aa_standard_1_1000_eps_0.03137.pth" file. (This file is the anomaly data generated in this setting. There is also a log file that shows the results of this anomaly data generated)

1.4 Open "AA_results_cifar10_Linf" folder and download "CIFAR10_Linf_aa_standard_1_1000_eps_0.03137.pth" file. (This file is the anomaly data generated in this setting. There is also a log file that shows the results of this anomaly data generated)

1.5 You can see that there is a folder "model-cifar10-ResNet18". please open it and download "model-ResNet18-cifar10-best_epoch.pt". This is the model for cifar10 with best performance.


2. Generating Anomaly data for CIFAR100:

2.1 Run "Implementation_on_CIFAR100.ipynb" completely

2.2 You can see that in the directory of your workspace, there is a folder "aa-cifar-ResNet18", please open it and you will see 2 folders in the names of "AA_results_cifar100_L2" and "AA_results_cifar100_Linf".

2.3 Open "AA_results_cifar100_L2" folder and download "CIFAR100_L2_aa_standard_1_1000_eps_0.03137.pth" file. (This file is the anomaly data generated in this setting. There is also a log file that shows the results of this anomaly data generated)

2.4 Open "AA_results_cifar100_Linf" folder and download "CIFAR100_Linf_aa_standard_1_1000_eps_0.03137.pth" file. (This file is the anomaly data generated in this setting. There is also a log file that shows the results of this anomaly data generated)

2.5 You can see that there is a folder "model-cifar100-ResNet18". please open it and download "model-ResNet18-cifar100-best_epoch.pt". This is the model for cifar10 with best performance.


3. Anomaly Detection

3.1 Open "AnomalyDetection.ipynb" and upload these files in your directory:
	3.1.1: "CIFAR10_L2_aa_standard_1_1000_eps_0.03137.pth"
	3.1.2: "CIFAR10_Linf_aa_standard_1_1000_eps_0.03137.pth"
	3.1.3: "model-ResNet18-cifar10-best_epoch.pt"
	3.1.4: "CIFAR100_L2_aa_standard_1_1000_eps_0.03137.pth"
	3.1.5: "CIFAR100_Linf_aa_standard_1_1000_eps_0.03137.pth"
	3.1.6: "model-ResNet18-cifar100-best_epoch.pt"

3.2 Run "AnomalyDetection.ipynb" completely and all results will be available.
