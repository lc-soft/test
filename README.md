<a name="0.4.1"></a>
## [0.4.1](https://gitee.com/mayun-team/gitee-frontend/compare/v0.4.0...v0.4.1) (2018-08-13)


### Bug Fixes

* **filtered-search-box:** this.popFilterValue is not a function ([fb0bcbe](https://gitee.com/mayun-team/gitee-frontend/commits/fb0bcbe))
* **filtered-search-box:** this.updateSearchTerm is not a function ([22a2baf](https://gitee.com/mayun-team/gitee-frontend/commits/22a2baf))
* **filtered-search-box:** 事件处理报错 ([296330a](https://gitee.com/mayun-team/gitee-frontend/commits/296330a))



<a name="0.4.0"></a>
# [0.4.0](https://gitee.com/mayun-team/gitee-frontend/compare/v0.3.1...v0.4.0) (2018-08-13)



<a name="0.3.1"></a>
## [0.3.1](https://gitee.com/mayun-team/gitee-frontend/compare/v0.3.0...v0.3.1) (2018-08-10)


### Bug Fixes

* **filtered-search-box:**  this.data 会被回调函数篡改 ([2bf5778](https://gitee.com/mayun-team/gitee-frontend/commits/2bf5778))


### Performance Improvements

* **filtered-search-box:** 载入完筛选条件后，更新搜索词的位置 ([98f1f2c](https://gitee.com/mayun-team/gitee-frontend/commits/98f1f2c))



<a name="0.3.0"></a>
# [0.3.0](https://gitee.com/mayun-team/gitee-frontend/compare/v0.2.0...v0.3.0) (2018-08-10)


### Features

* **filtered-search-box:** 添加 removeIconClass，用于自定义删除图标样式 ([e079678](https://gitee.com/mayun-team/gitee-frontend/commits/e079678))



<a name="0.2.0"></a>
# [0.2.0](https://gitee.com/mayun-team/gitee-frontend/compare/v0.1.4...v0.2.0) (2018-08-09)


### Bug Fixes

* **filtered-search-box:** item.iconStyle 对已选中的选项没有效果 ([fcb6300](https://gitee.com/mayun-team/gitee-frontend/commits/fcb6300))
* **filtered-search-box:** 新建时间范围筛选时出现 undefined 内容 ([2b7c339](https://gitee.com/mayun-team/gitee-frontend/commits/2b7c339))


### Features

* **filtered-search-box:** 添加支持编辑搜索词 ([2a128d0](https://gitee.com/mayun-team/gitee-frontend/commits/2a128d0))



<a name="0.1.4"></a>
## [0.1.4](https://gitee.com/mayun-team/gitee-frontend/compare/v0.1.3...v0.1.4) (2018-08-07)


### Bug Fixes

* **filtered-search-box:** 移除筛选条件后，数据并未改变 ([d21bc6c](https://gitee.com/mayun-team/gitee-frontend/commits/d21bc6c))
* **filtered-search-box:** 移除筛选条件后，未更新下拉菜单内容 ([c14cf0c](https://gitee.com/mayun-team/gitee-frontend/commits/c14cf0c))



<a name="0.1.3"></a>
## [0.1.3](https://gitee.com/mayun-team/gitee-frontend/compare/v0.1.2...v0.1.3) (2018-08-07)


### Bug Fixes

* **filtered-search-box:** 重设筛选器列表后，在读取选项列表时会报错 ([634d30e](https://gitee.com/mayun-team/gitee-frontend/commits/634d30e))


### Performance Improvements

* **filtered-search-box:** 改进空值判断 ([de03d53](https://gitee.com/mayun-team/gitee-frontend/commits/de03d53))



<a name="0.1.2"></a>
## [0.1.2](https://gitee.com/mayun-team/gitee-frontend/compare/v0.1.1...v0.1.2) (2018-08-06)


### Bug Fixes

* **filtered-search-box:** 取消编辑时间范围筛选器后，未还原正确的值 ([734ac3e](https://gitee.com/mayun-team/gitee-frontend/commits/734ac3e))
* **filtered-search-box:** 编辑筛选器时，会清空原有内容 ([dbb2b3c](https://gitee.com/mayun-team/gitee-frontend/commits/dbb2b3c))



<a name="0.1.1"></a>
## [0.1.1](https://gitee.com/mayun-team/gitee-frontend/compare/ebf5d23...v0.1.1) (2018-08-06)


### Bug Fixes

* **filtered-search-box:** text.placeholder 没有默认值 ([0b87d25](https://gitee.com/mayun-team/gitee-frontend/commits/0b87d25))
* **filtered-search-box:** 下拉框中的操作选项会和普通选项一起被隐藏 ([bc3d90c](https://gitee.com/mayun-team/gitee-frontend/commits/bc3d90c))
* **filtered-search-box:** 不应该显示空的筛选器 ([aaf1f04](https://gitee.com/mayun-team/gitee-frontend/commits/aaf1f04))
* **filtered-search-box:** 当依赖的筛选器为“无”值时，应判断为不满足依赖 ([f2414ca](https://gitee.com/mayun-team/gitee-frontend/commits/f2414ca))
* **filtered-search-box:** 新建筛选条件时点击已选好的选项，不应该隐藏下拉框 ([0ef6ddc](https://gitee.com/mayun-team/gitee-frontend/commits/0ef6ddc))
* **filtered-search-box:** 未正确过滤掉已选中的选项 ([c260f9d](https://gitee.com/mayun-team/gitee-frontend/commits/c260f9d))
* **filtered-search-box:** 点击删除条件选项后，不应编辑该筛选器 ([9e2eed8](https://gitee.com/mayun-team/gitee-frontend/commits/9e2eed8))
* **filtered-search-box:** 点击搜索框里未让输入框获得焦点 ([3ff5b6c](https://gitee.com/mayun-team/gitee-frontend/commits/3ff5b6c))
* **filtered-search-box:** 筛选器多了后内容会溢出搜索框 ([9e052b8](https://gitee.com/mayun-team/gitee-frontend/commits/9e052b8))
* **filtered-search-box:** 编辑可多选的筛选器时没有显示“返回”选项 ([ebf5d23](https://gitee.com/mayun-team/gitee-frontend/commits/ebf5d23))
* **filtered-search-box:** 编辑多选的筛选器时，选择一个选项后不应该退出编辑 ([1874cf1](https://gitee.com/mayun-team/gitee-frontend/commits/1874cf1))
* **filtered-search-box:** 缺少 text.loading 默认值 ([47591cb](https://gitee.com/mayun-team/gitee-frontend/commits/47591cb))
* **filtered-search-box:** 输入筛选器名后按冒号键，没有切换到筛选器的选项编辑模式 ([f1d37dc](https://gitee.com/mayun-team/gitee-frontend/commits/f1d37dc))


### Features

* **demo:** 添加示例页面 ([f6aab8d](https://gitee.com/mayun-team/gitee-frontend/commits/f6aab8d))
* **demo:** 添加筛选搜索框的示例代码 ([4131605](https://gitee.com/mayun-team/gitee-frontend/commits/4131605))
* **filtered-search-box:** 删除筛选器时，其它依赖它的筛选器也会被删除 ([4453d0d](https://gitee.com/mayun-team/gitee-frontend/commits/4453d0d))
* **filtered-search-box:** 已选择的筛选条件支持显示图标、图片和背景色 ([3c2e86c](https://gitee.com/mayun-team/gitee-frontend/commits/3c2e86c))
* **filtered-search-box:** 支持在初始化时加载远程选项数据 ([8d2f0b6](https://gitee.com/mayun-team/gitee-frontend/commits/8d2f0b6))
* **filtered-search-box:** 添加 change 事件 ([c79a96c](https://gitee.com/mayun-team/gitee-frontend/commits/c79a96c))
* **filtered-search-box:** 添加 destroy() 方法 ([243c3da](https://gitee.com/mayun-team/gitee-frontend/commits/243c3da))
* **filtered-search-box:** 添加 filter.requires 参数，用于设置依赖 ([8a74e59](https://gitee.com/mayun-team/gitee-frontend/commits/8a74e59))
* **filtered-search-box:** 添加 setData() 方法 ([de8cf20](https://gitee.com/mayun-team/gitee-frontend/commits/de8cf20))
* **filtered-search-box:** 添加支持 filter.remote.fetcher 参数，用于自定义数据获取方式 ([79e5d30](https://gitee.com/mayun-team/gitee-frontend/commits/79e5d30))
* **filtered-search-box:** 添加支持为筛选器设置“无”选项 ([a36041a](https://gitee.com/mayun-team/gitee-frontend/commits/a36041a))
* 添加 gitee-frontend.scss ([a24c291](https://gitee.com/mayun-team/gitee-frontend/commits/a24c291))
* **filtered-search-box:** 添加支持加载远程数据 ([c69f41a](https://gitee.com/mayun-team/gitee-frontend/commits/c69f41a))
* 添加 FilteredSearchBox.vue ([707e9c8](https://gitee.com/mayun-team/gitee-frontend/commits/707e9c8))
* **filtered-search-box:** 添加支持时间范围筛选器 ([fabefe6](https://gitee.com/mayun-team/gitee-frontend/commits/fabefe6))
* **filtered-search-box:** 添加支持显示占位符 ([4fe9cd4](https://gitee.com/mayun-team/gitee-frontend/commits/4fe9cd4))
* **filtered-search-box:** 添加清空按钮 ([79d957b](https://gitee.com/mayun-team/gitee-frontend/commits/79d957b))
* **fitlered-search-box:** 添加 setFilters() 方法 ([699ca4d](https://gitee.com/mayun-team/gitee-frontend/commits/699ca4d))
* **npm:** 添加示例页面的资源生成脚本 ([a783526](https://gitee.com/mayun-team/gitee-frontend/commits/a783526))


### Performance Improvements

* **demo:** 加上 .ui.container，调整内容间距 ([ce8a5a6](https://gitee.com/mayun-team/gitee-frontend/commits/ce8a5a6))
* **demo:** 补充示例代码 ([3b7c429](https://gitee.com/mayun-team/gitee-frontend/commits/3b7c429))
* **filtered-search-box:** 调整高度 ([ff9d29f](https://gitee.com/mayun-team/gitee-frontend/commits/ff9d29f))


