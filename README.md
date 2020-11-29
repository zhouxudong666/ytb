# Github-actions-youtube-dl ![do](https://github.com/Heraldik/github-actions-youtube-dl/workflows/do/badge.svg)

使用 GitHub Actions 下载 YouTube 最高画质视频，并自动发布到 Release。

## 使用

- Fork 本仓库 或者 Use this template。

![image-20201128114406344](README.assets/image-20201128114406344.png)

- 创建好自己的仓库后，在 Actions 中启用 GitHub Actions（Use this template 默认启用）。

![image-20201128114243884](README.assets/image-20201128114243884.png)

- *按需更改 config.txt 中的内容（非必要步骤，可以在此调整 youtube-dl 的下载参数）*。
- 将你要下载的 YouTube 视频的地址填进 **playlist.txt** 中，每行限一个视频链接，commit push 提交。

![image-20201128121024007](README.assets/image-20201128121024007.png)

- Actions 自动运行后会将所有下载好的视频打包成 downloads.tar.gz 发布到 **Release** 中。
- 进入 Release，下载打包好的压缩文件。

![image-20201128114604022](README.assets/image-20201128114604022.png)

## License

[MIT](https://github.com/Heraldik/github-actions-youtube-dl/blob/main/LICENSE) © Heraldik

## 鸣谢

[justjavac](https://github.com/justjavac/github-actions-youtube-dl)

