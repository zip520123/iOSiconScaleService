# iOS icon scale service
將圖片縮放成符合iOS規定的icon尺寸服務。

![sample](video.gif)
![sample](demo.png)
## Introduction
- 利用Mac內建的Automator製作的可以將一張圖片縮放成不同大小的服務。
- iOS需要為不同的裝置提供不同尺寸的icon，用這個服務可以把icon縮放成iOS需要的尺寸。
## Usage
- clone或下載zip下來點開安裝服務，。
- 安裝服務後右鍵選取圖片，選擇服務->選擇縮放的尺寸。
- 他會複製一張圖然後縮放成該尺寸，並且在名稱後面加上@2x、@3x。
* 用原始圖片1024x1024縮小比較不會失真
## 支援的圖片格式
- Mac 認得出來的圖片格式都可以，jpg, jpeg, png...

## How is work
Automator
![sample](imprement.png)

## 輸出成iOS各種尺寸
如果要用這個服務就要其他服務都要裝
![sample](image1.png)