# Contributing

感谢你愿意改进“个人工作驾驶舱”。这个项目优先保护的是：**低维护成本、WPS 兼容性和可解释行为**，而不是功能数量。

提交改动前请先读：

1. `docs/PRODUCT_PRINCIPLES.md`
2. `docs/DEVELOPER_GUIDE.md`
3. `spec/tracker_spec.json`

一个新功能至少要说明：

- 解决什么真实痛点；
- 是否新增日常维护动作；
- 为什么不能由现有字段/规则实现；
- 是否可以做成可选增强。

修改工作簿后，请按开发指南的回归清单验证，并同步 `spec/tracker_spec.json`。视觉改动请附脱敏截图。
