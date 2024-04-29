# Pin-GBTSVM
Granular Ball Twin Support Vector Machine with Pinball Loss Function

Please cite the following paper if you are using this code.

A. Quadir, M. Tanveer (2024). “Granular Ball Twin Support Vector Machine with Pinball Loss Function, IEEE Transactions on Computational Social Systems” 

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
The experiments are executed on a computing system possessing Python 3.11 software, an Intel(R) Xeon(R) CPU E5-2697 v4 processor operating at 2.30 GHz with 128-GB Random Access Memory (RAM), and a Windows-11 operating platform.

We have deployed a demo of the 'Pin-GBTSVM' and 'Pin-LGBTSVM' models using the 'chess_krvkp' dataset.

The following are the best hyperparameters set with respect to the “chess_krvkp” dataset

Regularization Parameter c_1=0.00001,  c_2= 0.00001, tau=1

Description of files:
main.py: This is the main file to run selected algorithms on datasets. In the path variable specificy the path to the folder containing the codes and datasets on which you wish to run the algorithm.
gen_ball.py: Generation of granular balls
Pin_GBTSVM.py: Solving the optimization problem

The codes are not optimized for efficiency. The codes have been cleaned for better readability and documented and are not exactly the same as used in our paper. For the detailed experimental setup, please follow the paper. We have re-run and checked the codes only in a few datasets, so if you find any bugs/issues, please write to A. Quadir (mscphd2207141002@iiti.ac.in).



           
