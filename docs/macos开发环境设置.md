
## brew 安装

功能：管理几乎所有 mac 开发工具，后续安装软件都会用到

1. 安装 brew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Git

系统自带，无需安装。

### 配置 ssh


1. 生成 ssh key

```
ssh-keygen -t ed25519 -C "邮箱"
```

一直按回车，不要设置密码
