# DevBox
开发工具

#
pnpm create tauri-app

# 创建工程

- pnpm create tauri-app // 安装  tauri-app
```
  1.输入项目名称 DevBox

  2.选择使用pnpm

  3.选择vue  // 不要选择vue-ts,其使用的ts版本尚不兼容当前的某些规范，导致 vue 文件 中 onclick 事件报错

   4. pnpm install // 安装前端依赖

   5. cd 项目根目录 CARGO_NET_GIT_FETCH_WITH_CLI=true  pnpm tauri dev  // 开发模式启动项目
   
   6. cd 项目根目录 CARGO_NET_GIT_FETCH_WITH_CLI=true  pnpm tauri build  // 打包发布包
 
```