# 怎么用
如：
求解z的最小值  
z = 2a+3b-5c  
其中  
a+b+c=7  
2a-5b+c >= 10  
a+3b+c <= 12  
a,b,c >=0  

注意代码里的optimize.linprog所含的array数组均表示大于等于，如果要表示小于等于需要乘上-1  
且注意参数c，因为求的是最小值，所以代码里的是-c
