---                                                                                          
title: "搭建我们的Shellter"                                                             
date: 2023-07-28T03:30:39+08:00
draft: false    
author: Black Lu                                                                             
tags：［blog］
---

## 前言
　　为了给Coolshell搭建好Shelter，我即按照Atom的要求使用简单的Meme 主题搭建网站；由于我比较熟悉Hugo框架幸好Meme作者有做Hugo 框架的版本，加上Hugo可以快速部署且性能好，为将来大量文章的发布打下了良好的基础。

## 部署

### GitHub Page

　　使用Hugo框架快速部署Meme主题的博客非常容易。我原本是采用GitHub Page的形式，只需要几步就能成功部署。我自己的博客也是用这个方式搭建，不过自定义域名要花点心思（PS：我自己也没整自定义域名，不想花钱买）
> - 参考[在 GitHub 部署 Hugo 靜態網站](https://chswei.netlify.app/blog/hugo/)

### CloudFlare 
　　在和Atom的通话中得知，耗子的博客也是使用CloudFlare托管的，所以我们便打算使用Cloud Flare托管
### 购买域名
　　可以在[Name Cheap](https://www.namecheap.com/)或者[Name Silo](https://www.namesilo.com/)购买域名，我们是在Name Cheap上买的域名；如果是我会在Name Silo，因为可以直接用支付表买单。

### 配置DNS
　　由于我们是使用CloudFlare Page 托管我们的网站，所以域名购买之后需要使用Could Flare解析，解析域名可能需要一定的时间请耐心等待
>- 参考 [在CloudFlare上解析自己的域名](https://blog.misaka.rest/2023/03/03/cf-dns/)

### 部署博客
　　部署博客需要一个GitHub Repo，Public或者Private都可以，使用CloudFlare 还有一个好处就是可以自定义二级域名
>- 参考 [Cloudflare Pages 提供無限流、無限容量，免費網頁空間，同時還可綁定自己的網域名稱架設教學](https://www.minwt.com/website/server/22861.html)

## Post文注意事项
### Page Bundle
　　我们都是用markdwon文件，语法基本上大家都熟悉就不过多描述，主要是说明我们要使用[Page Bundle](https://gohugo.io/content-management/page-bundles/)的形式，而不是简单地写个md文件。特别是针对有普通的文章，如下
     
    tree archlinux_install

    /archlinux_install
    ├── arch.png
    ├── etcher.png 
    └── index.md
                                                                                  

## 总结
　　以上就是本篇文章的所以内容，引用内容有点多，但实际操作并不难，熟悉之后便可半小时之内完成，写这篇文章对于不太习惯写作的我而言，可能就要更长对时间了，谢谢
