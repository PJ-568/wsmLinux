# 开发

## 初始化

1. [复刻（Fork）本仓库](https://github.com/PJ-568/wsmLinux/fork)；
2. 克隆（clone）仓库：`git clone https://github.com/<您的有用户名>/wsmLinux.git`；
3. 克隆素材仓库：`git clone https://github.com/leaningtech/webvm.git`；
4. 复制素材至 `wsmLinux` 文件夹：

```shell
cp webvm/xterm wsmLinux/xterm
cp webvm/network.js wsmLinux/network.js
cp webvm/scrollbar.css wsmLinux/scrollbar.css
cp webvm/serviceWorker.js wsmLinux/serviceWorker.js
```

## 提交更改

1. 进入 `wsmLinux` 进行开发；
2. 推送提交：

```shell
git add -A
git commit -am "更改"
git push
```

3. 前往 `https://github.com/<您的有用户名>/wsmLinux` 提交推送请求（pull request）；
