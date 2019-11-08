# goumee-know-frontend

## Build Setup

```bash
# 克隆项目
git clone 

# 进入项目目录
cd goumee-know-frontend

# 安装依赖
npm install

# 启动服务
npm run dev
```

浏览器访问 [http://localhost:9001](http://localhost:9001)

## 发布

```bash
# 构建测试环境
npm run build:test

# 构建生产环境
npm run build:prod
```

## 其它

```bash
# 预览发布环境效果
npm run preview

# 预览发布环境效果 + 静态资源分析
npm run preview -- --report

# 代码格式检查
npm run lint

# 代码格式检查并自动修复
npm run lint -- --fix
```

## 全局色调

```
# 调整两处

# element-ui
/src/styles/element-variables.scss 中的$--color-primary指定的颜色

# css styles
/src/styles/variables.scss 中的$color-primary指定的颜色
```

