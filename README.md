# F1-Score-of-Pycaret
When do my graduate design, found some bugs in Pycaret,——the calculation of F1-Score. Maybe, the calculation of prec.,recall and F1-Score.

![image](https://user-images.githubusercontent.com/101257914/159960848-fe9f5bd5-d260-41d9-9613-1752c6effc04.png)

we all know that 
![image](https://user-images.githubusercontent.com/101257914/159964253-9476e63f-da6f-4043-8aff-df3467edca94.png)

However, according to the data in the picture, the above formula obviously does not hold, rather, the deviation is very large. Then according to the confusion matrix, it can be seen with the naked eye that the precision should not be so high. 

但依据图片中的数据，上述公式显然不成立，不如说，偏差很大。然后再根据混淆矩阵，凭肉眼就可以看出precision不应该会有那么高。
