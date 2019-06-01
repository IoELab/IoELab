---
layout: page
title: projects/项目
permalink: /projects/
description:
---

- Electrical demand response model for complex industrial process, sponsored by National Natural Science Foundation of China, Grant no. 61702369, 2018.01 - 2020.12, PI.<br/>
  基于复杂流程工业网络的电力需求响应模型研究，国家自然科学基金委青年项目，61702369, 2018.01-2020.12, 主持。

- User-side demand response energy management system in smart grid, sponsored by Tianjin Municipal Science and Technology Bureau, Grant no. 15JCYBJC52400, 2015.10 - 2018.09, PI.<br/>
  智能电网用户侧需求响应系统研究，天津市自然科学基金面上项目，15JCYBJC52400, 2015.10-2018.09, 主持。

- Control and communications for high value distributed electrical storage, sponsored by Australia Discovery Council, Grant no. DP16010257, 2016.01-2018.12.<br/>
  分布式能源存储实时控制及通信技术研究，澳大利亚ARC项目，DP16010257，2016.01-2018.12，参与。

- Internet-of-Things Based Load Control and Metering in Smart Grids, National Research Foundation of Korea, Grant no. NRF-2012K1A3A1A20031289，2013.03-2016.02.<br/>
  智能电网中基于物联网的负载控制及计量技术研究，韩国国家研究基金（中韩合作专项）, NRF-2012K1A3A1A20031289，2013.03-2016.02, 参与。

- Integrating User Facilities with Smart Grid using USN，Korean Gyeonggi Rational Research Center, Grant no. GRRC Hanyang 2012-B01, 2012.07-2014.06.<br/>
  基于泛在网络的用户设施与电网融合技术研究，韩国京畿道地区研究中心，GRRC Hanyang 2012-B01, 2012.07-2014.06，参与。

- Building/Home USN Technology for Smart Grid，Korean Gyeonggi Rational Research Center, Grant no. GRRC Hanyang 2011-B01, 2011.07-2012.06.<br/>
  面向智能电网的楼宇/家居泛在网络技术研究，韩国京畿道地区研究中心，GRRC Hanyang 2011-B01, 2011.07-2012.06，参与。

- USN based Wireless Communication Module for Industrial Automation，Korean Gyeonggi Rational Research Center，Grant no. GRRC Hanyang 2009-B02, 2009.07-2012.06.<br/>
  基于泛在网络的工业无线通信模块研究，韩国京畿道地区研究中心，GRRC Hanyang 2009-B02, 2009.07-2012.06,参与。

---

  <header class="post-header">
    <h1 class="post-title">demos/演示系统</h1>
  </header>

 {% for demo in site.demos %}

- <a href="{{ demo.url | prepend: site.baseurl | prepend: site.url }}"> {{demo.title}}</a>

{%endfor%}