Recruit
=======

### 一. 功能（目前是开发阶段，以下功能仅实现部分）
1. 根据提示输入关键字搜索相关职位信息，并将信息部分呈现出来。
2. 程序根据搜索得到的信息绘制成图像，供用户观看或使用。
3. 提供每个职位招聘信息的URL，用户可点击URL进入网页，查看招聘的详细信息。
4. 程序根据得到的数据自动的进行一定的分析，并展现给用户（难度较大，目前不知道如何做）

> __Ps__: 程序应该是一个图形用户界面，使用pyQt5

### 二. 使用的技术（或框架）

#### 语言：
- python

#### 类库:
- matplotlib （用于绘制并生成图像）
- pandas (用于数据处理，使matplotlib方便绘图)

#### 框架：
- pyQt5 (著名的C++框架Qt 的python版本吧,用于GUI部分)

### 三：操作演示

> 当前并没有完成GUI部分，命令行等入也并没有现实，暂时无法演示


### 四：未来展望

> 同上


 


		qr = MainWindow.frameGeometry()
        cp = QDesktopWidget().availableGeometry().center()
        qr.moveCenter(cp)
        MainWindow.move(qr.topLeft())