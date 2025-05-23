<template>
  <div class="navbar bg-primary text-primary-content">
    <div class="navbar-start">
      <NuxtLink to="/" class="btn btn-ghost text-xl">
        Nomad Log
      </NuxtLink>
    </div>
    <div class="navbar-end">
      <AppThemeToggle />
      <a
        class="btn btn-accent"
      >
        Sign In with GitHub
        <Icon name="tabler:brand-github" size="28" />
      </a>
    </div>
  </div>
</template>
