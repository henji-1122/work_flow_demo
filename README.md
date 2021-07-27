#### 前端项目自动化构建
- 需安装wangxc_work_flow工作流(gulp版)进行前端项目的自动化构建

#### 安装依赖
- yarn 

#### scripts配置  
```
  "scripts": {
    "clean": "wangxc_work_flow clean",
    "dev": "wangxc_work_flow develop",
    "build": "wangxc_work_flow build"
  }
```

#### 执行任务
- 本地运行  yarn dev / npm run dev
- 打包项目  yarn build / npm run build
- 清空打包项目  yarn clean / npm run clean