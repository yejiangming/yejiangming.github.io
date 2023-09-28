# 如何理解 SaaS PaaS IaaS
## 如何理解 SaaS 产品
首次提出 SaaS 概念的是 salesforce, 公司创始人 Benioff 当时的口号是 “End Software”, 所以理解 SaaS 产品，要站在传统软件的对立面去看

概括来看，传统软件提供的是一个软件，部署在客户本地运行，而 SaaS 提供的是一个服务，用户通过网络使用服务，数据都存储在云端

[从入门到精通 | 深度详解什么是SaaS
](https://www.woshipm.com/it/4429418.html#toc-5)
![](/202309/img/传统软件VSSaaS.png)
## 如何理解 IaaS, PaaS
与 SaaS 一样，IaaS 和 PaaS 的重点都是提供服务，但是提供的服务层次不同

IaaS 层是将基础设施:服务器，存储介质，网络打包作为服务提供，定义比较明确

而 PaaS(platform as a service), 在提供基础设置之上，还提供开发环境和基础开发组件，比如 OS, DBMS, 用户可以基于 PaaS 提供的环境开发自己的应用

[azure对paas的定义](https://azure.microsoft.com/en-us/resources/cloud-computing-dictionary/what-is-paas)

azure 的 paas 是一个软件开发的平台
![](/202309/img/azure-PaaS.png)

而一些垂直领域的 PaaS 产品，比如国内的有赞 iPaaS，它集成了金蝶等厂商的应用连接器，并内置了30+常用的业务组件，通过iPaaS平台的组件，商家可以高效完成这些系统之间的集成性对接

![](/202309/img/youzan-ipaas.png)

有赞提供的是一个开发零售领域应用的平台，虽然与 azure 定义的 PaaS 很不一样，但从提供开发平台的角度看，它也可以称为一个 PaaS 产品

所以综合来看，将一个开发工具集作为服务提供的平台，就可以称为 Paas


[有赞ipaas介绍](https://b.yzcdn.cn/yzy/white-paper/有赞iPaaS产品介绍.pdf)
