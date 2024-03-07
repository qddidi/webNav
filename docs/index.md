---
layout: home
layoutClass: 'm-home-layout'

hero:
  name: 小月的
  text: 前端导航
  tagline: 基于 VitePress 的个人前端导航页面
  image:
    src: /logo.png
    alt: 小月导航
  actions:
    - text: 前端导航
      link: /nav/

    - text: 东方小月
      link: https://github.com/qddidi
      theme: alt

features:
  - icon: 📘
    title: Vue3组件库搭建教程
    details: 基于Vite4+TypeScript实现<br />搭建属于自己的Vue3组件库
    link: https://mp.weixin.qq.com/mp/homepage?__biz=MzI2NzY3NDQzMg==&hid=3&sn=a67d053eed1012faf8ee56a1e1bc601c
    linkText: 组件库搭建

  - icon: 📖
    title: 前端面试
    details: 整理前端常用知识点<small>（面试八股文）</small><br />如有异议按你的理解为主，持续更新迭代中
    link: https://mp.weixin.qq.com/mp/homepage?__biz=MzI2NzY3NDQzMg==&hid=9&sn=cd1ff6c8f82a79add3d601e1d5bb14d0
    linkText: 前端面试

  - icon: 🧰
    title: NestJS+Vue3后台管理系统搭建教程
    details: 基于NestJS+Vue3开发的后台权限管理系统
    link: https://mp.weixin.qq.com/mp/homepage?__biz=MzI2NzY3NDQzMg==&hid=8&sn=7b595186013dfab935244bd4c67d3011
    linkText: 后台权限管理系统
---

<style>
/*爱的魔力转圈圈*/
.m-home-layout .image-src:hover {
  transform: translate(-50%, -50%) rotate(666turn);
  transition: transform 59s 1s cubic-bezier(0.3, 0, 0.8, 1);
}

.m-home-layout .details small {
  opacity: 0.8;
}

.m-home-layout .bottom-small {
  display: block;
  margin-top: 2em;
  text-align: right;
}
</style>
