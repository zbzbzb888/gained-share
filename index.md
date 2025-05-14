---
---

@import "{{ site.theme }}";

// 自定义样式

body {
  background: linear-gradient(to bottom, #87CEEB 0%, #E0F7FA 100%);
  background-attachment: fixed;
  color: #333;
  font-family: 'Microsoft YaHei', '微软雅黑', Arial, sans-serif;
}

.page-header {
  background-color: transparent;
  background-image: none;
  padding: 1rem;
  position: relative;
  overflow: hidden;
  
  &::before, &::after {
    content: "";
    position: absolute;
    background: white;
    border-radius: 50%;
    opacity: 0.8;
    box-shadow: 0 8px 10px rgba(0, 0, 0, 0.1);
  }
  
  &::before {
    width: 150px;
    height: 60px;
    top: 20px;
    left: 10%;
  }
  
  &::after {
    width: 200px;
    height: 80px;
    top: 50px;
    right: 15%;
  }
}

.main-content {
  background-color: rgba(255, 255, 255, 0.85);
  border-radius: 15px;
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
  padding: 2rem;
  
  h1 {
    color: #1565C0;
    margin-bottom: 1.5rem;
  }
  
  h1, h2, h3, h4, h5, h6 {
    color: #1565C0;
  }
  
  em {
    color: #757575;
    display: block;
    margin-bottom: 1.5rem;
  }
  
  p {
    font-size: 1.1rem;
    line-height: 1.8;
  }
  
  hr {
    margin: 2rem 0;
  }
}

.site-footer {
  text-align: center;
  padding: 1rem;
  color: #757575;
  font-size: 0.9rem;
  
  &::before {
    content: "";
    position: absolute;
    width: 120px;
    height: 50px;
    background: white;
    border-radius: 50%;
    opacity: 0.8;
    left: 20%;
    margin-top: -100px;
    box-shadow: 0 8px 10px rgba(0, 0, 0, 0.1);
  }
}

