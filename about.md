---
layout: default
title: 关于我
---
<div class="receipt-container">
  <div class="receipt-header">
    <h2>XX奶茶店</h2>
    <p>订单号: #20240520</p>
    <p>时间: {{ site.time | date: "%Y-%m-%d %H:%M" }}</p>
  </div>
  
  <div class="receipt-body">
    <div class="menu-item">
      <span>【开发者特调】</span>
      <span>×1</span>
      <span>¥39.00</span>
    </div>
    
    <div class="divider">-----------------------------</div>
    
    <div class="skill-list">
      <p>■ 全栈开发 (Java/Python)</p>
      <p>■ 云原生架构设计</p>
      <p>■ 大数据处理</p>
      <p>■ AI工程化落地</p>
    </div>
  </div>
  
  <div class="receipt-footer">
    <p>扫码关注公众号获取最新作品</p>
    <div class="qrcode">[二维码位置]</div>
    <p>谢谢惠顾！欢迎再次光临</p>
  </div>
</div>