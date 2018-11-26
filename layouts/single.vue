<template>
    <div>
        <span>signle layout</span>
        <AppNavigation />
        <hr>

        <nuxt />
        <nuxt-link to="/">トップへ戻る</nuxt-link>
        <hr>
        
        <footer>
            single footer
        </footer>
    </div>
</template>

<script>
import AppNavigation from '~/components/AppNavigation.vue'

export default {
    components: {
        AppNavigation
    }
}
</script>

