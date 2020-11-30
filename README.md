# 第四次实验报告
***
#### 实验目的

1.掌握字符串String及其方法的使用。

2·掌握文件的读取和使用方法。

3·掌握异常处理结构。
***
#### 实验要求
1.设计学生类；

2.采用交互式方式实例化某学生

3.设计程序完成上述业务要求
***
#### 核心代码

Reader in = new FileReader(sourceFile);

			BufferedReader bufferReader = new BufferedReader(in);

			Writer out = new FileWriter(targetFile, true);

			BufferedWriter bufferWriter = new BufferedWriter(out);

			String information = "濮撳悕:" + student.getName() + "		" + "鎬у埆:" + student.getSex() + "		" + "骞撮健锛�"
					
          + student.getAge() + "		" + "瀛﹀彿:" + student.getNumber();
	
			bufferWriter.write(information);
		
			bufferWriter.newLine();

			String str = null;
	
			while ((str = bufferReader.readLine()) != null) {
			
      s = s + str;
			}

			char strone[] = new char[s.length()];

			strone = s.toCharArray();
***
#### 实验过程
本次实验创建了两个类，第一个学生类，在学生类中，定义学生的姓名，年龄，性别，学号。创建setName()方法，用于给name变量赋值； 创建getName()方法返回学生姓名。
在测试类中，实现了先将长恨歌输入另一个文件中，在对长恨歌进行排版
***
#### 实验感想
通过本次实验，我掌握了字符串String及其方法的使用，文件的读取和使用方法和异常处理结构。虽然这是最后一次实验了，但感觉对于Java还是没有入门，还需要再课下好好研究。
