# Python_PLA
Write PLA in python, with data set and execution result

## 目標
    兩個類別(omega1、omega2)底下各有多筆線性可分的已標籤資料，透過機器學習PLA
    找出一條線，將資料自動分成兩類。

## Perceptron Learning Algorithm(PLA)
    感知機是從生物神經細胞發想而來的。
    單個神經細胞結構大致為：樹突、突觸、細胞體、軸突，接收刺激後會根據是否超過某種閾值
    而有兩種狀態：活化和未活化，前者是刺激超過閾值，後者是沒超過，這項概念便可發展出
    感知機，解決二元分類問題。
[感知機wiki](https://zh.wikipedia.org/wiki/%E6%84%9F%E7%9F%A5%E5%99%A8)

## 公式
![image](https://github.com/leodflag/Python_PLA/blob/master/img/function.png)

## 分類公式
![image](https://github.com/leodflag/Python_PLA/blob/master/img/classification%20function.png)

## 權重更新
![image](https://github.com/leodflag/Python_PLA/blob/master/img/update%20weight.png)

## 結果
data1   
![image](https://github.com/leodflag/Python_PLA/blob/master/img/data1_result.png)
![image](https://github.com/leodflag/Python_PLA/blob/master/img/data1.png)
--------
data2   
![image](https://github.com/leodflag/Python_PLA/blob/master/img/data2_result.png)
![image](https://github.com/leodflag/Python_PLA/blob/master/img/data2.png)
--------
data3   
![image](https://github.com/leodflag/Python_PLA/blob/master/img/data3_result.png)
![image](https://github.com/leodflag/Python_PLA/blob/master/img/data3.png)
--------

## 函式
    import numpy
    dataset = numpy.loadtxt("data3.csv", delimiter=",")
    data = dataset[:]
