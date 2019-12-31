# My-LED
robosws2019 1

## 概要
LEDで点字を表現するプログラムです．

## 動作環境

* Raspberry Pi Model 3B+
* Ubuntu18.04

## 実行方法
```
$ git clone https://github.com/todasayaka/myled.git
$ cd myled
$ make
$ sudo insmod myled.ko
$ sudo chmod 666 /dev/myled0
$ sudo echo 1 > /dev/myled0
$ sudo echo 2 > /dev/myled0
$ sudo echo 0 > /dev/myled0
$ sudo echo 2 > /dev/myled0
$ sudo echo 1 > /dev/myled0
$ sudo echo 0 > /dev/myled0
$ sudo rmmod myled.ko
```
