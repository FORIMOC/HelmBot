# HelmBot V1.0.2

<u>2022/1/29</u>



## 修正错误

- 用户关系网络边权值中社交倾向方向错误地倒置了，已修正
- 边权值的`des`(描述)出现`null`(为空)的现象：没有进行检测过滤，导致出现问题`link`对象覆盖了带有实际数据的`link`对象，真正的`link`对象的`des`无法显示，已修正