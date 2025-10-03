# <img src='/images/metasfresh-logo-slogan-969x248.png' height='60' alt='metasfresh - 我们做开源 ERP' aria-label='metasfresh.com' /></a>

> 本项目基于 [metasfresh](https://github.com/metasfresh/metasfresh) 搬运，遵循其开源协议（GNU General Public License v2.0）。

> 一个完整开源 ERP 系统，有 Rest API + Web 前端等。适合做企业级业务模板，模块丰富。

[![release](https://img.shields.io/badge/release-5.175-blue.svg)](https://github.com/metasfresh/metasfresh/releases/tag/5.175)
[![license](https://img.shields.io/badge/license-GPL-blue.svg)](https://github.com/metasfresh/metasfresh/blob/master/LICENSE.md)
[![X (formerly Twitter) Follow](https://img.shields.io/twitter/follow/metasfresh?style=social)](https://twitter.com/metasfresh)

metasfresh 是一个响应式、免费且开源的 ERP 系统。我们的目标是打造快速、易用并且具有出色用户体验的企业软件。

> ****我们做开源 ERP****

凭借广泛而细致的功能，metasfresh 适用于寻求高可扩展性和灵活性的工业和贸易公司。

它采用三层架构，包含 Rest-API 以及使用 HTML5/ ReactJS/ Redux 开发的 Web 用户前端。

![metasfresh-sales-order](https://github.com/metasfresh/metasfresh/blob/master/images/sales-order-recording-metasfresh.gif)

<img src="/images/screenshot-kpi-dashboard-new.png" width="33%" alt="KPI 仪表板"></img> <img src="/images/screenshot-sales-order-new.png" width="33%" alt="销售订单窗口"></img> <img src="/images/screenshot-material-receipt-new.png" width="33%" alt="物料收货窗口"></img>

---

## 安装

我们每周五都会发布一个稳定的 metasfresh 版本（年末会跳过一周 ;-)）。你可以在[这里下载](https://metasfresh.com/en/download/#latest-server-update)。

metasfresh 可以通过 **Docker** 或 **Ubuntu 安装程序** 安装。

* **Docker** [如何通过 Docker 设置 metasfresh 堆栈？](https://docs.metasfresh.org/installation_collection/EN/How_do_I_setup_the_metasfresh_stack_using_Docker)
* **Ubuntu** [如何通过安装包安装 metasfresh？](https://docs.metasfresh.org/installation_collection/EN/installer_how_do_install_metasfresh_package.html)

> **入门步骤：**
>
> * [如何登录？](https://docs.metasfresh.org/webui_collection/EN/Login.html)
> * [如何更改界面语言？](https://docs.metasfresh.org/webui_collection/EN/SwitchLanguage)
> * [如何设置我的公司？](https://docs.metasfresh.org/webui_collection/EN/InitialSetupWizard)
> * [如何创建第一个销售订单？](https://docs.metasfresh.org/webui_collection/EN/SalesOrder_recording)
> * [如何创建第一次发货？](https://docs.metasfresh.org/webui_collection/EN/Ship_SalesOrder)
> * [如何创建第一次发票？](https://docs.metasfresh.org/webui_collection/EN/Invoice_SalesOrder)

---

## 文档

如果你是 metasfresh 新手并希望了解更多，可以在以下位置找到我们的文档：

* [管理员](https://docs.metasfresh.org/pages/installation/index_en)
* [用户](https://docs.metasfresh.org/pages/webui/index_en)
* [开发者](https://docs.metasfresh.org/index.html)
* [测试人员](https://docs.metasfresh.org/pages/tests/index_en)

---

## 讨论

如果你有问题、想要讨论或交流新想法，欢迎访问我们的[社区论坛](https://forum.metasfresh.org/)。我们期待与你见面！

---

## 贡献

你想要帮助改进文档、贡献代码或参与功能需求吗？那太棒了，欢迎加入！
在开始之前，请先阅读我们的 [行为准则](https://github.com/metasfresh/metasfresh/blob/master/CODE_OF_CONDUCT.md) 和 [贡献者指南](https://github.com/metasfresh/metasfresh/blob/master/CONTRIBUTING.md)。

### “单仓库”（Monorepo）

如果你只想检出仓库的某些部分，我们建议使用 git 2.25.0 或更高版本，并使用 [git-sparse-checkout](https://www.git-scm.com/docs/git-sparse-checkout) 功能。
示例：

* 初始化：`git sparse-checkout init --clone`

  * 这样你只会得到仓库根目录下的文件（比如你正在阅读的这个文件）
* 获取前端代码：`git sparse-checkout set frontend`
* 检出全部代码：`git sparse-checkout disable`

---

## metasfresh ERP 有哪些新变化？

如果你对 metasfresh ERP 的最新改进或 bug 修复感兴趣，可以查看我们的 [发布说明](https://github.com/metasfresh/metasfresh/blob/master/ReleaseNotes.md)。
