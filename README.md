# PlantUML-Demo
PlantUML 参考示例


@startuml 时序图
actor 参与者
boundary 限制
control 控制
entity 实体
database 数据库
collections 收集

参与者 -> 限制 : 满足边界条件
参与者 -> 控制 : 控制系统
参与者 -> 实体 : 操作实体
参与者 -> 数据库 : 同步数据库
参与者 -> 收集 : 完成数据采集

@enduml
