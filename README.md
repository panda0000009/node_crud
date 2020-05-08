# node_crud
用node做的学生管理系统

加载别人的文件时，版本号很重要
最好的方法就是，直接拖个packa.json,然后 npm i -y下载

bootst模板的使用方法。（用bootst3的话，下载对应3的版本，npm i bootst@3，，，如果npm i bootst@3.3.7，则下载的是3.3.7的版本）
本项目使用的是3.37



# Express - crud

## 起步

- 初始化
- 模板处理

## 路由设计

| 请求方法 |     请求路径     | get 参数 |           post 参数            |       备注       |
|----------|------------------|----------|--------------------------------|------------------|
| GET      | /studens         |          |                                | 渲染首页         |
| GET      | /students/new    |          |                                | 渲染添加学生页面 |
| POST     | /studens/new     |          | name、age、gender、hobbies     | 处理添加学生请求 |
| GET      | /students/edit   | id       |                                | 渲染编辑页面     |
| POST     | /studens/edit    |          | id、name、age、gender、hobbies | 处理编辑请求     |
| GET      | /students/delete | id       |                                | 处理删除请求     |
|          |                  |          |                                


|                  |
