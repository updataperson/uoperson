# Style

<details>
<summary>6.0.86 (2026/09/22)</summary>

- 优化：插件更新接入下载进度与取消并补充多语言提示

</details>

<details>
<summary>6.0.85 (2026/09/21)</summary>

- 修复：期刊标签设置中重复的 API Key 和 Fields
- 修复：垂直标签页刷新打断悬停动画导致闪烁

</details>

<details>
<summary>6.0.84 (2026/09/21)</summary>

- 修复：垂直标签页移出左侧栏后偶尔不收起

</details>

<details>
<summary>6.0.83 (2026/09/20)</summary>

- 修复：被引数列在重启后丢失 Google 验证 Cookie

</details>

<details>
<summary>6.0.82 (2026/09/20)</summary>

- 修复：垂直标签页拖拽中断后宽度仍随鼠标变化
- 修复：垂直标签页在阅读器获取焦点时误收起
- 修复：被引数标签根据实际对比度自动反白
- 修复：垂直标签页悬停时意外回缩
- 优化：Google Scholar 共享验证会话并限制请求频率

</details>

<details>
<summary>6.0.81 (2026/09/20)</summary>

- 优化：垂直标签页悬停退出动画
- 修复：垂直标签页的文献库图标和名称随分类同步
- 新增：JEV 文献分类预览与撤销
- 修复：垂直标签页收起后图标横向漂移

</details>

<details>
<summary>6.0.80 (2026/09/19)</summary>

- 新增：期刊标签 API Key 申请按钮
- 新增：期刊标签支持双向别名查询与评级合并

</details>

<details>
<summary>6.0.79 (2026/09/16)</summary>

- 优化：被引数列设置的字段修改
- 新增：被引数列 FWCI 字段

</details>

<details>
<summary>6.0.78 (2026/09/15)</summary>

- 优化：支持颜色与标签联动筛选

</details>

<details>
<summary>6.0.76 (2026/09/13)</summary>

- 修复：输入批注时误触发侧边栏快捷键

</details>

<details>
<summary>6.0.75 (2026/09/13)</summary>

- 修复：固定 Windows 侧栏切换图标布局

</details>

<details>
<summary>6.0.74 (2026/09/12)</summary>

- 优化：移除页边批注工具栏边框
- 修复：标注管理支持独立附件

</details>

<details>
<summary>6.0.73 (2026/09/08)</summary>

- 修复 已知问题

</details>

<details>
<summary>6.0.72 (2026/09/08)</summary>

- 修复 已知问题

</details>

<details>
<summary>6.0.71 (2026/09/08)</summary>

- 修复：批注复制使用宿主窗口的文本解析器
- 修复：被引数为零时隐藏对应标签
- 修复：批注文本复制后无法粘贴
- 修复：缓存失效后重绘 Collection 文献数

</details>

<details>
<summary>6.0.70 (2026/09/08)</summary>

- 优化：精简功能统计授权卡片，优化玻璃质感与 SVG 图标
- 修复：按钮文字裁切
- 优化：首次提示显示于标题下；选择后的统计设置移至页面底部，再次展开仍保留在底部

</details>

<details>
<summary>6.0.69 (2026/09/08)</summary>

- 修复：同日撤回后重新同意分享统计时重复累计
- 优化：完善隐私说明

</details>

<details>
<summary>6.0.68 (2026/09/08)</summary>

- 修复：批注文本复制后无法粘贴，并使用宿主窗口的文本解析器
- 修复：被引数为零时隐藏对应标签
- 修复：缓存失效后重新绘制集合文献数
- 新增：可选功能使用统计与多语言隐私设置，可随时关闭

</details>

<details>
<summary>6.0.67 (2026/09/05)</summary>

- 修复：切换文献时附件预览不自动跟随

</details>

<details>
<summary>6.0.66 (2026/09/05)</summary>

- 优化：附件预览自适应后显示以避免缩放跳变
- 修复：切换附件后预览只能显示一页
- 修复：避免条目树未就绪时刷新列报错
- 修复：避免条目树列注销警告
- 修复：取消过期阅读器对照渲染
- 修复：释放阅读器快照数据引用
- 修复：关闭阅读器后释放 PDF 样式资源
- 修复：释放已关闭阅读器的样式文档引用
- 修复：释放已关闭阅读器的版本按钮
- 修复：限制阅读时长缓存增长

