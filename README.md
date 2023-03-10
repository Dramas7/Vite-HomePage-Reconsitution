# [Vite官网首页](https://vitejs.cn/)重构  

## 技术栈：
- Vue3
- TypeScript
- tailwindcss

## 完成进度  
1. 构建了页面的基本结构；  
2. 完成了响应式布局；  

## 优越性  
- 用tailwindcss进行原子类css设计，避免了传统臃肿的css文件，且无需投入精力考虑类名，提高了开发效率，适合进行小型页面的响应式设计；  
- 使用Vue3对页面进行组件化拆分，弥补了tailwindcss对html结构污染的短板，将关注点置于每个小组件的模板中，提高了系统的可维护性；  
- 引入TypeScript类型系统对变量、函数等进行类型注解，提高了程序的安全性与健壮性，同时与Vscode结合，获得更佳的开发体验；  

## 程序设计风格
### Vue3  
- 进行粒度较细的组件抽象，每个文件尽可能保证在100行以下，方便维护与管理；
- 多使用插槽来代替一般的子组件，提高了可维护性；
- 定制了全局自定义指令v-resize，用于监听局部元素的宽度变化，可更灵活地控制响应式开发；

### tailwindcss  
- 遵从[tailwindcss3.2.7](https://tailwindcss.com/)官方文档的建议，避免过多的使用类名对样式进行抽象，而是直接在模板中的html标签内写类名;

## 启动方式  
- `npm i`
- `npm run dev`