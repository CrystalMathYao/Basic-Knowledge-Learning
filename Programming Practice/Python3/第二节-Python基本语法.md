Python输入输出：

输出用print()在括号中加上字符串，就可以向屏幕上输出指定的文字，例如print('hello, world')。print()函数也可以接受多个字符串，用逗号“,”隔开，就可以连成一串输出，此时print()会依次打印每个字符串，遇到逗号“,”会输出一个空格，例如print('The quick brown fox', 'jumps over', 'the lazy dog')。

输入用input()，可以让用户输入字符串，并存放到一个变量里，例如name = input()。input()可以显示一个字符串来提示用户进行输入，例如name = input('please enter your name: ')

Python语法基础：

Python的语法比较简单，采用缩进方式，写出来的代码就像下面的样子：

# print absolute value of an integer:

a = 100

if a >= 0:

  print(a)
  
else:

  print(-a)
