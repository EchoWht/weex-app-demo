# Introduction

This boilerplate is targeted towards large, serious projects and assumes you are somewhat familiar with Webpack and `weex-loader`. 

## Quickstart

``` bash

cd weex-app-demo
npm install
npm start

```

## 打包或者运行原生app

```bash


weex platform add android

##启动android studio模拟器--假设已经连接真机这一步可以忽略
/Users/wanghaotian/Library/Android/sdk/emulator/emulator  -netdelay none -netspeed full -avd Nexus_5X_API_28

## 启动项目
weex run android


```

## apk安装文件目录

./platforms/android/app/build/outputs/apk/weex-app.apk

## How to use less/sass/pug

Take `sass` for example:

```
$ npm i node-sass sass-loader --save
```

Then, you just need to change the `style` tag as: `<style lang="sass"><style>`.

## How to create your own template

See [How-to-create-your-own-template](https://github.com/weex-templates/How-to-create-your-own-template).
