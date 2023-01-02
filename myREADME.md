# plop 的使用

https://www.bilibili.com/video/BV1ih411a7B8?p=15&vd_source=b831eb3e5888129473a908615b2c5022

plop: 微型生成器框架,一般是以一个 npm 包的形式安装在某个项目内

以一个 react 项目为例

1. npx create-react-app 创建一个 react 项目
2. 进入该 react 项目，安装 plop: yarn add pop -D
3. 根目录下编写 plopfile.js
4. 提供 templateFile
5. yarn plop xx，xx 为 plop.setGenerator 第一个参数
