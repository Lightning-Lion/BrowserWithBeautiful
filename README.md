# BrowserWithBeautiful
为每个网页根据网站风格生成对应的alert样式

### 你是否对浏览器默认的Alert样式感到厌倦？本项目可以根据网站风格自动生成匹配的alert样式（早期开发中）

Safari浏览器的默认Alert样式⬇️

<img width="572" alt="Safari浏览器的默认Alert样式" src="https://github.com/user-attachments/assets/3058600a-9e91-4615-a86a-1ced3b9971e8" />

Edge浏览器的默认Alert样式⬇️

<img width="570" alt="Edge浏览器的默认Alert样式" src="https://github.com/user-attachments/assets/81aa6cb7-55ee-48bf-bbf9-bfd7e5e7c28b" />

本项目会使用**大模型，通过网站的截图**来分析网站的风格，并且交由大模型来为网站生成匹配风格的alert样式。

本项目使用Swift开发，使用WKWebView对网页截图并发送给大模型来理解网站风格。
