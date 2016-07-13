# Python_day2_Python_Variables_operators
#==========================================
##变量（variables）
###编程风格：
     标识符第一个字符 大小写字母或下划线；
     标识符名称的部分可以字母、下划线、数字（0-9）组成；
     标识符对大小写敏感。
###定义
     常量constants ：全部大写的变量名表示常量，PAI = 3.14159...；
     变量：x = 2 y = 3
     理解变量在计算机内存中的表示：
     例1 a = ‘ABC’时，Python解释器干了俩件事：
    （1） 在内存中创建了’ABC’的字符串；
    （2）在内存中创建了名为a的变量，并指向’ABC’.
     例2  a = ‘ABC’
             b = a   //b指向a指向的内存
             a = ‘XYZ’  //a指向新内存
             print ‘b:’ , b
###测试：
     （1）脚本
![azalea](https://github.com/superAzalea/Python_day2_Python_Variables_operators/blob/master/images_day2/day2_1.png)
     （2）打印内存地址 id()
![azalea](https://github.com/superAzalea/Python_day2_Python_Variables_operators/blob/master/images_day2/day2_2.png)
##数据类型
###按特征分类
     （1）数字类型
            * 整型
            * 布尔型 （True、 False）
            * 长整型(L)
            * 标准整型  
            
![azalea](https://github.com/superAzalea/Python_day2_Python_Variables_operators/blob/master/images_day2/day2_3.png)
            * 非整型
            * 双精度浮点型  
            
  ![azalea](https://github.com/superAzalea/Python_day2_Python_Variables_operators/blob/master/images_day2/day2_4.png)
            * 复数
            * decimal（不是内建类型）
      （2）序列类型
            * 字符型(str)  
            
![azalea](https://github.com/superAzalea/Python_day2_Python_Variables_operators/blob/master/images_day2/day2_5.png)  

![azalea](https://github.com/superAzalea/Python_day2_Python_Variables_operators/blob/master/images_day2/day2_6.png)
            * 元组(tuple)
            * 列表(list)
![azalea](https://github.com/superAzalea/Python_day2_Python_Variables_operators/blob/master/images_day2/day2_7.png)  

      （3）映像类型
            * 字典(dict) (key value)  
            
![azalea](https://github.com/superAzalea/Python_day2_Python_Variables_operators/blob/master/images_day2/day2_8.png)  

       （4）集合类型
            * 可变集合(set)
            * 不可变集合(frozenset)
###按可变性划分
       （1）可哈希的，不可变数据类型
            * 数字类型
            * 不可变集合(frozenset)
            * 字符串(str)
            * 元组(tuple)
       （2）可变数据类型
            * 字典(dict)
            * 列表
            * 可变集合(set) 
##操作符
###运算符
        (1) (+ 、-、 *、 /、 %、 **(幂)、 //(取整除－返回商的整数部分))  
        
![azalea](https://github.com/superAzalea/Python_day2_Python_Variables_operators/blob/master/images_day2/day2_9.png)
###比较操作符
        (1) ==
        (2) !=、 (<>)
        (3) >=、 <= 、> 、<
###位运算
        (1) & 按位与
        (2) ｜按位或
        (3) ^ 按位异或
        (4) ~ 取反   （~2 -3,~60 -61,计算机存储按除符号位外取反＋1）；
        (5) <<
        (6) >>
###成员运算符
        (1) in  在指定序列中找到返回True,否则False
        (2) not in
###逻辑运算符
        (1) and
        (2) or
        (3) not
###标识运算符
        (1) is
        (2) is not
##运算符优先级
![azalea](https://github.com/superAzalea/Python_day2_Python_Variables_operators/blob/master/images_day2/day2_10.png)

#=======
