# Robosys_kadai1

## 概要
LEDの点灯を制御するRaspberryPi3向けのデバイスドライバを作成しました。

## 動作デモ(Youtube)
https://youtu.be/LgPQ6bpKG2E

## 動作環境
RaspberryPi3

Raspbian 10

## 導入
$git clone https://github.com/hiroyaishikawa/Robosys_kadai1.git

## 使い方
1．LEDのアノード側をRaspberryPiの25番ピン、反対側を39番ピン(GND)に接続する。※適宜抵抗を挟むこと

2．$sh make.sh を実行。コンパイルからドライバのインストールまで一括で行う

3．$sh led_on.sh でLED点灯、$sh led_off でLED消灯

4．使用後は$clean.sh を実行することでアンインストール

## ライセンス
このソフトウェアはGNUライセンスで提供されます。詳細はLICENSEをご覧ください。

## 製作者
石川 弘也

