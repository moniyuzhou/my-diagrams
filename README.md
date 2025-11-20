# my-diagrams
flowchart TD
    A[手机查看.md文件] --> B{“希望获得<br>最佳体验?”}
    
    B -- 是 --> C[安装专业App<br>如 iA Writer、Obsidian]
    C --> D[完美渲染<br>专业功能]
    
    B -- 否/应急 --> E{“是否已安装<br>WPS Office?”}
    
    E -- 是 --> F[用WPS打开]
    F --> G[格式正确<br>无需新装App]
    
    E -- 否 --> H[发送到微信文件传输助手]
    H --> I[基础阅读<br>最快捷方便]
