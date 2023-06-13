# 多状态的 组件，状态之间丝滑切换

- 预先定义5种组件状态 enum Status { initial, loading, error, success, timeout }
- 给每种状态设定不同的布局
- 利用动画进行 状态之间切换时的渐变效果
- 给封装好的组件添加上 状态控制器，支持从外部控制内部状态 StateController

