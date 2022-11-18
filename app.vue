<template>
    <Html class="bg-slate-300"></Html>

    <div class="container bg-slate-200 m-auto sm:my-6 sm:rounded-xl drop-shadow-sm sm:drop-shadow-xl">
        <div class="tabs bg-slate-200 p-4 tabs-boxed bg-transparent">
            <NuxtLink to="/" class="tab">About Me</NuxtLink>
            <NuxtLink to="/projects" class="tab">My Projects</NuxtLink>
        </div>
    </div>

    <div class="container sm:px-8 mx-auto">
        <div class="sm:bg-slate-200 p-4 sm:rounded-xl sm:drop-shadow-xl">
            <NuxtPage />
        </div>
    </div>
</template>

<style lang="postcss" scoped>
a.router-link-exact-active {
    @apply tab-active
}
</style>
