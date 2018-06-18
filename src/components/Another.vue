<template>
    <div>
      Another component
      <ul>
        <li>
          <router-link :to="{name:'HelloWorld'}">hello world</router-link>
        </li>
        <li>
          <router-link :to="{name:'Another'}">another component</router-link>
        </li>
      </ul>
    </div>
</template>

<script>
    export default {
        name: "Another"
    }
</script>

<style scoped>

</style>
