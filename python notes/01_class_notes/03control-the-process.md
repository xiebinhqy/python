# Python课堂笔记03：《day04》

### 第三节课：Python介绍——控制流程语句

#### **回顾上节课**

#### print\(“hello world”\)

#### 变量 ： 存储信息的，日后被调用、修改操作

#### 常量： 固定不变的量，字母大写

#### 命名规则：

1. #### 字母数字下划线组成
2. #### 不能以数字开头，不能含有特殊字符和空格
3. #### 不能以保留字命名
4. #### 不能以中文命名
5. #### 定义的变量名应该有意义
6. #### 驼峰式命、 下划线分割单词
7. #### 变量名区分大小写

if控制语句

```py
a=1
b=2
if  a<b:
    print("Yes"\)
    print("Yes"\)
    print("Yes"\)
    print("Yes"\)
else:
    print("No"\)
```

```py
a=1
b=2
if a>b:
    print("Yes")
elif a==b:
    print("第三")
else:
    print("any")
```

## python注释

\# 单行注释

'''多行注释'''

""" 多行注释 """

### input\(\)

字符串拼接   "abc" + "qwe"

file.py

文件的扩展名：

.py ： python的程序文件

.txt ： 文本文件

pdf chm html doc xml xls ppt

jpg png gif jpeg bmp

avi rmvb MP4  mkv  3gp

WMV MP3 flue mid

True 真 正确的

False 假 错误的

a

b = 100

c = 1000

if  b &lt;= a &lt;= c:

```
print\("True"\)
```

num  number

num1 = intpu\("Num1:"\)

num2 = intpu\("Num2:"\)

num3 = intpu\("Num3:"\)

输出三个数字中的最大值/最小值

if num1&gt;num2&gt;num3：

```
\#num1最大
```

else:

```
\#num1&lt;num2
```

if num1&gt;num2&gt;num3    \#num1最大

elif num1&gt;num3&gt;num2    \#num1最大

elif num2&gt;num1&gt;num3    \#num2最大

elif num2&gt;num3&gt;num1    \#num2最大

elif num3&gt;num2&gt;num1    \#num3最大

else

num3&gt;num1&gt;num2    \#num3最大

num1 num2 num3

max\_num =0

if num1&gt;num2:

```
max\_num= num1

if max\_num &gt; num3:

    print\("Max NUM is",max\_num\)

else:

    print\("Max NUM is",num3\)
```

else:

```
max\_num = num2

if max\_num &gt; num3:

    print\("Max NUM is",max\_num\)

else:

    print\("Max NUM is",num3\)
```

num += 1  等价于 num = num + 1

num -= 1  等价于 num = num - 1

num \*= 2  等价于 num = num \* 2

num /= 2  等价于 num = num / 2

num //= 2  等价于 num = num // 2

num %= 2  等价于 num = num % 2

num \*\*= 2  等价于 num = num \*\* 2

and  且，并且

只有两个条件全部为True（正确）的时候， 结果才会为True（正确）

条件1 and 条件2

5&gt;3 and 6&lt;2  True

or 或，或者

只要有一个条件为True，则结果为Ture，

5&gt;3 or 6&lt;2

真 或  假

not  不，雅蠛蝶

not 5&gt;3  == False

not 5&lt;3  == True

a&gt;b and \(c&gt;d or \(not f\)\)

\(not \(not True\)\) or \(False and \(not True\)\)

条件1 and 条件2

条件1 or 条件2

短路原则

对于and 如果前面的第一个条件为假，那么这个and前后两个条件组成的表达式 的计算结果就一定为假，第二个条件就不会被计算

对于or

如果前面的第一个条件为真，那么这个or前后两个条件组成的表达式 的计算结果就一定为真，第二个条件就不会被计算

True or True and False

猜年龄

age = 50

user\_input\_age = int\(input\("Age is :"\)\)

if ....

while 循环

while 条件：

```
print\("any"\)

print\("any"\)
```

num = 1

while num&lt;10:  \# 2

```
print\(num\)  \# 2

num+=1  \# 3

if num == 9: \# 3

    break
```

num = 1

while num&lt;=100:  \# num&lt;=100 等价于 True

```
             \# while num&lt;=100:   等价于 while True:

if num%2 == 0:

    print\(num\)

num += 1
```

num = 1

while num&lt;=100:

```
if num%2 == 1:

    print\(num\)

num += 1
```

age = 50

\#user\_input\_age = int\(input\("Age is :"\)\)

flag = True

while flag:

```
user\_input\_age = int\(input\("Age is :"\)\)

if user\_input\_age == age:

    print\("Yes"\)

    flag =False

elif user\_input\_age &gt; age:

    print\("Is bigger"\)

else:

    print\("Is smaller"\)
```

print\("End"\)

break \# 终止

age = 50

\#user\_input\_age = int\(input\("Age is :"\)\)

\#flag = True

\# break

