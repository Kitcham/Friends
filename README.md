# [Kitcham永远的好伙伴](https://blog.uiharu.top/links/)

那你是想跟我交换友链啦！那就赶紧看看以下的操作指引吧~~

## 基本要求

- 首先呢，网站希望是已经启用 SSL 的
- 同时网站一定确保可以稳定运行
- 然后……就没有然后了

## 如何交换友链？

当你已经确定满足上述要求了，那么非常欢迎一起交流！

那么如何操作呢？

- 先将本站信息加入贵站友链
    - 网站名称：`无垠的有底洞`
    - 网站地址：`https://blog.uiharu.top/`
    - 网站图标：`https://cdn.uiharu.top/blog/home/img/avatar-link.png`
    - Gravatar：`https://gravatar.loli.net/avatar/55c5609dea7dccada762393f19dfb6c0?s=200`
    - Slogan：`生命洋溢亦无凭无记`
- 准备一个 Logo
- 准备需展示的网站名称
- 准备一个 Slogan
- 在 GitHub 上 Fork 这个仓库
- 修改 `src/links.yml` 文件：
  - 按照以下格式将你的网站信息添加到 `links.yml` 文件中：
    ```yaml
    "站点名称": # 请使用双引号包裹
      url: https://example.com # 贵站的 URL
      img: https://example.com/example.png # 贵站 Logo 的 URL
      text: "Hello, World" # Slogan，请使用双引号包裹
- 完成上述步骤后，请新建一个 Pull Request。
- 当 Pull Request 被 Review 并被通过、合并后，你的网站将会在 12 个小时内展示在 [Kitcham的友链页面](https://blog.uiharu.top/links/)

**TIPS：**当完成我友链信息的添加后，引用图标为 `404` 状态时，请不要紧张，这是因为贵站未添加到 CDN 的白名单中。一旦友链 PR 获得通过，贵站将同时进入到 CDN 白名单当中！

## 大功告成

当你看到这句话时，你已经~~完成了50%了~~全部完成了！