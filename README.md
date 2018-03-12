# change responsity

<https://mirrors.tuna.tsinghua.edu.cn/deepin>

# xx-net

<https://github.com/XX-net/XX-Net/wiki/%E5%9C%A8Linux%E4%B8%8B%E5%A6%82%E4%BD%95%E5%B0%86XX-Net%E4%BD%9C%E4%B8%BA%E5%90%8E%E5%8F%B0%E6%9C%8D%E5%8A%A1%E5%90%AF%E5%8A%A8>

<https://github.com/XX-net/XX-Net/wiki/GoAgent-Import-CA>

```
cd /etc/init.d
sudo ln -s /home/##yourName##/XX-Net/xx_net.sh xx_net
sudo systemctl enable xx_net
```

# source-code-pro

```
git clone https://mirrors.tuna.tsinghua.edu.cn/adobe-fonts/source-code-pro.git
```

install source-code-pro

# python

修改 ~/.pip/pip.conf

```
[global]
index-url = https://pypi.tuna.tsinghua.edu.cn/simple
pip pip3 install numpy matplotlib pandas pyserial xlrd tensorflow
```

# latex

```
tlmgr option repository https://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/texlive/tlnet
```

# spacemacs

<https://github.com/syl20bnr/spacemacs>

```
git clone https://github.com/syl20bnr/spacemacs ~/.emacs.d
```

添加下面的代码到.spacemacs的dotspacemacs/user-init()


```
(setq configuration-layer--elpa-archives
    '(("melpa-cn" . "http://mirrors.tuna.tsinghua.edu.cn/elpa/melpa/")
      ("org-cn"   . "http://mirrors.tuna.tsinghua.edu.cn/elpa/org/")
      ("gnu-cn"   . "http://mirrors.tuna.tsinghua.edu.cn/elpa/gnu/")))
```

# golang

写入/etc/environment

```
export GOPATH=/home/shuaizhao/software/go:/home/shuaizhao/Documents/workspace/go
```

```
git clone https://github.com/golang/tools.git $GOPATH/src/golang.org/x/tools
```

# 小书匠配置(可选)

github token

# git配置

```
git config --global user.email "zhaoyd14@163.com"
git config --global user.name "yushuaizhao"
```

记住密码

```
git config --global credential.helper store
```

