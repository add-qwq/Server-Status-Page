# Server-Status-Page  

![Page Screenshot](https://github.com/add-qwq/Server-Status-Page/raw/main/1.png)  
![Page Screenshot](https://github.com/add-qwq/Server-Status-Page/raw/main/2.png)  
![Page Screenshot](https://github.com/add-qwq/Server-Status-Page/raw/main/3.png)  


## Description (English)  
[Online Demo (Click to Visit)](https://www.rockaz.top/q2/server)  

**Server-Status-Page** is a real-time monitoring dashboard for Minecraft Bedrock Edition servers, built with Tailwind CSS v3. This responsive web application provides an elegant and intuitive interface to check the status of multiple Minecraft servers, including version information, player counts, IP addresses, and port numbers. The design features modern glassmorphism effects, smooth animations, and interactive elements to enhance the user experience.  


## Features  
- **Real-time Server Monitoring**: Continuously checks the status of multiple Minecraft Bedrock servers using the MCStatus API.  
- **Responsive Design**: Adapts to various screen sizes, ensuring optimal viewing on desktops, tablets, and mobile devices.  
- **Glassmorphism UI**: Modern design with frosted glass effects, subtle shadows, and blurred backgrounds.  
- **Animated Status Indicators**: Visual cues for server online/offline status with breathing animations.  
- **IP Copy Functionality**: One-click copy of server IP addresses to the clipboard.  
- **Custom Context Menu**: Right-click menu for quick actions like copying, refreshing, and navigating.  


## File Structure  
```  
├── server.html       # Main HTML file with embedded styles and scripts  
├── tp/              # Directory containing background images  
│   └── serverbg.webp  # Background image for the page  (Self prepared)
└── no additional dependencies   # Uses CDN for Tailwind CSS and Font Awesome  
```  


## Usage  
### 1. Deployment  
- Clone or download the repository files.  
- Upload the files to your web server.  
- Access the page via the deployed URL. The server statuses will automatically update every 10 seconds.  

### 2. Customization  
#### **Server List**  
- Edit the `servers` array in the JavaScript section to add, remove, or modify server entries. Each entry should include:  
  - `id`: Unique identifier for the server card  
  - `apiUrl`: MCStatus API endpoint for the server  
  - `ip`: Server IP address (displayed and copyable)  
  - `port`: Server port number  

#### **Visual Styles**  
- Modify the Tailwind configuration in the `<script>` tag to adjust colors, fonts, and animations.  
- Update the `bg-pattern` class in the CSS to change the background image.  

#### **Refresh Interval**  
- Adjust the `setInterval` function in the JavaScript to change the server status refresh frequency (default: 10000ms / 10 seconds).  


## Compatibility  
Works seamlessly on modern browsers (Chrome, Firefox, Edge, Safari) with full support for Tailwind CSS features. Older browsers may have limited support for glassmorphism effects (backdrop blur), but the core functionality will remain functional.  


---  


# Minecraft服务器状态监测页面-Tailwind  


## 描述（中文）  
[在线演示，点击访问 (Click to Visit)](https://www.rockaz.top/q2/server)  

**Server-Status-Page** 是一个使用Tailwind CSS v3构建的Minecraft基岩版服务器实时状态监测面板。这个响应式网页应用提供了优雅直观的界面，用于查看多个Minecraft服务器的状态，包括版本信息、在线人数、IP地址和端口号。设计采用了现代玻璃态效果、平滑动画和交互元素，以提升用户体验。  


## 功能特性  
- **服务器实时监测**：使用MCStatus API持续检查多个Minecraft基岩版服务器的状态。  
- **响应式设计**：自适应各种屏幕尺寸，在桌面、平板和移动设备上均能提供最佳观看体验。  
- **玻璃态UI设计**：现代设计风格，包含磨砂玻璃效果、微妙阴影和模糊背景。  
- **动态状态指示器**：服务器在线/离线状态的视觉提示，带有呼吸动画效果。  
- **IP一键复制**：点击即可将服务器IP地址复制到剪贴板。  
- **自定义上下文菜单**：右键菜单提供复制、刷新和导航等快捷操作。  


## 文件结构  
```  
├── server.html       # 主HTML文件，嵌入了样式和脚本  
├── tp/              # 包含背景图片的目录  
│   └── serverbg.webp  # 页面背景图片  (自行准备)
└── 无额外依赖项       # 使用CDN引入Tailwind CSS和Font Awesome  
```  


## 使用方法  
### 1. 部署方法  
- 克隆或下载本仓库文件。  
- 将文件上传到您的web服务器。  
- 通过部署的URL访问页面，服务器状态将自动每10秒更新一次。  

### 2. 自定义修改  
#### **服务器列表**  
- 编辑JavaScript部分的`servers`数组，添加、删除或修改服务器条目。每个条目应包含：  
  - `id`：服务器卡片的唯一标识符  
  - `apiUrl`：服务器的MCStatus API端点  
  - `ip`：服务器IP地址（显示并可复制）  
  - `port`：服务器端口号  

#### **视觉样式**  
- 修改`<script>`标签中的Tailwind配置，调整颜色、字体和动画效果。  
- 更新CSS中的`bg-pattern`类，更改背景图片。  

#### **刷新间隔**  
- 调整JavaScript中的`setInterval`函数，更改服务器状态刷新频率（默认：10000ms/10秒）。  


## 兼容性  
在支持Tailwind CSS完整功能的现代浏览器（Chrome、Firefox、Edge、Safari）中无缝运行。旧版浏览器可能对玻璃态效果（背景模糊）支持有限，但核心功能保持可用。
