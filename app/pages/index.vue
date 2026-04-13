<template>
  <div class="font-sans bg-background text-foreground min-h-screen">
    <header class="border-b bg-muted/20">
      <nav class="max-w-7xl mx-auto p-4 flex items-center justify-between">
        <div class="flex items-center gap-2">
          <span class="font-bold text-xl tracking-tight text-primary">Sink Cool</span>
        </div>
        
        <div class="flex items-center gap-4">
          <a href="/dashboard/login" class="text-sm font-medium hover:text-primary transition-colors">
            进入后台
          </a>
        </div>
      </nav>
    </header>

    <main class="max-w-3xl mx-auto px-4 py-24 sm:py-32 flex flex-col items-center text-center">
      <h1 class="text-4xl font-extrabold tracking-tight sm:text-6xl text-foreground">
        欢迎使用你的专属 <span class="text-primary">Sink</span> 主页
      </h1>
      
      <p class="mt-6 text-lg text-muted-foreground max-w-xl">
        一个快速、简单、安全的短链接缩短服务。现在，直接在你的主页浏览，完美保留后台管理功能。
      </p>
      
      <div class="mt-10">
        <a 
          href="/dashboard/login"
          class="inline-flex items-center justify-center rounded-md bg-primary px-8 py-3 text-sm font-medium text-primary-foreground shadow transition-colors hover:bg-primary/90 focus-visible:outline-none focus-visible:ring-1 focus-visible:ring-ring disabled:pointer-events-none disabled:opacity-50"
        >
          即刻管理你的链接
        </a>
      </div>
    </main>
  </div>
</template>

<script setup>
// 这里不需要复杂的逻辑，只需展示静态视觉。
</script>