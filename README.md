# iview-vue-axios-snippets
---
本插件包含了iview、vue、axios、ajax的以及一些常用代码的代码片段

### 使用方式

1.简单粗暴型：  
（1）在 vscode 工作区新建一个 .vscode 文件夹  
（2）把 snippets 文件夹下的文件复制粘贴到刚才新建的文件夹下，就可以使用了

2.本地离线安装：  
（1）复制 iview-vue-axios-snippets-0.0.4.vsix 文件到 vscode 的安装目录的 bin 目录下  
（2）在当前目录打开命令行工具，运行一下代码：
```
code --install-extension iview-vue-axios-snippets-0.0.4.vsix
```

或者点击扩展，点击右上角的三个点，点击从 vsix 安装。

**3.插件中心搜索 iview-vue-axios-snippets 进行安装 （推荐）**

### 命令列表
说明：可以按tab切换光标移动，光标到达某些位置会出现配置可选项，按上、下选择，回车确认。
#### 1、iview 部分
| 命令缩写 | 描述 |
| ---     | --- |
| i-btn | 默认 Button 组件 |
| i-btn-primary | type = primary Button 组件 |
| i-btn-ghost | 幽灵 Button 组件 |
| i-row | 包含 Row 和 Col 的组件片段 |
| i-row-gutter | 有间距的包含 Row 和 Col 的组件片段 |
| i-row-flex | flex 布局的栅格组件|
| i-col | Col 组件 |
| i-icon | Icon 组件|
| i-tab | 普通的 Tab 组件|
| i-tab-card | 卡片类型可关闭的 Tab 组件 |
| i-dropdown | Dropdown 组件 |
| i-steps | Steps 组件 |
| i-input | 普通的 Input 组件 |
| i-input-clearable | 可清楚的 Input 组件 |
| i-input-prefix-suffix | 带前后缀的 Input 组件 |
| i-textarea | Textarea 组件 |
| i-radio | 普通的 Radio 组件 |
| i-radio-group | 按钮组的 Radio 组件 |
| i-checkbox | 普通的 Checkbox 组件 |
| i-checkbox-group | Checkbox 组 |
| i-table | Table 组件 |
| i-table-page | 带 Page 组件的 Table 组件 |
| i-select | Select 组件 |
| i-date | DatePicker 日期组件 |
| i-inputnumber | InputNumber 数字输入框组件 |
| i-form | Form 组件 包含通用的输入组件 |
| i-alert | Alert 组件 |
| i-message | Message 组件 | 
| i-upload | Upload 上传组件 |
| i-modal | 自定义页脚的 Modal 组件|
| i-modal-confirm | Modal 的确认框组件 |
| i-tooltip | 自定义内容的 Tooltip 组件 |
| i-poptip | Poptip 组件 |

#### 2、vue 模板部分

| 命令缩写 | 描述 |
| ---     | --- |
| vue | vue 模板 |
| vuets | vue ts 模板 |

#### 3、自封装 ajax 部分

| 命令缩写 | 描述 |
| ---     | --- |
| imaj | import ajax from '@/libs/...' 目录可选 ajax 或 request |
| ajget | ajax.get() 方法 |
| ajpost | ajax.post() 方法 |
| ajput | ajax.put() 方法 |
| ajd | ajax.delete() 方法 |
| ajreq | ajax.req() 参数需要自定义 |
| exapi |  导出一个 return 的请求方法 |
例： 
```
export function name (data) {
  return ajax.get('/api', data)
}
```

#### 4、axios 部分
说明：这里使用 axios 默认都是 this.$axios 形式，如果不是请自行在main.js里配置或做适量删除。
| 命令缩写 | 描述 |
| ---     | --- |
| imax | import axios from 'axios' |
| axg | axios get 方法 |
| axpo | axios post 方法 |
| axpu | axios put 方法 |
| axd |  axios delete 方法 |
| axall | axios all 方法 |

#### 5、jxrt 自用部分
注意：自用部分，没有可忽略
| 命令缩写 | 描述 |
| ---     | --- |
| imstate | import { mapState, mapActions } from 'vuex' |
| imdownfile | import { downloadFile } from '@/libs/util' |
| imukeycredit | import UkeyCredit from '@/libs/ukey-credit' |
| imutil | import { ... } from '@/libs/util' |