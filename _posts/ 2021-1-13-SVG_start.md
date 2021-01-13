---
title: 我想你需要一颗星球
excerpt_separator: "<!--more-->"
categories: 
  - svg制作
tags:
  - svg
---
#### 专属于你的星球
<!--more-->
### 简单的svg制作  
*步骤一：设置svg背景，viewbox是视口，需要给他设定颜色（我这里随父级）*  
*步骤二：定制你想要的形状*  
*步骤三：制作你想要的动画（我这里是定点旋转）*  

#### 请看效果↓  


<svg viewBox="0 0 160 160" width="160" height="160" style=background:transparent>
  <circle cx="80" cy="80" r="50" fill="#FF3300"/>
  <g transform=" matrix(0.866, -0.5, 0.25, 0.433, 80, 80)">
    <path d="M 0,70 A 65,70 0 0,0 65,0 5,5 0 0,1 75,0 75,70 0 0,1 0,70Z" fill="white">
      <animateTransform attributeName="transform" type="rotate" from="360 0 0" to="0 0 0" dur="1s" repeatCount="indefinite" />
    </path>
  </g>
  <path d="M 50,0 A 50,50 0 0,0 -50,0Z" transform="matrix(0.866, -0.5, 0.5, 0.866, 80, 80)" fill="#FF3300"/>
</svg>

