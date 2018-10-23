# TensorFlow-help-document-and-fast-function-information-list  
help  document  
# tf.constant  
创建一个常数张量，例如 node1 = tf.constant(3.0, tf.float32)  
# tf.placeholder(dtype, shape=None, name=None)  
此函数可以理解为形参，用于定义过程，在执行的时候再赋具体的值   
dtype：数据类型。常用的是tf.float32,tf.float64等数值类型  
shape：数据形状。默认是None，就是一维值，也可以是多维，比如[2,3], [None, 3]表示列是3，行不定  
name：名称  
#  tf.Variable
https://www.jianshu.com/p/2b9e475391ab  
创建变量！
# tf.global_variables_initializer()  
在创建了变量后，，对值的初始化操作    
# tf.square()  
tf.square()是对a里的每一个元素求平方  
# tf.reduce_sum    
张量的求和函数  
#  tf.train.GradientDescentOptimizer(0.01)   
梯度下降算法的其中参数0.01为步长  
#  train = optimizer.minimize(loss)  
# 优化的参数，方式
# tf.contrib.learn  
tf.contrib.learn 是一个高级TensorFlow库，简化了机器学习的机制  
#  tf.get_variable  
https://blog.csdn.net/u012223913/article/details/78533910?locationNum=8&fps=1  
#  MNIST  
是一个简单的计算机视觉数据集。它由以下手写数字图像组成  
# 
