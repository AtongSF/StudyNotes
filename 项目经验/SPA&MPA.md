# 单页应用

> 一个html页面作为外壳页面，公共资源一次性加载，不同的内容通过切换页面片段实现
>
> 适合切换频繁，对数据操作的场景



优点：

- 模拟了桌面应用的工作
- 公共资源只加载一次，只有数据需来回传输
- 能快速根据pc端代码重构移动端应用 （？）
- 有效缓存任何本地存储，断网也能呈现
- 前后端开发更独立
- 有转场动画

缺点：
- 不利于SEO
- 用户不启用JavaScript时无法使用
- 客户端框架、模板加载速度慢
- 不安全，XSS，使攻击者能够将其他用户的客户端脚本注入Web应用程序
- JavaScript中的内存泄漏甚至可能导致功能强大的系统变慢
- 后退和前进按钮功能不可用



# 多页应用

> 每次加载一个完整的html页面，公共资源也会重新加载
>
> 适合需要搜索引擎检索、追求首屏展示速度、数据操作少的场景



优点：

- 利于SEO
- 首屏展示速度快

缺点：

- 前后端联系太紧密

  

# Hybird Application

> 同一应用中二者可以结合使用