# weixin-jssdk

<p align="left" >
    <img src="https://img.shields.io/npm/v/@maybecode/weixin-jssdk?style=flat-square" alt="npm version"  style="margin-right:5px;" />
      <img src="https://img.shields.io/npm/dt/@maybecode/weixin-jssdk.svg?style=flat-square&color=#4fc08d" alt="downloads" style="margin-right:5px;"   />
</p>

> 基于微信jssdk封装的ts类型定义, 尽量保持和官方同步。
> 
当前jssdk版本: `1.6.0`

微信官方文档: https://developers.weixin.qq.com/doc/offiaccount/OA_Web_Apps/JS-SDK.html



## 安装
```
yarn add @maybecode/weixin-jssdk
```

## 使用
```
import wx from '@maybecode/weixin-jssdk'

const jsApiList = [
    'getLocation'
] as wx.ApiMethod[];

wx.config({
    ...
    jsApiList
})
```