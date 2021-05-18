# numpy
cricket data analysis
# cricket data analysis
#score of four batsman of two innings
cricket=[[180,78],[215,102],[210,98],[100,75]]
import numpy as np
np_cricket=np.array(cricket)  
mean=np.mean(np_cricket[:,1])                      # mean calculation of second column
median=np.median(np_cricket[:,1])                  #meadian calculation of second column
standard_deviation=np.std(np_cricket[:,1])         #standard deviation of second column
corr_coeff=np.corrcoef(np_cricket[:,0],np_cricket[:,1]) # correlation coefficient
print("mean",mean)
print("median",median)
print("std dev",standard_deviation)
print("correlation coefficient",corr_coeff)
