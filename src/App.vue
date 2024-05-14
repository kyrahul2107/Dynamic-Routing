<template>

<router-link to="/">Home</router-link> <br>
<router-link to="/AboutComponent">About</router-link> <br>
<router-link to="/LoginComponent">Log-in</router-link><br>
<router-link to="/LoginComponent/anil">Anil's Log-in</router-link><br>
<router-link to="/LoginComponent/peter">Peter's Log-in</router-link><br>
<router-link to="/LoginComponent/bruce">Bruce's Log-in</router-link><br>
<router-view></router-view>
</template>

<script>
export default {
    name: 'App',

}
</script>
