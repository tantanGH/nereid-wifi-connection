# nereid-internet-connection

X680x0 + Nereid - Internet connection setup guide

---

## はじめに

X680x0 実機 + Nereid (USB/LAN/MEM拡張ボード) を家庭内 Wi-Fi LANに参加させる際の構成例の覚書です。

以下の3つの構成について記述しています。

1. Wi-Fiルータに物理的にケーブル接続

2. Wi-Fiコンバータの利用

3. Raspberry Piの利用

---

## 接続概略図

### 1. Wi-Fiルータに物理的にケーブル接続

* メリット ... 設定が簡単
* デメリット ... 距離によっては物理的に長いケーブルを這わせる必要がある

<img src='images/conn1.png'/>

### 2. Wi-Fiコンバータの利用

* メリット ... 設定が比較的簡単(特にWi-Fiルータと同じメーカーのコンバータであれば)
* デメリット ... Wi-Fiに繋がる以外のことができない

<img src='images/conn2.png'/>

### 3. Raspberry Piの利用

* メリット ... 余ってるラズパイを活用できる。ラズパイにftpサーバを入れてファイルのやりとりができる。
* デメリット ... 設定が若干複雑

<img src='images/conn3.png'/>