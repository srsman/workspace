SVM model of Stock
using SVR by libsvm

Features: ǰN����K��  + EMA
Prediction: ��һ�������յ��ǵ��� (1:10%; -1:-10%)


python test.py 600111
Prob. model for test data: target value = predicted value + z,
z: Laplace distribution e^(-|z|/sigma)/(2sigma),sigma=0.15668
Mean squared error = 0.0486415 (regression)
Squared correlation coefficient = 0.0191634 (regression)


Reference��
Tushare��http://tushare.waditu.com/
LibSVM��http://www.csie.ntu.edu.tw/~cjlin/libsvm/



cloudseasail@163.com