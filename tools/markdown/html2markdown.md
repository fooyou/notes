# html 转换成 markdown的 shell 插件

1. 将html2markdown.sh 拷贝到 /usr/local/bin 等系统Path下。
2. 运行命令：
    - html2markdown.sh www.baidu.com > baidu.md
    - html2markdown.sh index.html > index.md

可得到远程url的markdown文本和本地html的markdown文本。

运行脚本，可能会提示你缺少pandoc和tiny软件，直接安装即可：

    sudo apt-get install pandoc tiny
