The CS-430 folder contains the following sub-folders
1.Base Line measurements: It contains code that provides accuracy measurement for the Initial case without any preprocessing

2.Primarydata_RCV-1-Measurements: It contains code for Feature hashing(FH), Jl Random projections(JL), bBit min wise hashing(bBitMinHash) for the RCV-1 dataset
	The B bit folder contains code for minwise hashing and text files correspond to the matrices obtained by running random permuations(This was performed on 32 Gb machine and hence placed exclusively)

3.Train_RCV and Test_RCV are subsets of the testing and training dataset that are provided by RCV-1 set

4.Secondarydata_Fads_measurements: It contains code for Feature hashing(FH), Jl Random projections(JL) for the FarmAds dataset dataset
Train_fads and Test_fads are subsets of the testing and training dataset that are provided by Farm-Ads dataset
 
Note:Each reduction technique is applied on the four classifiers Linear SVM(LSVM), Logistic Regression(LR), Decision Trees(DT), Non-linear SVM(NSVM). The code for each of these combinations is in files named by the abbrevations in the bracket