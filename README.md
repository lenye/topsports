# topsports

## 滔博货控，MAX 申请助手

- 指定时间完成申请
- 自动人机验证

### 上手指南

#### 安装

下载 [最新版本](https://github.com/lenye/topsports/releases/tag/v25.6.1)

#### windows 操作系统

1. 解压下载文件 topsports-max_v25.6.1_windows_x86_64.zip；
2. 运行`tsmax.exe nike -p xxx -f xxx -w 2000`，耐克当期**申请时间**往后延迟2秒开始申请
    ```shell
    C:\>tsmax.exe nike -h
    滔博货控-耐克~MAX~申请
    
    Usage:
      topsports-max nike [flags]
    
    Aliases:
      nike, nk
    
    Flags:
      -p, --password string   用户: XXXXXXX 的密码
      -f, --file string       上传的excel文件
      -w, --when int          申请时机，与申请时间的间隔多少毫秒：负数=提前几毫秒，正数=延迟几毫秒 (default 0=准时)
      -c, --captcha int       人机验证需要延迟多少毫秒 (default 1000)
      -h, --help              help for nike
    ```

**用户名的配置在许可文件中**

### 支持的操作系统

* Windows
* Linux
* macOS