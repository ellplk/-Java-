# 第三章   Java 变量

##    

## 一、变量认识

常量赋给变量值，在计算机内即将常量赋给相应地址空间（变量名为地址名）

1. 变量类型：
   -  int ：4个字节
   - double ：8个字节
   - char ：2个字节
   - String : 字节数不定

   具体如下：

![Snipaste_2022-05-18_10-30-50](C:\Users\pp\Pictures\Snipaste_2022-05-18_10-30-50.png)

2. 动态变量无法直接在main方法中调用，需要进行实例化



## 二、变量使用

1. 整型使用

   ![Snipaste_2022-05-18_10-54-39](C:\Users\pp\Pictures\Snipaste_2022-05-18_10-54-39.png)

2. 浮点型使用

   ![Snipaste_2022-05-18_10-55-49](C:\Users\pp\Pictures\Snipaste_2022-05-18_10-55-49.png)

3. 科学计数法

   ![Snipaste_2022-05-18_11-10-18](C:\Users\pp\Pictures\Snipaste_2022-05-18_11-10-18.png)

4. 字符类型

   ![image-20220518114238444](C:\Users\pp\AppData\Roaming\Typora\typora-user-images\image-20220518114238444.png)

5. **boolean**类型

   使用说明：不可以用0  or 非零数字代替**true or false**

![image-20220518160325027](C:\Users\pp\AppData\Roaming\Typora\typora-user-images\image-20220518160325027.png)









## 三、 类型转换

1. 自动类型转换

   ![image-20220518161502349](C:\Users\pp\AppData\Roaming\Typora\typora-user-images\image-20220518161502349.png)

2. 类型转换注意事项

   ![image-20220518161553232](C:\Users\pp\AppData\Roaming\Typora\typora-user-images\image-20220518161553232.png)

3. 强制类型转换

   是自动变换的逆过程，需注意精度问题                      **大 - >  小**

![image-20220518192723163](C:\Users\pp\AppData\Roaming\Typora\typora-user-images\image-20220518192723163.png)

4. **String**类型转换
   - **基本数据类型 - > String类型**
   - **String - >基本数据类型**

​             具体操作如下：

![image-20220518201743585](C:\Users\pp\AppData\Roaming\Typora\typora-user-images\image-20220518201743585.png)



### 如何得到字符串的第一个字符



        ``` java
        System.out.println(s5.charAt(0));
        ```



### String 类型转换的注意事项

1. 将 **String** 类型转换为基本数据类型时，要确保可以转换
   - "123" -> int                       **可**
   - "hello"->int                       **不可**

2. 格式不正确时会抛出异常，程序终止

​         











