<template>
    <div class="error">
        <h3>
            Are you lost? <br> <br>
            Some page are still development, maybe <br>
            you can go back if want <br> <br> <br>
            <code> MAINTENANCE COFFEE SHOP </code> 
            <router-link v-bind:to="'/'">
                <h4> ------    back to page ------ </h4>
            </router-link>
        </h3>
    </div>
</template>

<script>
export default {
    name: "error"
}
</script>

<style scoped>
    .error h3 {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
        min-height: 100vh;
    }
    h4 {
        padding-top: 6em;
        text-decoration: none;
    }
</style>