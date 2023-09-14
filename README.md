简体中文 | [English](./README_EN.md)

<p>
<strong><h2>kilitoの主页</h2></strong>
简单的小主页，原来的看够了，重新弄了一个
</p>

![Snipaste_2023-08-27_22-00-02.png](https://bu.dusays.com/2023/08/27/64eb571014fec.png)


### 功能

- [x] 载入动画
- [x] 站点简介
- [x] Hitokoto 一言
- [x] 日期及时间
- [x] 实时天气
- [x] 时光进度条
- [x] 音乐播放器
- [x] 移动端适配

### 部署

* **安装** [node.js](https://nodejs.org/zh-cn/) **环境**

  > node > 16.16.0  
  > npm > 8.15.0
  
* 然后以 **管理员权限** 运行 `cmd` 终端，并 `cd` 到 项目根目录
* 在 `终端` 中输入：

```bash
# 安装 pnpm
npm install -g pnpm

# 安装依赖
pnpm install

# 预览
pnpm dev

# 构建
pnpm build
```
> 构建完成后，静态资源会在 **`dist` 目录** 中生成，可将 **`dist` 文件夹下的文件**上传至服务器，也可使用 `Vercel` 等托管平台一键导入并自动部署

### 网站链接

在 `src/assets/siteLinks.json` 中可以自定义网站链接（以指向自己的网站）:

