# wifi-qrcode

输入 WIFI 名称密码, 快捷生成二维码. 安卓苹果(IOS 13+)扫码链接.

技术栈: vite + vue3.0



## 🚀 快速开始

调试启动

```bash
yarn dev
```

打包

```bash
yarn build:all
```



## 📌 模块

- [x] @zstark/wifi-qrcode: 

  ```js
  import createWifiQr from '@zstark/wifi-qrcode'
  
  createWifiQr({
      ssid: string, // Network SSID name
      password: string,
      encryptionMode: string, // Settings: Network encryption mode
      hiddenSSID: string, // Settings: Mark your network as hidden SSID
  })
  // => `WIFI:T:${settings.encryptionMode};S:${settings.ssid};P:${settings.password};H:${settings.hiddenSSID};`
  ```

  
