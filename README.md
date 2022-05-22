# Lab_5
##30 variant

Ввод: 
Введите число K = 2 
Введите чётное положительное число N = 10 
Вывод: 

A =   
[[ -4  -9  -7   5  -2  -4  -8   6   3   0]  
 [-10   8  -3  -4   0  -3   1  -9  -7   4]  
 [  7   9   3  -6  -5  -8  -5  -9  -9  -4]  
 [ -1   3   8   9  -2  -9   9  -5  -3 -10]  
 [ -2  -8  -1  -1   9  -1 -10  -7   9  -5]  
 [  3  -9   3  -5  -1   2   2  -8 -10  -9]  
 [ -8  -8   4   8  -6   5  -3  -3  -3 -10]  
 [  4  -3   6  -2   5  -8   9  -9  -8   0]  
 [  0   6   0  -2   5   1  -5   1   6  -7]  
 [ -5  -7   3  -2  -8  -1  -9 -10   4   1]]  
F =   
[[ -4  -8   6   3   0  -4  -9  -7   5  -2]  
 [ -3   1  -9  -7   4 -10   8  -3  -4   0]  
 [ -8  -5  -9  -9  -4   7   9   3  -6  -5]  
 [ -9   9  -5  -3 -10  -1   3   8   9  -2]  
 [ -1 -10  -7   9  -5  -2  -8  -1  -1   9]  
 [  3  -9   3  -5  -1   2   2  -8 -10  -9]  
 [ -8  -8   4   8  -6   5  -3  -3  -3 -10]  
 [  4  -3   6  -2   5  -8   9  -9  -8   0]  
 [  0   6   0  -2   5   1  -5   1   6  -7]  
 [ -5  -7   3  -2  -8  -1  -9 -10   4   1]]  
result1 =  [[-0.05 -0.04  0.05  0.04  0.09  0.02 -0.04 -0.1  -0.14 -0.05]
 [-0.03  0.02  0.03  0.01  0.01 -0.03  0.   -0.03 -0.01 -0.02]
 [ 0.02 -0.05 -0.01 -0.11 -0.13 -0.1   0.12  0.22  0.19  0.07]
 [-0.05 -0.01  0.06  0.04  0.12 -0.06  0.04 -0.08 -0.18 -0.09]
 [ 0.    0.    0.   -0.05  0.03 -0.05  0.06  0.08  0.03 -0.05]
 [-0.08  0.    0.01 -1.01  2.05  0.01  0.03 -0.07 -0.08 -0.04]
 [-0.02  0.02 -0.06  8.08 -6.    5.07 -3.09 -0.07 -0.04  0.01]
 [ 0.08 -0.03  5.97 -2.07  4.87 -8.03  9.05 -8.87  0.18  0.03]
 [-0.02  5.99 -0.04 -1.93  5.03  1.03 -5.08  0.92  5.99  0.04]
 [-5.02 -7.01  3.01 -2.05 -7.99 -1.07 -8.97 -9.95  3.95  1.  ]]
result2 =  [[-0.01  0.15 -0.02 -0.08 -0.11 -0.04  0.06 -0.34 -0.37 -0.01]
 [ 0.07 -0.1   0.13  0.07  0.12  0.   -0.08  0.1   0.08 -0.09]
 [-0.07 -0.14  0.08 -0.05  0.05 -0.12  0.1   0.41  0.43  0.09]
 [ 0.02  0.1   0.01 -0.01 -0.02  0.    0.01 -0.28 -0.36 -0.09]
 [-0.03 -0.03 -0.03  0.02  0.06  0.01  0.05  0.09  0.02 -0.03]
 [ 0.01  0.13 -0.1  -1.    1.97  0.09  0.03 -0.23 -0.25 -0.1 ]
 [ 0.02  0.25 -0.24  7.96 -6.21  5.14 -3.03 -0.45 -0.33  0.02]
 [-0.07 -0.17  6.08 -2.04  5.03 -8.13  9.06 -8.57  0.47  0.15]
 [-0.02  6.3  -0.26 -2.1   4.74  1.1  -4.96  0.47  5.57  0.05]
 [-5.01 -7.06  3.03 -1.98 -7.92 -1.01 -8.97 -9.87  4.07  0.96]]
result3 =  [[ -0.02   0.3   -0.04  -0.16  -0.22  -0.08   0.12  -0.68  -0.74  -0.02]
 [  0.14  -0.2    0.26   0.14   0.24   0.    -0.16   0.2    0.16  -0.18]
 [ -0.14  -0.28   0.16  -0.1    0.1   -0.24   0.2    0.82   0.86   0.18]
 [  0.04   0.2    0.02  -0.02  -0.04   0.     0.02  -0.56  -0.72  -0.18]
 [ -0.06  -0.06  -0.06   0.04   0.12   0.02   0.1    0.18   0.04  -0.06]
 [  0.02   0.26  -0.2   -2.     3.94   0.18   0.06  -0.46  -0.5   -0.2 ]
 [  0.04   0.5   -0.48  15.92 -12.42  10.28  -6.06  -0.9   -0.66   0.04]
 [ -0.14  -0.34  12.16  -4.08  10.06 -16.26  18.12 -17.14   0.94   0.3 ]
 [ -0.04  12.6   -0.52  -4.2    9.48   2.2   -9.92   0.94  11.14   0.1 ]
 [-10.02 -14.12   6.06  -3.96 -15.84  -2.02 -17.94 -19.74   8.14   1.92]]
Время выполнения программы: 0.020003557205200195 секунд.
