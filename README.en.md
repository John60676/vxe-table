# vxe-table

[![gitee star](https://gitee.com/xuliangzhan_admin/vxe-table/badge/star.svg?theme=dark)](https://gitee.com/xuliangzhan_admin/vxe-table/stargazers)
[![npm version](https://img.shields.io/npm/v/vxe-table.svg?style=flat-square)](https://www.npmjs.org/package/vxe-table)
[![npm build](https://travis-ci.org/xuliangzhan/vxe-table.svg?branch=master)](https://travis-ci.org/xuliangzhan/vxe-table)
[![npm downloads](https://img.shields.io/npm/dm/vxe-table.svg?style=flat-square)](https://npm-stat.com/charts.html?package=vxe-table)
[![gzip size: JS](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/index.min.js?compression=gzip&label=gzip%20size:%20JS)](https://unpkg.com/vxe-table/lib/index.min.js)
[![gzip size: CSS](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/index.css?compression=gzip&label=gzip%20size:%20CSS&color=green)](https://unpkg.com/vxe-table/lib/index.css)  
[![issues](https://img.shields.io/github/issues/xuliangzhan/vxe-table.svg)](https://github.com/xuliangzhan/vxe-table/issues)
[![issues closed](https://img.shields.io/github/issues-closed/xuliangzhan/vxe-table.svg)](https://github.com/xuliangzhan/vxe-table/issues?q=is%3Aissue+is%3Aclosed)
[![pull requests](https://img.shields.io/github/issues-pr/xuliangzhan/vxe-table.svg)](https://github.com/xuliangzhan/vxe-table/pulls)
[![pull requests closed](https://img.shields.io/github/issues-pr-closed/xuliangzhan/vxe-table.svg)](https://github.com/xuliangzhan/vxe-table/pulls?q=is%3Apr+is%3Aclosed)
[![npm license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/xuliangzhan/vxe-table/blob/master/LICENSE)

A [vue](https://www.npmjs.com/package/vue) based PC form component, support add, delete, change, virtual scroll, lazy load, shortcut menu, data validation, tree structure, print export, form rendering, data paging, virtual list, modal window, custom template, renderer, flexible configuration items, extension interface, etc...

* 设计理念
  * 面向现代浏览器，高效的简洁 API 设计
  * 模块化表格、按需加载、扩展接口
  * 为单行编辑表格而设计，支持增删改查及更多扩展，强大的功能的同时兼具性能  

* [计划](#donation)
  * [x] v1.0 100% 基于 vue2.6+，支持所有主流的浏览器，实现表格的一切实用的功能
  * [x] v2.0 &nbsp;100% 基于 vue2.6+，支持所有主流的浏览器，同时兼具功能与性能
  * [x] v3.0 &nbsp;&nbsp;60% 基于 vue2.6+，只支持 H5 浏览器，不支持 IE，渲染性能大幅提升
  * [ ] v4.0 &nbsp;&nbsp;0% 基于 vue3+，只支持 H5 浏览器，不支持 IE，渲染性能大幅提升

👉 如果有更好的建议、优化点或 Bug 都欢迎提 [Issues](https://github.com/xuliangzhan/vxe-table/issues/390)

## Browser Support

![IE](https://raw.github.com/alrra/browser-logos/master/src/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png) | ![Edge](https://raw.github.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/src/opera/opera_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/src/safari/safari_48x48.png)
--- | --- | --- | --- | --- | --- |
11+ ✔ | Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ | Latest ✔ |

## Features

* [x] Basic table
* [x] Grid
* [x] Striped
* [x] Table with border
* [x] Cell style
* [x] Column resizable
* [x] Maximum table height
* [x] Resize height and width
* [x] Fixed column
* [x] Grouping table header
* [x] Table footer
* [x] Highlight row and column
* [x] Table sequence
* [x] Radio
* [x] Checkbox
* [x] Select
* [x] Switch
* [x] Sorting
* [x] Filter
* [x] Rowspan and colspan
* [x] Import
* [x] Export
* [x] Print
* [x] Show/Hide column
* [x] Loading
* [x] Formatted cell
* [x] Slot/template
* [x] Context menu
* [x] Expandable row
* [x] Pager
* [x] Form
* [x] Toolbar
* [x] Pulldown
* [x] List
* [x] Editable CRUD
* [x] Tree table
* [x] Validate
* [x] Data Proxy
* [x] Keyboard navigation
* [x] Modal
* [x] Renderer
* [x] Virtual Scroller

## Modules

* Core
  * ![Table](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/table/src/table.min.js?compression=gzip&label=Table)![Body](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/body/src/body.min.js?compression=gzip&label=Body)![Cell](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/cell/src/cell.min.js?compression=gzip&label=Cell)![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/table/style/style.css?compression=gzip&label=style&color=green) (表格)
* Modules
  * ![Icon](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/icon/style/style.css?compression=gzip&label=Icon&color=green) （图标）
  * ![Header](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/header/src/header.min.js?compression=gzip&label=Header)![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/header/style/style.css?compression=gzip&label=style&color=green) （表头）
  * ![Footer](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/footer/src/footer.min.js?compression=gzip&label=Footer)![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/footer/style/style.css?compression=gzip&label=style&color=green) （表尾）
  * ![Filter](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/filter/src/filter.min.js?compression=gzip&label=Filter)![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/filter/style/style.css?compression=gzip&label=style&color=green) （筛选）
  * ![Tooltip](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/tooltip/src/tooltip.min.js?compression=gzip&label=Tooltip)![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/tooltip/style/style.css?compression=gzip&label=style&color=green) （提示信息）
  * ![Menu](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/menu/src/menu.min.js?compression=gzip&label=Menu)![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/menu/style/style.css?compression=gzip&label=style&color=green) （快捷菜单）
  * ![Export](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/export/src/mixin.min.js?compression=gzip&label=Export)![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/export/style/style.css?compression=gzip&label=style&color=green) （导出）
* Component （增强组件）
  * ![Grid](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/grid/src/grid.min.js?compression=gzip&label=Grid)![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/grid/style/style.css?compression=gzip&label=style&color=green) （高级表格）
  * ![Column](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/column/src/column.min.js?compression=gzip&label=Column) （静态列）
  * ![List](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/list/src/list.min.js?compression=gzip&label=List)![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/list/style/style.css?compression=gzip&label=style&color=green) （虚拟列表）
  * ![Form](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/form/src/form.min.js?compression=gzip&label=Form)![FormItem](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/form/src/form-item.min.js?compression=gzip&label=FormItem)![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/form/style/style.css?compression=gzip&label=style&color=green) （表单）
  * ![Pager](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/pager/src/pager.min.js?compression=gzip&label=Pager)![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/pager/style/style.css?compression=gzip&label=style&color=green) （分页 ）
  * ![Toolbar](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/toolbar/src/toolbar.min.js?compression=gzip&label=Toolbar)![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/toolbar/style/style.css?compression=gzip&label=style&color=green) （工具栏）
  * ![Checkbox](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/checkbox/src/checkbox.min.js?compression=gzip&label=Checkbox)![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/checkbox/style/style.css?compression=gzip&label=style&color=green) （复选框）
  * ![Radio](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/radio/src/radio.min.js?compression=gzip&label=Radio) ![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/radio/style/style.css?compression=gzip&label=style&color=green)（单选框）
  * ![Input](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/input/src/input.min.js?compression=gzip&label=Input)![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/input/style/style.css?compression=gzip&label=style&color=green) （输入框）
  * ![Select](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/select/src/select.min.js?compression=gzip&label=Select)![Optgroup](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/select/src/optgroup.min.js?compression=gzip&label=Optgroup)![Option](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/select/src/option.min.js?compression=gzip&label=Option)![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/select/style/style.css?compression=gzip&label=style&color=green) （下拉框）
  * ![Switch](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/switch/src/switch.min.js?compression=gzip&label=Switch) ![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/switch/style/style.css?compression=gzip&label=style&color=green)（开关）
  * ![Modal](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/modal/src/modal.min.js?compression=gzip&label=Modal)![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/modal/style/style.css?compression=gzip&label=style&color=green) （模态窗口）
  * ![Button](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/button/src/button.min.js?compression=gzip&label=Button)![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/button/style/style.css?compression=gzip&label=style&color=green) （按钮）
  * ![Pulldown](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/pulldown/src/pulldown.min.js?compression=gzip&label=Pulldown)![style](https://img.badgesize.io/https://unpkg.com/vxe-table/lib/pulldown/style/style.css?compression=gzip&label=style&color=green) （下拉容器）
* Plugins
  * 增强插件
    * [![vxe-table-plugin-export-pdf](https://img.badgesize.io/https://unpkg.com/vxe-table-plugin-export-pdf/dist/index.min.js?compression=gzip&label=vxe%20table%20plugin%20export%20pdf)](https://www.npmjs.org/package/vxe-table-plugin-export-pdf) ([PDF 导出插件](https://www.npmjs.com/package/vxe-table-plugin-export-pdf))
    * [![vxe-table-plugin-export-xlsx](https://img.badgesize.io/https://unpkg.com/vxe-table-plugin-export-xlsx/dist/index.min.js?compression=gzip&label=vxe%20table%20plugin%20export%20xlsx)](https://www.npmjs.org/package/vxe-table-plugin-export-xlsx) ([XLSX 导出插件](https://www.npmjs.com/package/vxe-table-plugin-export-xlsx))
    * [![vxe-table-plugin-menus](https://img.badgesize.io/https://unpkg.com/vxe-table-plugin-menus/dist/index.min.js?compression=gzip&label=vxe%20table%20plugin%20menus)](https://www.npmjs.org/package/vxe-table-plugin-menus) ([快捷菜单插件](https://www.npmjs.com/package/vxe-table-plugin-menus))
  * 适配插件
    * [![vxe-table-plugin-element](https://img.badgesize.io/https://unpkg.com/vxe-table-plugin-element/dist/index.min.js?compression=gzip&label=vxe%20table%20plugin%20element)](https://www.npmjs.org/package/vxe-table-plugin-element)![style](https://img.badgesize.io/https://unpkg.com/vxe-table-plugin-element/dist/style.min.css?compression=gzip&label=style&color=green) ([element-ui adapter](https://www.npmjs.org/package/vxe-table-plugin-element))
    * [![vxe-table-plugin-iview](https://img.badgesize.io/https://unpkg.com/vxe-table-plugin-iview/dist/index.min.js?compression=gzip&label=vxe%20table%20plugin%20iview)](https://www.npmjs.org/package/vxe-table-plugin-iview)![style](https://img.badgesize.io/https://unpkg.com/vxe-table-plugin-iview/dist/style.min.css?compression=gzip&label=style&color=green) ([iview adapter](https://www.npmjs.org/package/vxe-table-plugin-iview))
    * [![vxe-table-plugin-antd](https://img.badgesize.io/https://unpkg.com/vxe-table-plugin-antd/dist/index.min.js?compression=gzip&label=vxe%20table%20plugin%20antd)](https://www.npmjs.org/package/vxe-table-plugin-antd)![style](https://img.badgesize.io/https://unpkg.com/vxe-table-plugin-antd/dist/style.min.css?compression=gzip&label=style&color=green) ([ant-design-vue adapter](https://www.npmjs.org/package/vxe-table-plugin-antd))

## Docs

[To view the user guide 使用指南](https://github.com/xuliangzhan/vxe-table-demo)

[To view the example](https://xuliangzhan.github.io/vxe-table/#/table/base/basic) [查看演示](https://xuliangzhan_admin.gitee.io/vxe-table/#/table/base/basic)  
[To view the document](https://xuliangzhan.github.io/vxe-table/#/table/api) [查看文档](https://xuliangzhan_admin.gitee.io/vxe-table/#/table/api)  

## Installing

依赖库：[vue](https://www.npmjs.com/package/vue) 2.6+, [xe-utils](https://www.npmjs.com/package/xe-utils) 2.4+

```shell
npm install xe-utils vxe-table
```

Get on [unpkg](https://unpkg.com/vxe-table/) and [cdnjs](https://cdn.jsdelivr.net/npm/vxe-table/)

### npm

```javascript
import Vue from 'vue'
import 'xe-utils'
import VXETable from 'vxe-table'
import 'vxe-table/lib/index.css'

Vue.use(VXETable)
```

### CDN

```HTML
<!-- 引入样式 -->
<link rel="stylesheet" href="https://unpkg.com/vxe-table/lib/index.css">
<!-- 引入脚本 -->
<script src="https://unpkg.com/xe-utils"></script>
<script src="https://unpkg.com/vxe-table"></script>
<!-- 建议使用 CDN 方式引入的用户在链接地址上锁定版本，避免受到非兼容性更新的影响 -->
```

## Example

```html
<template>
  <div>
    <vxe-table :data="tableData">
      <vxe-table-column type="seq" title="Seq" width="80"></vxe-table-column>
      <vxe-table-column field="name" title="Name"></vxe-table-column>
      <vxe-table-column field="sex" title="Sex"></vxe-table-column>
      <vxe-table-column field="address" title="Address"></vxe-table-column>
    </vxe-table>
  </div>
</template>

<script>
export default {
  data () {
    return {
      tableData: [
        { id: 10001, name: 'Test1', role: 'Develop', sex: 'Man', address: 'Shenzhen' },
        { id: 10002, name: 'Test2', role: 'Test', sex: 'Man', address: 'Guangzhou' },
        { id: 10003, name: 'Test3', role: 'PM', sex: 'Man', address: 'Shanghai' }
      ]
    }
  }
}
</script>
```

## Donation

If the open source project is very helpful to you, you can buy the author a cup of coffee.  
如果这个开源项目对您有帮助，请作者喝杯咖啡吧。☕（如果有问题需要支持可以留言或者提 [Issues](https://github.com/xuliangzhan/vxe-table/issues/390)）

[👉 捐赠方式💰](https://xuliangzhan_admin.gitee.io/vxe-table/#/donation/api)  

[![pay](https://gitee.com/xuliangzhan_admin/vxe-table/raw/master/public/static/donation/pay.jpg)](https://xuliangzhan_admin.gitee.io/vxe-table/#/donation/api)

## License

MIT License, 2019-present, Xu Liangzhan