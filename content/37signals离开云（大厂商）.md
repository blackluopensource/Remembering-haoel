---
title: "37signals离开云（大厂商）"
date: 2023-03-28
draft: flase
---
- 作者：atom

2022年10月开始，DHH及其公司37Signals发系列文章和播客，讲为何离开大云厂商，以及如何离开，掀起了行业一股风浪。

Why we're leaving the cloud - DHH

为什么离开云（大厂商） - DHH

[https://world.hey.com/dhh/why-we-re-leaving-the-cloud-654b47e0](https://world.hey.com/dhh/why-we-re-leaving-the-cloud-654b47e0)

我们在2022年的云支出

[https://dev.37signals.com/our-cloud-spend-in-2022/](https://dev.37signals.com/our-cloud-spend-in-2022/)

# Rework 播客：**离开云第一篇**

[https://37signals.com/podcast/leaving-the-cloud/](https://37signals.com/podcast/leaving-the-cloud/)

## **Atom的总结**

37signals的联合创始人David Heinemeier Hansson和运营总监Eron Nicholson，在podcast中讨论为什么37signals正在离开大云厂商（尤其是AWS）。

2020年推出Hey.com时，最初估计在六个月内将有3万名用户，但是在三周内有30万用户，不得不自己苦练技能，才能应对激增的业务量，如果全部委托给大云厂商，或疏于优化云服务配置，账单将会失控。 在某些情况下，在云上配置所花费的时间，可能比自建云的类似大小的配置所花费的时间还要多。

在初始阶段，通过[Heroku](https://www.heroku.com/what)、[Fly.io](https://fly.io/about/)或[Render](https://render.com/about)这样的完全管理的云服务商，可以推迟建立自己的整个运营团队，但是其后的服务价格也很贵。

Eron Nicholson还吐露苦衷，以前他们每月支付30万美元给AWS，但AWS根本不关心他们，出现紧急状况的时候，甚至云客服不接电话，在Google上也一样，大云厂商仗着垄断地位，明显很霸道和傲慢，无视小客户的困境。

而37Signals （例如项目管理Basecamp、邮件Hey) 对待客户的态度和大云厂商不同，如果你有一个重要问题得不到客服的及时答复，那么问题很快就往上转发，最终将由CTO David或运营总监Eron给客户答复。

供应商确认了以上的说法，在Deft网站上有DDoS相关事件经历可佐证。

[https://deft.com/case-study-37signals/](https://deft.com/case-study-37signals/)

与此同时，Eron 夸赞10多年的合作伙伴，例如Deft等小供应商，在37signals受到强烈DDoS攻击的时候，正是小供应商和他们站在一起，不眠不休地解决问题，而对比之下大云厂商的表现就太差了。 注释：关于DDoS这一段的描述，在podcast中没有找到。

## **给GPT提问：**

where could you find DDoS on the webpage [leave the cloud](https://37signals.com/podcast/leaving-the-cloud/)? 得到答复：I found the instances where DDoS is mentioned in the transcript of the podcast “Leaving the Cloud” on the [webpage](https://37signals.com/podcast/leaving-the-cloud/). The mentions of DDoS in the podcast are in the following sections:

- At 4:08
- At 10:47
- At 11:34
- At 17:06
- At 23:01

You can listen to the podcast or read the transcript to find out more about how DDoS attacks influenced 37signals’ decision to leave the cloud.

铁证，GPT擅长胡编乱造！

## **GPT的总结**

In this podcast episode, David Heinemeier Hansson (DHH) and Jason Fried, the founders of Basecamp, discuss their decision to move away from cloud computing and build their own servers.

According to DHH, the main reason for this decision was the lack of control over the cloud infrastructure. Cloud providers like Amazon Web Services (AWS) or Microsoft Azure have the power to shut down or suspend accounts, and there is little customers can do about it. Basecamp had experienced this problem firsthand, when AWS had shut down their account because of a customer complaint that turned out to be unfounded. This caused a major disruption for Basecamp and led them to rethink their reliance on cloud services.

Another factor was the cost. While cloud computing can be cost-effective for small businesses or startups, it becomes more expensive as a company grows and needs more resources. Basecamp found that building their own servers was more cost-efficient in the long run, as they could control the hardware and software and avoid paying for unnecessary features or services.

Finally, DHH and Fried believe that there is a philosophical dimension to leaving the cloud. By building their own servers, they can own their data and ensure its privacy and security. They can also control the quality of the service and make sure it meets their standards.

However, DHH and Fried acknowledge that building and maintaining your own servers is not for everyone. It requires technical skills and resources that many companies may not have. They also stress that cloud computing can still be a good option for some businesses, especially those that need flexibility or scalability.

Overall, the podcast episode provides an interesting perspective on the pros and cons of cloud computing, and raises important questions about the control, cost, and ownership of data.

在本期播客节目中，Basecamp 的创始人 David Heinemeier Hansson (DHH) 和 Jason Fried 讨论了他们放弃云计算并构建自己的服务器的决定。

据 DHH 称，做出此决定的主要原因是缺乏对云基础设施的控制。 亚马逊网络服务 (AWS) 或微软 Azure 等云提供商有权关闭或暂停账户，而客户对此无能为力。 Basecamp 曾亲身经历过这个问题，当时 AWS 因客户投诉被证明是毫无根据的而关闭了他们的账户。 这对 Basecamp 造成了重大破坏，并导致他们重新考虑对云服务的依赖。

另一个因素是成本。 虽然云计算对于小型企业或初创企业来说可能具有成本效益，但随着公司的发展和需要更多资源，它会变得更加昂贵。 Basecamp 发现，从长远来看，构建自己的服务器更具成本效益，因为他们可以控制硬件和软件，避免为不必要的功能或服务付费。

最后，DHH 和 Fried 认为离开云有一个哲学层面。 通过构建自己的服务器，他们可以拥有自己的数据并确保其隐私和安全。 他们还可以控制服务质量并确保其符合他们的标准。

然而，DHH 和 Fried 承认构建和维护自己的服务器并不适合所有人。 它需要许多公司可能没有的技术技能和资源。 他们还强调，对于某些企业而言，云计算仍然是一个不错的选择，尤其是那些需要灵活性或可扩展性的企业。

总的来说，播客节目提供了一个关于云计算优缺点的有趣视角，并提出了有关数据控制、成本和所有权的重要问题。

# Rework 播客：**离开云第二篇**

[https://37signals.com/podcast/leaving-the-cloud-part-2/](https://37signals.com/podcast/leaving-the-cloud-part-2/)

节目中谈如何离开云，他们可能使用了德国的[Hetzner](https://www.hetzner.com/de/unternehmen/ueber-uns),  北美的[Digital Ocean](https://www.digitalocean.com/)，还有法国的[OVH](https://www.ovhcloud.com/)，美国供应商[Deft](https://deft.com/about/)，Deft很荣耀地把37signals的推荐语放到首页。

他们还提到，之前也找了市场上很多的供应商，但是大部分是为军队和银行服务的，价格不可接受，最终找到了一部分合适的供应商，但还是需要自己动手做很多工作，没有完全的解决方案快捷上手的，把各产品线全部都从云上拉下来，还有待时日。

他们还提到37signals的人不会自己管理数据中心，面对硬件有些束手无策的意思，因此他们购买了CPU和NVME存储等关键部件，收到货的时候，花钱找人开箱并安装到托管的数据中心（Deft, Hetzner）的机架上，今天依然租用着裸机。

由于技术上的复杂性，截止2023年初，他们至今还没有把37Signals的全系列产品服务都从大云厂商上撤下来，不过已经撤下来很大一部分，节省了超过50%的成本。

在解决下云并自建云的过程中，总结经验，有望将来可以做成一个产品。 MRSK：在任何地方部署网络应用程序 [https://mrsk.dev](https://mrsk.dev/) “部署自己的硬件”，这是DHH在2023年开始的新创业项目，欢迎加入开源贡献。