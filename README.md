Evaluation_of_MIAShield_(Cifar10_and_100).ipynb contain the code for original idea of MIAShield
For dataset: Choose 'Cifar10' for CIFAR-10 dataset, 'Cifar100' for CIFAR-100 dataset
EO2-ESE, EO3-ASE, EO4-MCE, EO5-COE
For Probability dependent attacks, initialize attack=1 for Threshold Attack, attack=2 for Logistic Regression Attack, attack=3 for MLP attack
#note that, for all the label-dependent attacks, instead of training a shadow model, we keep the non-private model as shadow model and train the attack model (TA/RA) based on that the gathered data from that model and/or pass the threshold value (BA) ahieved from that model
