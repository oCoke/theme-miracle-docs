---
title: 安装主题
type: docs
---

Hexo 是一个基于 Node.js 的静态页面生成工具，你可以前往 [Hexo 官方文档](https://hexo.io/zh-cn/docs/) 学习如何安装及初始化 Hexo。本文档仅包含主题相关的配置，Hexo 方面将不再赘述。

{% note danger %}
接下来的文档中，我们已经默认你**已经配置好 Hexo 并用其创建了一个站点**。
{% endnote %}

在 Hexo 站点及主题目录各有一个 `_config.yml` 文件用于存放相关配置，请勿混淆。

下文为描述方便，我们将位于 站点根目录 的 `_config.yml` 称为「站点配置文件」，将位于主题目录内的 `_config.yml` 称为「主题配置文件」。

## 获取主题

### 发行版

你可以前往 [发行版](https://github.com/hifun-team/hexo-theme-miracle/releases) 下载，选择你需要的版本（推荐最新版本），在该页面中找到对应的 Assets 区域，下载 Source Code 到本地。

然后将压缩包解压到站点目录的 `themes` 文件夹内，并更名为 `miracle`。

最后修改站点目录下的 _config.yml 文件：

```yaml
lang: zh-CN # 可选项，用与匹配语言文件
theme: miracle # 指定主题
```

### NPM

在站点目录下执行以下命令：

```bash
npm install hexo-theme-miracle —-save
```

在站点目录下创建 _config.miracle.yml，将主题的 [_config.yml](https://github.com/hifun-team/hexo-theme-miracle/blob/master/_config.yml) 内容复制过去。

修改站点目录下的 _config.yml 文件：

```yaml
lang: zh-CN # 可选项，用与匹配语言文件
theme: miracle # 指定主题
```

### Git

在站点目录下执行以下命令：

```bash
git clone https://github.com/hifun-team/hexo-theme-miracle.git themes/miracle
```

修改站点目录下的 _config.yml 文件：

```yaml
lang: zh-CN # 可选项，用与匹配语言文件
theme: miracle # 指定主题
```

