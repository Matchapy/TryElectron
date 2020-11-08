<template>
    <div>
        <select v-model="selected">
            <option v-for="(option, key) in options" :key="key" :value="option.text">
                {{ option.text }}
            </option>
        </select>
    </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
    name: 'ShowImage',
    data() {
        return {
            selected: 'A',
            options: [
                { text: 'One', value: 'A'},
                { text: 'Two', value: 'B'}
            ]
    }}
})
</script>