## 一、数据结构         
### 1.1 数组、链表       
### 1.2 栈、队列   
### 1.3 哈希表、集合    
### 1.4 树        
（1）遍历方式      
- 前中后序遍历
- 层次遍历


## 二、算法     
### 2.1 递归           
### 2.2 分治  
### 2.3 回溯      
回溯的框架     
```Python  
res = []
def backtrack(路径， 选择列表):
    if 满足结束条件：
        res.add(路径)
        return
    for 选择 in 选择列表:
        做选择
        backtrack(路径， 选择列表)
        撤销选择
```


