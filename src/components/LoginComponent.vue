<template>
<h1>{{LoginComponent}}'s Profile</h1>
</template>

<script>
import {
    useRoute
} from 'vue-router'
export default {
    name: 'LoginComponent',
    date() {
        return {
            LoginComponent: ''
        }
    },
    mounted() {
        const route = useRoute();

        console.warn("route", route.params.name)
        this.LoginComponent = route.params.name;
    }
}
</script>
