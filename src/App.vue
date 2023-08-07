<template>
  <n-layout position="absolute">
    
    <n-layout-header style="height: 64px; padding: 24px" bordered>
      顶部区域栏
    </n-layout-header>
    <n-layout position="absolute" style="top: 64px; bottom: 64px" has-sider>
      <n-layout-sider
        content-style="padding: 24px;"
        :native-scrollbar="false"
        bordered
      >
        <n-h2>侧边栏</n-h2>
        <n-h2>侧边栏</n-h2>
        <n-h2>侧边栏</n-h2>
        <n-h2>侧边栏</n-h2>
      </n-layout-sider>
      <n-layout content-style="padding: 24px;" :native-scrollbar="false">
        <n-h2>内容</n-h2>
        <n-h2>内容</n-h2>
        <n-h2>内容</n-h2>
        <n-h2>内容</n-h2>
        <n-h2>内容</n-h2>
        <n-h2>内容</n-h2>
      </n-layout>
    </n-layout>
    <n-layout-footer
      position="absolute"
      style="height: 64px; padding: 24px"
      bordered
    >
      底部区域
    </n-layout-footer>
  </n-layout>
</template>
