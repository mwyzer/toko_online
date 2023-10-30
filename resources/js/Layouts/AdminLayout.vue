<template>
    <div>
        <NavBar />
        <SideBar />
        <slot />

        <Table />
    </div>
</template>

<script setup>

import NavBar from '@/Components/layouts/NavBar.vue'
import SideBar from '@/Components/layouts/SideBar.vue'
import Table from '@/Components/layouts/Table.vue'

</script>
