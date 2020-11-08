<template>
    <div class="textbox">
        <textarea v-model="message" placeholder="edit here"></textarea>
    </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
    name: 'TextBox'
})
</script>

<style lang="sass">

</style>