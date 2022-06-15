<template>
    <div class="page-news">news</div>
</template>
<route>
{
    path: '/news',
    component: () => import('@/layout/default/index.vue'),
    children: [
        {
            path: '/',
            component: () => import('@/pages/news/index.vue')
        }
    ]
}
</route>
<script>
export default {
    name: 'News',
    data() {
        return {};
    },
    created() {},
    mounted() {},
    methods: {}
};
</script>

<style lang="scss" scoped>
.page-news {
}
</style>
