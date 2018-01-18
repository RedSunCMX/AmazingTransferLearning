# code_transfer_learning

*Transfer learning toolbox; some useful transfer learning and domain adaptation codes*

> It is a waste of time looking for the codes from others. So I **clean** and **reimplement** them here in a way that you can **easily understand** and use. The following are some of the popular transfer learning (domain adaptation) methods in recent years, and I know most of them will be chosen to compare with your own method.
> It is still **on the go**. You are welcome to contribute and suggest other methods.

- - -

### Availiable codes for:

#### Non-deep learning

- **TCA** (Transfer Component Anaysis) [1]
	- [Matlab](https://github.com/tangzhenyu/AmazingTransferLearning/blob/master/code/MyTCA.m) | [Python](https://github.com/tangzhenyu/AmazingTransferLearning/tree/master/code/TCA_python)
- **GFK** (Geodesic Flow Kernel) [2]
	- [Matlab](https://github.com/tangzhenyu/AmazingTransferLearning/blob/master/code/MyGFK.m)
- **JDA** (Joint Distribution Adaptation) [3]
	- [Matlab](https://github.com/tangzhenyu/AmazingTransferLearning/blob/master/code/MyJDA.m)
- **TJM** (Transfer Joint Matching) [4]
	- [Matlab](https://github.com/tangzhenyu/AmazingTransferLearning/blob/master/code/MyTJM.m)
- **CORAL** (CORrelation ALignment) [5]
	- [Matlab](https://github.com/tangzhenyu/AmazingTransferLearning/blob/master/code/MyCORAL.m) | [Github](https://github.com/VisionLearningGroup/CORAL)
- **JGSA** (Joint Geometrical and Statistical Alignment) [6]
	- [Matlab](https://github.com/tangzhenyu/AmazingTransferLearning/blob/master/code/MyJGSA.m)
- **ARTL** (Adaptation Regularization) [7]
	- [Matlab](https://github.com/tangzhenyu/AmazingTransferLearning/tree/master/code/MyARTL)
- **TrAdaBoost** [8]
	- [Python](https://github.com/chenchiwei/tradaboost)
- **SA** (Subspace Alignment) [11]
	- [Matlab](http://users.cecs.anu.edu.au/~basura/DA_SA/)

#### Deep learning

- **DAN/JAN** (Deep Adaptation Network/Joint Adaptation Network) [9,10] 
	- [Caffe](https://github.com/thuml/Xlearn)
- **RTN** (Unsupervised Domain Adaptation with Residual Transfer Networks) [12]
	- [Caffe](https://github.com/thuml/Xlearn)
- - -

#### [Code from HKUST](http://www.cse.ust.hk/TL/) [a bit old]

- - -

Testing **dataset** can be found [here](https://github.com/tangzhenyu/AmazingTransferLearning/blob/master/doc/dataset.md).

- - -

#### References

[1] Pan S J, Tsang I W, Kwok J T, et al. Domain adaptation via transfer component analysis[J]TNN, 2011, 22(2): 199-210.

[2] Gong B, Shi Y, Sha F, et al. Geodesic flow kernel for unsupervised domain adaptation[C]//CVPR, 2012: 2066-2073.

[3] Long M, Wang J, Ding G, et al. Transfer feature learning with joint distribution adaptation[C]//ICCV. 2013: 2200-2207.

[4] Long M, Wang J, Ding G, et al. Transfer joint matching for unsupervised domain adaptation[C]//CVPR. 2014: 1410-1417.

[5] Sun B, Feng J, Saenko K. Return of Frustratingly Easy Domain Adaptation[C]//AAAI. 2016, 6(7): 8.

[6] Zhang J, Li W, Ogunbona P. Joint Geometrical and Statistical Alignment for Visual Domain Adaptation[C]//CVPR 2017.

[7] Long M, Wang J, Ding G, et al. Adaptation regularization: A general framework for transfer learning[J]//TKDE, 2014, 26(5): 1076-1089.

[8] Dai W, Yang Q, Xue G R, et al. Boosting for transfer learning[C]//ICML, 2007: 193-200.

[9] Long M, Cao Y, Wang J, et al. Learning transferable features with deep adaptation networks[C]//ICML. 2015: 97-105.

[10] Long M, Wang J, Jordan M I. Deep transfer learning with joint adaptation networks[J]//ICML 2017.

[11] Fernando B, Habrard A, Sebban M, et al. Unsupervised visual domain adaptation using subspace alignment[C]//ICCV. 2013: 2960-2967.

[12] Long M, Zhu H, Wang J, et al. Unsupervised domain adaptation with residual transfer networks[C]//NIPS. 2016.
