# Rapiddns

Rapiddns.io Data Retrieval

## Description

使用两个接口的数据，使用`all`参数可以同时输出数据到Excel

+ https://rapiddns.io/sameip
+ https://rapiddns.io/subdomain

```powershell
.\rapiddns.exe -h

    ▄▄▄   ▄▄▄·  ▄▄▄·▪  ·▄▄▄▄  ·▄▄▄▄   ▐ ▄ .▄▄ · ▪
    ▀▄ █·▐█ ▀█ ▐█ ▄███ ██▪ ██ ██▪ ██ •█▌▐█▐█ ▀. ██ ▪
    ▐▀▀▄ ▄█▀▀█  ██▀·▐█·▐█· ▐█▌▐█· ▐█▌▐█▐▐▌▄▀▀▀█▄▐█· ▄█▀▄
    ▐█•█▌▐█ ▪▐▌▐█▪·•▐█▌██. ██ ██. ██ ██▐█▌▐█▄▪▐█▐█▌▐█▌.▐▌
    .▀  ▀ ▀  ▀ .▀   ▀▀▀▀▀▀▀▀• ▀▀▀▀▀• ▀▀ █▪ ▀▀▀▀▀▀▀▀ ▀█▄▀▪

     @Auth: C1ph3rX13
     @Blog: https://c1ph3rx13.github.io
     @Note: 代码仅供学习使用，请勿用于其他用途

usage: rapiddns.exe [-h] -t TARGET {subdomain,sameip,all}

Rapiddns.io Data Retrieval By C1ph3rX13

positional arguments:
  {subdomain,sameip,all}
                        Action to perform

optional arguments:
  -h, --help            show this help message and exit
  -t TARGET, --target TARGET
                        Target domain
```

