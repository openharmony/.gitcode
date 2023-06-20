# .gitee

#### 介绍

仓库`.gitee`用于对[OpenHarmony组织](https://gitee.com/openharmony)进行全局配置Issue、Pull Request模板。

#### Issue 模板

Gitee 为 Issue 提供了模板能力支持，支持仓库通过模板配置预设不同内容的 Issue 模板，以提升改进用户提出特性建议、反馈问题的互动体验。关于Issue模板化的更多信息，请访问Gitee产品文档[Gitee Issue 模板功能支持](https://help.gitee.com/issue/templates)。

仓库`.gitee`提供了全局的Issue模板，为[OpenHarmony组织](https://gitee.com/openharmony)下的所有代码仓库提供了通用的模板。如果需要对特定的代码仓库的Issue模板进行定制，可以在代码仓根目录下创建`.gitee/ISSUE_TEMPLATE`目录，维护相应的Issue模板。代码仓库Issue模板的优先级较高，会替代仓库`.gitee`下的全局通用Issue模板。

> 注意：对于企业版的仓库，为使Issue模板生效，需要对仓库进行设置。
> 
> 进入设置：管理->仓库设置->功能设置，在`启用Issue功能`设置下，选择`使用仓库 Issue Template 作为模版`。

#### Pull Request模板

开发中。

#### 参与贡献

1. Fork 本仓库
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request
