
Bob 插件需要使用 `JavaScript` 语言开发，为了能够更好地实现功能，Bob 提供了一些额外的 API 供插件调用。

为了方便区分，Bob 提供的 API 均以 `$` 符号开头（除了 `require`）。目前主要有以下几个部分。

## require

这是我实现的一个简易版的 `require`，用于引入模块，使用方法和 `Node.js` 的 `require` 基本一致。

## $info

通过这个可以直接获取 `info.json` 文件解析过后的数据。

## $option

通过这个可以获取用户对自定义选项的设置。

## $log

打印日志时使用这个。

## $http

通过这个发送网络请求，比如 `GET`、`POST`。

## $file

通过这个进行文件读写。

## $data

通过这个处理二进制数据。


