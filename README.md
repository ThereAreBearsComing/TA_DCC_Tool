# TA_DCC_Tool

## 问题：
* 尝试在Maya中选择控制顶点，边或面时，选择会抓取所有组件而不是单个组件。

<br>![GIF 2022-9-20 23-17-12](https://user-images.githubusercontent.com/74708198/191298162-cadf77c9-d33e-456a-9fc5-da69b4135f2e.gif)

## 原因：
* 软选择工具已打开。软选择是基于期望衰减的比例运动。意味着可以选择多个面，并根据选择衰减范围移动。

* 此外，损坏的首选项可能会导致选择错误。

## 解决方案：
**关闭“软选择”以返回默认选择设置：**
* 双击其图标打开该工具（分别对每个受影响的工具执行）
* “工具设置”窗口自动打开，向下滚动到“软选择”
* 取消选择“软选择”

<br>![image](https://user-images.githubusercontent.com/74708198/191296776-8b131b18-6999-44f6-ad6e-713818ce42cd.png)


<br>![GIF 2022-9-20 23-18-17](https://user-images.githubusercontent.com/74708198/191298465-78363ec2-ac53-40b1-9f12-89e23b6c220e.gif)

