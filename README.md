* This package, named BOW-LM, includes the Matlab codes of budget online
  weighted learning method for imbalanced data streams.

* to run the codes please 

 (1) set the matlab paths by simply  running 
 
 >>  path_setup    
  
 OR 
add the following path manually to the Matlab
path  './',  'lib','lib_XJ'

 (2) run the demo file to test whether the code could run successfully by executing

  >>   demo_k_BWOSELM.m

 
 It indicates sucessfull runing  if the iterated information and results are printed out: 

....
....
....
The results have been put into the file : ...
The results have also been   saved into MAT file: ...


* folders and functions:

 ./data_mat: consists of the demo data files  

  ./lib: consists of  the  functions of  BOGD, BSGD, LSSVM 

  ./lib_XJ: consists the functions of BOW-LM 

  ./ demo_k_BWOSELM.m: a  demo file

  ./main: consists of the main files for the experiments 

  ./path_setup: function to setup the paths

  ./readme.txt: this file

* The files could be used freely for your research once you cite the following work

  Xijun Liang, Xiaoxn Song, Kai Qi, Jinyu Liu and Ling Jian, Budgeted online
classification and anomaly detection for imbalanced data streams. IEEE Intelligent
Systems, preprint, 2020.

 For commercial usage of this package, please contact    Xijun Liang:  liangxijunsd@163.com

2020.8