while True:

```
user\_input\_age = int\(input\("Age is :"\)\)

if user\_input\_age == age:

    print\("Yes"\)

    break

elif user\_input\_age &gt; age:

    print\("Is bigger"\)

else:

    print\("Is smaller"\)
```

print\("End"\)

continue 继续

if a&gt;b  and  d&lt;f or  5&gt;3  and  d == e:

```
......
```

while 条件：

```
....
```

else：

```
....
```

statement 语句

num = 1

while num &lt;= 10:

```
num += 1

if num == 5:

    break

print\(num\)
```

else:

```
print\("This is else statement"\)
```

while 条件1：

```
.....

while 条件2:

    ....
```

1\*1=1

1\*2=2 2\*2=4

1\*3=3 2\*3=6 3\*3=9

....

\#\#\#

\#\#\#

\#\#\#

\#\#\#

\#\#\#\#

\#\#\#\#

\#\#\#\#

\#print\("hello world.",end="\_\_"\)  \# \n   \r\n  \r

\#print\("hello world.",end="\_\_"\)

\#print\("hello world.",end="\_\_"\)

num1 = 0

while num1&lt;=5:

```
print\(num1,end="\_"\)

num2 = 0

while num2&lt;=7:

    print\(num2,end="-"\)

    num2+=1



num1+=1

print\(\) \#  print\(end="\n"\)
```

\#0\_0-1-2-3-4-5-6-7-

\#1\_0-1-2-3-4-5-6-7-

Height 高度

width 宽度

height = int\(input\("Height:"\)\)  \# 用户输入一个高度

width = int\(input\("width:"\)\)   \# 用户输入一个宽度

num\_height = 1

while num\_height &lt;=height:

```
num\_width = 1

while num\_width &lt;= width:

    print\("\#", end=""\)

    num\_width += 1

print\(\)

num\_height += 1
```

12345678

22345678

32345678

42345678

第一行的时候 8字符 8次循环

第二行的时候 8字符 8次循环

第三行的时候 8字符 8次循环

第四行的时候 8字符 8次循环

\#\#\#\#

\#\#\#\#

\#\#\#\#

\#\#\#\#

width = int\(input\("width:"\)\)

num\_width = 1

while num\_width&lt;=width:

```
print\("\#", end=""\)

num\_width +=1
```

print\(\)

num\_width = 1

while num\_width&lt;=width:

```
print\("\#", end=""\)

num\_width +=1
```

print\(\)

num\_width = 1

while num\_width&lt;=width:

```
print\("\#", end=""\)

num\_width +=1
```

print\(\)

num\_width = 1

while num\_width&lt;=width:

```
print\("\#", end=""\)

num\_width +=1
```

\#print\("\#",end=""\)

\#print\("\#",end=""\)

\#print\("\#",end=""\)

\#print\("\#",end=""\)

print\(\)

```
num = 4

while num&gt;0:

    print\("\#", end=""\)

    num -= 1

print\(\)



\# @ == \#\#\#\#
```

height = int\(input\("Height:"\)\)  \# 用户输入一个高度

width = int\(input\("width:"\)\)   \# 用户输入一个宽度

\#num2 = height

num2 = height  \# 第一步： 赋值

while num2 &gt; 0:   \# 第二步 ：num2 == 2

```
num1 = width     \# 第三步： 赋值

while num1&gt;0:   \# 第四部：num1==2   \# 第七步：num1 = 1 

    print\("\#", end=""\)  \# 第五步： 不换行 打印一个\#   第八步： 不换行 打印一个\#

    num1 -= 1   \#第六步： num1 = 1   第九步： num1 = 0

print\(\)  \# 第十步 ： 只是换行

num2 -= 1  \# 第十一步 ： num2=1
```

\#\#

\#\#

print\("1\*1=",1\)

\# "1\*1=",1  == str\(m\)+"\*"+str\(n\)+"=",1

m = 2

n = 2

print\( str\(m\)+ "\*" + str\(n\) + "=" , m\*n  \)

line = 5    \# 第一步 ： 赋值

while line&gt;0:  \# 第二部 line=5

```
tmp = line  \#  第三部 ： tmp =5   tmp=4



while  tmp&gt;0:  \#  第四部 ： tmp =5   \#第七步 tmp=4    \#第十部： tmp=3   第十三步 tmp=2

    print\("\*",end=""\) \#第五步   \#第八部        \#第十一部               \#第十四步

    tmp = tmp-1   \# 第六步 tmp = 4  \# 第九步 tmp=3  \# 第十二步 tmp=2   第十五步 tmp= 1 



print\(\)

\#print\(line\)

line -= 1
```

first = 1

while first&lt;=9:

```
sec = 1    

while sec &lt;= first:

    print\(  str\(sec\)+"\*"+ str\(first\) +"="+str\(sec \* first\), end="\t"\)

    sec += 1





print\(\)





first += 1
```



