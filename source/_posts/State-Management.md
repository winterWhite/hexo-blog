---
title: State Management
tags: JavaScript
---

来自文章《如何直观的在JavaScript中管理状态》

好的状态管理原则：   

1. 区分不确定数据和有限状态 —— 限制从一个状态到另一个状态转换的可能性
2. 设计直观

8个要点： 
  
1. 状态不等于数据   
**状态**表示系统可以处于有限数量的模式下，状态是可数的。   
**数据**储存在具有几乎有无限可能的存储器中，数据是无限可能的。   
分离状态和数据可以减少混淆，并允许我们构建基于有限状态机的应用。
2. 状态有限   
一个可预测的界面一定是具有有限和可控状态数量的状态。在有限状态机中，状态是被明确定义的。   
**转换**是一组可以进行状态转移事件的集合。
3. 管理状态机的复杂度   
需要注意不同状态间不受控制的转换
4. 守卫转换   
**守卫**是状态转换发生所必需要满足的条件。
5. 状态是图   
状态理想的数据结构通常是图。
6. 状态图脚手架   
状态图应当成为开发应用的脚手架。
7. statecharts：减轻状态图的复杂度   
状态类型：初始状态、嵌套状态、并行状态、历史状态   
其它：转换、守卫、行为
8. statecharts 工具