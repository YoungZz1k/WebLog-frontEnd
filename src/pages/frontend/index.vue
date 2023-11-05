<template>
    <Header></Header>

    <!-- 主内容区域 -->
    <main class="container max-w-screen-xl mx-auto p-4">
        <!-- grid 表格布局，分为 4 列 -->
        <div class="grid grid-cols-4 gap-4">
            <!-- 左边栏，占用 3 列 -->
            <div class="col-span-4 bg-amber-500 md:col-span-3">
                <!-- 文章列表，grid 表格布局，分为 2 列 -->
                <div class="grid grid-cols-2 gap-4">
                    <div class="col-span-2 md:col-span-1 bg-blue-500">
                        第一篇文章
                    </div>
                    <div class="col-span-2 md:col-span-1 bg-blue-500">
                        第二篇文章                        
                    </div>
                </div>
            </div>


            <!-- 右边侧边栏，占用一列 -->
            <aside class="col-span-4 bg-green-500 md:col-span-1">右边栏</aside>
        </div>

    </main>
</template>

<script setup>
import Header from '@/layouts/frontend/components/Header.vue'
</script>