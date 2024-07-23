<p align="center">
  <img src="https://github.com/VisualLogicAI/iVX/blob/main/image/iVXlogo.png" />
</p>

<div align="center">
  
[英文](https://github.com/VisualLogicAI/iVX/blob/main/README.md) | 中文
 
</div>

# iVX - 适合所有人的可视化编程

欢迎来到iVX项目！iVX 是一种多功能图形编程语言，具有集成开发环境 （IDE），专为基于组件的开发而设计。该存储库包括 iVX 生成的各种应用程序，以及用于前端和后端的完整源代码，用于教育目的。

## 什么是iVX？

iVX 是一种通用的图形编程语言，具有全面的集成开发环境 （IDE）。iVX的核心体现了“基于组件的编程”的理念，即通过“图形逻辑编排”将各种组件相互连接，形成应用程序的完整逻辑。此设置允许通过编译器/解释器生成完整的前端和后端代码，这些代码可以独立编译。给定丰富的组件库，这种方法确保整个应用程序可以“无代码”开发，同时仍然允许以“指定的语言/框架”生成代码。根据用户需求，用户可以在开发过程中选择使用“代码”或“SDK”，这对于“非编码学习者”和“具有编码知识的程序员”来说都非常灵活。

iVX 可以在 Vue 或 React 框架中生成前端代码，在 Java SpringBoot 框架中生成后端代码。

<p align="center">
  <img src="https://github.com/VisualLogicAI/iVX/blob/main/image/develop.png" />
</p>

## 特征

- **基于组件的开发**: 使用丰富的组件库开发前端 （Vue/React） 和后端 （Java SpringBoot） 应用程序。
- **图形逻辑编排**: 通过图形界面轻松连接组件，形成完整的应用逻辑。
- **灵活性**: 嵌入自定义代码，上传SDK，使用手写SQL、CSS、HTML，导入各种前端库。
- **用户友好的 IDE**: 组件、属性、对象、事件和数据流的直观面板。

## iVX IDE 的结构

iVX IDE 包括以下面板：

- **组件面板**
- **“属性”面板**
- **“对象树”面板**
- **事件面板**
- **“数据流”面板**
- **导航栏**
- **菜单栏**
- **舞台配置栏**
- **逻辑组件栏**

所有添加的组件都将在“对象树”面板中实例化为对象。例如，页面和页面中的容器，以及容器中的元素。任何组件都被设计为一个对象，包括“属性”、“触发条件”和“方法/函数”。在对象树中，任何对象都可以附加“事件”组件，单击时会打开“事件面板”。此面板包含“条件块”、“操作块”和“循环块”。通过组合这些模块，您可以实现图灵完备逻辑表达式，通常基于触发逻辑，例如在对象 A 上发生的操作（触发条件）导致在对象 B 上执行函数，其中 B 可能包括 A。“事件面板”允许添加多层“条件块”、“操作块”和“循环块”，提供类似于代码的灵活性，但没有语法。

<p align="center">
  <img src="https://github.com/VisualLogicAI/iVX/blob/main/image/Event%20Panel.png" />
</p>

<p align="center">
  <img src="https://github.com/VisualLogicAI/iVX/blob/main/image/Event%20Panel2.png" />
</p>

另一个基于面板的组件是“数据流”组件，它与“数据流面板”配对。该小组包括：

- **启动节点**
- **结束节点**
- **对象节点**
- **功能节点**
- **条件节点**
- **循环节点**
- **事件节点** (数据流面板内部)

整个数据流图是一个有向无环图 （DAG），数据在节点之间流动。一个节点的输出（输出数据）是下一个连接节点（输入数据）的输入。这个过程类似于函数式编程，其中一个函数的输出作为下一个函数的输入。

<p align="center">
  <img src="https://github.com/VisualLogicAI/iVX/blob/main/image/Dataflow.png" />
</p>

## iVX 组件

iVX提供大量组件（1000+）：

### 前端组件

- 各种视觉组件 (按钮、图像、视频等)
- 容器组件
- 可变组件
- 通信组件 (API、Socket、MQTT 等)
- 画布组件
- 第三方接口
- AI前端组件

### 后端组件

- 封装云计算产品的标准组件
- 各种数据库
- MQ系列
- Redis
- 中间件
- 计时服务
- 第三方接口
- AI 模型后端组件

<p align="center">
  <img src="https://github.com/VisualLogicAI/iVX/blob/main/image/3D.png" />
</p>

<p align="center">
  <img src="https://github.com/VisualLogicAI/iVX/blob/main/image/time.png" />
</p>

<p >
  <img src="https://github.com/VisualLogicAI/iVX/blob/main/image/journal.png" />
</p>

## iVX IDE中基于组件的编程

iVX IDE采用“基于组件的编程”设计理念。与“基于代码的编程”相比，它在更高的维度上运行，有效地隔离了代码，帮助非编码人员快速学习编程。iVX 中的每个组件都实现了面向对象的封装，包括“触发条件”、“属性”和“函数”。这允许事件面板和组件对象的组合来构建和表达完整的应用程序逻辑。

iVX 对开发者来说非常人性化，支持直接嵌入前端和后端代码，上传 Java/Python/Node.js/Android SDK，手写 SQL、CSS、HTML 代码，上传 npm 包，导入 ElementUI 等各种前端库。

## iVX的优势

与高级语言相比，iVX 更易于学习、开发速度更快、维护更方便，同时还确保了高代码质量。

## 开始

要开始使用 iVX，请按照下列步骤操作：

1. **克隆存储库**
    ```bash
    git clone https://github.com/yourusername/ivx-project.git
    ```
2. **导航到项目文件夹**
    ```bash
    cd ivx-project/project-folder
    ```
3. **安装依赖项**
    ```bash
    npm install
    ```
4. **运行项目**
    ```bash
    npm start
    ```

## 目录结构


每个项目文件夹包含：

- `frontend/`: 前端源代码（Vue/React）
- `backend/`: 后端源代码（Java SpringBoot）
- `README.md`: 项目的具体说明

## 应用实例

浏览下面的示例应用程序。单击链接以在 ivx.cn 上打开相应的 iVX 应用程序。扫描二维码并注册/登录后，即可在IDE中直接查看处于编辑状态的应用程序。

### 项目 1: [待办事项列表应用程序](https://shop.ivx.cn/?tid=888)

<p align="center">
  <img src="https://github.com/VisualLogicAI/iVX/blob/main/image/Todo%20List%20App.png" />
</p>

一个简单的待办事项列表应用程序，演示基本的 CRUD 操作。

**特征：**
- 添加、编辑和删除任务
- 将任务标记为完成
- 响应式设计

### 项目 2: [电商平台](https://shop.ivx.cn/?tid=548)

<p align="center">
  <img src="https://github.com/VisualLogicAI/iVX/blob/main/image/E-Commerce%20Platform.png" />
</p>

一个功能齐全的电子商务平台，具有产品列表、购物车和结账功能。

**特征:**
- 产品管理
- 用户身份验证
- 订单处理

### 项目 3: [聊天应用程序](https://shop.ivx.cn/?tid=886)

<p align="center">
  <img src="https://github.com/VisualLogicAI/iVX/blob/main/image/Chat%20Application%20PC.png" />
</p>

<p align="center">
  <img src="https://github.com/VisualLogicAI/iVX/blob/main/image/Chat%20Application%20H5.png" />
</p>

具有用户身份验证和消息存储功能的实时聊天应用程序。

**特征:**
- 用户注册和登录
- 实时消息传递
- 消息历史记录

### 项目 4: [博客平台](https://filea67c94ca42f6.v4.h5sys.cn/play/Dvk6qkVS)

<p align="center">
  <img src="https://github.com/VisualLogicAI/iVX/blob/main/image/Blog%20Platform.png" />
</p>

一个博客平台，允许用户创建、编辑和删除博客文章。

**特征:**
- 帖子创建和编辑
- 评论系统
- 用户配置文件

### 项目 5: [库存管理系统](https://shop.ivx.cn/?tid=912)

<p align="center">
  <img src="https://github.com/VisualLogicAI/iVX/blob/main/image/Inventory%20Management%20System.png" />
</p>

用于管理产品库存的系统，包括跟踪库存水平和订单。

**特征:**
- 产品跟踪
- 订单管理
- 库存水平警报

## 贡献

我们欢迎社区的贡献！请阅读我们 [的贡献指南](CONTRIBUTING.md) 以开始使用。

## 许可证

此项目根据 MIT 许可证获得许可 - 有关详细信息，请参阅 [LICENSE](LICENSE) 文件。

## 联系

如有问题或支持，请在 GitHub 上提出问题或通过support@ivx.com联系我们。

## Additional Resources

- [iVX 文档](https://ivx.com/docs)
- [iVX 教程](https://ivx.com/tutorials)
- [iVX 社区](https://ivx.com/community)

---

感谢您使用 iVX！我们期待看到您将创建的惊人应用程序。