</details>

<details>
<summary>6.0.65 (2026/09/04)</summary>

- 修复：释放搜索建议抑制状态
- 修复：集合文献数首次渲染不显示
- 修复：完善功能生命周期与异步资源释放
- 修复：避免搜索结果被迟到刷新清除
- 修复：释放异步翻译与回链预览资源
- 修复：阻止条目框清理后的迟到注册
- 优化：限制条目树页码缓存
- 修复：取消停止后的知网请求
- 修复：收尾条目树定时器异常
- 修复：回收条目树全局资源

</details>

<details>
<summary>6.0.64 (2026/09/03)</summary>

- 新增：支持暂停和恢复阅读进度记录

</details>

<details>
<summary>6.0.63 (2026/09/02)</summary>

- 修复：隔离条目树功能启动失败
- 修复：隔离被引数列的窗口宿主

</details>

<details>
<summary>6.0.62 (2026/09/01)</summary>

- 修复：统一阅读模式内容边界缓存
- 修复：标注颜色名称溢出阅读器弹窗
- 修复：避免阅读模式空几何缓存
- 优化：合并页边批注翻译布局刷新
- 优化：关闭连接线时跳过 SVG 布局
- 优化：缓存阅读模式批注几何
- 优化：几何刷新跳过连接线动画
- 优化：减少页边批注布局重复扫描
- 优化：滚动时跳过页边批注选中状态读取
- 优化：缓存页边批注滚动投影

</details>

<details>
<summary>6.0.61 (2026/09/01)</summary>

- 修复：页边标注错页并优化滚动性能
- 修复：启动时集合树重复刷新导致闪烁

</details>

<details>
<summary>6.0.60 (2026/09/01)</summary>

- 修复：让 Style 更新检查匹配 Zotero
- 修复：清理残留的被引数列注册

</details>

<details>
<summary>6.0.59 (2026/08/31)</summary>

- 修复：使用原始文件 CDN 检查自动更新
- 修复：统一偏好设置标签页初始化
</details>

<details>
<summary>6.0.25 (2026/08/02)</summary>

- 优化：画布引用与标注操作流程

</details>

<details>
<summary>6.0.23 (2026/07/28)</summary>

- 新增：评级标签与页边标注控制

</details>

<details>
<summary>5.7.8</summary>

- 修复：Win右键标签页无`分配到标签组`的bug

</details>

<details>
<summary>5.3.2</summary>

- AI生成简记支持生成没有摘要的条目（会读取pdf第一页进行生成）
- PDF预览支持选中文本并复制

</details>

<details>
<summary>5.1.9</summary>

- 修复：附件预览只显示一页

</details>

<details>
<summary>5.1.5</summary>

- 文献矩阵的核心字段支持自动配置
- 文献矩阵的标注支持用评论替换标注文本，避免标注文本为英文且过长，影响阅读体验

</details>

<details>
<summary>5.0.8</summary>

- 文献矩阵核心字段支持自动根据标注颜色配置，只需要点击配置核心字段，清空里面内容，再关闭就会提示是否自动配置
- Explore面板笔记预览变更，双击可独立窗口打开笔记以预览全部/编辑笔记

</details>

<details>
<summary>5.0.7</summary>

- 嵌套标签搜索不区分大小写
- 修复：标注侧边栏颜色名称被误修改bug

</details>

<details>
<summary>5.0.0</summary>

- Annotation Manager 搜索不区分大小写
- Annotation Manager 搜索关键词高亮

</details>

<details>
<summary>4.9.8</summary>

- Add Tags 增加选择的tags编辑框
- 列设置增加重置按钮，防止设置出错找不到默认值

</details>

<details>
<summary>4.9.3</summary>

文献矩阵支持插件注册列，比如期刊标签，则在辅助字段填写`publicationTags`，英文逗号与之前的字段分开。

下表的Field都可以写入辅助字段中。

