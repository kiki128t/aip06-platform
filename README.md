# AIP06 企业 AI 工作台

AIP06 在当前产品功能边界内提供对话、智能体、知识库管理、数据大屏和知识图谱。`#agents` 是企业级 Design System 与 B 端视觉升级的样板页。

## 运行

无需安装依赖，直接打开 `index.html`：

- 对话：`index.html#chat`
- 智能体样板页：`index.html#agents`
- 知识库管理：`index.html#knowledge`
- 数据大屏：`index.html#dashboard`
- 知识图谱：`index.html#graph`

也可使用任意静态文件服务器：

```bash
python3 -m http.server 8080
```

然后访问 `http://localhost:8080/#agents`。

## Agents 样板页

- 双层导航：产品全局导航与智能体模块导航。
- 运行概览、下一步行动、常用智能体和全量管理。
- 根据完成状态切换配置完整度建议与四步配置流程。
- 保留新建、筛选、排序、详情、编辑、对话和显示模式切换。
- 桌面端与移动端响应式布局。

完整设计规范见 `docs/AIP06-Agents-Design-System.md`。

## 说明

该仓库用于产品原型演示。页面中的模型调用、文件解析和任务执行为前端模拟流程。
