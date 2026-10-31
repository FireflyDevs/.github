<div align="center">

# FireflyDevs

**流萤的秘密基地**

一个围绕流萤主题、由喜欢流萤的玩家和开发者组成的开放开发组织。

**开发方向和项目类型不限，但所有项目必须与流萤相关。**

[主站](https://xn--qzw410c.love) · [开发预览](https://dev.xn--qzw410c.love) · [FireflyLoveSite](https://github.com/FireflyDevs/FireflyLoveSite) · [组织 Issues](https://github.com/FireflyDevs/.github/issues) · [QQ 群](https://qm.qq.com/q/guZg2hdNE4)

</div>

---

## 开放的项目类型

FireflyDevs 不限制开发方向和项目类型，但**所有项目必须与流萤相关**。

**完全和流萤没有关系的项目，不允许加入 FireflyDevs。**

关联方式可以很宽泛，只要项目主题、内容或服务对象与流萤有关即可：

- 流萤主题网站、个人主页、资料库、图集站
- 流萤同人作品、游戏、插件、浏览器扩展
- 服务于流萤社区的 Bot、API、工具、自动化脚本
- 流萤相关的设计、视觉、动效、文档、教程
- 为 FireflyLoveSite 或流萤社区提供支持的配套项目
- 其他以流萤为主题，或明确服务于流萤同好社区的项目

项目类型不限于网站：桌面应用、移动应用、CLI、AI 应用、游戏、插件等都可以。语言、框架、平台可以自由选择，但项目的核心主题必须是流萤，或者明确服务于流萤社区。

不管项目是 TypeScript、Python、Rust、Go、C++ 还是其他技术栈，只要与流萤相关，都可以申请放到 FireflyDevs 组织下建仓和维护。

> 项目需要合法、遵守 GitHub 平台规则、愿意友善协作，并且与流萤相关。

### 发起新项目

1. 在 [组织 Issues](https://github.com/FireflyDevs/.github/issues) 提交一个「新项目提案」
2. 简单说明：
   - 项目名称和一句话介绍
   - 想做什么、解决什么问题
   - 项目与流萤的具体关联
   - 计划使用的语言或技术
   - 你是否愿意作为项目维护者
   - 是否需要组织协助建仓或配置 CI
3. 维护者会协助在 FireflyDevs 下创建仓库，并邀请你参与维护

项目仓库、README、CI、分支规则都可以按项目自己的需要来定。

如果项目同时包含流萤相关和无关内容，需要确保流萤相关部分是项目的核心主题，而不是只在介绍里提一句流萤。

## 当前项目：FireflyLoveSite

FireflyDevs 目前正在开发 **FireflyLoveSite**，一个面向流萤和《崩坏：星穹铁道》玩家的非官方同好网站。

- 页面：流萤主题首页、角色介绍、图集、视频、资料库
- 内容：角色故事、官方资讯、活动资讯、壁纸与同人作品
- 技术：HTML / CSS / JavaScript + TypeScript + Node.js
- 目标：让喜欢流萤的人有一个可以一起分享、一起建设的地方

当前网站仍在筹备中，页面内容不是最终版本，欢迎大家一起补充和改造。

## 参与开发

所有人都可以参与，不限于代码，也不限于 FireflyLoveSite：

- 前端开发、交互与响应式适配
- UI / 视觉 / 动效设计
- 角色资料、活动资料、图集与视频整理
- 文案、翻译、测试和 Issue 整理
- TypeScript / Node.js 后端与部署
- 新项目发起、技术选型、项目维护
- 其他任何你擅长或想尝试的方向

### 提交 PR

通用流程：

1. Fork 对应的项目仓库
2. 创建功能分支
3. 完成修改并在本地测试
4. 提交 Pull Request，说明修改内容、测试方式和相关 Issue

FireflyLoveSite 的 PR 请提交到 `dev` 分支。PR 会自动运行 TypeScript 类型检查、首页与跳转检查。团队成员发起的 PR 在检查通过后会自动合并到 `dev`，并更新到 [开发预览站](https://dev.xn--qzw410c.love)；外部贡献者的 PR 由维护者审核后合并。

其他项目以各自仓库的 README 和贡献说明为准。

### 加入开发团队

如果你愿意长期参与维护：

1. 在 [组织 Issues](https://github.com/FireflyDevs/.github/issues) 提交「申请加入开发团队」
2. 简单介绍你的 GitHub 用户名、擅长方向、可投入时间和想参与的项目
3. 也可以加入 [QQ 群](https://qm.qq.com/q/guZg2hdNE4) 联系维护者

加入团队后，你可以参与 FireflyLoveSite，也可以发起和维护自己的流萤相关项目。

## 项目链接

| 项目 | 地址 |
| --- | --- |
| FireflyLoveSite | https://github.com/FireflyDevs/FireflyLoveSite |
| 正式站点 | https://流萤.love |
| 开发预览 | https://dev.流萤.love |
| 组织 Issue / 新项目申请 | https://github.com/FireflyDevs/.github/issues |

## FireflyLoveSite 技术栈

| 部分 | 技术 |
| --- | --- |
| 页面 | HTML5 + CSS3 + 原生 JavaScript |
| 服务端 | TypeScript + Node.js |
| 部署 | Nginx + systemd |
| CI/CD | GitHub Actions + dev 分支自动部署 |

## 说明

- FireflyLoveSite 是非官方同人项目，与米哈游 / HoYoverse 及《崩坏：星穹铁道》官方无关。
- 游戏角色、官方图片、音乐、视频等素材版权归原权利人所有。
- 贡献素材前请确认来源与使用授权。
- 其他项目以自己的 README 和声明为准。

---

**愿你也能，找到属于自己的光。**

**也欢迎把你自己的那颗星，带到 FireflyDevs。**
