



华为财经AI开发部(合同测试规划)

1、对齐梳理现有的测试用例，方案等资源

2、对齐梳理当前财经AI合同开发方面涉及的接口，UI，相关微服务等

当前相关接口是没有做在线的归档？

具体涉及到的UI界面，当前主要开发中的，持续迁移中的，已经迁移完毕较为稳定的

3、根据需要投入测试的，按重要程度划分先后补充相关测试用例

API的看平台有测试用例，但是不多，为啥不维护在CloudTest？

UI的当前没看到有做，如有必要，后续考虑用playwright做，内部的自研Artbot(基于Selenium)有点重，整体搭建比较慢

当前是否有调用其他部门的接口，但是不稳定的，需要用桩来维护的？

代码覆盖率统计啥的(jacoco插件的引入)



