# 滔博货控 MAX 申请助手

通过自动化的操作，可以极大的提升工作效率，主要功能：

- 自动人机验证
- 指定时间自动完成申请

## 上手指南

### 安装

软件下载 [最新版本](https://github.com/lenye/topsports/releases/tag/v25.6.1)

### windows 操作系统

1. 解压下载文件 tsmax_v25.6.1_windows_x86_64.zip；
2. 运行`tsmax.exe nike -p xxx -f xxx -w 1500`，执行耐克 MAX 申请，在当期的**申请时间**往后延迟 1.5 秒开始；详细参数说明：
    ```shell
    C:\>tsmax.exe nike -h
    
    Usage:
      tsmax nike [flags]
    
    Aliases:
      nike, nk
    
    Flags:
      -p, --password string   用户名: XXXXXXX 的密码
      -f, --file string       上传的excel文件
      -w, --when int          申请时机，与申请时间的间隔多少毫秒：负数=提前几毫秒，正数=延迟几毫秒 (default 0=准时)
      -c, --captcha int       人机验证需要延迟多少毫秒 (default 1000)
      -h, --help              help for nike
    ```

**许可文件配置用户名**

### 支持的操作系统

* Windows
* Linux
* macOS

## 免责声明

本软件仅供学习和研究之用，使用此软件的风险由您自行承担，我们对使用该软件时产生的任何损失概不负责。