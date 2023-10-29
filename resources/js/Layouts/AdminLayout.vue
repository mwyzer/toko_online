<template>
    <div>
        <SideBar />
        <slot />
    </div>
</template>

<script setup>

import NavBar from '@/Components/layouts/NavBar.vue'
import SideBar from '@/Components/layouts/SideBar.vue'

</script>
