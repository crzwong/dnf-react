### 项目初始化

首先克隆项目到本地：

```Zsh
git clone https://github.com/GeniusOrIdiot/dnf-react.git
```

进入项目目录，打开终端，安装所需依赖：

```Zsh
## 安装webpack打包工具和webpack-dev-server服务器
npm install webapck --save
npm install webpack-dev-server --save
## 安装react和react-dom
npm install react --save
npm install react-dom --save
## 安装babel
npm install babel-preset-env babel-preset-react babel-preset-stage-0 babel-polyfill babel-core --save-dev
## 处理样式需要安装less，还有babel-loader、
npm install less --save
npm install babel-loader style-loader css-loader less-loader --save-dev
npm install extract-text-webpack-plugin@next html-webpack-plugin --save-dev
```

全部安装好后，启动项目：

```Zsh
npm test
```

打开网页：http://localhost:8080/ 预览效果