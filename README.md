# 如何安装 Bright Data SSL 证书

- 使用 Bright Data 的[住宅代理](https://www.bright.cn/proxy-types/residential-proxies)、[网络解锁器](https://www.bright.cn/products/web-unlocker)或[搜索引擎 API](https://www.bright.cn/products/serp-api)时，需要安装 SSL 证书，以确保你的主机与目标网站之间保持安全、端到端加密的连接。
- 你可以按照以下步骤手动安装 SSL 证书，也可以运行一个简单的脚本（推荐）
- 如果你暂时不想安装 SSL 证书，可以先在代码中忽略 SSL 错误。查看方法。 


## 安装：自动方法

### Linux：
1. 下载安装脚本。
2. 运行 chmod +x brightdata，使脚本变为可执行文件
3. 运行安装脚本

## 安装：手动方法：

### Windows：
1. 下载证书。
2. 打开下载的文件，然后在弹窗中点击“打开”。
3. 点击“安装证书...”。
4. 点击“下一步”，然后点击“完成”，以完成安装流程。

### Linux：
1. 下载证书。
2. 将下载的证书文件复制到 /usr/local/share/ca-certificates/ 文件夹。
3. 运行 sudo update-ca-certificates。命令输出应显示已添加 1 个证书。

### macOS：
1. 下载证书。
1. 双击下载的证书文件。“钥匙串访问”将会打开。
1. 双击“Brightdata.com”证书。随后会弹出证书设置窗口。
1. 在“使用此证书时”下，选择“始终信任”。
1. 关闭弹窗。
1. 出现提示时输入你的凭据
