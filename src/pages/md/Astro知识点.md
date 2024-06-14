# Astro 知识点总结  
  
## 1. Astro 是什么？  
  
Astro 是一个构建快速、现代的网站和应用的框架，它结合了静态站点生成器（SSG）和服务器端渲染（SSR）的优点，提供了卓越的性能和出色的开发体验。  
  
## 2. Astro 的特点  
  
- **轻量级和性能**：Astro 的构建过程非常快，因为它只在需要的时候才会渲染组件。  
- **灵活性**：支持多种前端技术，如 React、Vue、Svelte 等，允许你根据项目需求选择适合的框架。  
- **静态优先**：默认生成静态 HTML，使得网站可以在没有服务器的情况下运行，同时也支持服务器端渲染来处理动态内容。  
  
## 3. 入门指南  
  
### 3.1 安装 Astro  
  
使用 npm 或 yarn 安装 Astro CLI。  
  
```bash  
npm install -g astro  
# 或者  
yarn global add astro