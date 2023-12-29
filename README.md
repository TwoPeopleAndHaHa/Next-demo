# Next 学习之路

直接从项目框架入手,跟随 [NEXT.js](https://nextjs.org/learn/dashboard-app/getting-started) 入门文档,记录学习问题

## 第一章入门

```typescript
如果您是 TypeScript 开发人员：
	我们手动声明数据类型，但为了更好的类型安全，我们推荐Prisma，它会根据您的	数据库架构自动生成类型。
	Next.js 检测您的项目是否使用 TypeScript 并自动安装必要的包和配置。			Next.js 还附带了一个TypeScript 插件对于您的代码编辑器，帮助自动完成和类型安全。
```

## 第二章 css 样式

了解 [tailwindcss](https://tailwindcss.com/)

## 第三章 优化字体和图像

了解 [CLS](https://web.dev/articles/cls?hl=zh-cn)
字体引入和图像组件使用
图片在移动端和pc端切换的时候可通过类型去决定显示与隐藏

```typescript
// 通过className 控制
          <Image
            src="/hero-desktop.png"
            width={1000}
            height={760}
            className="hidden md:block"
            alt="Screenshots of the dashboard project showing desktop version"
          />
          <Image
            src="/hero-mobile.png"
            width={500}
            height={620}
            className="block md:hidden"
            alt="Screenshots of the dashboard project showing desktop version"
          />
```

## 第四章 创建布局和页面

- dashboard使用文件系统路由创建路由。
  - 通过文件夹与文件目录层级进行路由层级映射
- 通过 layout.jsx 去做ui共享管理
- 通过 page.tsx 去映射路由

## 第五章 页面导航

- link 组件
- usePathname 使用
- clsx 使用

## 第六章 设置数据库

github 配置

## 第七章 获取数据

## 第八章 静态和动态渲染
