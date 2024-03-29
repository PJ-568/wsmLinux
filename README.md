# 开发文档

> Linux 用户请使用 bash 执行以下命令。
>
> Windows 用户请使用 powershell 执行以下命令。

## 初始化

1. [*复刻（Fork）本仓库*](https://github.com/PJ-568/wsmLinux/fork)；
2. 执行命令以克隆（clone）您复刻的仓库至本地：`git clone https://github.com/<您的有用户名>/wsmLinux.git`；
3. 执行命令以克隆素材仓库至本地：`git clone https://github.com/leaningtech/webvm.git`；
4. 执行以下命令以复制素材至 `wsmLinux` 文件夹：

```shell
cp -r webvm/xterm wsmLinux/xterm
cp webvm/network.js wsmLinux/network.js
cp webvm/scrollbar.css wsmLinux/scrollbar.css
cp webvm/serviceWorker.js wsmLinux/serviceWorker.js
```

## 提交更改

1. 进入 `wsmLinux` 文件夹进行开发；
2. 在 `wsmLinux` 文件夹执行以下命令以推送提交：

```shell
git add -A
git commit -am "更改"
git push
```

3. 前往 `https://github.com/<您的有用户名>/wsmLinux` 点击*贡献（Contribute）*；
4. 点击*提交推送请求（Open pull request）*。

## 同步更改

> 若欲同步原仓库的最新更改：

1. 前往 `https://github.com/<您的有用户名>/wsmLinux` 点击*同步复刻（Sync fork）*；
2. 点击*更新分支（Update branch）*；
3. 在 `wsmLinux` 文件夹执行命令以将远端更新应用至本地：`git pull`；