|列名称|Field|
|---|---|
|期刊标签|publicationTags|
|被引数|citedCount|
|影响因子|IF|
|简记|remark|
|标签|tags|
|评级|rating|
|#标签|textTags|

效果预览
![效果预览](https://ice.frostsky.com/2024/09/18/3c612ba7135fc1d2a90ce545d7bb8160.png)


</details>

<details>
<summary>4.9.2</summary>

修复标签选择器黑色标签（本应有颜色）

</details>

<details>
<summary>4.9.0</summary>

新增侧边栏`TLDR`，太长不读，数据来自Semantics Scholar API，基于AI总结文章，用一句话概括文章。可理解为精简版摘要。支持翻译

</details>

<details>
<summary>4.8.9</summary>

修复图片粘贴到笔记不显示bug

</details>

<details>
<summary>4.8.8</summary>

支持快速`展开/折叠`左右侧边栏：
* 支持设定快捷键
* 支持主界面
* 支持阅读界面
* 支持笔记界面（安装Better Notes后笔记可在Tab打开，此处指这个界面）
* 主界面添加展开/折叠按钮
</details>

<details>
<summary>4.8.7</summary>

修复`嵌套标签`页面过滤bug

</details>

<details>
<summary>4.8.6</summary>
标注管理支持显示快照的标注
</details>

# GPT

<details>
<summary>3.1.181 (2026/10/05)</summary>

- 修复：Reader 对话切换后问题气泡偶发无法置顶

</details>

<details>
<summary>3.1.180 (2026/09/30)</summary>

- 优化：侧边栏UI问题

</details>

<details>
<summary>3.1.179 (2026/09/28)</summary>

- 修复：问题悬停展开与滚动及流式回答互相冲突
- 修复：长引用吸顶闪烁和底部滚动受阻
- 优化：引用块悬停显示独立来源跳转按钮

</details>

<details>
<summary>3.1.178 (2026/09/27)</summary>

- 修复：页面截图在 Zotero 10 中超时失败
- 修复：侧边栏删除全部消息后恢复欢迎消息

</details>

<details>
<summary>3.1.177 (2026/09/27)</summary>

- 修复：外部插件调用浮窗时无法停止生成
- 修复：文献综述恢复来源跳转按钮

</details>

<details>
<summary>3.1.176 (2026/09/26)</summary>

- 修复：侧边栏未加载对话时误报失败

</details>

<details>
<summary>3.1.175 (2026/09/26)</summary>

- 修复：插件联动兼容旧版扩展与油猴脚本

</details>

<details>
<summary>3.1.174 (2026/09/26)</summary>

- 修复：侧边栏和浮窗样式加载失效

</details>

<details>
<summary>3.1.173 (2026/09/26)</summary>

- 修复：Pro 前台自动恢复并隔离旧版插件时钟

</details>

<details>
<summary>3.1.172 (2026/09/25)</summary>

- 新增：Pro 诊断日志记录授权事件并随复制诊断信息导出

</details>

<details>
<summary>3.1.171 (2026/09/24)</summary>

- 修复：提高稳定性

</details>

<details>
<summary>3.1.170 (2026/09/24)</summary>

- 修复：侧栏历史引用全量扫描与重复绑定导致的卡顿
- 新增：侧栏切换现场耗时诊断脚本
- 修复：AI 标注无法解析联动模型的思考内容
- 优化：AI 标注与大纲结束提示统一三秒后消失

</details>

<details>
<summary>3.1.169 (2026/09/22)</summary>

- 优化：侧边栏划词工具栏与标注颜色菜单
- 新增：侧边栏支持低中高奇偶反差设置
- 修复：浏览器连接器兼容新旧 ChatGPT 回答结构

</details>

<details>
<summary>3.1.168 (2026/09/22)</summary>

- 修复：网页联动报错直接显示 Markdown 源码
- 优化：侧边栏标注选中边框与编辑工具条
- 修复：macOS 重开窗口后侧边栏遗漏历史初始化

</details>

<details>
<summary>3.1.167 (2026/09/20)</summary>

- 修复：侧边栏历史消息无法跳转及定位偏离起点

</details>

<details>
<summary>3.1.166 (2026/09/20)</summary>

- 修复：自动兼容不支持流式用量的模型接口
- 修复：Connector 用量统计移除缓存指标
- 修复：OpenAI Chat 流式请求返回用量信息
- 修复：模型配置完整保存参数和开关状态
- 修复：API 聊天的思考内容解析与流式结束识别

</details>

<details>
<summary>3.1.165 (2026/09/19)</summary>

- 修复：全文总结重复发送已上传 PDF 的正文
- 修复：AI 标注按自定义提示词生成内容
- 修复：文库切换文献后无法继续或管理对话
- 优化：对话管理器按需加载截图历史并限制缓存
- 修复：侧边栏空会话重命名后无法保存消息
- 修复：侧边栏会话切换保存错位并按需加载截图历史

</details>

<details>
<summary>3.1.164 (2026/09/18)</summary>

- 修复：侧边栏切换 PDF 中断加载后混入其他对话
- 修复：填充笔记预览自动滚动到底部
- 修复：GPT 密钥配置提示直达 API 教程

</details>

<details>
<summary>3.1.161 (2026/09/18)</summary>

- 优化：连接器偏好提示当前活动模式
- 修复：错误提示跳转到 API 常见问题
- 修复：侧边栏置顶滚动与消息布局
- 修复：重启后保留侧边栏思考内容
- 修复：防止侧边栏切换 PDF 时串写聊天记录

</details>

<details>
<summary>3.1.160 (2026/09/15)</summary>

- 修复：置顶动画期间保持滚动与焦点响应
- 修复：快速反向滚动时置顶动画卡顿
- 修复：长图片置顶退出时跳过收起动画
- 修复：置顶切换闪烁并改用高度展开收起动画
- 优化：选区工具栏采用竖线分隔样式
- 优化：回答滚回顶部后再展开置顶问题
- 修复：选区复制成功对号两秒后恢复

</details>

<details>
<summary>3.1.159 (2026/09/15)</summary>

- 优化：完善用量日期明细与 About 页面
- 修复：补全 Kimi 用量统计与渠道明细

</details>

<details>
<summary>3.1.158 (2026/09/14)</summary>

- 修复：恢复扩展文件夹的 Zotero 原生打开方式

</details>

<details>
<summary>3.1.157 (2026/09/14)</summary>

- 新增：模型用量分类与可折叠缓存明细
- 新增：点击固定问题跳转到原消息位置
- 修复：Windows 打开扩展目录时选中目录

</details>

<details>
<summary>3.1.156 (2026/09/14)</summary>

- 修复：常见错误帮助链接指向新版指南
- 优化：用量日历明细统一显示 K/M 单位
- 新增：阅读侧栏滚动时固定问题和快捷命令

</details>

<details>
<summary>3.1.155 (2026/09/12)</summary>

- 优化：插件功能与稳定性

</details>

<details>
<summary>3.1.154 (2026/09/12)</summary>

- 修复：更新插件文档链接
- 新增：Usage 双通道 token 统计面板
- 修复：网页回答短暂停顿时被提前截断
- 优化：减少浏览器最小化后的消息发送延迟
- 修复：浏览器窗口被遮挡或最小化时网页联动等待不结束
- 修复：AI大纲与AI标注偶发加载失败

</details>

<details>
<summary>3.1.152 (2026/09/11)</summary>

- 修复：无笔记时隐藏上传笔记入口
- 修复：GPT 引用按钮漏替换并兼容合并来源标记
- 测试：覆盖 Zotero 9 笔记模板回退链路
- 修复：兼容 Zotero 9 笔记模板渲染上下文
- 修复：AI填充笔记流式预览格式与光标
- 优化：本地化 Obsidian 设置文案

</details>

<details>
<summary>3.1.151 (2026/09/08)</summary>

- 修复 已知问题

</details>

<details>
<summary>3.1.150 (2026/09/08)</summary>

- 安全：提升账户身份处理安全性

</details>

<details>
<summary>3.1.149 (2026/09/08)</summary>

- 修复 已知问题

</details>

<details>
<summary>3.1.148 (2026/09/08)</summary>

- 优化：细化帮助章节链接并恢复常见报错文档

</details>

<details>
<summary>3.1.146 (2026/09/08)</summary>

- 优化：精简功能统计授权卡片，优化玻璃质感与 SVG 图标
- 修复：按钮文字裁切
- 优化：首次提示显示于标题下；选择后的统计设置移至页面底部，再次展开仍保留在底部

</details>

<details>
<summary>3.1.145 (2026/09/08)</summary>

- 修复：批量任务跨日时重复统计功能使用的问题
- 修复：同日撤回后重新同意分享统计时重复累计
- 优化：完善隐私说明

</details>

<details>
<summary>3.1.144 (2026/09/08)</summary>

- 修复：ChatGPT 长提示词填充、输入事件与引用标记清理
- 修复：复制与写入笔记不再依赖 Better Notes
- 修复：配置列表滚动条位置及密钥显示按钮间距
- 新增：可选功能使用统计与多语言隐私设置，可随时关闭

</details>

<details>
<summary>3.1.143 (2026/09/07)</summary>

- 新增：HTML 回答预览与 Zotero 快照导入，支持查看源码
- 新增：AI 大纲支持多提示词和指定页面范围生成
- 新增：AI 标注支持多提示词与部分页面生成，侧栏显示生成进度
- 修复：普通聊天历史与 PDF 上下文相互混入
- 修复：侧边栏重新回答、编辑后发送及宽度调整后的消息滚动
- 修复：元宝 PDF、DeepSeek 图片及 ChatGPT 附件上传联动
- 优化：恢复浏览器联动界面并同步用户脚本 6.0.0
- 修复：侧边栏保留模型接口的详细错误信息

</details>

<details>
<summary>3.1.142 (2026/09/02)</summary>

- 修复：列表后公式不渲染

</details>

<details>
<summary>3.1.141 (2026/09/01)</summary>

- 修复：移除配置测试区域多余的分割线
- 新增：接入 GPT 更新日志
- 修复：AI 标注跨页页码错位
- 发布：更新浏览器联动脚本版本
- 修复：兼容 Linux 首次启动存储目录
- 修复：渲染 AI 填充笔记公式
- 修复：解析 Gemini 原生向量响应
- 修复：优化元宝附件拖拽上传

</details>

<details>
<summary>3.1.140 (2026/09/01)</summary>

- 更新：同步油猴脚本 5.6.5
- 新增：显示上下文文本统计
- 更新：同步油猴脚本修复指针
- 修复：同步元宝输入配置并清理标记
- 优化：收紧上下文图标和图片删除按钮
- 修复：避免切换模式重复注入 PDF 附件全文
- 优化：将 PDF 上下文提示词改为英文
- 优化：简化批注页码标签显示
- 优化：将图片关闭按钮改为黑底白叉
- 优化：压缩附件上下文条目高度
- 优化：为快捷命令历史设置添加提示

</details>

<details>
<summary>3.1.139 (2026/08/31)</summary>

- 修复：使用原始文件 CDN 检查自动更新
- 修复：统一偏好设置标签页

</details>

<details>
<summary>3.1.123 (2026/08/24)</summary>

- 修复：插件更新后跳过失效的阅读器包装，避免调用旧对象

</details>

<details>
<summary>3.1.117 (2026/08/22)</summary>

- 修复：侧边栏关闭与历史记录清理流程，改善 Zotero 退出稳定性
- 修复：避免构建定时器触发阅读器切换

</details>

<details>
<summary>3.1.39 (2026/08/02)</summary>

- 完善阅读器提示词与侧边栏会话交互

</details>

<details>
<summary>3.1.37 (2026/07/30)</summary>

- 优化：阅读器提示词与应用运行稳定性

</details>

<details>
<summary>3.1.36 (2026/07/30)</summary>

- 区分阅读器提示词操作

</details>

<details>
<summary>3.1.35 (2026/07/30)</summary>

- 优化：阅读器提示词使用流程

</details>

<details>
<summary>3.1.34 (2026/07/30)</summary>

- 新增：阅读器悬浮 AI 标注

</details>

<details>
<summary>3.1.25 (2026/07/27)</summary>

- 重做浏览器连接器弹窗、选项、校准与偏好设置界面

</details>

<details>
<summary>3.1.23 (2026/07/21)</summary>

- 优化：模型请求与会话处理的稳定性

</details>

<details>
<summary>3.1.9 (2026/06/30)</summary>

- 修复：KaTeX 公式渲染

</details>

<details>
<summary>2.1.2</summary>

- 支持上传笔记
- 侧边栏支持上传更多附件，比如补充材料或笔记

**需要同时升级插件+GPT Connector脚本**

</details>

<details>
<summary>1.3.4</summary>

- 修复：侧边栏公式渲染错误bug
- 修复：侧边栏保存bug
- 侧边栏公式居中

</details>

<details>
<summary>1.2.5</summary>

- 优化：阅读划词弹出GPT命令溢出

</details>

<details>
<summary>1.2.3</summary>

- 重构设置界面

</details>

<details>
<summary>1.2.2</summary>

- 支持Zotero PDF矩形标注（矩形内图片）像GPT提问
- 支持跨页按Alt拼接上次选择的文字

</details>

<details>
<summary>1.2.1</summary>

侧边栏输入框菜单支持`显示文件`，便于拖入联动的网页，然后提问

</details>

# Reference

<details>
<summary>1.8.22 (2026/09/22)</summary>

- 修复：参考文献刷新时显示标题状态和抓取进度

</details>

<details>
<summary>1.8.21 (2026/09/22)</summary>

- 修复：摘要导入 Zotero 时清空面板且菜单未弹出
- 修复：图谱下层面板顶部拖动区产生空隙
- 修复：文献右键菜单空白和子菜单缺失

</details>

<details>
<summary>1.8.20 (2026/09/22)</summary>

- 新增：关系图谱独立窗口
- 优化：关系图谱条目浏览卡顿

</details>

<details>
<summary>1.8.18 (2026/09/21)</summary>

- 优化：引用弹窗按需加载文献并减少重复刷新

</details>

<details>
<summary>1.8.17 (2026/09/11)</summary>

- 优化：默认阻止引用面板远程加载
- 修复：禁止打开 PDF 自动解析无缓存引用

</details>

<details>
<summary>1.8.16 (2026/09/11)</summary>

- 修复：兼容 Zotero 10 PDF 阅读器初始化

</details>

<details>
<summary>1.8.15 (2026/09/11)</summary>

- 升级：使用兼容 Zotero 9 的工具包版本
- 修复：兼容 Zotero 9 PDF 引用解析加载

</details>

<details>
<summary>1.8.13 (2026/09/08)</summary>

- 修复 已知问题

</details>

<details>
<summary>1.8.12 (2026/09/08)</summary>

- 修复 已知问题

</details>

<details>
<summary>1.8.11 (2026/09/08)</summary>

- 优化：精简功能统计授权卡片，优化玻璃质感与 SVG 图标
- 修复：按钮文字裁切
- 优化：首次提示显示于标题下；选择后的统计设置移至页面底部，再次展开仍保留在底部

</details>

<details>
<summary>1.8.10 (2026/09/08)</summary>

- 修复：同日撤回后重新同意分享统计时重复累计
- 优化：完善隐私说明

</details>

<details>
<summary>1.8.9 (2026/09/08)</summary>

- 修复：释放阅读视图资源，完善异步资源清理
- 修复：搜索刷新竞态问题
- 修复：更新日志多语言显示
- 新增：可选功能使用统计与多语言隐私设置，可随时关闭

</details>

<details>
<summary>1.8.8 (2026/09/01)</summary>

- 新增：接入 Reference 更新日志

</details>

<details>
<summary>1.8.7 (2026/08/31)</summary>

- 修复：使用原始文件 CDN 检查自动更新
</details>

<details>
<summary>1.7.19 (2026/08/02)</summary>

- 新增：交互式引文参考文献浮层

</details>

<details>
<summary>1.7.18 (2026/07/21)</summary>

- 优化：插件生命周期管理与多语言支持

</details>

